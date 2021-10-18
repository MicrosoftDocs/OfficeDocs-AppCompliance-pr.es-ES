---
title: Información de la aplicación para La Teams de Powell software
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Teams, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bdf4afe576656e8aed81c00364fefd1b99a822ac
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427952"
---
# <a name="powell-teams"></a>Powell Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/423d394a-892e-44d1-b9f0-ff382643df42" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001585" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Software de Powell a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Powell Teams |
| Id. | WA200001585 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Powell Software |
| Dirección URL del sitio web de partners | [https://www.powell-software.com](https://www.powell-software.com) |
| Dirección URL de Teams de información de la aplicación | [https://helpteams.powell-software.com](https://helpteams.powell-software.com) |
| Dirección URL de la directiva de privacidad | [https://powell-software.com/en/powell-teams-privacy](https://powell-software.com/en/powell-teams-privacy) |
| DIRECCIÓN URL de términos de uso | [https://powell-software.com/en/powell-teams-terms-of-use/](https://powell-software.com/en/powell-teams-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por software de Powell sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Group.ReadWrite.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Notes.Read.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Notes.ReadWrite.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Sites.Read.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| User.Read.All | delegado | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Id. Azure AD usuario e identificador de inquilino de usuario

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>ningún partner contiene datos

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Este software de Powell ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
