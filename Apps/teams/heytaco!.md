---
title: Información de la aplicación para HeyTaco! por HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para HeyTaco!, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7b4641b33166043dd311bdd89568c9eaea4b87a1
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521643"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por HeyTaco! a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | HeyTaco! |
| Id. | WA200001346 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | HeyTaco! |
| Dirección URL del sitio web de partners | [https://www.heytaco.chat](https://www.heytaco.chat) |
| Dirección URL de la directiva de privacidad | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por HeyTaco. acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | se usa para coincidir con el usuario para las transferencias de datos de Slack a MS Teams | se usa para hacer coincidir el usuario para transferencias de datos de Slack a MS Team | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| OpenID | delegado | se usa para iniciar sesión en HeyTaco. | se usa para iniciar sesión en HeyTaco. | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| perfil | delegado | se usa para capturar el nombre de usuario, la imagen de perfil, el desplazamiento de zona horaria, el identificador de inquilino y el identificador de equipo | se usa para capturar el nombre de usuario, el avatar, el desplazamiento de zona horaria, el identificador de inquilino y el identificador de equipo | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para decirle al usuario que ha recibido un taco y de quién es. | Dirección de correo electrónico (para la migración de tacos de una plataforma a otra) Nombre (para saludar al usuario) Imagen de perfil (para mostrar en la tabla de clasificación) Zona horaria (para mostrar correctamente los tacos dados en la página de actividad) Identificador de inquilino (Para agregar datos por inquilino) Id. de equipo (Para agregar datos por equipo)  |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>EUII y OII no están conectados a ningún registro. Solo tipos de error y tipos de acción.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>HeyTaco! bases de datos y copias de seguridad de datos se hospedan en Amazon Web Services (AWS). 

Las operaciones del centro de datos de Amazon se han acreditado según ISO 27001 , SOC 1 y SOC 2/SSAE 16/ISAE 3402 (anteriormente SAS 70 Tipo II ), NIVEL PCI 1, FISMA Moderado y Sarbanes-Oxley (SOX).

Cuando envía información a través de nuestro servicio, su información está protegida y cifrada tanto en reposo como en tránsito a través de conexiones seguras. Implementamos una variedad de medidas de seguridad para mantener la seguridad de su información personal.

Disponemos de privileged Access Management para proteger los datos de nuestros servidores.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

