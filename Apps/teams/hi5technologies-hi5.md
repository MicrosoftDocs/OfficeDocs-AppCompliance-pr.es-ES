---
title: Información de aplicación para Hi5 de Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Hi5, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1356b3e31e309379e1943dc5ca59e10c72c23410
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525604"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Hi5Technologies a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Hi5 |
| Id. | WA200001610 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Hi5Technologies |
| Dirección URL del sitio web de partners | [https://www.get5.io](https://www.get5.io) |
| Dirección URL de Teams de información de la aplicación | [https://help.get5.io](https://help.get5.io) |
| Dirección URL de la directiva de privacidad | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Hi5Technologies ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Solo almacenamos la información de sesión de los usuarios Teams y el usuario debe aprobarlo agregando notificaciones (pueden quitar esto en cualquier momento). No se almacena ninguna otra información. | Necesario para el inicio de sesión sso y la autenticación en nuestro servidor | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| email | delegado | Solo almacenamos la información de sesión de los usuarios Teams y el usuario debe aprobarlo agregando notificaciones (pueden quitar esto en cualquier momento). No se almacena ninguna otra información. | Necesario para el inicio de sesión sso y la autenticación en nuestro servidor | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| offline_access | delegado | Solo almacenamos la información de sesión de los usuarios Teams y el usuario debe aprobarlo agregando notificaciones (pueden quitar esto en cualquier momento). No se almacena ninguna otra información. | Mantiene que el usuario ve la información correcta y que podemos enviar la información correcta a otros usuarios que se unan a la misma empresa o área de trabajo. | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| OpenID | delegado | Solo almacenamos la información de sesión de los usuarios Teams y el usuario debe aprobarlo agregando notificaciones (pueden quitar esto en cualquier momento). No se almacena ninguna otra información. | Necesario para el inicio de sesión sso y la autenticación en nuestro servidor | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| perfil | delegado | Solo almacenamos la información de sesión de los usuarios Teams y el usuario debe aprobarlo agregando notificaciones (pueden quitar esto en cualquier momento). No se almacena ninguna otra información. | Necesario para el inicio de sesión sso y la autenticación en nuestro servidor | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para notificar al usuario en un canal que se le ha dado un Hi5 | No se almacena información, el usuario solo será @ por la tarjeta enviada de vuelta en el canal | No se almacena información, el usuario solo será @ por la tarjeta enviada de vuelta en el canal |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No, Hi5 se limita a iFramed in y todos los datos se almacenan de forma segura.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Estamos usando OAuth y proporcionamos 3 opciones de inicio de sesión:
- SSO de Googles (OAuth).
- Sso de Microsoft (OAuth).
- Nuestro propio cifrado, que es una combinación de cifrado SHA y AES.
Una vez autenticado e iniciado sesión, el nivel de permiso le concede acceso a las secciones autorizadas dentro de la Plataforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Hi5Technologies ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
