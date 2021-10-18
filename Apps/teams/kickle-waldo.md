---
title: Información de la aplicación para Waldo por Kickle
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Waldo, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 88766f29eb80c8d9378fc117b42e688db3dff755
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434589"
---
# <a name="waldo"></a>Waldo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 30, 2021</p>

* <a href="https://teams.microsoft.com/l/app/1d041f16-ab49-4627-bfda-6b60ad2cab6a" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003139" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Kickle a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Waldo |
| Id. | WA200003139 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Kickle |
| Dirección URL del sitio web de partners | [https://hellowaldo.app](https://hellowaldo.app) |
| Dirección URL de Teams de información de la aplicación | [https://hellowaldo.app/takeatour/](https://hellowaldo.app/takeatour/) |
| Dirección URL de la directiva de privacidad | [https://hellowaldo.app/privacy-policy/](https://hellowaldo.app/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://hellowaldo.app/terms-and-conditions](https://hellowaldo.app/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Kickle ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | delegado | En función del historial de chat, Waldo identifica a sus compañeros. Esta lista se usa después para mostrar el estado en la vista de calendario. | Waldo almacena el identificador de usuario de cada compañero. Estos IDs se usan para mostrar la lista de compañeros con los que estamos acostumbrados a trabajar. | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.Read | delegado | Este permiso lo usa la persona componente de microsoft Graph Toolkit | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.ReadBasic.All | delegado | Este permiso lo usa la persona componente de microsoft Graph Toolkit | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| offline_access | delegado | Usado por la aplicación para realizar tareas en segundo plano en nombre del usuario (token de renovación para la autenticación) | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| OpenID | delegado | Necesario para la autenticación | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |


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

>La organización puede ver los administradores de Waldo, los contactos administrativos y los contactos técnicos en https://app.hellowaldo.app/admin-orga-contacts .  La organización puede ponerse en contacto hello@kickle.com para quitar información de identificación personal de nuestra aplicación. Esto puede limitar el servicio que podemos proporcionar.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Kickle ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
