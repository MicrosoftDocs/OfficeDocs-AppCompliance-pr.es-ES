---
title: Información de la aplicación para la participación de ventas de alcance Outlook por Outreach
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Outreach Sales Engagement para Outlook, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 483fb4fd6741e479403e4cd05ad284b50a87f9c4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413562"
---
# <a name="outreach-sales-engagement-for-outlook"></a>Engagement de ventas de alcance para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Outreach a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Engagement de ventas de alcance para Outlook |
| Id. | WA104381052 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la Web |
| Nombre de la compañía asociada | Alcance |
| Dirección URL del sitio web de partners | [https://www.outreach.io](https://www.outreach.io) |
| Dirección URL de la directiva de privacidad | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Outreach ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook API de complemento, API de EWS, API de REST de O36 | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | La integración de alcance con Salesforce permite la sincronización bidireccional segura de un conjunto de datos limitado entre ambos servicios, entre los que se incluyen; Nombre de la organización, dirección de correo electrónico y nombre de usuario. | La sincronización bidireccional inteligente de Outreach garantiza una fidelidad completa entre los datos de ambos sistemas. Todas las actividades ejecutadas en Outreach &#8212; llamadas, correos electrónicos, etc &#8212;. se registran automáticamente en Salesforce y la resolución de conflictos detecta y resuelve conflictos para mantener los datos sin problemas. Funciona en las ediciones Salesforce Aloha y Lightning. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>El alcance no aplica períodos de retención a los datos de&#8217;cliente. El alcance funciona como procesador de datos y, como tal, nunca realiza cambios en los datos de&#8217;sin su permiso explícito. Todos los datos de los clientes se eliminan 60 días después de finalizar la relación comercial, según nuestra MSA y DPA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El alcance, por motivos contractuales y reglamentarios, también es necesario proporcionar un aviso a tiempo a todos los clientes sobre el uso de un nuevo o cambio en un subprocesador. Para la mayoría de los clientes de outreach, este período es de 30 días. Sin embargo, tenemos algunos clientes con requisitos de 60 y 90 días de aviso. No se pueden transferir datos de clientes hasta después de que se haya enviado a todos los clientes la notificación legalmente requerida de un nuevo subproceso y haya pasado el período de tiempo aplicable requerido.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Outreach ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

