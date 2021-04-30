---
title: Herramienta De información de aplicaciones para campañas de Zoho para automatización de marketing de Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para la herramienta Campañas de Zoho para la automatización de marketing, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0c8422a016ac803605ab37c10e93f1afe4de657c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096657"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>Herramienta Campañas de Zoho para la automatización de marketing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Herramienta Campañas de Zoho para la automatización de marketing |
| Id. | WA104380835 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la compañía asociada | Zoho Corporation Private Limited |
| Dirección URL del sitio web de partners | [https://www.zoho.com/](https://www.zoho.com/) |
| Dirección URL de la directiva de privacidad | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegado | El identificador de calendario se almacena para crear eventos en ese calendario a partir de las campañas de Zoho. | Permite al usuario importar el evento del calendario de Office365 a las campañas de Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Calendars.ReadWrite | delegado |  | Permite al usuario agregar eventos de Campañas Zoho al calendario de Office365. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.Read | delegado |  Para guardar la información de contacto. | Permite al usuario importar contactos de Office365 a campañas de Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegado | El correo electrónico se almacena para la identificación del usuario. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Leer elemento | Este complemento puede tener acceso a información personal del mensaje activo, como nombres de remitente, nombres de destinatarios, direcciones de correo electrónico, cuerpo del mensaje e información de datos adjuntos. El complemento puede enviar estos datos a un servicio de terceros. Otros elementos del buzón de correo&#8217;no se pueden leer ni modificar. |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts en su lugar para buscar y alertar para corregir dichos datos que están visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El cliente puede seleccionar los datos que deben cifrarse mediante EAR (Cifrado en reposo) con restricciones de certaat. Las contraseñas se hasherán de forma predeterminada. El acceso lógico a los servidores se proporciona a través de una red &amp; dedicada aislada y está altamente protegido y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

