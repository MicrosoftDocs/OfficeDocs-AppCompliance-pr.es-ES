---
title: Información de la aplicación para InStation por desarrolladores Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para InStation, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7185027c5fe21b388076d5fd655e3d9240905e25
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250758"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por los desarrolladores invillia a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | InStation |
| ID | WA200001701 |
| Capacidades | Pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Developers Invillia |
| Dirección URL del sitio web de partners | [https://instation.invillia.com/](https://instation.invillia.com/) |
| Dirección URL de la directiva de privacidad | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Los desarrolladores de Invillia han proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | delegado | stores: id, join_url, join_web_url y chat_id. Permite que la aplicación cree reuniones | stores: id, join_url, join_web_url y chat_id. Permite que la aplicación cree reuniones | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | delegado | stores: id, join_url, join_web_url y chat_id. Permite que la aplicación cree reuniones | stores: id, join_url, join_web_url y chat_id. Permite que la aplicación cree reuniones | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | delegado | Permite que la aplicación inicie sesión en la organización en su primer paso | actividad y avaliability. Permite que la aplicación capture el estado de los usuarios; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | delegado | Permite que la aplicación inicie sesión en la organización en su primer paso, | actividad y avaliability. Permite que la aplicación capture el estado de los usuarios; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | delegado | stores: id, mail, display name, surname and picture. Permite que la aplicación busque datos de usuario; | stores: id, mail, display name, surname and picture. Permite que la aplicación busque datos de usuario; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | delegado | stores: id, mail, display name, surname and picture. Permite que la aplicación busque datos de usuario; | stores: id, mail, display name, surname and picture. Permite que la aplicación busque datos de usuario; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | delegado | Permite que la aplicación capture la información&#180;información básica del administrador en el primer inicio de sesión | Permite que la aplicación capture la información&#180;información básica del administrador en el primer inicio de sesión | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | delegado | almacenes: token y token de actualización. Permite que la aplicación realice una actualización en el token de MS | almacenes: token y token de actualización. Permite que la aplicación realice una actualización en el token de MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OpenID | delegado | Permite que la aplicación inicie sesión en la organización en su primer paso | Permite que la aplicación inicie sesión en la organización en su primer paso | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| perfil | delegado | Permite que la aplicación capture la información&#180;información básica del administrador en el primer inicio de sesión; | Permite que la aplicación capture la información&#180;información básica del administrador en el primer inicio de sesión; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Solo guardamos registros de uso de usuarios en nuestra aplicación.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Solo guardamos registros de uso de usuarios en nuestra aplicación. Nada confidencial, que no requiere cifrado y solo nuestros administradores específicos tienen acceso a estos datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

