---
title: 'Información de la aplicación para la matriz de prioridad: convertir correos electrónicos en tareas de Appfluence Inc'
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 'Toda la información de seguridad y cumplimiento disponible para Priority Matrix: convierta los correos electrónicos en tareas, sus directivas de control de datos, la información del catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.'
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3f4ba1a7f888c576ae7a87286488d7b5f06037a2
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258997"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Matriz de prioridad: convertir correos electrónicos en tareas

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: April 16, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Appfluence Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Matriz de prioridad: convertir correos electrónicos en tareas |
| ID | WA104381735 |
| Clientes de Office 365 compatibles | Outlook 2016 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en iOS, Outlook en Android, Outlook en la web |
| Nombre de la compañía asociada | Appfluence Inc |
| Dirección URL del sitio web de partners | [https://appfluence.com/](https://appfluence.com/) |
| Dirección URL de la directiva de privacidad | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Appfluence Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar los [permisos de Microsoft Graph que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegado | Solo cuando se agrega un nuevo usuario a la cuenta, almacenamos su correo electrónico. | En la creación de nuevas cuentas, lo usamos para sugerir a otros miembros del equipo. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | delegado | Solo cuando se agrega un nuevo usuario a la cuenta, almacenamos su correo electrónico. | En la creación de nuevas cuentas, lo usamos para sugerir a otros miembros del equipo. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | delegado | Almacenamos el token de inicio de sesión para realizar solicitudes en nombre del usuario | Actualice el token sin molestar al usuario. (Matriz de prioridad para Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | delegado | No almacenamos ninguna información de archivo, a menos que el usuario cree explícita y conscientemente un elemento de matriz de prioridad que se vincula al archivo original. | En nuestra característica uno a uno (disponible a través de nuestra aplicación web y también de nuestros complementos de Outlook/Teams), usamos esta característica para resaltar los archivos de SharePoint/OneDrive que se comparten entre dos usuarios de nuestro sistema, como una forma de facilitar las reuniones y la colaboración general. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | delegado | La información básica del perfil de usuario (nombre para mostrar, nombre, apellido, correo electrónico, avatar) la almacenamos nosotros. | Obtén el nombre, el correo electrónico, el avatar del usuario para personalizar su cuenta con nosotros. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| OpenID | delegado | Almacenamos la conexión SSO para indicar el modo de inicio de sesión del usuario. | Para iniciar sesión en los usuarios mediante el inicio de sesión único. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | delegado | Un pequeño número de eventos de calendario se convierten en tareas almacenadas en nuestro sistema. | Lea los eventos del calendario para que se puedan mostrar en nuestra vista 1:1. También para inicializar cuentas nuevas.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | delegado | Almacenamos las tareas creadas en nuestro sistema, con un vínculo al mensaje original. | Se usa en nuestro complemento de Outlook para convertir correos electrónicos en tareas y para mostrar el trabajo compartido en la vista 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | delegado | Algunas tareas de Outlook/Planner se replican en nuestro sistema para ayudar a los nuevos usuarios. | Iniciamos nuevas cuentas de usuario con sus tareas de Graph. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Servicios que no son de Microsoft usados

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se usan servicios que no son de Microsoft.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Buzón de ReadWrite | Este complemento puede leer o modificar el contenido de cualquier elemento del buzón y crear nuevos elementos. Puede tener acceso a información personal (como el cuerpo, el asunto, el remitente, los destinatarios o los datos adjuntos) en cualquier mensaje o elemento del calendario. Puede enviar estos datos a un servicio de terceros. |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí, usamos el correo electrónico del usuario como su identificador único en nuestro sistema, que se usa para realizar un seguimiento de los errores de la aplicación y para realizar un seguimiento de los eventos clave del sistema (descargas, inicios de sesión, versiones de aplicaciones, etc.) para que nuestro equipo de servicio al cliente pueda proporcionar una respuesta rápida a las consultas de los clientes. Como parte de nuestro cumplimiento del RGPD, eliminamos todos los datos de clientes dentro de las dos semanas siguientes a una solicitud de eliminación, aunque en la práctica lo hacemos el mismo día, ya que tenemos scripts internos para hacerlo de forma semiautomática.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de la aplicación se almacenan de forma segura en una base de datos cifrada con acceso limitado a un pequeño grupo de administradores. Para proteger aún más el acceso, aplicamos la autenticación en dos fases, limitamos el acceso a un conjunto controlado de direcciones IP y localizamos la base de datos en su propia subred privada, directamente inaccesible desde Internet abierto.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Appfluence Inc ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de la plataforma de identidades de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
