---
title: Información de aplicación para LMS365 por ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para LMS365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f8e10bb30857c055ab4916c4f944225d50ef44ba
ms.sourcegitcommit: abce882d3e2ca5b9b0b47fc4a26c01e6e111a9b4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/24/2021
ms.locfileid: "52629675"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: March 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ELEARNINGFORCE International a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | LMS365 |
| ID | WA104381467 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ELEARNINGFORCE International |
| Dirección URL del sitio web de partners | [https://www.elearningforce.com](https://www.elearningforce.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| Dirección URL de la directiva de privacidad | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ELEARNINGFORCE International ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicación | Ninguno | Permite que la aplicación expanda los miembros del grupo de AD, que es necesario inscribir un grupo de usuarios en los cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | delegado | Ninguno | El permiso se solicita dinámicamente durante la configuración de la cuenta de correo electrónico para la notificación. Permite que la aplicación envíe correos electrónicos de notificación | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicación | Ninguno | Permite que la aplicación obtenga SharePoint dominio durante el aprovisionamiento de inquilinos. El dominio se usa para la construcción de direcciones URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | delegado | Ninguno | Permite que la aplicación invite a usuarios externos en nombre del usuario que ha iniciado sesión actual | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | delegado | Ninguno | Inicie sesión y lea el perfil de usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | delegado | Ninguno | Permite que la aplicación lea el perfil completo del usuario que ha iniciado sesión actual. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicación | Permite que la aplicación lea el perfil de usuario completo. Es&#8217;para leer a los usuarios&#8217; administradores para crear informes de jerarquía. | Los siguientes datos personales se almacenan en una base de datos dedicada para el cliente correspondiente que se usa para la funcionalidad del Panel del Administrador de administración de &amp; learner dentro de la aplicación. Nombre de cuenta, Nombre para mostrar del usuario, Dirección de correo electrónico, Departamento, Puesto de trabajo, Office, País, Ciudad, Id. de administrador/Correo electrónico | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | delegado | Ninguno | Ver el perfil básico del usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Usamos el nombre solo para mostrar un mensaje personalizado cuando el Bot saluda al usuario. | Los datos personales se almacenan en una base de datos de Azure dedicada para el cliente correspondiente que se usa para la funcionalidad del Panel del Administrador de administración de learner dentro de la &amp; aplicación LMS365. | Nombre de cuenta, Nombre para mostrar del usuario, Dirección de correo electrónico, Departamento, Puesto de trabajo, Office, País, Ciudad, Id. de administrador/Correo electrónico |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí, usamos registros y telemetría de Insights Log Analytics que se usan solo para la captura de problemas y tienen una directiva de retención de 90 días después de la cual se eliminan todos los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>LMS365 está equipado con una función purge que eliminará los datos personales de los clientes LMS365 Database.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ELEARNINGFORCE International ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Plataformas de dispositivos, Estado del dispositivo, Aplicaciones cliente |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
