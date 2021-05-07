---
title: Información de la aplicación para el alcance de LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Reach, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 81a3afa06f4843c68a5e32da49f7e7be09e0684a
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252460"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por LiveTiles a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Reach |
| ID | WA200002045 |
| Capacidades | Pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | LiveTiles |
| Dirección URL del sitio web de partners | [https://livetilesglobal.com](https://livetilesglobal.com) |
| Dirección URL de Teams de información de la aplicación | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| Dirección URL de la directiva de privacidad | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

LiveTiles ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | aplicación | ninguno | ninguno | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | delegado | User DisplayName, User Email Address, UPN. Necesario para permitir que los usuarios inicien sesión en la aplicación y obtengan información básica del usuario que ha iniciado sesión, como el nombre para mostrar. La dirección de correo electrónico se usa para enviar notificaciones por correo electrónico.  | User DisplayName, User Email Address, UPN. Necesario para permitir que los usuarios inicien sesión en la aplicación y obtengan información básica del usuario que ha iniciado sesión, como el nombre para mostrar. La dirección de correo electrónico se usa para enviar notificaciones por correo electrónico.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | delegado | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Teléfono Number, User Business Teléfono Number, User Office Location. Necesario para permitir que los usuarios busquen otros usuarios dentro de la aplicación (Libreta de teléfonos) y vean el perfil básico y la información de contacto de otros usuarios.  | ninguno | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | aplicación | Pertenencia a grupos, Grupos de AD en directorio. La pertenencia a grupos de usuarios se almacena en una memoria caché para minimizar las llamadas a la API Graph Microsoft. Necesario para permitir que los usuarios busquen grupos de Active Directory. Además, este permiso es necesario para que la aplicación resuelva la pertenencia a grupos de AD de usuarios en trabajos web del back-end. | Pertenencia a grupos de usuarios. La pertenencia a grupos de usuarios se almacena en una memoria caché para minimizar las llamadas a la API Graph Microsoft. Necesario para permitir que los usuarios busquen grupos de Active Directory. Además, este permiso es necesario para que la aplicación resuelva la pertenencia a grupos de AD de usuarios en trabajos web del back-end.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | aplicación | Los datos recuperados del perfil de usuario dependen de la configuración de la característica De destino de audiencia especificada en la aplicación. Necesario para permitir que la aplicación lea perfiles de usuario sin que un usuario haya iniciado sesión. La lectura de datos de perfil es necesaria para la característica de destino de información dentro de la aplicación, de modo que la información se muestre a usuarios específicos en función de un valor de propiedad de perfil específico.  | ninguno | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | dirección de correo electrónico, nombre para mostrar | Enviar notificación al usuario por correo electrónico y notificaciones de inserción móviles |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>dirección de correo electrónico, UPN. retención máxima de 60 días, después de que se quiten

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los administradores pueden ponerse en contacto con el soporte técnico para cualquier consulta

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

LiveTiles ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | No |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Autenticación multifactor, restricción de ubicaciones de usuario e intervalos IP |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
