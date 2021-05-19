---
title: Información de la aplicación DBit by Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para DBit, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553961"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 23 de junio de 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Diamondsoft Solutions, LLC a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | DBit |
| ID | WA200001536 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Diamondsoft Solutions, DIAMOND |
| URL del sitio web de socios | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| URL de la Política de Privacidad | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL de los Términos de uso | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Diamondsoft Solutions, LLC ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Iniciar sesión y leer el perfil del usuario | 1533d702-7604-463a-9fa3-63077c425e76 |
>| email | Delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Ver la dirección de correo electrónico de los usuarios | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | Delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Mantener el acceso a los datos a los que se le ha concedido acceso | 1533d702-7604-463a-9fa3-63077c425e76 |
>| OpenID | Delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Inicio de sesión de los usuarios | 1533d702-7604-463a-9fa3-63077c425e76 |
>| perfil | Delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Ver el perfil básico de los usuarios | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para crear un mensaje de bienvenida | No almacenamos información de lista en nuestro sistema o bases de datos. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No recopilamos esta información.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Usamos Azure Cache Redis, la vida útil máxima de los datos en caché es de 300 minutos. Los elementos de datos de caché se cifran con AES256. Solo el servicio de aplicaciones puede conectarse a Azure Cache Redis a través de SSL, la cadena de conexión se almacena en Azure Environmental Variable.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

