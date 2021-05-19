---
title: Información de la aplicación smart Conectar for Jira por yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Smart Conectar para Jira, sus políticas de gestión de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6fb1be576d588727c75f14d72db48bc3a7a8aeb5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550740"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 22 de enero de 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por yasoon GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Smart Connect for Jira |
| ID | WA200002055 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | yasoon GmbH |
| URL del sitio web de socios | [https://yasoon.com](https://yasoon.com) |
| URL de Teams página de información de la aplicación | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL de la Política de Privacidad | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| URL de los Términos de uso | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Yasoon GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Delegado | El permiso se utiliza para permitir al usuario seleccionar uno de estos canales unidos en Jira. | Id. de canal, con fines de almacenamiento en caché | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Read.Group | aplicación | Permite a la aplicación mostrar mensajes de canal vinculados en Jira. | ID de mensaje para vincular mensajes a problemas de Jira | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Send | Delegado | No se utilizan datos, esta API se utiliza para permitir al usuario responder a los mensajes de canal de Jira. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings.Read.Group | aplicación | Se utiliza para buscar información detallada sobre un canal. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Chat.ReadWrite | Delegado | Se utiliza para permitir al usuario añadir nuevas respuestas a los chats y ver los mensajes de chat de Jira. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member.Read.Group | aplicación | Se usa para comprobaciones de permisos, permite a la aplicación validar la pertenencia al equipo de los usuarios. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Team.ReadBasic.All | Delegado | El permiso se utiliza para permitir al usuario seleccionar uno de estos equipos unidos en Jira. | Identificacións de equipo con fines de almacenamiento en caché | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings.Read.Group | aplicación | Permite que la aplicación lea la configuración del equipo para respetar ciertos valores predeterminados. | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | Delegado | Permite al usuario seleccionar compañeros de trabajo a @-mention en un mensaje de canal | Ninguno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira y posiblemente uno de nuestros contratistas, se pueden ver aquí: https://go.yasoon.com/contractors | Metadatos de mensajes (ids, marcas de tiempo), metadatos de usuario y organización (id de usuario, identificadores de organización) y direcciones de correo electrónico de usuario | Compatibilidad con la funcionalidad de la aplicación (por ejemplo, hacer coincidir cuentas atlassianas con cuentas Office) y permitir que nuestro soporte solucione problemas más rápido. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Hacer coincidir los usuarios Teams cuenta con la cuenta atlassian jira de los usuarios | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Metadatos de usuario (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Solo trabajamos con servicios que ofrecen estrictas garantías de privacidad de datos. 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por yasoon GmbH sobre cómo esta aplicación maneja la autenticación, autorización, prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | No |
| ¿La aplicación usa API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
