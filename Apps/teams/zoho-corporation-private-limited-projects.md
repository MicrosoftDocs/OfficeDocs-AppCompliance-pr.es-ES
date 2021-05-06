---
title: Información de aplicación para proyectos de Zoho de Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Proyectos Zoho, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cd86e3cbd7fbdadbeacf6788678f53e121de6eaf
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251970"
---
# <a name="zoho-projects"></a>Zoho Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/4a39aea9-8537-4c2f-b66d-ca364eb3b80d" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381668" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zoho Projects |
| ID | WA104381668 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Zoho Corporation Private Limited |
| Dirección URL del sitio web de partners | [https://www.zoho.com/projects/](https://www.zoho.com/projects/) |
| Dirección URL de Teams de información de la aplicación | [https://www.zoho.com/projects/help/microsoft-teams-integrat...](https://www.zoho.com/projects/help/microsoft-teams-integration.html) |
| Dirección URL de la directiva de privacidad | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado |  | Tener acceso completo a los calendarios de usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read | delegado |  | Lea todos los archivos. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read.All | delegado |  | Lea todos los archivos a los que el usuario puede tener acceso. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read.Selected | delegado |  | Lea los archivos que selecciona el usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Tasks.Read | delegado |  | Leer tareas de usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Tasks.ReadWrite | delegado |  | Crear, leer, actualizar y eliminar proyectos y tareas de usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Tasks.ReadWrite.Shared | delegado |  | Leer y escribir tareas compartidas y de usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| User.Read | delegado |  | Inicie sesión y lea el perfil de usuario. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| User.ReadBasic.All | delegado |  | Lea los perfiles básicos de todos los usuarios. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| offline_access | delegado |  | Mantenga el acceso a los datos a los que le ha concedido acceso. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La información confidencial, como la anterior, se detecta a través de herramientas y se filetea como errores. Estas se abordan y se solucionan en actualizaciones correctas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>La información del partner no se almacena.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22961' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22961" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

