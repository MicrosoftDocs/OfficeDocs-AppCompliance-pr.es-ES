---
title: Información de la aplicación para LMS365
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para LMS365, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224994"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>Información de la aplicación para LMS365 by ELEARNINGFORCE International Aps

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización del desarrollador: 23 de junio de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ELEARNINGFORCE International Aps a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | LMS365 |
| ID | elearningforce.lms365_spfx |
| Nombre de la empresa asociada | ELEARNINGFORCE International Aps |
| Dirección URL del sitio web del asociado | [https://www.elearningforce.com](https://www.elearningforce.com) |
| Dirección URL de la directiva de privacidad | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| Dirección URL de los términos de uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Esta información ha sido proporcionada por ELEARNINGFORCE International Aps sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicación | Ninguno | Permite que la aplicación expanda los miembros del grupo de AD, que son necesarios para inscribir un grupo de usuarios en los cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegado | Ninguno | El permiso se solicita dinámicamente durante la configuración de la cuenta de correo electrónico para la notificación. Permite a la aplicación enviar correos electrónicos de notificación | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicación | Ninguno | Permite que la aplicación obtenga SharePoint dominio durante el aprovisionamiento de inquilinos. El dominio se usa para la construcción de direcciones URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegado | Ninguno | Permite a la aplicación invitar a usuarios externos en el nombre del usuario que ha iniciado sesión actualmente. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegado | Ninguno | Inicie sesión y lea el perfil de usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegado | Ninguno | Permite a la aplicación leer el perfil completo del usuario actual que ha iniciado sesión. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicación | Permite que la aplicación lea el perfil de usuario completo. &#8217;es necesario leer a los usuarios&#8217; administradores para crear informes de jerarquía. | Los siguientes datos personales se almacenan en una base de datos dedicada para el cliente correspondiente que se usa para la funcionalidad del panel de Learner Management &amp; Manager dentro de la aplicación. Nombre de cuenta, nombre para mostrar del usuario, dirección de correo electrónico, departamento, título del trabajo, Office, país, ciudad, id. de administrador/correo electrónico | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | Delegado | Ninguno | Ver el perfil básico del usuario. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph para recopilar o procesar información de identificación de la organización (OII). Enumere las API de Microsoft distintas de Microsoft Graph que use esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para la recopilación de OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>No se usan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, usamos Ideas telemetría o registros de Log Analytics que se usan solo para la toma de problemas y tienen una directiva de retención de 90 días después de la cual se eliminan todos los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>LMS365 está equipado con una función de purga que quitará los datos personales de la base de datos LMS365 de los clientes.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por ELEARNINGFORCE International Aps sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Plataformas de dispositivos, Estado del dispositivo, Aplicaciones cliente |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de versión preliminar? | No |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
