---
title: 'Información de la aplicación para PlayQuiz: Aprende &amp; Juega de TeamsChamp'
ms.author: elmalova
author: elenamalova
ms.date: 06/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 'Toda la información de seguridad y cumplimiento disponible para PlayQuiz: Aprende Juega, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro &amp; CSA STAR.'
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8d3cc87e089321333074ef577ba2afca0172e31c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411445"
---
# <a name="playquiz---aprende-amp-juega"></a>PlayQuiz - Aprende &amp; Juega

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d36eac22-ff28-4392-9ba7-6e32151b9894" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002820" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por TeamsChamp a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | PlayQuiz - Aprende &amp; Juega |
| Id. | WA200002820 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | TeamsChamp |
| Dirección URL del sitio web de partners | [https://www.encamina.com](https://www.encamina.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.teamsquiz.com](https://www.teamsquiz.com) |
| Dirección URL de la directiva de privacidad | [https://www.teamsquiz.com/en/privacy-policy/](https://www.teamsquiz.com/en/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.teamsquiz.com/en/terms/](https://www.teamsquiz.com/en/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

TeamsChamp ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Nombre, correo electrónico e imagen de perfil del usuario | email, for sing into the app and name to display it in the app | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| User.ReadBasic.All | delegado | Nombre, correo electrónico e imagen de perfil | no almacenar los datos, solo leerlos para mostrarlos en el leaderboad (aplicación) | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| OpenID | delegado | ver el perfil básico del usuario | email, for sing in the app and name to display it in the app | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| perfil | delegado | Leer el perfil básico del usuario | email, for sing in the app and name to display it in the app | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |


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

>eliminación, retención, auditoría, archivado, todas las directivas de la aplicación

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39114" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

TeamsChamp ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

