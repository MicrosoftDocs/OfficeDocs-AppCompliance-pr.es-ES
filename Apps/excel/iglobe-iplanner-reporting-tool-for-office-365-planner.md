---
title: Herramienta de informes de la aplicación para iPlanner para Office 365 Planner por iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para la herramienta de informes de iPlanner para Office 365 Planner, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 354eaa3d38bd05834d7083a52ee6f5b723aaab64
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428172"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Herramienta de informes de iPlanner para Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Herramienta de informes de iPlanner para Office 365 Planner |
| Id. | WA104380686 |
| Office 365 clientes compatibles | Excel 2016 o posterior en Windows, Excel en la Web, Excel 2016 o posterior en Mac |
| Nombre de la compañía asociada | iGlobe |
| Dirección URL del sitio web de partners | [https://iglobecrm.com/](https://iglobecrm.com/) |
| Dirección URL de la directiva de privacidad | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| DIRECCIÓN URL de términos de uso | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para crear una entrada de calendario en el calendario&#8217;calendario en la fecha de vencimiento de la tarea. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para comprobar que el usuario tiene consentimiento y tiene acceso a la API. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de Outlook To Do, marca los correos electrónicos y actualizándolos. Para crear una nueva tarea de Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para tener acceso al archivo como datos adjuntos y cargar archivos en una tarea. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la lista de planes y actualizar la tarea. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea del organizador y agregar nuevas tareas, actualice el cubo y la línea de natación. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | delegado | No se almacenan datos en bases de datos de aplicaciones. | User.Read, para obtener la tarea de Outlook To Do, marcar correos electrónicos y actualizarlos. Para crear una nueva tarea de Planner | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para mostrar los correos y enviar correo. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Obtener el asunto de correo del correo seleccionado. Permite que la aplicación obtenga información del correo electrónico seleccionado, lo que permite copiar el campo de descripción en la descripción de la tarea y permitir guardar datos adjuntos del correo o del propio correo en la tarea. Enviar notificación. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener los usuarios que han iniciado sesión Outlook To Do y actualizar User.Read, para obtener la tarea del organizador Outlook To Do, marcar correos electrónicos y actualizarlos. Para crear una nueva tarea de Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegado | No se almacenan datos en bases de datos de aplicaciones. | Iniciar sesión y leer el perfil del usuario | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



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

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

