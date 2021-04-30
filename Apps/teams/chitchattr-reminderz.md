---
title: Información de la aplicación para Reminderz de ChitChattr
ms.author: elmalova
author: elenamalova
ms.date: 12/09/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Reminderz, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c7d3cecbbfa9613f706e52c8e71b64bd93c6cba0
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096563"
---
# <a name="reminderz"></a>Reminderz

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 9, 2020</p>

* <a href="https://teams.microsoft.com/l/app/672c12b8-883e-4138-8318-224420bdafe8" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001976" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ChitChattr a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Reminderz |
| Id. | WA200001976 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ChitChattr |
| Dirección URL del sitio web de partners | [https://www.chitchattr.com?p=reminderz](https://www.chitchattr.com?p=reminderz) |
| Dirección URL de Teams de información de la aplicación | [https://www.chitchattr.com/reminderz/](https://www.chitchattr.com/reminderz/) |
| Dirección URL de la directiva de privacidad | [https://www.chitchattr.com/privacy?p=reminderz](https://www.chitchattr.com/privacy?p=reminderz) |
| DIRECCIÓN URL de términos de uso | [https://www.chitchattr.com/termsofuse?p=reminderz](https://www.chitchattr.com/termsofuse?p=reminderz) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ChitChattr ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Bot Framework Services | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Los nombres de los usuarios se recuperan, para mostrar el nombre del usuario que envió el mensaje, en el aviso.  | Nombre para mostrar del usuario | Los nombres se almacenan para la identificación de las consultas de licencias (cuando un usuario pide una licencia, necesitamos determinar los usuarios con licencia actualmente)  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>id. de inquilino y usuario AadObjectId

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Solo usamos servicios hospedados en Azure (incluido Mongo Atlas) y tenemos control total sobre los datos de estos servicios.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36320' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36320" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ChitChattr ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
