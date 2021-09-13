---
title: Información de aplicaciones para Salesforce por salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Salesforce, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 152885012f81c077fc0bb018fda7080867c54986
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288656"
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
>| API de JavaScript para Office | Sí | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad Outlook usuario actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores, CreateItem (.js), que se usa para crear un borrador de mensaje. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad Outlook usuario actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores, CreateItem (.js), que se usa para crear un borrador de mensaje. |
>| Servicios Web Exchange (EWS) | Sí | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones de Office.js y EWS para copiar contenido y datos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. En el lado del calendario, se usan funciones similares para registrar citas en Salesforce. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad Outlook usuario actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores, CreateItem (.js), que se usa para crear un borrador de mensaje. | El complemento usa funciones como getUserIdentityTokenAsync para obtener la identidad Outlook usuario actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregar al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta borradores, CreateItem (.js), que se usa para crear un borrador de mensaje. |

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

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

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
