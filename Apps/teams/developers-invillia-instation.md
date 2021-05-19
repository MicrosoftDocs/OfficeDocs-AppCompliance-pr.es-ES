---
title: Información de la aplicación para InStation por los desarrolladores Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para InStation, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552251"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 6 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por developers Invillia a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | InStation |
| ID | WA200001701 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Developers Invillia |
| URL del sitio web de socios | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL de la Política de Privacidad | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL de los Términos de uso | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por Developers Invillia sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | Delegado | tiendas: id, join_url, join_web_url y chat_id. Permite a la aplicación crear reuniones | tiendas: id, join_url, join_web_url y chat_id. Permite a la aplicación crear reuniones | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | Delegado | tiendas: id, join_url, join_web_url y chat_id. Permite a la aplicación crear reuniones | tiendas: id, join_url, join_web_url y chat_id. Permite a la aplicación crear reuniones | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | Delegado | Permite a la aplicación iniciar sesión en la organización en su primer paso | actividad y avalabilidad. Permite a la aplicación capturar el estado de los usuarios; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | Delegado | Permite que la aplicación inicie sesión en la organización en su primer paso, | actividad y avalabilidad. Permite a la aplicación capturar el estado de los usuarios; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | Delegado | tiendas: id, correo, nombre para mostrar, apellidos e imagen. Permite a la aplicación buscar datos de usuario; | tiendas: id, correo, nombre para mostrar, apellidos e imagen. Permite a la aplicación buscar datos de usuario; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | Delegado | tiendas: id, correo, nombre para mostrar, apellidos e imagen. Permite a la aplicación buscar datos de usuario; | tiendas: id, correo, nombre para mostrar, apellidos e imagen. Permite a la aplicación buscar datos de usuario; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | Delegado | Permite a la aplicación capturar la información básica del administrador&#180;s en el primer inicio de sesión | Permite a la aplicación capturar la información básica del administrador&#180;s en el primer inicio de sesión | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | Delegado | tiendas: token y token de actualización. Permite a la aplicación realizar una actualización en el token de MS | tiendas: token y token de actualización. Permite a la aplicación realizar una actualización en el token de MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OpenID | Delegado | Permite a la aplicación iniciar sesión en la organización en su primer paso | Permite a la aplicación iniciar sesión en la organización en su primer paso | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| perfil | Delegado | Permite a la aplicación capturar la información básica del administrador&#180;s en el primer inicio de sesión; | Permite a la aplicación capturar la información básica del administrador&#180;s en el primer inicio de sesión; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Solo guardamos los registros de uso del usuario dentro de nuestra aplicación.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Solo guardamos los registros de uso del usuario dentro de nuestra aplicación. Nada confidencial, que no requiere cifrado y sólo nuestros administradores específicos tienen acceso a estos datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

