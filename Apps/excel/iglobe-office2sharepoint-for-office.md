---
title: Información de aplicaciones para Office2SharePoint para Office por iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Office2SharePoint para Office, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1d1fccbab2aab91eacbc5a43ef79462dd536ff6e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548850"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint para Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Office2SharePoint para Office |
| ID | WA104381787 |
| Office 365 clientes compatibles | Excel 2016 o posterior en Mac, Excel 2016 o posterior en Windows, Excel en la Web, Word 2016 o posterior en Mac, Word en la Web, Word 2016 o posterior en Windows, PowerPoint 2016 o posterior en Mac, PowerPoint en la Web, PowerPoint 2016 o posterior en Windows |
| Nombre de la compañía asociada | iGlobe |
| Dirección URL del sitio web de partners | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| Dirección URL de la directiva de privacidad | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| DIRECCIÓN URL de términos de uso | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Compruebe si hay permiso y para obtener los sitios y las listas. Crear carpetas, obtener archivos y guardar archivos. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Compruebe si hay permiso y para obtener los sitios y las listas. Crear carpetas, obtener archivos y guardar archivos. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener los sitios de grupo de usuarios. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener acceso a los correos seleccionados y obtener los datos adjuntos. Desde el correo o desde el sitio SharePoint grupos al correo. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Mail.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener acceso a los correos seleccionados y obtener los datos adjuntos. Desde el correo o desde el sitio SharePoint grupos al correo. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación cree o elimine listas y bibliotecas de documentos en todas las colecciones de sitios en nombre del usuario que ha iniciado sesión. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener los usuarios SharePoint sitio. Obtener archivos y guardar datos adjuntos del correo seleccionado. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener SharePoint, bibliotecas y archivos. Para guardar archivos en SharePoint listas. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener los usuarios SharePoint sitio, OneDrive y Sitios de grupo. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange: EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange- Mail.ReadWrite | No |  |  |  |  |
>| Exchange- MailboxSettings.ReadWrite | No |  |  |  |  |
>| SharePoint: AllSites.Manage | No |  |  |  |  |
>| SharePoint: AllSites.Write | No |  |  |  |  |
>| SharePoint: MyFiles.Write | No |  |  |  |  |
>| SharePoint- User.Read.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>iGlobe recopila datos para funcionar eficazmente y proporcionarle las mejores experiencias con nuestros productos y servicios. Para licencias: los datos recopilados para administrar la cuenta de licencia de&#8217;organización, como cuando implementas complementos gratuitos, creas una suscripción de prueba o compras una suscripción. Se recopila la siguiente información. Con fines financieros: Nombre de la compañía y dirección Usuarios suscritos: nombre de usuario y correo electrónico


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos de la aplicación están en el propio inquilino del cliente y son controlados por el administrador de inquilinos como todos los demás servicios de Office 365. No se almacenan datos de la aplicación en el complemento. Un complemento moderno se ejecuta en un explorador de espacio aislado, &#8220;fuera de proceso&#8221;. El complemento solo puede tener acceso a los datos con los que trabaja el usuario. Interactúa con los datos de los usuarios mediante servicios Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

IGlobe ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Valores predeterminados de seguridad y cualquier otra de las directivas comunes como Bloquear autenticación heredada* Requerir MFA para administradores* Requerir MFA para administración de Azure* Requerir MFA para todos los usuarios* |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
