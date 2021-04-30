---
title: Información de la aplicación para iGlobe CRM Office 365 para Microsoft Office 365 por iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para iGlobe CRM Office 365 para Microsoft Office 365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 92b4b115c22593fac898e9ebaeaf49af855c5137
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096619"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>IGlobe CRM Office 365 para Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | IGlobe CRM Office 365 para Microsoft Office 365 |
| Id. | WA104379222 |
| Office 365 clientes compatibles | SharePoint 2013 o posterior |
| Nombre de la compañía asociada | iGlobe |
| Dirección URL del sitio web de partners | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| Dirección URL de la directiva de privacidad | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| DIRECCIÓN URL de términos de uso | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Tener acceso a los calendarios de usuario al retirar un informe de reunión del canlendar en iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | delegado |  Directory.AccessAsUser.All | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Compruebe si hay permiso y para obtener los sitios y las listas. Crear carpetas, obtener archivos y guardar archivos. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos y datos en SharePoint listas. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en SharePoint listas. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en SharePoint listas. Integración con iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Svae el eamil a iGlobe CRM y obtener informatiopn de iGlobe a un nuevo e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Crear, editar y eliminar elementos y listas en iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer elementos en iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. |  Editar y eliminar elementos y listas en iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Crear tarea de planner desde iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener información sobre el CRM de iGlobe para el usuario de speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange: Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange- Mail.Read.All | No |  |  |  |  |
>| Exchange- Contacts.Read | No |  |  |  |  |
>| Exchange: EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange- Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint: AllSites.Manage | No |  |  |  |  |
>| SharePoint: AllSites.Read | No |  |  |  |  |
>|  SharePoint -AllSites.Write | No |  |  |  |  |
>| SharePoint: MyFiles.Write | No |  |  |  |  |
>| SharePoint: Sites.Manage.All | No |  |  |  |  |
>| SharePoint: Sites.Read.All | No |  |  |  |  |
>| SharePoint: Sites.ReadWrite.All | No |  |  |  |  |
>| SharePoint- Sites.Search.All | No |  |  |  |  |
>|  SharePoint- TermStore.Read.All | No |  |  |  |  |
>| SharePoint- TermStore.ReadWrite.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Valor predeterminado | No&#8217;leer o realizar cambios en el documento |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>iGlobe recopila datos para funcionar eficazmente y proporcionarle las mejores experiencias con nuestros productos y servicios. Para licencias: los datos recopilados para administrar la cuenta de licencia de&#8217;organización, como cuando implementas complementos gratuitos, creas una suscripción de prueba o compras una suscripción. Se recopila la siguiente información. 
- Con fines financieros: nombre y dirección de la empresa
- Usuarios suscritos: nombre de usuario y correo electrónico

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos están en el propio inquilino del cliente. No se almacenan datos de aplicación. Un complemento moderno se ejecuta en un explorador de espacio aislado, &#8220;fuera de proceso&#8221;. Interactúa con los datos de los usuarios mediante servicios Microsoft. El complemento solo puede tener acceso a los datos con los que trabaja el usuario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Ver en una pestaña nueva</a>

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
