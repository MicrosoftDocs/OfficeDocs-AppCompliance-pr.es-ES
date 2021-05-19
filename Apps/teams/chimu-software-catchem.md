---
title: Información de la aplicación CatchEm by Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para CatchEm, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55b248c8f99e18d08ddf60dec177ce92b543f008
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552321"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 27 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Chimu Software a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | CatchEm |
| ID | WA200002639 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Chimu Software |
| URL del sitio web de socios | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| URL de Teams página de información de la aplicación | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL de la Política de Privacidad | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL de los Términos de uso | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Chimu Software ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | Delegado | Este permiso es necesario para determinar los contactos de un usuario de la aplicación. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Email, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. ID de chat más reciente: para habilitar &quot; el clic para chatear &quot; funcionalidad | Este permiso es necesario para determinar los contactos de un usuario de la aplicación. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Email, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. ID de chat más reciente: para habilitar &quot; el clic para chatear &quot; funcionalidad | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | Delegado | Para mejorar la precisión de los datos de los contactos externos. DisplayName: para identificar contactos con los usuarios de la aplicación. | Para mejorar la precisión de los datos de los contactos externos. DisplayName: para identificar contactos con los usuarios de la aplicación. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | Delegado | Contactos estado de presencia actual | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | ambos | Para enviar notificaciones a los usuarios cuando cambia el estado de presencia de contactos | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | Delegado | Para habilitar las actualizaciones automáticas de la aplicación | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | Delegado | AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Correo electrónico, direcciones IP, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. Nombre de la empresa, País: Análisis. AccountEnabled, DeletedDateTime: eliminación automática de datos de usuario para usuarios deshabilitados | AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Correo electrónico, direcciones IP, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. Nombre de la empresa, País: Análisis. AccountEnabled, DeletedDateTime: eliminación automática de datos de usuario para usuarios deshabilitados | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | Delegado | Para mejorar la precisión de los datos de los contactos internos. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Email, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. | Para mejorar la precisión de los datos de los contactos internos. AadObjectId: para identificar de forma única a un usuario. TenantId: para determinar si un contacto es interno o externo al usuario. DisplayName, GivenName, Apellido: para identificar contactos con los usuarios de la aplicación. Email, UserPrincipalName: para ayudar a distinguir entre contactos con el mismo nombre y permitir &quot; que el clic &quot; chatee funcionalidad. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | Delegado | Graph tokens de seguridad, para permitir que la aplicación notifique sobre los cambios de presencia de contacto y actualice las listas de contactos cuando el usuario no está utilizando activamente la aplicación | tokens de seguridad Graph | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| La &quot; etiqueta de la funcionalidad del mensaje debe usar el nombre para mostrar del contacto para &quot; mostrarlo al usuario de la aplicación | El nombre para mostrar del contacto | Para poder presentar el nombre del contacto al usuario de la aplicación |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en la telemetría o registros de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Chimu Software ha proporcionado esta información sobre cómo esta aplicación maneja la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | No |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
