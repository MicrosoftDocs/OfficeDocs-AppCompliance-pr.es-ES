---
title: Información de solicitud de ServiceDesk Plus para correo electrónico por Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para ServiceDesk Plus para correo electrónico, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dc342375eba7084f5afb31b0f879e46e959fa970
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553661"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus para correo electrónico

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ServiceDesk Plus para correo electrónico |
| ID | WA104381518 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la empresa asociada | Zoho Corporation Private Limited |
| URL del sitio web de socios | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de la Política de Privacidad | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
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
>| Calendars.ReadWrite | aplicación |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegado | ID de correo electrónico del usuario. | Permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | aplicación |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegado | ID de correo electrónico, Nombre, ID de empleado, Título de trabajo, Teléfono, Móvil, Sitio, Departamento, Configuración regional, Foto de perfil del usuario. | Permite importar la información básica de los usuarios desde Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegado | ID de correo electrónico del usuario. | Ver la dirección de correo electrónico del usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegado |  | Mantenga el acceso a los datos a los que le ha dado acceso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | Delegado |  | Ver el perfil básico del usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No recopilamos EUII / PII en telemetría / registros. Tenemos scripts en su lugar que buscan patrones y alerta para arreglarlo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Todos los datos se cifran en REST. Sólo las personas autorizadas tienen acceso al sistema que de todos modos está protegido, completamente auditado para todo tipo de acceso. MFA en su lugar para el acceso, las cuentas autorizadas se mantienen en un directorio corporativo y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

