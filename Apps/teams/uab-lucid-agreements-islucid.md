---
title: Información de la aplicación para isLucid por contratos de lúcido de UAB
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para isLucid, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414907"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por UAB Contratos lúcidos a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | isLucid |
| Id. | WA200002385 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | UAB Lucid Agreements |
| Dirección URL del sitio web de partners | [https://islucid.com](https://islucid.com) |
| Dirección URL de Teams de información de la aplicación | [https://islucid.com](https://islucid.com) |
| Dirección URL de la directiva de privacidad | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por UAB Contratos lúcidos sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | ambos | Con un consentimiento específico del usuario para cada llamada por separado (transcripción iniciada) tiene acceso a la secuencia de audio. La secuencia de audio se reenvía a un servicio de transcripción para que los usuarios obtengan más funcionalidad. | La aplicación almacena en contenedores separados en Azure (almacenamiento de blobs y base de datos Cosmos para cada cliente por separado) transcripción e información de meta relacionada. Esto es necesario para proporcionar acceso adicional a la información de una reunión para el usuario, que usó la aplicación y estuvo en la reunión específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | ambos | Con un consentimiento específico del usuario para cada llamada por separado (transcripción iniciada) tiene acceso a la secuencia de audio. La secuencia de audio se reenvía a un servicio de transcripción para que los usuarios obtengan más funcionalidad. | La aplicación almacena en contenedores separados en Azure (almacenamiento de blobs y base de datos Cosmos para cada cliente por separado) transcripción e información de meta relacionada. Esto es necesario para proporcionar acceso adicional a la información de una reunión para el usuario, que usó la aplicación y estuvo en la reunión específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | ambos | Cuando el usuario usa la integración con Microsoft Planner para crear tareas a partir de llamadas y almacenar automáticamente en MS Planner, isLucid recopila para ese usuario grupos, planes, usuarios asignados. Sin este permiso, el usuario no podría crear tareas a partir de la transcripción mediante isLucid | El título de la tarea, el creador de tareas, la marca de tiempo de la tarea, la descripción de la tarea se almacenan para que los usuarios puedan obtener acceso al historial de tareas, realizado desde una reunión específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | ambos | La aplicación recopila títulos de reunión para que los usuarios más adelante (cuando finalice la reunión) puedan encontrar las transcripciones y tareas anteriores más fáciles. | Título de la reunión, marca de tiempo de la reunión, organizador de la reunión | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | ambos | Cuando el usuario usa la integración con Microsoft Planner para crear tareas a partir de llamadas y almacenar automáticamente en MS Planner, isLucid recopila para ese usuario grupos, planes, usuarios asignados. Sin este permiso, el usuario no podría crear tareas a partir de la transcripción mediante isLucid | El título de la tarea, el creador de tareas, la marca de tiempo de la tarea, la descripción de la tarea se almacenan para que los usuarios puedan obtener acceso al historial de tareas, realizado desde una reunión específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | ambos | Cuando el usuario usa la integración con Microsoft Planner para crear tareas a partir de llamadas y almacenar automáticamente en MS Planner, isLucid recopila para ese usuario grupos, planes, usuarios asignados. Sin este permiso, el usuario no podría crear tareas a partir de la transcripción mediante isLucid | El título de la tarea, el creador de tareas, la marca de tiempo de la tarea, la descripción de la tarea se almacenan para que los usuarios puedan obtener acceso al historial de tareas, realizado desde una reunión específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OpenID | ambos | Id. de usuario, identificador de inquilino recopilado para proporcionar Azure Active Directory de inicio de sesión para nuestros usuarios | Id. de usuario, identificador de inquilino para más administración de derechos | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | Nombre, Apellidos, Correo electrónico y Teléfono número de usuarios recién registrados | Estamos usando Hubspot CRM para mantener información relacionada con las ventas |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot está habilitando el envío de secuencia de audio al servicio de transcripción. Para proporcionar una transcripción legible, debemos asociar el audio con los usuarios (altavoces). Sin proporcionar estas transcripciones de información no sirve de nada | Nombre, apellido, estado si se trata de una cuenta de invitado o de Microsoft uno | Bot está habilitando el envío de secuencia de audio al servicio de transcripción. Para proporcionar una transcripción legible, debemos asociar el audio con los usuarios (altavoces). La información de los participantes de la reunión también es relevante para permitir a los usuarios ver, que estaban asistiendo a la reunión. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Los usuarios al usar nuestro servicio están generando transcripciones. En las transcripciones se presentan los participantes de la reunión (nombres, apellidos). Potencialmente se puede mencionar cualquier cosa durante la llamada. Almacenamos estos datos para los usuarios siempre que estén usando nuestros servicios. Una vez que el cliente termina de usarnos, en un plazo de 30 días destruiremos todos los datos asociados.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No controlamos ningún dato de nuestros clientes cuando las compras de cliente se hacen como una solución hospedada. Para la solución SaaS, habilitamos a los usuarios para cancelar con nuestros servicios y, a continuación, eliminamos Cosmos db isntance, asociado con el partner. También estamos en proceso de enviar información a la API de cumplimiento

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por UAB Contratos lúcidos sobre cómo esta aplicación controla la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

