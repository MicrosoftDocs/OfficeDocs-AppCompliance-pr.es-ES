---
title: Información de la aplicación para BlackBerry AtHoc by BlackBerry
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para BlackBerry AtHoc, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 38d1d54293b3f406a0a5c8028850dae27a9c9294
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284080"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por BlackBerry a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | BlackBerry AtHoc |
| Id. | WA200003065 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | BlackBerry |
| Dirección URL del sitio web de partners | [https://www.blackberry.com](https://www.blackberry.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| Dirección URL de la directiva de privacidad | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

BlackBerry ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| OpenID | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| perfil | delegado | Accedemos a los&#8217;básicos del usuario, como el nombre principal y el vínculo al canal general de teams (para el que está autorizado el usuario que ha iniciado sesión) para enviar la tarjeta de alerta a los equipos. | No almacenamos&#8217;datos de usuario en la base de datos, sino en la memoria bot. Almacenamos el nombre principal del usuario que ha iniciado sesión, token de AAD, token AtHoc de BlackBerry, preferencia o configuración del servidor AtHoc de BlackBerry en la memoria del bot. Necesita la información para enviar una solicitud api a la API de Microsoft Graph y nuestro servidor AtHoc de BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

BlackBerry ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
