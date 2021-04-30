---
title: 'Información de la aplicación para el seguimiento de facturas y horas: zoho invoice by Zoho Corporation Private Limited'
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: 'Toda la información de seguridad y cumplimiento disponible para el seguimiento de facturas y horas: Factura Zoho, sus directivas de tratamiento de datos, su información del catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.'
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 900935b6422b2a9e48ddb0a79c92c0b1f6b4d139
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096653"
---
# <a name="invoice-and-time-tracking---zoho-invoice"></a>Seguimiento de factura y tiempo: factura de Zoho

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381067" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Seguimiento de factura y tiempo: factura de Zoho |
| Id. | WA104381067 |
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
>| Contacts.Read | delegado |  |  Permitir que los usuarios sincronicen contactos de Office365 con Zoho Invoice. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Read | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Send | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Export.All | delegado |  | Permitir que el usuario exporte toda la información relacionada con el usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | delegado |  | Permitir a los usuarios iniciar sesión y leer el perfil de usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegado |  | Permitir a los usuarios importar usuarios de Office365 a Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
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

>No recopilamos EUII / PII en telemetría y registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos se recuperarán solo después del consentimiento del usuario. El acceso lógico a los servidores se proporciona a través de una red &amp; dedicada aislada y está altamente protegido y supervisado. Esta red está protegida con firewall, autenticación de factor 2 y autenticación Kerberos


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

