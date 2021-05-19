---
title: Información de la aplicación AtBot by H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para AtBot, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
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
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por H3 Solutions, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | AtBot |
| ID | WA104381219 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | H3 Solutions, Inc. |
| URL del sitio web de socios | [https://atbot.io](https://atbot.io) |
| URL de Teams página de información de la aplicación | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL de la Política de Privacidad | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL de los Términos de uso | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

H3 Solutions, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicación | Nombre del grupo AAD, GUID del grupo AAD, UPN | Enumerar grupos AAD para permitir el recorte de seguridad de las habilidades de bot. Enumerar usuarios para poder aplicar licencias. Enumerar usuarios para agregar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | Delegado | Nombre del grupo AAD, GUID del grupo AAD, UPN | Enumerar grupos AAD para permitir el recorte de seguridad de las habilidades de bot. Enumerar usuarios para poder aplicar licencias. Enumerar usuarios para agregar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | Delegado | No | Enumerar personas en una acción Obtener persona de Flow.  Permite al bot recuperar personas del punto de conexión /People en Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | Delegado | Id. de inquilino, UPN | Nos da acceso al ID de inquilino de&#8217;usuario y a UPN para permitirnos vincular flujos/aplicaciones lógicas creadas a los usuarios que los crearon. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | Delegado | No | Nos da acceso a la dirección de correo electrónico del usuario. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | Delegado | Tokens de acceso/actualización. | Nos permite usar un token de actualización para mantener a los usuarios conectados. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| OpenID | Delegado | No | Permite a los usuarios iniciar sesión. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| perfil | Delegado | UPN | Acceso a UPN del usuario. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| La creación de menciones en mensajes de chat generados por bots | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Id. de inquilino, UPN Usamos Application Insights y nuestros registros durarán 90 días antes de ser archivados automáticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los administradores tienen la capacidad de eliminar configuraciones de bot que pueden contener nombres de grupo/GUID de AAD.
Tras la cancelación del servicio, todas las UPN se eliminarán de la base de datos de licencias.
Consulte 'Servicios de Azure' en Data Residency.  Gran parte de los datos específicos del cliente producidos mediante el uso de AtBot se almacenan en el inquilino del cliente, por lo que los administradores de ese inquilino tienen el control total de los datos allí.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

