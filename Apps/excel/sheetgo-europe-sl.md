---
title: Información de la aplicación sheetgo por SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Sheetgo, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cba1d32ef248cc8228a0e38e1dc953dd07f4e5ad
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548730"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 3 de noviembre de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SHEETGO EUROPE SL a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Sheetgo |
| ID | WA200002128 |
| Office 365 clientes compatibles | Excel 2016 o posterior en Mac, Excel 2016 o posterior en Windows, Excel en la Web |
| Nombre de la empresa asociada | SHEETGO EUROPE SL |
| URL del sitio web de socios | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL de la Política de Privacidad | [https://www.sheetgo.com/legal/privacy](https://www.sheetgo.com/legal/privacy) |
| URL de los Términos de uso | [https://www.sheetgo.com/legal/terms](https://www.sheetgo.com/legal/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Sheetgo EUROPE SL ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB: Grabar datos de sistema y usuario para funcionar, Google BigQuery: Grabar el uso de registros del sistema, Google Firestore: Un sistema que mantiene y orquesta el estado de nuestros microservicios, Stripe: Sistema de pago |  | Estas aplicaciones no usan API adicionales de Microsoft |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Telemetría/registros incluye la dirección de correo electrónico del usuario solo como información identificable por el usuario final. Cuando el usuario lo solicita, el equipo de soporte técnico de la aplicación ejecuta una rutina automática interna que desenfoca las direcciones de correo electrónico en telemetría/registros y hace que los datos de usuario ya no sean identificables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>MongoDB: Grabar datos de usuario y sistema para funcionar con Google BigQuery: Grabar registros del sistema de uso Google Firestore: Un sistema que mantiene y orquesta el estado de nuestros microservicios. Los únicos datos críticos que transita este servicio son la credencial de usuario, que se cifra mediante AES256 Stripe: Sistema de pago.
 
Todos los datos en tránsito utilizan HTTPS para conexiones seguras y todos los datos confidenciales se cifran mediante AES256

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

