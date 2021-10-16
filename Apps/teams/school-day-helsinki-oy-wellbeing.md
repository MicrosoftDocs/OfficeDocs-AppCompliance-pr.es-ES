---
title: Información de la aplicación para el bienestar del día escolar por el día escolar Oy de Helsinki
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para el bienestar del día escolar, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: babc51460ddb23fd19007f2ebfc8ebab00300a69
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408429"
---
# <a name="school-day-wellbeing"></a>Día escolar del bienestar

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/7caaa66b-34b0-4c15-a65d-dba6edf0c8fd" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001430" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por School Day Helsinki Oy a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Día escolar del bienestar |
| Id. | WA200001430 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Día escolar Helsinki Oy |
| Dirección URL del sitio web de partners | [https://www.schoolday.com](https://www.schoolday.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.schoolday.com/en/resources/faq](https://www.schoolday.com/en/resources/faq) |
| Dirección URL de la directiva de privacidad | [https://www.schoolday.com/privacy](https://www.schoolday.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.schoolday.com/eula](https://www.schoolday.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por School Day Helsinki Oy acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | delegado | Pertenencias a grupos y nombres de grupo. El usuario que es profesor, puede agregar alumnos al Día escolar desde sus grupos. | Nombre del grupo, miembros del grupo. El grupo en el día de la escuela se puede nombrar en función del grupo O365. Los miembros del grupo se agregan a esta clase como alumnos. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| Team.ReadBasic.All | delegado | El nombre del equipo se usa cuando el usuario del profesor desea agregar alumnos de sus equipos y grupos. | El nombre del equipo no se almacena en school day. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.Read | delegado | El correo electrónico del usuario, el nombre y el token de id. se usan para la administración y autenticación de usuarios. | El correo electrónico, el nombre y el token de usuario se almacenan con fines de autenticación y administración de usuarios. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.ReadBasic.All | delegado | Imágenes de perfil de usuario que se usarán en avatares de usuario. | La imagen de perfil de usuario no se almacena. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| email | delegado | El correo electrónico del usuario se recopila para la autenticación de cuentas. | El correo electrónico del usuario se almacena con fines de autenticación o creación de cuentas. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| offline_access | delegado | Autenticación: actualización de tokens de acceso. Experiencia de usuario más suave. | Tokens de acceso con fines de autenticación. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| OpenID | delegado | Identificador único del usuario para el inicio de sesión de OpenID.  | El identificador único del usuario se almacena con fines de autenticación. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| perfil | delegado | Nombre de usuario y identificador de objeto preferidos para fines de autenticación y administración de usuarios. | Identificador de objeto para fines de autenticación y administración de usuarios. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Lector inmersivo | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Cuenta de usuario, grupo al que pertenece el usuario, datos de respuesta de preguntas de bienestar. Una vez eliminada la cuenta, los datos se quitan en un plazo de 90 días.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El administrador de la organización puede controlar los datos (CRUD) a través de las herramientas de administrador del día escolar. 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por School Day Helsinki Oy sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
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

