---
title: Información de la aplicación para StealthMail de Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para StealthMail, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 322cdc906ab0cd2ae8980d1412bb4dd9c897a5f6
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286880"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 31, 2021</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Stealthmail Software Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | StealthMail |
| Id. | WA200001748 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Stealthmail Software Ltd |
| Dirección URL del sitio web de partners | [https://stealthmail.com](https://stealthmail.com) |
| Dirección URL de Teams de información de la aplicación | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| Dirección URL de la directiva de privacidad | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| DIRECCIÓN URL de términos de uso | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Stealthmail Software Ltd sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | delegado | La aplicación envía el mensaje al canal con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| ChannelMessage.Send | delegado | La aplicación envía el mensaje al canal con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| Chat.ReadWrite | delegado | La aplicación envía el mensaje para chatear con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| GroupMember.Read.All | delegado | La aplicación obtiene miembros del canal para que les hagan correo electrónico seguro | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| User.Read.All | delegado | La aplicación obtiene miembros de chat para que les hagan correo electrónico seguro | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| User.ReadBasic.All | delegado | La aplicación obtiene miembros de chat para que les hagan correo electrónico seguro | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| email | delegado | Autenticar usuario | almacén de nothing en la base de datos | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No tenemos control sobre los datos de los partners en sus sistemas.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Stealthmail Software Ltd sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
