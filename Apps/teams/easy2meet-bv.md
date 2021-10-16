---
title: Información de la aplicación para Easy2Meet de Easy2Meet B.V.
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Easy2Meet, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 6983b46f281ed725aa4597acfa87944b5bc2c023
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412429"
---
# <a name="easy2meet"></a>Easy2Meet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8dbb8c54-678e-4c02-bc35-0f393416e532" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003277" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Easy2Meet B.V. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Easy2Meet |
| Id. | WA200003277 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Easy2Meet B.V. |
| Dirección URL del sitio web de partners | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| Dirección URL de Teams de información de la aplicación | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| Dirección URL de la directiva de privacidad | [https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf](https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf) |
| DIRECCIÓN URL de términos de uso | [https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet...](https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet%20General%20Terms%20and%20Conditions%20Sept%202020%20EN.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Easy2Meet B.V ha proporcionado esta información. acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Necesitamos información de usuario para administrar usuarios y reuniones en Easy2Meet | Correo electrónico y nombre. Necesitamos esto para administrar usuarios y reuniones. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| email | delegado | Para ver las adres de correo electrónico del usuario actual. Necesitamos las adres de correo electrónico para enviar invitaciones a reuniones | Correo electrónico y nombre. Necesitamos esto para administrar usuarios y reuniones. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| OpenID | delegado | aquí no recopilamos datos. Estamos usando esto para iniciar sesión en el usuario | aquí no recopilamos datos. Estamos usando esto para iniciar sesión en el usuario. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| perfil | delegado | Necesitamos información de usuario para administrar usuarios y reuniones en Easy2Meet | Correo electrónico y nombre. Necesitamos esto para administrar usuarios y reuniones. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint Online | No |  |  |  |  |
>| MS Exchange Online | No |  |  |  |  |

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

>auditoría

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Easy2Meet B.V ha proporcionado esta información. acerca de cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

