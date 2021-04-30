---
title: Información de la aplicación para ServiceDesk Plus Cloud de Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para ServiceDesk Plus Cloud, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3a0123395ff8f6991648c25e6d6e7e10a8d1f3a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096794"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ServiceDesk Plus Cloud |
| Id. | WA200000037 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Zoho Corporation Private Limited |
| Dirección URL del sitio web de partners | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| Dirección URL de Teams de información de la aplicación | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| Dirección URL de la directiva de privacidad | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicación |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegado | Id. de correo electrónico del usuario. | Permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | aplicación |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegado | Id. de correo electrónico, nombre, id. de empleado, puesto de trabajo, Teléfono, móvil, sitio, departamento, configuración regional, foto de perfil del usuario. | Permite importar la información básica de los usuarios desde Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegado | Id. de correo electrónico del usuario. | Ver la dirección de correo electrónico del usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegado |  | Mantenga el acceso a los datos a los que le ha concedido acceso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | delegado |  | Ver el perfil básico del usuario. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No recopilamos EUII / PII en telemetría / registros. Tenemos scripts en su lugar que buscan patrones y alertas para corregirlo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos se cifran en REST. Solo las personas autorizadas tienen acceso al sistema que, de todos modos, está protegido y completamente auditado para todo tipo de acceso. MFA en su lugar para el acceso, las cuentas autorizadas se mantienen en un directorio corporativo y un host


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

