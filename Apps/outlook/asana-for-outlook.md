---
title: Información de aplicación para Asana para Outlook por Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Asana para Outlook, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 635d3f73c582fbc6a89fbca0798b0dec271ab3f5
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252981"
---
# <a name="asana-for-outlook"></a>Asana para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 2, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Asana a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Asana para Outlook |
| ID | WA104381833 |
| Office 365 clientes compatibles | Outlook 2016 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la compañía asociada | Asana |
| Dirección URL del sitio web de partners | [https://asana.com/](https://asana.com/) |
| Dirección URL de la directiva de privacidad | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Asana sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| El complemento transfiere información básica de correo electrónico (remitente, recepient, asunto, cuerpo) y datos adjuntos a Asana cuando lo solicita el usuario. |  | Correo electrónico: lee el correo electrónico abierto actualmente cuando se muestra en un panel de tareas. - Lee los datos adjuntos de correo electrónico abiertos actualmente para cargarlos en tareas de Asana. - Esto proporciona a los usuarios la capacidad de realizar tareas rápidamente en Asana con información de correos electrónicos. |



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Elemento ReadWrite | Este complemento puede tener acceso y modificar la información personal del mensaje activo, como el cuerpo, el asunto, el remitente, los destinatarios y la información de datos adjuntos. Puede enviar estos datos a un servicio de terceros. Otros elementos del buzón de correo&#8217;no se pueden leer ni modificar. |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nuestra aplicación solo registra información relacionada con los datos de Asana. La única vez que registramos cualquier cosa relacionada con la información de usuario de Outlook es cuando el usuario adjunta explícitamente un correo electrónico o carga datos adjuntos en Asana, e incluso entonces no registramos el contenido. Los registros a corto plazo existen en servidores que pueden incluir algunos datos de usuario, pero son efímeros y se limitan a períodos inferiores a 72 horas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Enterprise clientes tienen cifrado garantizado en reposo con AES-256. Los datos se almacenan en Amazon Web Services y AWS administra las claves de cifrado mediante su sistema de administración de claves. Tenemos 2FA para todos los administradores. El acceso se da en el principio de privilegios mínimos.
Los administradores de la organización de Asana tienen la capacidad de configurar SAML, SCIM, cuentas de servicio y tener una vista general de los datos que se ponen en la herramienta. Los administradores pueden solicitar una exportación organizativa completa desde la consola de administración y auditar según sea necesario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

