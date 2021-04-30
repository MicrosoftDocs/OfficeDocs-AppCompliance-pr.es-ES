---
title: Información de la aplicación para Google Analytics Insights de Freevolut LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Google Analytics Insights, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 54a47ddd9cfda3dd6d8b480eb1501e5cf8191e40
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096516"
---
# <a name="google-analytics-insights"></a>Google Analytics Insights

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/aeff86e0-d07b-4537-ad02-9980424a93c5" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000743" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Freevolut LTD a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Google Analytics Insights |
| Id. | WA200000743 |
| Capacidades | Conector |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Freevolut LTD |
| Dirección URL del sitio web de partners | [https://www.ga-insights.com](https://www.ga-insights.com) |
| Dirección URL de la directiva de privacidad | [https://www.ga-insights.com/Privacy](https://www.ga-insights.com/Privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.ga-insights.com/Terms](https://www.ga-insights.com/Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Freevolut LTD ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>no

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>CosmosDb, cifrado en reposo. También Redis, también cifrado. Las credenciales de Azure están protegidas en el último paso, solo una persona tiene acceso a las claves de producción y una autenticación de 2FA. Las IP están en la lista blanca.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35840' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35840" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

