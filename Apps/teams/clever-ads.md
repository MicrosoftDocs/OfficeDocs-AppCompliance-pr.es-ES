---
title: Información de la aplicación para anuncios inteligentes de Anuncios inteligentes
ms.author: elmalova
author: elenamalova
ms.date: 04/24/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Anuncios inteligentes, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23ea73534c5bafc739798de6e9326ee908961c03
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096554"
---
# <a name="clever-ads"></a>Clever Ads

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: April 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/ac2b56c0-f2a5-4e90-b618-882f8d3596f0" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001182" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Clever Ads a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Clever Ads |
| Id. | WA200001182 |
| Capacidades | Bot, pestaña, extensión de mensajería, conector |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Clever Ads |
| Dirección URL del sitio web de partners | [https://www.cleverads.com/](https://www.cleverads.com/) |
| Dirección URL de la directiva de privacidad | [https://www.cleverads.com/privacy-policy](https://www.cleverads.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.cleverads.com/terms-conditions](https://www.cleverads.com/terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Clever Ads ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegado | User.Read: Almacenamos UPN, AzureObjectId para identificar al usuario. | User.Read, permite al usuario iniciar sesión en nuestro panel de aplicaciones. Usamos UPN, AzureObjectId para iniciar sesión en el usuario. | ac2b56c0-f2a5-4e90-b618-882f8d3596f0 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| La aplicación accede a la lista para identificar si un usuario pertenece al equipo o no y envía mensajes programados por el usuario a sus equipos. | Almacenamos el id. de usuario, azureObjectId, UPN, tenantId, conversationId y serviceUrl para poder enviar mensajes al usuario o equipo e identificarlo al acceder a la pestaña del panel. |  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No almacenamos información organizativa en nuestros registros o telemetría. Solo registramos acciones de usuario como enviar un mensaje al bot o hacer clic en un botón, incluso en esos registros el identificador del usuario es nuestro identificador de usuario interno, no relacionado con el identificador de Microsoft Teams.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de la aplicación se almacenan en una base de datos de MySQL hospedada en Google Cloud, el sistema de copia de seguridad se agrega para nuestras bases de datos y se administran mediante PMA y ip protegidas.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

