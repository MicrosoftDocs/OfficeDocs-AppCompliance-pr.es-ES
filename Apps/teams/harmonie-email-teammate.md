---
title: Información de la aplicación para Email TeamMate por harmon.ie
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Email TeamMate, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 91fb188a6bc2894ec14c0faef09b3fb28902f5fd
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250658"
---
# <a name="email-teammate"></a>Email TeamMate

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3ae27f31-ceea-4d13-a212-cdc9d786eae1" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002338" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por harmon.ie a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Email TeamMate |
| ID | WA200002338 |
| Capacidades | Bot, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | harmon.ie |
| Dirección URL del sitio web de partners | [https://harmon.ie](https://harmon.ie) |
| Dirección URL de Teams de información de la aplicación | [https://emailteammate.com](https://emailteammate.com) |
| Dirección URL de la directiva de privacidad | [https://harmon.ie/legal/privacy-policy](https://harmon.ie/legal/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://harmon.ie/legal/teammate-eula](https://harmon.ie/legal/teammate-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por harmon.ie acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.Read | delegado | Requerido por TeamMate para obtener miembros de chat de una conversación específica para compartir archivos guardados en una unidad SharePoint/One con los miembros del chat de conversación | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |
>| Files.ReadWrite.All | delegado | Requerido por TeamMate para guardar datos adjuntos de correo &amp; electrónico en SharePoint / Teams / OneDrive | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |
>| Mail.ReadWrite | delegado | Requerido por TeamMate para mostrar los correos electrónicos del usuario y responder a los correos electrónicos guardados en Teams | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |
>| People.Read | delegado | TeamMate necesita buscar correos electrónicos de personas y sugerir personas con las que se está contactando con frecuencia. | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |
>| User.Read | delegado | permite a los usuarios iniciar sesión en TeamMate con su cuenta y permite a TeamMate ver información básica del perfil de usuario | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |
>| User.ReadBasic.All | delegado | Requerido por TeamMate para resolver las direcciones de correo electrónico de los miembros del chat para que los archivos compartidos se guarden OneDrive con ellos  | ninguno | 74a31d8c-1ee9-4fb8-bc22-640ba5f457f4 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Upn de datos de uso y usuarios

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>-

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por harmon.ie sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
