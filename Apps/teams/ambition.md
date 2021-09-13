---
title: Información de la aplicación para Ambición por ambición
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Ambition, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d6c4a598cd115edd52e6dbd37cabd60b7a011aad
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284167"
---
# <a name="ambition"></a>Ambition

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/250ef61a-9fa3-434b-ae2a-0ecbe3f8116b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003159" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Ambition a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Ambition |
| Id. | WA200003159 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Ambition |
| Dirección URL del sitio web de partners | [https://ambition.com](https://ambition.com) |
| Dirección URL de Teams de información de la aplicación | [https://ambition.com](https://ambition.com) |
| Dirección URL de la directiva de privacidad | [https://ambition.com/privacy/](https://ambition.com/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://ambition.com/pages/terms/](https://ambition.com/pages/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Ambition sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | Enviar notificaciones de ambición al canal | Nombre del &amp; id. de canal. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| Group.Read.All | delegado | Configurar una notificación de flujo de trabajo de Ambición en un canal determinado dentro de un equipo. | Identificador de nombre del &amp; equipo. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.Read | delegado | Para identificar al administrador que autorizó la aplicación de Ambición | Los usuarios nombre &amp; correo electrónico, para sincronizar con usuarios de Ambición | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.ReadBasic.All | delegado | Mensajes de correo electrónico de nombres &amp; de usuario, para sincronizar usuarios con sus cuentas de Ambición. | Los correos electrónicos de nombres &amp; de usuario se almacenan. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| offline_access | delegado | Para sincronizar los Microsoft Teams mientras los usuarios están sin conexión. | El token de actualización del token de acceso de OAuth &amp; se almacena. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| OpenID | delegado | Esto es necesario para usar la característica de inicio de sesión de Microsoft | N/D | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://ambition.com/pages/subprocessors/ | Nombre del empleado, apellido, dirección de correo electrónico | Finalidades de pantalla/búsqueda/filtro |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Mostrar propósitos.  | Nombra &amp; correos electrónicos. | Para vincular a los usuarios de Microsoft con sus cuentas de Ambition. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>https://ambition.com/privacy/

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Permisos de acceso necesarios.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Ambition acerca de cómo esta aplicación controla la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
