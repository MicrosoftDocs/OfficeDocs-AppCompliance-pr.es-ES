---
title: Información de la aplicación para el rastreador de vacaciones de Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Vacation Tracker, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55d54fbb94141dec562a829fdc647279a3cc006e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527546"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Vacation Tracker a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Vacation Tracker |
| Id. | WA200002167 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Vacation Tracker |
| Dirección URL del sitio web de partners | [https://vacationtracker.io](https://vacationtracker.io) |
| Dirección URL de Teams de información de la aplicación | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| Dirección URL de la directiva de privacidad | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

El Rastreador de vacaciones ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | delegado | Leemos los nombres y los nombres de los canales públicos cuando los usuarios establecen sus notificaciones semanales o diarias. | Los usuarios pueden seleccionar un canal en el que desean recibir notificaciones diarias o semanales de Vacation Tracker. Cuando un usuario elige su canal preferido, almacenamos el identificador del canal. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | delegado | Enumeramos el usuario Microsoft Teams teams unidos durante el registro para permitir a los usuarios seleccionar un equipo al que desean registrarse en Vacation Tracker. También pueden registrarse con toda la organización. | Almacenamos el Microsoft Teams de equipo de un equipo seleccionado solo si el usuario se inscribe en Vacation Tracker como un único equipo (no como toda una organización). Usamos los id. de equipo para conectar un usuario que ha iniciado sesión con una cuenta existente en Vacation Tracker. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | delegado | Recopilamos la información básica del usuario, incluido su nombre, identificador e identificador de inquilino. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | Almacenamos el nombre, el identificador y el identificador de inquilino del usuario. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | delegado | Nuestros usuarios pueden importar todos los usuarios de su Microsoft 365 organización o Microsoft Teams equipo. Usamos este permiso para importar solo usuarios con licencia para un equipo u organización Microsoft Teams seleccionado. | Almacenamos información básica sobre los usuarios importados, incluido su nombre, dirección de correo electrónico e id. de usuario. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | delegado | Permitimos que los usuarios importen los demás usuarios de su organización o su Microsoft Teams usuario. Usamos este permiso para enumerar los usuarios disponibles y sus direcciones de correo electrónico en el elemento emergente de importación. | Cuando los usuarios seleccionan a sus compañeros de trabajo para importarlos a Vacation Tracker, almacenamos información básica sobre estos usuarios importados, incluido su nombre, dirección de correo electrónico e id. de usuario. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| email | delegado | Cuando el usuario inicia sesión con Microsoft AAD, almacenamos su dirección de correo electrónico como un identificador único. | Almacenamos el correo electrónico del usuario como un identificador único. No usamos este correo electrónico para la comunicación, los usuarios escriben su dirección de correo electrónico empresarial que usamos para la comunicación durante el registro. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | delegado | No recopilamos datos con este permiso. Se usa para mantener el acceso a los datos a los que tenemos permiso. | No almacenamos datos con este permiso. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| OpenID | delegado | Usamos este permiso para iniciar sesión o registrar usuarios en Vacation Tracker. No recopilamos datos específicos con este permiso. | Usamos este permiso para iniciar sesión o registrar usuarios en Vacation Tracker. No almacenamos datos específicos con este permiso. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| perfil | delegado | Recopilamos la información básica del usuario, incluido su nombre, identificador e identificador de inquilino. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | Almacenamos el nombre, el identificador y el identificador de inquilino del usuario. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nombre de la compañía (según lo especificado por el usuario) | Cuando un usuario se inscribe, escribe su nombre de empresa y usamos este nombre como el nombre de la organización dentro del producto |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El bot puede ver la información básica sobre la comunicación del usuario con el bot. Sin embargo, no almacenamos ni usamos esa información. Solo usamos el identificador del usuario, el identificador de conversación y un mensaje enviado a nuestro bot. | Almacenamos la dirección de correo electrónico del usuario, el nombre del usuario (tal como se define en microsoft AAD) y la foto de perfil del usuario (de Microsoft AAD) | Usamos una dirección de correo electrónico como identificador único para nuestros usuarios y el nombre y la foto de perfil del usuario para permitir que los administradores y aprobadores de la misma compañía reconozcan a sus empleados en nuestro panel.  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nombre de la empresa y se conserva y quita de acuerdo con nuestra directiva de retención estándar de un año para este tipo de datos

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Para empezar, recopilamos la cantidad mínima de datos necesarios para los usuarios. A continuación, compartimos el mínimo posible con nuestros partners y, por último, tenemos directivas de retención de datos para que todos los datos se quiten en el plazo de un año, si procede.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Vacation Tracker ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
