---
title: Información de la aplicación para Asana para Outlook por Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Asana para Outlook, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cd3d403d7b25c1ad5dda60dff8d93c18dfe59c30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553751"
---
# <a name="asana-for-outlook"></a>Asana para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 2 de noviembre de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Asana a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Asana para Outlook |
| ID | WA104381833 |
| Office 365 clientes compatibles | Outlook 2016 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la empresa asociada | Asana |
| URL del sitio web de socios | [https://asana.com/](https://asana.com/) |
| URL de la Política de Privacidad | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL de los Términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Asana ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| El complemento transfiere información básica de correo electrónico (remitente, recepient, sujeto, cuerpo) y archivos adjuntos a Asana cuando lo solicita el usuario. |  | Correo electrónico: lee el correo electrónico abierto actualmente cuando se muestra en un panel de tareas. - Lee actualmente archivos adjuntos de correo electrónico abiertos para cargarlos en tareas de Asana. - Esto proporciona a los usuarios la capacidad de realizar rápidamente tareas en Asana con información de correos electrónicos. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Nuestra aplicación solo registra información relacionada con los datos de Asana. La única vez que registramos algo relacionado con Outlook información del usuario es cuando el usuario adjunta explícitamente un correo electrónico o carga un archivo adjunto a Asana, e incluso entonces no registramos el contenido. Existen registros a corto plazo en servidores que pueden incluir algunos datos de usuario, pero son efímeros y están limitados a períodos inferiores a 72 horas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Enterprise clientes tienen cifrado garantizado en reposo mediante AES-256. Los datos se almacenan en Amazon Web Services y AWS administra las claves de cifrado mediante su sistema de administración de claves. Tenemos 2FA para todos los administradores. El acceso se da sobre el principio de privilegio mínimo.
Los administradores de Asana Organizational tienen la capacidad de configurar cuentas SAML, SCIM, Service y tienen una vista general de los datos que se colocan en la herramienta. Los administradores pueden solicitar una exportación completa de la organización desde la consola de administración y la auditoría según sea necesario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

