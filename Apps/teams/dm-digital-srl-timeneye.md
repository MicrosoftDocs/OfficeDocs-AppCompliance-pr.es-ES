---
title: Información de la aplicación para Timeneye por DM Digital SRL
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Timeneye, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 30c0543469970b94d1020a3c1c64f668ab833075
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412450"
---
# <a name="timeneye"></a>Timeneye

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 31, 2021</p>

* <a href="https://teams.microsoft.com/l/app/015bf4ec-bc37-4931-9862-ef8686da652b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001950" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por DM Digital SRL a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Timeneye |
| Id. | WA200001950 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | DM Digital SRL |
| Dirección URL del sitio web de partners | [https://www.dmdigital.it](https://www.dmdigital.it) |
| Dirección URL de la directiva de privacidad | [https://www.timeneye.com/privacy-policy](https://www.timeneye.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.timeneye.com/terms-and-conditions](https://www.timeneye.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

DM Digital SRL ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Event Start/End DateTime, Event Subject, Event ID, Event Web URI. Generar sugerencias basadas en eventos de calendario. | Event Start/End DateTime, Event Subject, Event ID, Event Web URI. Poder vincular una sugerencia generada al evento de calendario correspondiente. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Calendars.Read.Shared | delegado | Event Start/End DateTime, Event Subject, Event ID, Event Web URI. Usamos esta información para generar sugerencias basadas en eventos de calendario. | Event Start/End DateTime, Event Subject, Event ID, Event Web URI. Usamos esta información para vincular una sugerencia generada al evento de calendario correspondiente. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Directory.Read.All | delegado | Identificadores de grupos de usuarios. Usamos esta información para comprobar los grupos de los que el usuario es miembro para poder sincronizar los organizadores de sus grupos. | Identificadores de grupos de usuarios. Usamos esta información para comprobar los grupos de los que el usuario es miembro para poder sincronizar los organizadores de sus grupos. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Group.Read.All | delegado | Nombre del grupo, Id. de grupo. Usamos esa información al sincronizar los proyectos de planner. | Nombre del grupo, Id. de grupo.  | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Tasks.Read | delegado | nombre de lista de tareas, id. de lista de tareas. Usamos esta información al sincronizar los proyectos de planner. | nombre de lista de tareas, id. de lista de tareas. Usamos esta información al sincronizar los proyectos de planner. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.Read | delegado | correo electrónico, nombre. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | correo electrónico, nombre. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.ReadBasic.All | delegado | nombre de usuario, correo electrónico. Usamos esta información para que el usuario pueda importar otros usuarios de Planner/Microsoft a nuestro servicio. | nombre de usuario, correo electrónico. Información básica necesaria para crear un nuevo usuario en nuestro servicio. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| email | delegado | Correo electrónico. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | Correo electrónico. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| offline_access | delegado | Permiso necesario para sincronizar el organizador/calendario mientras el usuario no está en línea. | Permiso necesario para sincronizar el organizador/calendario mientras el usuario no está en línea. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| OpenID | delegado | id_token. Iniciar sesión en el usuario a través de Sso de Microsoft | id_token. Iniciar sesión en el usuario a través de Sso de Microsoft. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| perfil | delegado | correo electrónico, nombre. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | correo electrónico, nombre. Usamos esta información para iniciar sesión en el usuario o crear la cuenta de usuario | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook API de calendario | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nombre de usuario y correo electrónico, detalles de facturación de la empresa. Cuando se elimina la cuenta o el usuario, se quita la información.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No pasamos información razonable a nuestros sistemas asociados, excepto para el correo electrónico del usuario con fines de soporte técnico, venta de entradas y facturación. La información se elimina al eliminar la cuenta en nuestro sistema.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Dm Digital SRL ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
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
| ¿La aplicación usa API en desuso? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

