---
title: Información de la aplicación para Weekly10 de Binary Geek Limited
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Weekly10, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9bdd5e42398270719c9f0ecd9814155974dbee6f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411134"
---
# <a name="weekly10"></a>Weekly10

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c80cee99-d17f-4b2d-a2a4-57652ffd2a4b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001441" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Binary Geek Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Weekly10 |
| Id. | WA200001441 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Binary Geek Limited |
| Dirección URL del sitio web de partners | [https://www.weekly10.com](https://www.weekly10.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.weekly10.com/integrations/microsoft-teams/](https://www.weekly10.com/integrations/microsoft-teams/) |
| Dirección URL de la directiva de privacidad | [https://www.weekly10.com/terms/privacy](https://www.weekly10.com/terms/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.weekly10.com/terms/customer](https://www.weekly10.com/terms/customer) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Binary Geek Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | aplicación | Sincronización de usuarios de Azure AD a Weekly10 (opcional) | Datos de identidad de usuario: Nombre principal de usuario, Correo electrónico, Nombre, Apellidos y Administrador. | [2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb](https://docs.microsoft.com/microsoft-365-app-certification/azure/2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb) |
>| Calendars.ReadWrite | aplicación | Comprobación de la disponibilidad de los empleados y la reserva automatizada de reuniones (opcional). | Tiempos de disponibilidad de los empleados (no detalles) y cuando se reserva una reunión, la referencia a esa reunión. Estos datos se usan para comprender si un empleado está fuera de la oficina para una experiencia de empleado sin problemas y para reservar reuniones para 1:1 o revisiones de rendimiento. | [494610b2-b490-4f54-8384-312d6f9b4869](https://docs.microsoft.com/microsoft-365-app-certification/azure/494610b2-b490-4f54-8384-312d6f9b4869) |
>| User.Read | delegado | Comprobación del usuario con fines de SSO en el Azure AD. | No se conservan datos adicionales aparte de la información del token. | [6fd1421e-89e8-4a8b-bd01-9397656a50d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fd1421e-89e8-4a8b-bd01-9397656a50d5) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Solo tenemos acceso al Teams de usuario de la persona. Esto significa que el bot puede responder de una forma específica a ese usuario. | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nombre de la organización y nombres de usuario en caso de error o problema notificado. Los registros se almacenan en este formato durante un máximo de 30 días y, a continuación, se eliminan.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos que residen en Weekly10 pueden ser controlados por administradores especificados. Al cambiar las directivas en Weekly10, esto afecta directamente a los datos de Microsoft Azure (donde residen los datos de cliente).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Binary Geek Limited ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

