---
title: Información de la solicitud para bot de calendario por contacto aprobado
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Calendar BOT, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7e34564a01f326390ce807373e33818bef877c3e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553421"
---
# <a name="calendar-bot"></a>Calendar BOT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381271" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por El contacto aprobado a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Calendar BOT |
| ID | WA104381271 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Contacto aprobado |
| URL del sitio web de socios | [https://approvedcontact.com](https://approvedcontact.com) |
| URL de la Política de Privacidad | [https://approvedcontact.com/Privacy%20Policy%20Bot.pdf](https://approvedcontact.com/Privacy%20Policy%20Bot.pdf) |
| URL de los Términos de uso | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por El contacto aprobado sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | Para el Bot de Calendario estamos almacenando a los usuarios tiempo libre / ocupado para encontrar tiempos libres para varias personas.  | Leemos y comparamos reuniones de tiempo y agenda gratuitas/ocupadas. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | Delegado | Sí, almacenamos información de contacto. | Importar y sincronizar contactos. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | Delegado | Sí | Información básica del perfil. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | Delegado | No | Se utiliza para ver los perfiles de los compañeros de trabajo y comparar los tiempos libres y programar salas de conferencias. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | Delegado | Sí, tiempos de disponibilidad para usuarios sin conexión. | Llame a Graph cuando el usuario no esté utilizando activamente nuestro sitio. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| OpenID | Delegado | No | Office 365 Sso. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilizamos la lista para comparar los tiempos libres/ocupados para que todos en el Equipo programe reuniones a la hora de apertura. | Sólo almacenamos la dirección de correo electrónico para que podamos comparar los tiempos de disponibilidad. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, registramos direcciones de correo electrónico para conectar compras de licencias a Commercial Appsource. Proporcionamos la capacidad de eliminar esta información de nuestros registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Solo los desarrolladores tienen acceso a nuestros registros. Aplicamos 2FA para el acceso a todas las plataformas de desarrollo.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

