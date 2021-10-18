---
title: Información de la aplicación para CatchEm de Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para CatchEm, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ba7936c4896fa9c6fc77eee773b6c52bec0af19d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435554"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Chimu Software a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | CatchEm |
| Id. | WA200002639 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Chimu Software |
| Dirección URL del sitio web de partners | [https://chimusoftware.com](https://chimusoftware.com) |
| Dirección URL de Teams de información de la aplicación | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| Dirección URL de la directiva de privacidad | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Chimu Software ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | delegado | Este permiso es necesario para determinar los contactos de un usuario de la aplicación. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. Identificador de chat más reciente: para habilitar la &quot; funcionalidad de hacer clic en &quot; chat | Este permiso es necesario para determinar los contactos de un usuario de la aplicación. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. Identificador de chat más reciente: para habilitar la &quot; funcionalidad de hacer clic en &quot; chat | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| People.Read | delegado | Para mejorar la precisión de los datos de los contactos externos. DisplayName: para identificar los contactos de los usuarios de la aplicación. | Para mejorar la precisión de los datos de los contactos externos. DisplayName: para identificar los contactos de los usuarios de la aplicación. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| Presence.Read.All | delegado | Estado de presencia actual de contactos | N/D | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | ambos | Para enviar notificaciones a los usuarios cuando cambia el estado de presencia de contactos | N/D | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegado | Para habilitar actualizaciones automáticas para la aplicación | N/D | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | delegado | AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, direcciones de mensajería instantánea, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: eliminación automática de datos de usuario para usuarios deshabilitados | AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, direcciones de mensajería instantánea, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: eliminación automática de datos de usuario para usuarios deshabilitados | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | delegado | Para mejorar la precisión de los datos de los contactos internos. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. | Para mejorar la precisión de los datos de los contactos internos. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Surname: para identificar los contactos de los usuarios de la aplicación. Correo electrónico, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y para permitir hacer &quot; clic en la funcionalidad de &quot; chat. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | delegado | Graph tokens de seguridad, para permitir que la aplicación notifique los cambios de presencia de contactos y actualice las listas de contactos cuando el usuario no esté usando la aplicación de forma activa | Graph de seguridad | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| La etiqueta de la funcionalidad del mensaje debe usar el nombre para mostrar del contacto &quot; para mostrar al usuario de la &quot; aplicación. | Nombre para mostrar del contacto | Para poder volver a presentar el nombre del contacto al usuario de la aplicación |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Chimu Software ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
