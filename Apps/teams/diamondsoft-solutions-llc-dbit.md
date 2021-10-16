---
title: Información de la aplicación para DBit de Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 04/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para DBit, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 095ce62c1d0b193cd63105e2df3599f6eac3725c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412460"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Diamondsoft Solutions, LLC a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | DBit |
| Id. | WA200001536 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Diamondsoft Solutions, DIAMOND |
| Dirección URL del sitio web de partners | [https://www.diamondsoftsolutions.com](https://www.diamondsoftsolutions.com) |
| Dirección URL de la directiva de privacidad | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Diamondsoft Solutions, LLC ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Iniciar sesión y leer el perfil del usuario | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| email | delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Ver la dirección de correo electrónico de los usuarios | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| offline_access | delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Mantener el acceso a los datos a los que se le ha concedido acceso | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| OpenID | delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Inicio de sesión de los usuarios | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| perfil | delegado | No almacenamos información Graph en nuestro sistema o bases de datos. | Ver el perfil básico de los usuarios | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para crear un mensaje de bienvenida | No almacenamos información de lista en nuestro sistema o bases de datos. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No recopilamos esta información.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Usamos Azure Cache Redis, la duración máxima de los datos en la memoria caché es de 300 minutos. Los elementos de datos de caché se cifran con AES256. Solo el servicio de aplicaciones puede conectarse a Azure Cache Redis a través de SSL, la cadena de conexión se almacena en La variable de entorno de Azure.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


