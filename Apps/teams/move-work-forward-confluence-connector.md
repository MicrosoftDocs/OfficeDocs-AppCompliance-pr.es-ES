---
title: Información de la aplicación para Confluence Connector por Move Work Forward
ms.author: elmalova
author: elenamalova
ms.date: 09/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Confluence Connector, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bcf00959b3f6e667adedf8dbffd017d01e1bbc65
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785599"
---
# <a name="confluence-connector"></a>Conector de confluencia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3c9fd7ca-5386-4179-9bb7-7fcdcc373017" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001604" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Move Work Forward to Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Conector de confluencia |
| Identificador | WA200001604 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Avance el trabajo |
| Dirección URL del sitio web de partners | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.moveworkforward.com/product/microsoft-teams-con...](https://www.moveworkforward.com/product/microsoft-teams-confluence-connector) |
| Dirección URL de la directiva de privacidad | [https://moveworkforward.com/privacy-policy](https://moveworkforward.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Move Work Forward proporciona esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | El nombre del canal y el identificador se usan para enviar notificaciones de Jira a Microsoft Teams. | El identificador de canal y el nombre se almacenan para configurar las notificaciones de Jira a Microsoft Teams. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| Teams.ReadBasic.All | delegado | El permiso se usa para permitir que el usuario seleccione uno de estos equipos unidos en Jira. | Id. de equipo y nombre que se mostrarán en la pantalla Configuración de Jira. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| TeamsAppInstallation.ReadForTeam | delegado | Lee las aplicaciones Teams instaladas en teams. Al configurar la entrega para Microsoft Teams la aplicación puede enviar a Teams con el Bot instalado. | Nothing | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| User.Read | delegado | Permite al usuario crear un canal de discusión con compañeros de trabajo y @-mencione en un mensaje de canal | Nothing | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| email | delegado | El correo electrónico se usa para coincidir con usuarios de Atlas y Microsoft | El correo electrónico no se almacena. Solo se usa durante el proceso de coincidencia. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Saluda a los usuarios por su nombre al instalar la aplicación. Coincide Microsoft Teams usuarios de Atlassian. | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Registramos la dirección URL del inquilino, que se almacena en los registros durante un máximo de 5 días.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Solo trabajamos con servicios que ofrecen estrictas garantías de privacidad de datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Move Work Forward proporciona esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
