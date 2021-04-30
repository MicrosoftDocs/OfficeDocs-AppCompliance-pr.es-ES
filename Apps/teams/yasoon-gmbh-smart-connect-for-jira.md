---
title: Información de aplicación para smart Conectar para Jira por yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Smart Conectar para Jira, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f0e3091eab95575c3a8ecc1c977d71fc29c4cbab
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096423"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por yasoon GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Smart Connect for Jira |
| Id. | WA200002055 |
| Capacidades | Bot, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | yasoon GmbH |
| Dirección URL del sitio web de partners | [https://yasoon.com](https://yasoon.com) |
| Dirección URL de Teams de información de la aplicación | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| Dirección URL de la directiva de privacidad | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| DIRECCIÓN URL de términos de uso | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Yasoon GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | delegado | El permiso se usa para permitir que el usuario seleccione uno de estos canales unidos en Jira. | Id. de canal, con fines de almacenamiento en caché | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Read.Group | aplicación | Permite que la aplicación muestre mensajes de canal vinculado en Jira. | IDs de mensajes para vincular mensajes a problemas de Jira | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Send | delegado | No se usa ningún dato, esta API se usa para permitir que el usuario responda a los mensajes de canal de Jira. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings.Read.Group | aplicación | Se usa para buscar información detallada sobre un canal. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Chat.ReadWrite | delegado | Se usa para permitir al usuario agregar nuevas respuestas a los chats y ver mensajes de chat de Jira. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member.Read.Group | aplicación | Se usa para las comprobaciones de permisos, permite que la aplicación valide la pertenencia al equipo de los usuarios. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Team.ReadBasic.All | delegado | El permiso se usa para permitir que el usuario seleccione uno de estos equipos unidos en Jira. | Team IDs for caching purposes | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings.Read.Group | aplicación | Permite que la aplicación lea la configuración del equipo para respetar ciertos valores predeterminados. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | delegado | Permite al usuario seleccionar compañeros de trabajo para @-mencione en un mensaje de canal | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira y posiblemente uno de nuestros contratistas, se pueden ver aquí: https://go.yasoon.com/contractors | Metadatos de mensaje (identificadores, marcas de tiempo), metadatos de usuario y organización (id. de usuario, id. de organización) y direcciones de correo electrónico de usuario | Compatibilidad con la funcionalidad de la aplicación (por ejemplo, coincidencia de cuentas atlassianas con Office cuentas) y habilitando nuestro soporte técnico para solucionar problemas con mayor rapidez. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Hacer coincidir la cuenta Teams usuarios con la cuenta de Atlassian Jira de los usuarios | No |  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Metadatos de usuario (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Solo trabajamos con servicios que ofrecen estrictas garantías de privacidad de datos. 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Yasoon GmbH ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,
<br />
- OAuth2 Implicit Flow, a menos que sea necesario para un SPA
<br />
- Flujo de credenciales de contraseña de propietario de recursos (ROPC) | | ¿Expone la aplicación alguna API web? | Sin | | ¿La aplicación usa las API de vista previa? | Sí | | ¿La aplicación usa API en desuso? | Sin |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
