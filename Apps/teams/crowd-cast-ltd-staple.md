---
title: Información de aplicación para Staple de Crowd Cast, Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Staple, sus directivas de tratamiento de datos, su Microsoft Cloud App Security del catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9eb6274274c3970b20ebb53d03a163fa79e206df
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410313"
---
# <a name="staple"></a>Staple

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ac9ca94a-e666-4f61-959a-12c063e13e69" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003281" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Crowd Cast, Ltd. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Staple |
| Id. | WA200003281 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Crowd Cast, Ltd. |
| Dirección URL del sitio web de partners | [https://crowdcast.jp/ja/](https://crowdcast.jp/ja/) |
| Dirección URL de Teams de información de la aplicación | [https://intercom.help/staple/ja](https://intercom.help/staple/ja) |
| Dirección URL de la directiva de privacidad | [https://crowdcast.jp/ja/privacy/](https://crowdcast.jp/ja/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://go.microsoft.com](https://go.microsoft.com) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Crowd Cast, Ltd. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Organization.Read.All | aplicación | Se usa para recopilar el identificador de inquilino. Se usa para garantizar que los usuarios que se autentican con nuestra plataforma sean miembros de un inquilino específico. | identificador de inquilino. Se usa para garantizar que los usuarios que se autentican con nuestra plataforma sean miembros de un inquilino específico. | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | aplicación | Teams aplicación se instala automáticamente en el equipo del usuario | N/D | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| AppCatalog.Read.All | delegado | Lee el catálogo de aplicaciones de un usuario para ver si la aplicación de teams está instalada. | N/D | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| User.Read | delegado | Se usa para leer el identificador de un usuario para asegurarse de que los mensajes se envían al usuario correcto. | Id. de usuario almacenado para enviar mensajes proactivos al usuario. | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| OpenID | delegado | Iniciar sesión en un usuario para leer su información básica de perfil | N/D | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de control de administrador de nuestra organización en los sistemas de un partner(AWS, Heroku).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Crowd Cast, Ltd. sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

