---
title: Información de la aplicación para el registro Ideas ASC por ASC Technologies AG
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para el registro de ASC Ideas, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4d3e2f1ec03c2437e12576b0fdff68b06392ae9c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412585"
---
# <a name="asc-recording-insights"></a>ASC Recording Insights

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8f79287d-5850-42f1-9af2-48ddf6ef89a8" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000708" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ASC Technologies AG a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ASC Recording Insights |
| Id. | WA200000708 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ASC Technologies AG |
| Dirección URL del sitio web de partners | [https://asctechnologies.com/english/index.html](https://asctechnologies.com/english/index.html) |
| Dirección URL de Teams de información de la aplicación | [https://asctechnologies.com/english/ASC_Recording_Insights_...](https://asctechnologies.com/english/ASC_Recording_Insights_Compliance_Recording_for_Microsoft_Teams.html) |
| Dirección URL de la directiva de privacidad | [https://teams.asc-recording.app/privacy](https://teams.asc-recording.app/privacy) |
| DIRECCIÓN URL de términos de uso | [https://asctechnologies.com/english/asc_impressum.html](https://asctechnologies.com/english/asc_impressum.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ASC Technologies AG ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicación | Información de las reuniones del usuario | Identificador de objeto de las reuniones | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read | aplicación | Chats generados de los usuarios | Identificador de objeto de los chats | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read.All | aplicación | Chats generados de los usuarios | Identificador de objeto de los chats | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Group.Read.All | aplicación | Grupo de usuarios de Ad de pertenencia | Id. de objeto del grupo ad | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| OnlineMeetings.Read.All | aplicación | Información de las reuniones del usuario | Identificador de objeto de las reuniones | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.Read | aplicación | Nombres y apellidos de los usuarios | Id. de objeto del usuario | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.ReadBasic.All | aplicación | Datos básicos del usuario | Id. de objeto del usuario | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EXPORTAR API | No |  |  |  |  |

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

>No tenemos datos en los sistemas de partners

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ASC Technologies AG ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | ,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

