---
title: Información de la aplicación para Plumm por Plumm Health LTD
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Plumm, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8fef6e74339b611b06d39e6bbe32f9661e20656c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429878"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Plumm Health LTD a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Plumm |
| Id. | WA200003326 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Plumm Health LTD |
| Dirección URL del sitio web de partners | [https://www.plummhealth.com](https://www.plummhealth.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| Dirección URL de la directiva de privacidad | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Plumm Health LTD ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | aplicación | Usamos el userID en este permiso. Esto se usa para enviar notificaciones de requisitos al usuario en función de su uso de nuestro servicio. Esto es importante para que el usuario reciba las notificaciones adecuadas para su cuenta en nuestra aplicación. | Con este permiso, no almacenamos ningún dato en nuestra base de datos. De hecho, estamos usando el userID para enviar una notificación adecuada a cada usuario individual en función de su uso. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | aplicación | Recibimos el id. de instalación mediante este permiso. Esto es importante para nosotros para poder enviar la notificación adecuada y correcta para cada usuario individual. | No almacenamos datos en nuestra aplicación con este permiso. No lo necesitamos porque solo necesitamos el identificador de instalación que se obtiene en tiempo de ejecución proporcionando el userID. Esto se obtiene dinámicamente en tiempo de ejecución, por lo tanto, no es necesario almacenar el identificador de instalación. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | delegado | Estamos recopilando el nombre, la imagen y el correo electrónico de nuestros usuarios a través de este permiso. Esto es necesario para que seamos capaces de identificar usuarios individuales y estos puntos de datos se mostrarán siempre que sea necesario, como la página de perfil individual y la comunicación por correo electrónico/notificación. | Estos permisos permiten a nuestra aplicación ver el perfil básico de nuestros usuarios (nombre, imagen, correo electrónico). Estos datos se usarán para mostrar el nombre y/o la imagen de perfil del usuario en su cuenta de aplicación con nosotros y en la comunicación por correo electrónico y/o notificación. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | aplicación | Este permiso permite a nuestra aplicación leer perfiles de usuario sin que un usuario haya iniciado sesión. En este momento estamos recopilando solo el nombre, la imagen de perfil y el correo electrónico. Esto es necesario para que seamos capaces de identificar usuarios individuales y estos puntos de datos se mostrarán siempre que sea necesario, como la página de perfil individual y la comunicación por correo electrónico/notificación. | Estos permisos permiten a nuestra aplicación ver el perfil básico de nuestros usuarios (nombre, imagen, correo electrónico). Estos datos se usarán para mostrar el nombre y/o la imagen de perfil del usuario en su cuenta de aplicación con nosotros y en la comunicación por correo electrónico y/o notificación. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | delegado | Se recopila el identificador de correo electrónico del usuario. Requerimos estos datos para conceder acceso al usuario para nuestros servicios e iniciar sesión en nuestra aplicación y recibir notificaciones sobre sus cuentas y nuestros servicios en este identificador de correo electrónico.  | El identificador de correo electrónico se almacena en la base de datos. Debemos almacenar el identificador de correo electrónico para identificar de forma única a los usuarios, proporcionarles acceso a nuestra aplicación, ayudarles a iniciar sesión y ayudarles a recibir notificaciones sobre su cuenta con nosotros. Por ejemplo, un usuario con identificador de correo abc@xyz.com podrá acceder a nuestra aplicación y servicios cuando inicie sesión en &quot; Teams con este identificador de correo &quot; electrónico. En función del uso, podremos enviar notificaciones a este usuario en su id. de correo electrónico. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| OpenID | delegado | Para este permiso, no recopilamos datos.  | Para este permiso, no recopilamos datos. Este permiso permite a los usuarios iniciar sesión en nuestra aplicación con su identificador de correo electrónico de trabajo y permite que la aplicación vea información básica del perfil de usuario. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| perfil | delegado | Estamos recopilando el nombre, la imagen y el correo electrónico de nuestros usuarios a través de este permiso. Esto es necesario para que seamos capaces de identificar usuarios individuales y estos puntos de datos se mostrarán siempre que sea necesario, como la página de perfil individual y la comunicación por correo electrónico/notificación. | Estos permisos permiten a nuestra aplicación ver el perfil básico de nuestros usuarios (nombre, imagen, correo electrónico). Estos datos se usarán para mostrar el nombre y/o la imagen de perfil del usuario en su cuenta de aplicación con nosotros y en la comunicación por correo electrónico y/o notificación. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | Nombre, apellido, correo electrónico | El interfono es nuestro CRM que nos ayuda a administrar la comunicación con todos nuestros usuarios. Es por ello que debemos enviar el nombre, apellidos e id. de correo electrónico de nuestros usuarios al CRM para que los mensajes o correos electrónicos adecuados se puedan enviar a los usuarios. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Almacenamos datos de uso del servicio, como el número de sesiones de tratamiento usadas, los cursos vistos, las meditaciones vistas, la fecha de las sesiones, etc. Conservamos los datos de nuestros usuarios hasta que el usuario pida específicamente que se elimine o "olvide" su cuenta.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Administramos los datos que se envían al CRM a través de nuestro servidor. Los datos mínimos necesarios para funcionar se pasan al CRM (intercomunicador). Plumm tiene control total sobre los datos que se pasan al CRM, la retención de los datos en el intercomunicador y eliminarlos. Este es un vínculo para revisar las directivas de datos de cliente de Intercom: https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Plumm Health LTD ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | ,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
