---
title: Información de la aplicación para Tikit de Cireson
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Tikit, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: de10b787d3e4100972e46efe76050ed0c7df31fd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553251"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cireson a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Tikit |
| ID | WA200002602 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Cireson |
| Dirección URL del sitio web de partners | [https://tikit.ai](https://tikit.ai) |
| Dirección URL de Teams de información de la aplicación | [https://tikit.ai](https://tikit.ai) |
| Dirección URL de la directiva de privacidad | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| DIRECCIÓN URL de términos de uso | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Cireson ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | aplicación | Información de gráfico de usuario usada para el inicio de sesión único, a través de la comunicación del bot de teams  | Almacenamos roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams id. de usuario. Este informe se usa para autenticación de aplicaciones, seguridad, RBAC, integración de equipos, notificaciones de equipos y asignación de relaciones de usuario   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | delegado | Nombres de grupo y roles para RBAC | Nombre del &amp; grupo Nombre del rol, necesita proporcionar un control de acceso asignado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | delegado | Nombres de grupo y roles para RBAC | Nombre del &amp; grupo Nombre del rol, necesita proporcionar un control de acceso asignado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | ambos | Nombres de grupo y roles para RBAC | Nombres de grupo y roles para RBAC | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | delegado | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | aplicación | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | delegado | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | Roles de usuario, nombre de familia, nombre determinado, correo electrónico, id. de AAD, Teams de usuario, usado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| email | delegado | Correo electrónico de usuario usado para el inicio de sesión y la identificación asociada de entidades relacionadas. &quot;Usuario asignado&quot; | Correo electrónico de usuario usado para el inicio de sesión y la identificación asociada de entidades relacionadas. &quot;Usuario asignado&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| OpenID | delegado | se usa para la autenticación mediante MSAL por requisitos  | se usa para la autenticación mediante MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| perfil | delegado | se usa para la autenticación mediante MSAL por requisitos  | se usa para la autenticación mediante MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nombre y correo electrónico para las relaciones de entidad de usuario &quot; Ticket Requestor&quot;  | Nombre y correo electrónico  | para relaciones de entidad de usuario &quot; Ticket Requestor&quot;  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Almacenamos el nombre de la empresa, el identificador de inquilino, el correo electrónico, el id. de cliente bot en información de la aplicación, con una directiva de retención de 30 dat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No tenemos datos en sistemas asociados.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Cireson ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
