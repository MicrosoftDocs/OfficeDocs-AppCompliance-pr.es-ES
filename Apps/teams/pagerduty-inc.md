---
title: Información de la aplicación para PagerDuty de PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para PagerDuty, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7c929966d7ab24f4e353ced553ea89737d5b7058
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430178"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por PagerDuty, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | PagerDuty |
| Id. | WA200001637 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | PagerDuty, Inc. |
| Dirección URL del sitio web de partners | [https://www.pagerduty.com](https://www.pagerduty.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| Dirección URL de la directiva de privacidad | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

PagerDuty, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | delegado | Desde la creación y obtención de respuestas de reuniones, estamos usando estos campos: join_web_url, audioconferencia. Estos campos son necesarios para mostrar al usuario un vínculo a una reunión o formas alternativas de conectarse en la reunión. | Guardamos: join_web_url, audioconferencia. Estos campos son necesarios para mostrar al usuario un vínculo a una reunión o formas alternativas de conectarse en la reunión. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | delegado | Usar para agregar la aplicación pagerduty al chat. | Usar para agregar la aplicación pagerduty al chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | delegado | Usar para agregar la aplicación pagerduty al chat. | Usar para agregar la aplicación pagerduty al chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | delegado | Usar para agregar la aplicación pagerduty como pestaña en la reunión | Usar para agregar la aplicación pagerduty como pestaña en la reunión | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | delegado | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | delegado | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos son necesarios para obtener información sobre reuniones de usuario y en línea | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos se requisa para obtener información sobre reuniones de usuario y en línea | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OpenID | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos se requisa para obtener información sobre el usuario y crear/obtener reuniones en línea | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| perfil | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos se requisa para obtener información sobre el usuario y crear/obtener reuniones en línea | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | delegado | Desde la creación y obtención de respuestas de reuniones, estamos usando estos campos: join_web_url, audioconferencia. Estos campos son necesarios para mostrar al usuario un vínculo a una reunión o formas alternativas de conectarse en la reunión. | Guardamos: join_web_url, audioconferencia. Estos campos son necesarios para mostrar al usuario un vínculo a una reunión o formas alternativas de conectarse en la reunión. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | delegado | Usar para agregar la aplicación pagerduty al chat. | Usar para agregar la aplicación pagerduty al chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | delegado | Usar para agregar la aplicación pagerduty al chat. | Usar para agregar la aplicación pagerduty al chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | delegado | Usar para agregar la aplicación pagerduty como pestaña en la reunión | Usar para agregar la aplicación pagerduty como pestaña en la reunión | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | delegado | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | delegado | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | Se usan datos: id, userPrincipalName . Se usa para que los usuarios de Microsoft Teams los agreguen a la reunión como participantes | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos son necesarios para obtener información sobre reuniones de usuario y en línea | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos son necesarios para obtener información sobre reuniones de usuario y en línea | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| OpenID | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos se requisa para obtener información sobre el usuario y crear/obtener reuniones en línea | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| perfil | delegado | Uso para solicitudes de autorización y token. Se usan datos: access_token, refresh_token, expires_in, ámbito | access_token, refresh_token, expires_in, ámbito. Estos datos se requisa para obtener información sobre el usuario y crear/obtener reuniones en línea | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Los datos que PagerDuty mantiene se limitan a los datos de máquina de productos de supervisión y la información de PII está limitada a: dirección de correo electrónico corporativa, nombre, apellido y número de teléfono. Aquí se puede encontrar una lista de subprocesadores con acceso a estos datos: https://www.pagerduty.com/subprocessors/ | Los datos que PagerDuty mantiene se limitan a los datos de máquina de productos de supervisión y la información de PII está limitada a: dirección de correo electrónico corporativa, nombre, apellido y número de teléfono. Aquí se puede encontrar una lista de subprocesadores con acceso a estos datos: https://www.pagerduty.com/subprocessors/ | Los datos que PagerDuty mantiene se limitan a los datos de máquina de productos de supervisión y la información de PII está limitada a: dirección de correo electrónico corporativa, nombre, apellido y número de teléfono. Puede encontrar una lista de subprocesadores con acceso a estos datos aquí: Encontrará más información sobre la privacidad de los datos https://www.pagerduty.com/subprocessors/ aquí: https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>PagerDuty requiere estándares de seguridad de datos al menos tan estrictos como los mantenidos por PagerDuty para que sean mantenidos por todos los proveedores con los que transferimos datos, incluida una obligación contractual en forma de DPA firmado. Puede encontrar más información sobre nuestros estándares de seguridad de datos aquí: https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

PagerDuty, Inc. ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
