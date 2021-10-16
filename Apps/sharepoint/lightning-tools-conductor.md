---
title: Información de aplicación para Lightning Tools Lightning Conductor de Lightning Tools
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Lightning Tools Lightning Conductor, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9541cab6ba5fcd7da59cfe43c89e2e3bf3fceab9
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412049"
---
# <a name="lightning-tools-lightning-conductor"></a>Lightning Tools Lightning Conductor

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001926" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Lightning Tools a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Lightning Tools Lightning Conductor |
| Id. | WA200001926 |
| Office 365 clientes compatibles | SharePoint 2016 o posterior |
| Nombre de la compañía asociada | Herramientas de Lightning |
| Dirección URL del sitio web de partners | [https://lightningtools.com](https://lightningtools.com) |
| Dirección URL de la directiva de privacidad | [https://lightningtools.com/lightning-conductor-cswp-privacy...](https://lightningtools.com/lightning-conductor-cswp-privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://lightningtools.com/lightning-tools-lightning-conduc...](https://lightningtools.com/lightning-tools-lightning-conductor-client-side-web-part-software-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Lightning Tools ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicación | Para consultar e informar sobre la información del calendario | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Contacts.Read | aplicación | No se recopilan ni almacenan datos. Los datos se usan para mostrar el DisplayName de los contactos de los usuarios actuales | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Directory.Read.All | aplicación | Mostrar usuarios en el director de rayos | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Files.Read.All | aplicación | Mostrar OneDrive archivos en el Conductor de rayos | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Mail.Read | aplicación | Si la consulta en el Administrador de rayos muestra mensajes del buzón de usuarios actuales | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| People.Read.All | aplicación | Para mostrar la vista de personas en el Administrador de rayos si se consulta a los usuarios como miembros de un sitio. | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Presence.Read.All | aplicación | Para mostrar la presencia de los usuarios en la tarjeta de personas | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Sites.Read.All | aplicación | Para enumerar sitios en la vista de árbol de Lightning Conductor | El conductor lightning no usa una base de datos ni almacena datos. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de la aplicación residen en el inquilino del cliente. Lightning Tools no almacena ni procesa datos fuera del inquilino del cliente. 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Lightning Tools ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

