---
title: Información de solicitud para recordar por 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Remind, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e2124ed68b2e9d750c8bc6a229eca0ccad200b5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552451"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 28 de septiembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por 88 Ventures Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Remind |
| ID | WA200001444 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | 88 Ventures Limited |
| URL del sitio web de socios | [https://www.teamsreminder.app](https://www.teamsreminder.app) |
| URL de la Política de Privacidad | [https://www.teamsreminder.app/#privacy](https://www.teamsreminder.app/#privacy) |
| URL de los Términos de uso | [https://www.teamsreminder.app/#terms](https://www.teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

88 Ventures Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Delegado | ninguna información almacenada en la base de datos | permite al administrador examinar el directorio de usuarios de la organización para los usuarios que han establecido recordatorios públicos | 88546d4f-9973-4716-98e4-cd181c04bc2d |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| (1) Cuando un usuario establece un recordatorio en un mensaje, el bot intenta obtener el nombre de la persona que envió originalmente el mensaje para mostrar esa información en la lista de recordatorios del usuario (2) Cuando un usuario establece un recordatorio para otro miembro del canal o chat, el bot intenta obtener la identidad (usuario o bot) y el nombre del usuario mencionado para mostrarla en la lista de recordatorios del usuario | (1) Cuando un usuario establece un recordatorio en un mensaje, el bot intenta obtener el nombre de la persona que envió originalmente el mensaje para mostrar esa información en la lista de recordatorios del usuario (2) Cuando un usuario establece un recordatorio para otro miembro del canal o chat, el bot intenta obtener la identidad (usuario o bot) y el nombre del usuario mencionado para mostrarla en la lista de recordatorios del usuario |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Ningún EEUI y OII se comparte con la telemetría o la funcionalidad de registro

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Cifrado en reposo, autenticación de dos factores (2FA) para restringir el acceso a nuestra infraestructura de TI y a los datos de los clientes, los rangos ip protegidos entre sistemas

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

