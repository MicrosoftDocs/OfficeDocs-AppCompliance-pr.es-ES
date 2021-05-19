---
title: Información de la aplicación para la herramienta de informes iPlanner para Office 365 Planner por iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para la herramienta de informes iPlanner para Office 365 Planner, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548770"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Herramienta de informes de iPlanner para Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Herramienta de informes de iPlanner para Office 365 Planner |
| ID | WA104380686 |
| Office 365 clientes compatibles | Excel 2016 o más tarde en Windows, Excel en la Web, Excel 2016 o posterior en Mac |
| Nombre de la empresa asociada | iGlobe |
| URL del sitio web de socios | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL de la Política de Privacidad | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL de los Términos de uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para crear una entrada de calendario en el calendario de&#8217;s del usuario en la fecha de vencimiento de la tarea. |  |
>| Directory.AccessAsUser.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para comprobar que el usuario tiene consentimiento y tiene acceso a utilizar la API. |  |
>| Directory.ReadWrite.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de planificador Outlook To Do, marcar correos electrónicos y actualizarlos. Para crear una nueva tarea de planificador. |  |
>| Files.ReadWrite.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para acceder al archivo como archivo adjunto y cargar archivos en una tarea. |  |
>| Group.Read.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la lista de planes y actualizar la tarea. |  |
>| Group.ReadWrite.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de planificador y agregar nuevas tareas, actualice el bucket y la línea de natación. |  |
>| Mail.Read | Delegado | No se almacenan datos en bases de datos de aplicaciones. | User.Read, para obtener la tarea de planificador Outlook To Do, correos electrónicos marcados y actualizarlos. Para crear una nueva tarea de planificador |  |
>| Mail.ReadWrite | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para mostrar los correos y enviar correo. |  |
>| Mail.ReadWrite.All | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Obtenga el asunto del correo del correo seleccionado. Permite a la aplicación obtener información del correo electrónico seleccionado que permite copiar el campo de descripción en la descripción de la tarea y permite guardar archivos adjuntos desde el correo o el propio correo en la tarea. Enviar notificación. |  |
>| Tasks.ReadWrite | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener el inicio de sesión de los usuarios Outlook To Do y actualizar User.Read, para obtener la tarea de planificador Outlook To Do, marcar correos electrónicos y actualizarlos. Para crear una nueva tarea de planificador. |  |
>| User.Read | Delegado | No se almacenan datos en bases de datos de aplicaciones. | Iniciar sesión y leer el perfil del usuario |  |


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

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

