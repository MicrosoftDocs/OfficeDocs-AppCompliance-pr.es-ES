---
title: Información de solicitud para LMS365 por ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para LMS365, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552221"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 25 de febrero de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ELEARNINGFORCE International a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | LMS365 |
| ID | WA104381467 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | ELEARNINGFORCE International |
| URL del sitio web de socios | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL de Teams página de información de la aplicación | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL de la Política de Privacidad | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL de los Términos de uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

ElEARNINGFORCE International ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicación | Ninguno | Permite a la aplicación expandir los miembros del grupo ad, que es necesario para inscribir a un grupo de usuarios en los cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegado | Ninguno | El permiso se solicita dinámicamente durante la configuración de la cuenta de correo electrónico para la notificación. Permite a la aplicación enviar correos electrónicos de notificación | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicación | Ninguno | Permite que la aplicación obtenga SharePoint dominio durante el aprovisionamiento de inquilinos. El dominio se utiliza para la construcción de URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegado | Ninguno | Permite a la aplicación invitar a usuarios externos en nombre de usuario que ha iniciado sesión actualmente | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegado | Ninguno | Inicie sesión y lea el perfil de usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegado | Ninguno | Permite a la aplicación leer el perfil completo del usuario que ha iniciado sesión actualmente. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicación | Permite que la aplicación lea el perfil de usuario completo. Se&#8217;s necesarios para leer usuarios&#8217; administradores para crear informes jerárquicos. | Los siguientes datos personales se almacenan en una base de datos dedicada para el cliente respectivo utilizado para la funcionalidad de panel de Learner Management &amp; Manager dentro de la aplicación. Nombre de la cuenta, Nombre para mostrar del usuario, Dirección de correo electrónico, Departamento, Título del trabajo, Office, País, Ciudad, Id. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | Delegado | Ninguno | Ver el perfil básico del usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilizamos el nombre solo para mostrar un mensaje personalizado cuando el Bot saluda al usuario. | Los datos personales se almacenan en una base de datos de Azure dedicada para el cliente respectivo que se usa para la funcionalidad de panel de Learner Management &amp; Manager dentro de la aplicación LMS365. | Nombre de la cuenta, Nombre para mostrar del usuario, Dirección de correo electrónico, Departamento, Título del trabajo, Office, País, Ciudad, Id. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, usamos telemetría/registros de Insights Log Analytics que solo se usan para la toma de problemas y tenemos una directiva de retención de 90 días después de la cual se eliminan todos los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>LMS365 está equipado con una función de purga que eliminará cualquier dato personal de la base de datos LMS365 de los clientes.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ElEARNINGFORCE International ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumere los tipos de directivas admitidas | Plataformas de dispositivos, Estado del dispositivo, Aplicaciones cliente |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
