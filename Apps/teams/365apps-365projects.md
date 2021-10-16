---
title: Información de la aplicación para 365Projects por 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para 365Projects, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d0b60f86e96d0ce35e51956a778f9379cdad9bef
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412019"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por 365Apps a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | 365Projects |
| Id. | WA200002160 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | 365Apps |
| Dirección URL del sitio web de partners | [https://365apps.com.au](https://365apps.com.au) |
| Dirección URL de Teams de información de la aplicación | [https://365projects.app](https://365projects.app) |
| Dirección URL de la directiva de privacidad | [https://365projects.app/privacy](https://365projects.app/privacy) |
| DIRECCIÓN URL de términos de uso | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

365Apps ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | canales dentro del equipo para vincular el proyecto con el canal | canales dentro del equipo para vincular el proyecto con el canal | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.Read.All | delegado | obtener tareas de organizador de equipo/organizador, será mejor si otro ámbito de privilegios mínimos permite a la aplicación obtener planes de usuario y planea tareas, pero lamentablemente no hay ámbitos que lo permitan | no almacenar en DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.ReadWrite.All | aplicación | Crear Teams  | no almacenado en DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| People.Read | delegado | nombre de usuario, para agregarlos como miembros del equipo o asignarles tareas | Guid de usuario se almacena en la asignación de tareas | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Team.ReadBasic.All | delegado | Nombres de equipo unidos, para vincular el proyecto Teams canal | Team Guid se almacena en los metadatos del proyecto para establecer el vínculo | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read | delegado | obtener información de usuario para mostrarla en el encabezado  | el correo electrónico del usuario se almacena como propietario cuando se aprovisiona por primera vez el espacio empresarial | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read.All | delegado | leer usuarios para actualizar la asignación de tareas | solo guid de usuario se almacena ninguna información identificada personal se almacena en la base de datos | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |


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

>La aplicación no almacena datos de usuario aparte del Guid del administrador de la aplicación (el primer usuario usa la aplicación dentro del espacio empresarial) 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

365Apps ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | ,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

