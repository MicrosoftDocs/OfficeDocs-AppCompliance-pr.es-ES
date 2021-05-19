---
title: Información de aplicación para la herramienta Zoho Campaigns para la automatización de marketing de Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para la herramienta Zoho Campaigns para la automatización de marketing, sus políticas de gestión de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e67de0ca2871d5432b5a29ead52194225bc51c9a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553691"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>Herramienta Zoho Campaigns para la automatización del marketing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Herramienta Zoho Campaigns para la automatización del marketing |
| ID | WA104380835 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la empresa asociada | Zoho Corporation Private Limited |
| URL del sitio web de socios | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la Política de Privacidad | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL de los Términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegado | Calendar Id se almacena para crear eventos en ese calendario a partir de campañas de Zoho. | Permite al usuario importar el evento de calendario de Office365 a zoho campaigns. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Calendars.ReadWrite | Delegado |  | Permite al usuario agregar eventos de Zoho Campaigns al calendario de Office365. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.Read | Delegado |  Para guardar la información de contacto. | Permite al usuario importar contactos de Office365 a campañas de Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegado | El correo electrónico se almacena para la identificación del usuario. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts en su lugar para buscar y alertar para la fijación de dichos datos que sean visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>El cliente puede seleccionar los datos que deben cifrarse a través de EAR (Cifrado en reposo) con restricciones de certaat. Las contraseñas se verán hash de forma predeterminada. El acceso lógico a los servidores se proporciona a través de una red dedicada aislada &amp; y está altamente protegido y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

