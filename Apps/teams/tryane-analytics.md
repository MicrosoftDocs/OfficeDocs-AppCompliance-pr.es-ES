---
title: Información de la aplicación tryane analytics de Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Tryane Analytics, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551110"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 28 de septiembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Tryane a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Tryane Analytics |
| ID | WA200001827 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Tryane |
| URL del sitio web de socios | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL de la Política de Privacidad | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL de los Términos de uso | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Tryane ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | aplicación |  | Leer todas las actividades de los usuarios en equipos | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | aplicación |  | Todos los canales de lista con nombres, descripciones | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | aplicación |  | Enumere todos los mensajes de canales&#8217; metadatos | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | aplicación |  | Identificar usuarios con una licencia de equipo en el inquilino | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | aplicación |  | Obtenga una lista de todos los equipos, miembros del equipo&#8217;s y membresías ocultas | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | aplicación |  | Leer todas las actividades de los usuarios en equipos | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | aplicación |  | Enumere todos los canales y propiedades de los equipos | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | Delegado | Id de usuario, Nombre, Dirección de correo electrónico, Fecha de creación. Almacenamos estos datos con el fin de proporcionar análisis de uso en Teams | Identificar al usuario actual durante la suscripción | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>La regla organizativa descrita en nuestra política de seguridad de TI y las normas de codificación nos impiden que EUII y OII aparezcan en los registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Dónde/Cómo: Azure/Azure Database para servidores PostgreSQL Quién puede acceder a ella: nuestra aplicación y el control de autorización de administradores de bases de datos: 
 - Control de autorización individual: RBAC
 - Control de autorización del sistema: puntos de conexión privados en redes virtuales de Azure

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

