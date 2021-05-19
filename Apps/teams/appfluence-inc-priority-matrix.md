---
title: Información de la aplicación para matriz prioritaria por Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Priority Matrix, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 50814045f621d38df3a4a8ce65fb361d72a6f7a3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552401"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 16 de abril de 2021</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382005" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Appfluence Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Priority Matrix |
| ID | WA104382005 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Appfluence Inc |
| URL del sitio web de socios | [https://appfluence.com](https://appfluence.com) |
| URL de Teams página de información de la aplicación | [https://appfluence.com/project-management-integration-for-m...](https://appfluence.com/project-management-integration-for-microsoft-teams/) |
| URL de la Política de Privacidad | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL de los Términos de uso | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Appfluence Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegado | Solo cuando se agrega un nuevo usuario a la cuenta, almacenamos su correo electrónico. | En la creación de nuevas cuentas, usamos esto para sugerir a otros miembros del equipo. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | Delegado | Solo cuando se agrega un nuevo usuario a la cuenta, almacenamos su correo electrónico. | En la creación de nuevas cuentas, usamos esto para sugerir a otros miembros del equipo. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | Delegado | Almacenamos el token de inicio de sesión para realizar solicitudes en nombre del usuario | Actualice el token sin molestar al usuario. (Matriz de prioridad para Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | Delegado | No almacenamos ninguna información de archivo, a menos que el usuario cree explícita y a sabiendas un elemento de matriz de prioridad que se vincule al archivo original. | En nuestra función Uno a uno (disponible a través de nuestra aplicación web y también nuestros complementos de Outlook/Teams), utilizamos esta función para resaltar SharePoint/OneDrive archivos que se comparten entre dos usuarios en nuestro sistema, como una forma de facilitar reuniones y colaboración general. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | Delegado | La información básica del perfil de usuario (nombre para mostrar, nombre, apellido, correo electrónico, avatar) es almacenada por nosotros. | Obtenga el nombre, el correo electrónico, el avatar del usuario, para personalizar su cuenta con nosotros. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| OpenID | Delegado | Almacenamos la conexión SSO para indicar el modo de inicio de sesión para el usuario. | Para iniciar sesión a los usuarios a través de un solo inicio de sesión. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | Delegado | Un pequeño número de eventos de calendario se convierten en tareas almacenadas en nuestro sistema. | Lea los eventos del calendario para que se puedan mostrar en nuestra vista 1:1. También para inicializar nuevas cuentas.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | Delegado | Almacenamos tareas creadas en nuestro sistema, con un enlace al mensaje original. | Se utiliza en nuestro complemento Outlook para convertir correos electrónicos en tareas y para mostrar el trabajo compartido en la vista 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | Delegado | Algunas tareas Outlook/Planificador se replican en nuestro sistema para ayudar a los nuevos usuarios. | Arrancamos nuevas cuentas de usuario con sus Graph tareas. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| El bot es capaz de crear tareas y asignarlas a un compañero de equipo específico, y para ello necesita saber su nombre. | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, utilizamos el correo electrónico del usuario como su ID único en nuestro sistema, y que se utiliza para rastrear errores de aplicación, y para realizar un seguimiento de eventos clave en el sistema (descargas, inicios de sesión, versiones de aplicaciones, etc.) para que nuestro equipo de servicio al cliente pueda proporcionar una respuesta rápida a las consultas de los clientes. Como parte de nuestro cumplimiento gdpr, eliminamos todos los datos de los clientes dentro de las 2 semanas posteriores a una solicitud de eliminación, aunque en la práctica lo hacemos el mismo día, ya que tenemos scripts internos para hacerlo de una manera semiautomática.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos de la aplicación se almacenan de forma segura en una base de datos cifrada con acceso limitado a un pequeño grupo de administradores. Para asegurar aún más el acceso, aplicamos la autenticación de 2 factores, limitamos el acceso a un conjunto controlado de direcciones IP y localizamos la base de datos en su propia subred privada, directamente inaccesible desde internet abierto.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Appfluence Inc ha proporcionado esta información sobre cómo esta aplicación maneja la autenticación, autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/><br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
