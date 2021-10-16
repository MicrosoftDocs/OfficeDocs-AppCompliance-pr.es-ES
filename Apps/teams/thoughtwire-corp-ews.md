---
title: Información de la aplicación para EWS ThoughtWire de ThoughtWire Corp.
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para EWS ThoughtWire, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ef425a6acb8cfe166502b4c4817229b1b33da14b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414917"
---
# <a name="thoughtwire-ews"></a>ThoughtWire EWS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ed27363f-755e-4658-b7bf-409d475959d6" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003239" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ThoughtWire Corp. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ThoughtWire EWS |
| Id. | WA200003239 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ThoughtWire Corp. |
| Dirección URL del sitio web de partners | [https://thoughtwire.com](https://thoughtwire.com) |
| Dirección URL de la directiva de privacidad | [https://thoughtwire.com/privacy-policy](https://thoughtwire.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.thoughtwire.com/end-user-license-agreement/](https://www.thoughtwire.com/end-user-license-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ThoughtWire Corp ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Create | aplicación | Permite que la aplicación cree grupos o equipos para salas o unidades de hospital. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| Group.ReadWrite.All | aplicación | Necesario para que la aplicación determine los grupos que puede necesitar para crear o volver a crear, y para administrar la pertenencia. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| GroupMember.ReadWrite.All | aplicación | Necesario para que la aplicación pueda administrar la pertenencia a grupos. Es decir, agregar o quitar enfermeras de un equipo a medida que cambian los turnos. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamMember.ReadWrite.All | aplicación | Necesario para que la aplicación pueda administrar la pertenencia a grupos. Es decir, agregar o quitar enfermeras de un equipo a medida que cambian los turnos. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamsAppInstallation.ReadWriteForTeam | aplicación | Permite que la aplicación instale automáticamente el bot de ThoughtWire en los equipos que crea o administra. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| User.Read | aplicación | Permitir que la aplicación recupere el AADID/nombre de usuario de un usuario según sea necesario al administrar la pertenencia o recuperar el nombre de usuario para identificar al usuario dentro de nuestra aplicación. | Ninguno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El nombre de usuario es necesario para identificar al usuario que realiza acciones. | Nombre de usuario e id. de usuario | Auditoría de notificaciones y eventos. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>ThoughtWire selecciona socios que cumplen o superan nuestros propios procesos de control de datos. Los datos no se proporcionan a los sistemas asociados a menos que sean absolutamente necesarios. Todos los servicios ThoughtWire y los sistemas asociados relacionados son vistos y aprobados por los clientes.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ThoughtWire Corp ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

