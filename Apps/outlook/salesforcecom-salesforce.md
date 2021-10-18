---
title: Información de aplicaciones para Salesforce por salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Salesforce, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b15f111d61d974a71eade2e5a3322ea3ee3431ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429748"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por salesforce.com a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Salesforce |
| Id. | WA104379334 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la Web |
| Nombre de la compañía asociada | salesforce.com |
| Dirección URL del sitio web de partners | [https://www.salesforce.com](https://www.salesforce.com) |
| Dirección URL de la directiva de privacidad | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por salesforce.com acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API de JavaScript para Office | Sí | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad de usuario de Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores,  CreateItem (.js), que se usa para crear un borrador de mensaje. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad de usuario de Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores,  CreateItem (.js), que se usa para crear un borrador de mensaje. |
>| Servicios Web Exchange (EWS) | Sí | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad de usuario de Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores,  CreateItem (.js), que se usa para crear un borrador de mensaje. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad de usuario de Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores,  CreateItem (.js), que se usa para crear un borrador de mensaje. |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El almacenamiento de Salesforce se describe en la Guía de seguridad en https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por salesforce.com sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
