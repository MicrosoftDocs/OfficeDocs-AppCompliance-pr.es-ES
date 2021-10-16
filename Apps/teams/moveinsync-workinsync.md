---
title: Información de la aplicación para WorkInSync de MoveInSync
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para WorkInSync, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 746a7b7c52d8905aaf65d86bc0f15202f486eb82
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413662"
---
# <a name="workinsync"></a>WorkInSync

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4e00663a-be72-4de1-a163-269a477a7a6e" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002974" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por MoveInSync a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | WorkInSync |
| Id. | WA200002974 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | MoveInSync |
| Dirección URL del sitio web de partners | [https://www.workinsync.io](https://www.workinsync.io) |
| Dirección URL de Teams de información de la aplicación | [https://www.workinsync.io/teams-app-for-workinsync/](https://www.workinsync.io/teams-app-for-workinsync/) |
| Dirección URL de la directiva de privacidad | [https://www.workinsync.io/privacy-policy/](https://www.workinsync.io/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.workinsync.io/terms-and-condition/](https://www.workinsync.io/terms-and-condition/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

MoveInSync ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | 1. Para obtener detalles de los miembros del grupo transitivos. Se usan en la pestaña Actividad del equipo cuando se instalan en el contexto del canal. 2. Para iniciar sesión en la lista de detalles del perfil de &amp;  usuario de los usuarios de la organización. Se usan cuando la pestaña Actividad de equipo se instala en contexto personal, como una reserva para mostrar una vista previa de compañeros de equipo en caso de que la API de personas falle (usuarios que no son de Outlook) | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| People.Read | delegado | Para que las personas más relacionadas con el usuario que ha iniciado sesión se muestren en la pestaña Actividad del equipo, se instala en contexto personal. | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read | delegado | Para obtener información de presencia de una lista de usuarios en la pestaña Actividad del equipo en contexto personal y de canal | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read.All | delegado | Para obtener información de presencia de una lista de usuarios en la pestaña Actividad del equipo en contexto personal y de canal | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.Read.All | aplicación | Se usa para obtener información del administrador de informes de cualquier usuario para enviar notificaciones de reserva y de checkin/checkout al administrador | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.ReadBasic.All | delegado | Se usa para leer la foto de perfil del empleado | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| email | delegado | Necesario para obtener el token de SSO mediante Teams biblioteca de cliente | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| offline_access | delegado | Necesario para obtener el token de SSO mediante Teams biblioteca de cliente | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| OpenID | delegado | Necesario para obtener el token de SSO mediante Teams biblioteca de cliente | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| perfil | delegado | Necesario para obtener el token de SSO mediante Teams biblioteca de cliente | Ninguno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Leemos la dirección de correo electrónico del empleado (nombre del principio de usuario) para que coincida con la lista de usuarios registrados con WorkInSync.  | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos no se comparten ni se almacenan en sistemas asociados. Todos los almacenes de datos son completamente propiedad y administrados solo por WorkInSync.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

MoveInSync ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Autenticación multifactor |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

