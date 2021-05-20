---
title: Información de la aplicación para AtBot by H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para AtBot, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552141"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por H3 Solutions, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | AtBot |
| ID | WA104381219 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | H3 Solutions, Inc. |
| Dirección URL del sitio web de partners | [https://atbot.io](https://atbot.io) |
| Dirección URL de Teams de información de la aplicación | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| Dirección URL de la directiva de privacidad | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| DIRECCIÓN URL de términos de uso | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

H3 Solutions, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicación | Nombre de grupo de AAD, GUID de grupo de AAD, UPN | Enumerar grupos de AAD para permitir el recorte de seguridad de las habilidades de bot. Enumerar los usuarios para poder aplicar licencias. Enumerar usuarios para agregar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | delegado | Nombre de grupo de AAD, GUID de grupo de AAD, UPN | Enumerar grupos de AAD para permitir el recorte de seguridad de las habilidades de bot. Enumerar los usuarios para poder aplicar licencias. Enumerar usuarios para agregar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | delegado | No | Enumerar personas en una acción Obtener persona desde Flow.  Permite al bot recuperar personas del extremo /People en Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | delegado | Id. de inquilino, UPN | Nos da acceso al identificador de inquilino&#8217;de usuario y UPN para permitirnos vincular flujos/aplicaciones lógicas creadas a los usuarios que los crearon. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | delegado | No | Nos da acceso a la dirección de correo electrónico del usuario. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | delegado | Tokens de acceso/actualización. | Nos permite usar un token de actualización para mantener la sesión iniciada por los usuarios. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| OpenID | delegado | No | Permite a los usuarios iniciar sesión. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| perfil | delegado | UPN | Acceso al UPN del usuario. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Creación de menciones en mensajes de chat generados por bots | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Identificador de inquilino, UPN Usamos Application Insights y nuestros registros durarán 90 días antes de archivarse automáticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los administradores tienen la capacidad de eliminar configuraciones de bot que pueden contener nombres de grupo o GUID de AAD.
Tras la cancelación del servicio, todos los UPN se quitarán de la base de datos de licencias.
Consulte "Servicios de Azure" en Data Residency.  Gran parte de los datos específicos del cliente producidos mediante el uso de AtBot se almacenan en el inquilino del cliente y, por lo tanto, los administradores de ese espacio empresarial tienen control total de los datos allí.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

