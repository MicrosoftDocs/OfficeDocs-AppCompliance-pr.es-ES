---
title: Información de la aplicación para Neelix.Team por Neelix.IO
ms.author: elmalova
author: elenamalova
ms.date: 07/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Neelix.Team, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 74f41c23436f1bfc47db6fea7dfca2e8b12731bb
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404852"
---
# <a name="neelixteam"></a>Neelix.Team

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bed170ee-dbd7-4efa-b48e-b0937ded1689" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003047" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Neelix.IO a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Neelix.Team |
| Id. | WA200003047 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Neelix.IO |
| Dirección URL del sitio web de partners | [https://www.neelix.team](https://www.neelix.team) |
| Dirección URL de Teams de información de la aplicación | [https://www.neelix.team](https://www.neelix.team) |
| Dirección URL de la directiva de privacidad | [https://www.neelix.team/data-security-policy](https://www.neelix.team/data-security-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.neelix.io/terms-of-use-en](https://www.neelix.io/terms-of-use-en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Neelix.IO acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | la aplicación usa identificadores de canal y nombres para proporcionar comodidad a los usuarios para administrar sus preferencias predeterminadas al enviar comentarios de MS Treams | Identificadores y nombres de canal se almacenan para la administración de valores predeterminados para comodidad del usuario | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| Team.ReadBasic.All | delegado | la aplicación usa identificadores de equipo y nombres para proporcionar comodidad a los usuarios para administrar sus preferencias predeterminadas al enviar comentarios de MS Treams | se almacenan los nombres y los identificadores de equipo. Estos datos nos permiten configurar valores predeterminados de comodidad que permiten la finalización más rápida del formulario de comentarios. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| email | delegado | el correo electrónico se usa como parte del registro del usuario dentro de Neelix. Después del registro inicial, el correo electrónico se usa para las notificaciones.  | el correo electrónico se almacena en el perfil de usuario. el correo electrónico también se usa para comprobar que el usuario no intente usar el mismo correo electrónico a través de otro canal de oauth. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| offline_access | delegado | Esto se usa para obtener el token de actualización |  el token de actualización se almacena para obtener un nuevo token de acceso | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| perfil | delegado | El nombre de usuario se usa para crear una cuenta de usuario al registrarse con Neelix.  | El nombre de usuario se almacena en la cuenta de usuario. Esto es necesario para que el usuario sea reconocido por otros miembros del equipo en su diario de grupo. El usuario puede actualizar el nombre almacenado en Neelix. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| User.Read | delegado | Bot app uses user.read in order to be able to send information user so that Neelix core platform can identify the user | La información no se almacena | [bed170ee-dbd7-4efa-b48e-b0937ded1689](https://docs.microsoft.com/microsoft-365-app-certification/azure/bed170ee-dbd7-4efa-b48e-b0937ded1689) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plataforma de identidad de Microsoft | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Los identificadores de inquilino se envían a nuestro servicio back-end que se ejecuta en Google Cloud Platform | Identificadores de inquilino | Los identificadores de inquilino se usan con fines de identificación de usuario durante la oauth |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| La aplicación usa el identificador de usuario para identificar al usuario con la información registrada con la plataforma Neelix | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Los identificadores de inquilino se registran en los registros del sistema. La directiva de retención de registros es de 30 días.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Directiva de usuario final, procedimientos de cumplimiento del RGPD, Cancelación de cuentas y Procedimientos de Acrichival de datos

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

Esta información ha sido proporcionada por Neelix.IO sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
