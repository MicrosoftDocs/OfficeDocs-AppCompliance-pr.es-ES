---
title: Información de aplicación para COCO de Hexaware Technologies Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para COCO, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8a25a95b277f41f30477182c9eec0b3b25b9351e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525614"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Hexaware Technologies Ltd. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | COCO |
| Id. | WA200001468 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Hexaware Technologies Ltd. |
| Dirección URL del sitio web de partners | [https://hexaware.com](https://hexaware.com) |
| Dirección URL de la directiva de privacidad | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| DIRECCIÓN URL de términos de uso | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf#page=6) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Hexaware Technologies Ltd ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegado | Ninguno | Directorio de access como el usuario que ha iniciado sesión | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.Read.All | aplicación | Ninguno | Leer datos del directorio | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.ReadWrite.All | delegado | Ninguno | Leer y escribir datos en el directorio | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read | delegado | Ninguno | Iniciar sesión y leer el perfil del usuario | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read.All | aplicación | Ninguno | Leer los perfiles completos de todos los usuarios | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.ReadWrite.All | delegado | Ninguno | Leer los perfiles completos de todos los usuarios y escribir en ellos | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| OpenID | delegado | Ninguno | Inicio de sesión de los usuarios | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para mantener los datos de sesión | Nombre, id. de correo electrónico |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>N/D

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

