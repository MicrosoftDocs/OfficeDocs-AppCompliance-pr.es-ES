---
title: Información de la aplicación para entrenamiento de Cuco de Cuckoo Networks Oy
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para El entrenamiento de Cuco, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bfe71be02837f49ca57b9ea4ddddaf83eea35511
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430238"
---
# <a name="cuckoo-workout"></a>Cuckoo Workout

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/71138876-8738-4935-95b6-ae7c2fbe4e54" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002750" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cuckoo Networks Oy a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Cuckoo Workout |
| Id. | WA200002750 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Cuckoo Networks Oy |
| Dirección URL del sitio web de partners | [https://cuckooworkout.com](https://cuckooworkout.com) |
| Dirección URL de Teams de información de la aplicación | [https://cuckooworkout.com](https://cuckooworkout.com) |
| Dirección URL de la directiva de privacidad | [https://cuckooworkout.com/service-privacy-policy/](https://cuckooworkout.com/service-privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://cuckooworkout.com/terms-of-service/](https://cuckooworkout.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Cuckoo Networks Oy sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Nombre de usuario, identificador de inquilino para comunicaciones y asignación de suscripción | Nombre de usuario, identificador de inquilino para comunicaciones y asignación de suscripción | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| email | delegado | Correo electrónico, necesario para autenticación y soporte técnico | Correo electrónico, necesario para autenticación y soporte técnico | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| offline_access | delegado | N/D | N/D | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| OpenID | delegado | Id. de usuario para autenticación | Id. de usuario para autenticación | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| perfil | delegado | Id. de perfil para autenticación | Id. de perfil para autenticación | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon AWS | Identificación del inquilino | Para hacer coincidir el plan de suscripción de usuario a empresa  |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Autenticación y seguimiento de progreso | Teams de usuario, id. de inquilino | Autenticación y seguimiento de progreso |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Chats, vistas de vídeo, configuración del usuario, idioma. Directivas de retención y eliminación según RGPD.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Superadministrador puede realizar eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Cuckoo Networks Oy sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
