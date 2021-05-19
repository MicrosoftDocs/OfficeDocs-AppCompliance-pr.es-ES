---
title: Información de la aplicación para Vacation Tracker por Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Vacation Tracker, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551000"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 5 de febrero de 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Vacation Tracker a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Vacation Tracker |
| ID | WA200002167 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Vacation Tracker |
| URL del sitio web de socios | [https://vacationtracker.io](https://vacationtracker.io) |
| URL de Teams página de información de la aplicación | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL de la Política de Privacidad | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL de los Términos de uso | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Vacation Tracker ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Delegado | Leemos los archivos de usuario y los nombres de los canales públicos cuando los usuarios establecen sus notificaciones semanales o diarias. | Los usuarios pueden seleccionar un canal donde quieran recibir notificaciones diarias o semanales de Vacation Tracker. Cuando un usuario elige su canal preferido, almacenamos el ID de canal. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | Delegado | Enumeramos el usuario de Microsoft Teams equipos unidos durante el registro para permitir a los usuarios seleccionar un equipo al que desean registrarse en Vacation Tracker. Alternativamente, pueden inscribirse en toda su organización. | Almacenamos el ID de equipo Microsoft Teams para un equipo seleccionado solo si el usuario se registra en Vacation Tracker como un solo equipo (no como una organización completa). Utilizamos ID de equipo para conectar a un usuario que ha iniciado sesión con una cuenta existente en Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | Delegado | Recopilamos la información básica del usuario, incluido su nombre, ID e identificador de inquilino. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | Almacenamos el nombre, el ID y el identificador del inquilino del usuario. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | Delegado | Nuestros usuarios pueden importar todos los usuarios de su organización Microsoft 365 o Microsoft Teams equipo. Usamos este permiso para importar solo usuarios con licencia para un equipo u organización de Microsoft Teams seleccionado. | Almacenamos información básica sobre los usuarios importados, incluido su nombre, dirección de correo electrónico e ID de usuario. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | Delegado | Permitimos a los usuarios importar los demás usuarios de su organización o de su equipo de Microsoft Teams. Usamos este permiso para enumerar los usuarios disponibles y sus direcciones de correo electrónico en la ventana emergente de importación. | Cuando los usuarios seleccionan a sus compañeros de trabajo para importarlos a Vacation Tracker, almacenamos información básica sobre estos usuarios importados, incluido su nombre, dirección de correo electrónico e ID de usuario. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | Delegado | Cuando el usuario inicia sesión con Microsoft AAD, almacenamos su dirección de correo electrónico como un identificador único. | Almacenamos el correo electrónico del usuario como un identificador único. No utilizamos este correo electrónico para la comunicación, los usuarios ingresan su dirección de correo electrónico comercial que utilizamos para la comunicación durante el registro. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | Delegado | No recopilamos ningún dato con este permiso. Se utiliza para mantener el acceso a los datos a los que autorizamos el acceso. | No almacenamos ningún dato con este permiso. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| OpenID | Delegado | Usamos este permiso para iniciar sesión o registrar usuarios en Vacation Tracker. No recopilamos ningún dato específico con este permiso. | Usamos este permiso para iniciar sesión o registrar usuarios en Vacation Tracker. No almacenamos ningún dato específico con este permiso. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| perfil | Delegado | Recopilamos la información básica del usuario, incluido su nombre, ID e identificador de inquilino. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | Almacenamos el nombre, el ID y el identificador del inquilino del usuario. Usamos estos datos para conectar usuarios que han iniciado sesión a su organización en Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitud, Google Tag Manager | Nombre de la empresa (según lo introducido por el usuario) | Cuando un usuario se registra, introduce el nombre de su empresa y usamos este nombre como nombre de organización dentro del producto |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| El bot puede ver la información básica sobre el usuario que se comunica con el bot. Sin embargo, no almacenamos ni usamos esa información. Solo usamos el ID del usuario, el ID de conversación y un mensaje enviado a nuestro bot. | Almacenamos la dirección de correo electrónico del usuario, el nombre del usuario (tal como se define en el AAD de Microsoft) y la foto de perfil del usuario (de Microsoft AAD) | Utilizamos una dirección de correo electrónico como identificador único para nuestros usuarios y el nombre del usuario y la foto de perfil para permitir que los administradores y aprobadores de la misma empresa reconozcan a sus empleados en nuestro panel de control.  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Nombre de la empresa y se conserva y elimina de acuerdo con nuestra política estándar de retención de un año para este tipo de datos

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Para empezar, recopilamos la cantidad mínima de datos requeridos a los usuarios. Luego compartimos el mínimo posible con nuestros socios y finalmente tenemos políticas de retención de datos para que todos los datos se eliminen dentro de un año si corresponde.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Vacation Tracker ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
