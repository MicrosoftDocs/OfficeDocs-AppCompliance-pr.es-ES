---
title: Información de la aplicación para Remind by 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Remind, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f39e0c35b88e3212743e30c7ab5ac40c74c708c3
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525934"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por 88 Ventures Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Remind |
| Id. | WA200001444 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | 88 Ventures Limited |
| Dirección URL del sitio web de partners | [https://moonbearapp.com](https://moonbearapp.com) |
| Dirección URL de la directiva de privacidad | [https://teamsreminder.app/#privacy](https://teamsreminder.app/#privacy) |
| DIRECCIÓN URL de términos de uso | [https://teamsreminder.app/#terms](https://teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

88 Ventures Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | no hay información almacenada en la base de datos | permite al administrador examinar el directorio de usuarios de la organización para los usuarios que han establecido avisos públicos | [88546d4f-9973-4716-98e4-cd181c04bc2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/88546d4f-9973-4716-98e4-cd181c04bc2d) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| (1) Cuando un usuario establece un aviso en un mensaje, el bot intenta obtener el nombre de la persona que envió originalmente el mensaje para mostrar esa información en la lista de avisos del usuario (2) Cuando un usuario establece un aviso para otro canal o miembro de chat, el bot intenta obtener la identidad (usuario o bot) y el nombre del usuario mencionado para mostrarla en la lista de avisos del usuario. | (1) Cuando un usuario establece un aviso en un mensaje, el bot intenta obtener el nombre de la persona que envió originalmente el mensaje para mostrar esa información en la lista de avisos del usuario (2) Cuando un usuario establece un aviso para otro canal o miembro de chat, el bot intenta obtener la identidad (usuario o bot) y el nombre del usuario mencionado para mostrarla en la lista de avisos del usuario. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No se comparte ninguna EEUI y OII con la funcionalidad de telemetría o registro

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Cifrado en reposo, autenticación de dos factores (2FA) para restringir el acceso a nuestra infraestructura de TI y a los datos de clientes, intervalos IP protegidos entre sistemas

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

