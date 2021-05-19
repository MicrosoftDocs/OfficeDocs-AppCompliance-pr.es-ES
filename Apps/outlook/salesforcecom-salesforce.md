---
title: Información de la aplicación para Salesforce por salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Salesforce, sus políticas de gestión de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553711"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por salesforce.com a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Salesforce |
| ID | WA104379334 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la empresa asociada | salesforce.com |
| URL del sitio web de socios | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL de la Política de Privacidad | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL de los Términos de uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Salesforce.com ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | El complemento utiliza funciones de Office.js e EWS para copiar contenido y archivos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. Se utilizan capacidades similares en el lado del calendario, para registrar citas en Salesforce. |  | El complemento utiliza funciones como getUserIdentityTokenAsync para obtener la identidad de usuario Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregarlos al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta drafts, CreateItem (.js), que se utiliza para crear un mensaje de borrador. |  |
>| Servicios Web Exchange (EWS) | Sí | El complemento utiliza funciones de Office.js e EWS para copiar contenido y archivos adjuntos sobre un correo electrónico que un usuario Outlook ha decidido iniciar sesión en Salesforce. Se utilizan capacidades similares en el lado del calendario, para registrar citas en Salesforce. |  | El complemento utiliza funciones como getUserIdentityTokenAsync para obtener la identidad de usuario Outlook actual, GetItem (.js y EWS) para obtener y establecer AdditionalProperties y el contenido del mensaje de correo electrónico actual al guardar en registros de Salesforce, GetAttachment (EWS) para recuperar los datos adjuntos de Exchange y agregarlos al correo electrónico de Salesforce emparejado, UpdateItem (.js), GetFolder (.js) para obtener la carpeta drafts, CreateItem (.js), que se utiliza para crear un mensaje de borrador. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>El almacenamiento de Salesforce se describe en la Guía de seguridad de https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

