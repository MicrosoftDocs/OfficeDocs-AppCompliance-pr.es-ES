---
title: Información de la aplicación para 365Proyectos por 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para 365Proyectos, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d760c1c5bacf37fa23e26f4a9a15eb7dbbd75bb1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553471"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por 365Apps a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | 365Projects |
| ID | WA200002160 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | 365Apps |
| URL del sitio web de socios | [https://365projects.app](https://365projects.app) |
| URL de Teams página de información de la aplicación | [https://365projects.app](https://365projects.app) |
| URL de la Política de Privacidad | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL de los Términos de uso | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

365Apps ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Delegado | canales dentro del equipo para vincular el proyecto con el canal | canales dentro del equipo para vincular el proyecto con el canal | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | Delegado | obtener tareas de planificador/planificador de equipos, será mejor si otro ámbito de privilegios mínimos permite a la aplicación obtener planes de usuario y tareas de planes, pero lamentablemente no hay ámbitos que permitan esto | no almacenar en DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | aplicación | Crear Teams  | no almacenado en DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| People.Read | Delegado | nombre de usuario, para agregarlos como miembros del equipo o asignarles tareas | usuario Guid se almacena en la asignación de tareas | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | Delegado | Se unieron a nombres de equipo, para vincular el proyecto a Teams Canal | Team Guid se almacena en los metadatos del proyecto para establecer el vínculo | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | Delegado | obtener información del usuario para mostrarla en el encabezado  | correo electrónico del usuario se almacena como propietario cuando se aprovisiona por primera vez el inquilino | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | Delegado | leer a los usuarios para actualizar la asignación de tareas | sólo el usuario Guid se almacena sin información personalizada identificada se almacena en la base de datos | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en la telemetría o registros de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>La aplicación no almacena datos de usuario aparte de Guid del administrador de la aplicación (el primer usuario usa la aplicación dentro del inquilino) 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

365Apps ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | ,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/> |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
