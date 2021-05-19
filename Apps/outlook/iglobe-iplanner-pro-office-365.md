---
title: Información de la aplicación para iPlanner Pro Office 365 por iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/05/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para iPlanner Pro Office 365, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a191dc43512ce9a58ff36277c3a602aff2e799a7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553731"
---
# <a name="iplanner-pro-office-365"></a>iPlanner Pro Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 5 de noviembre de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380464" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | iPlanner Pro Office 365 |
| ID | WA104380464 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en iOS, Outlook en la web |
| Nombre de la empresa asociada | iGlobe |
| URL del sitio web de socios | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la Política de Privacidad | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL de los Términos de uso | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de planificador y agregar nuevas tareas, actualice el bucket y la línea de natación para el usuario específico | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Contacts.ReadWrite | Delegado | No se almacenan datos en bases de datos de aplicaciones. | para crear una cita en el calendario de usuarios en las tareas fecha de vencimiento | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Directory.AccessAsUser.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.Read | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para acceder al archivo como archivo adjunto y cargar archivos en una tarea | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.ReadWrite.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Obtenga el asunto del correo del correo seleccionado. Permite a la aplicación obtener información del correo electrónico seleccionado que permite copiar el campo de descripción en la descripción de la tarea y permite guardar archivos adjuntos desde el correo o el propio correo en la tarea. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Group.Read.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. |  para obtener la tarea de planificador y agregar nuevas tareas actualizar el cubo y la línea de natación para el usuario específico | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.Read | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de planificador y agregar nuevas tareas, actualice el bucket y la línea de natación para el usuario específico | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.ReadBasic.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. |  Compruebe si hay permiso y para obtener la tarea de planificador y agregar nuevas tareas actualizar el bucket y la línea de natación para el usuario específico | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| perfil | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de planificador y agregar nuevas tareas, actualice el bucket y la línea de natación para el usuario específico | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.Read.All | No |  |  |  |  |
>| SharePoint - AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Read | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - MyFiles.Read | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>iGlobe recopila datos para operar eficazmente y proporcionarle las mejores experiencias con nuestros productos y servicio. Para licencias: los datos recopilados para administrar la cuenta de licencias de su organización&#8217;s, por ejemplo, al implementar un complemento gratuito, crear una suscripción de prueba o comprar una suscripción. Se recopila la siguiente información. 
- Para fines financieros: Nombre y dirección de la empresa
- Usuarios suscritos: nombre de usuario y correo electrónico

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Todos los datos están en el propio inquilino del cliente. No se almacenan datos de la aplicación. Un complemento moderno se ejecuta en un explorador de espacio aislado, &#8220;fuera de proceso&#8221;. Interactúa con los datos de los usuarios mediante servicios Microsoft. El complemento solo puede tener acceso a los datos con los que trabaja el usuario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

IGlobe ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumere los tipos de directivas admitidas | Valores predeterminados de seguridad y cualquier otra directiva común como Bloquear autenticación heredada* Requerir MFA para los administradores* Requerir MFA para la administración de Azure* Requerir MFA para todos los usuarios* |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| ¿La aplicación expone alguna API web? | No |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
