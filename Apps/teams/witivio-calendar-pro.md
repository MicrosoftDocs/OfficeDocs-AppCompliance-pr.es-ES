---
title: Información de la aplicación para Pro calendario por Witivio
ms.author: elmalova
author: elenamalova
ms.date: 09/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para calendar Pro, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 262747068d05ac8aa5c0987c8f6838715eabdf0c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444940"
---
# <a name="calendar-pro"></a>Calendar Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/19a29a41-cbca-4152-a2af-dd9728ea35f1" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002152" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Witivio a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Calendar Pro |
| Id. | WA200002152 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Witivio |
| Dirección URL del sitio web de partners | [https://www.witivio.com](https://www.witivio.com) |
| Dirección URL de la directiva de privacidad | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Witivio ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Se usan los datos | Los datos se usan para mostrar la información en la interfaz de usuario | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| User.ReadBasic.All | delegado | Se usan los datos | Los datos se usan para enumerar personas para habilitar el selector de personas | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| email | delegado | Se usa el correo electrónico | El correo electrónico se usa para identificar al usuario en la interfaz de usuario | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| offline_access | delegado | Se usan los datos | El acceso sin conexión se usa para habilitar SSO con Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| OpenID | delegado | Autenticación | OpenID se usa para la autenticación con Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| perfil | delegado | Se usan los datos | El perfil se usa para habilitar SSO con Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La telemetría contiene el UPN y el AAD de diagnóstico. Solo los administradores de PROD/Run tienen acceso a la telemetría de producción. Los registros se almacenan durante 90 días y se pueden eliminar a petición por correo electrónico en dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Witivio solo usa Microsoft Azure componentes, implementados en la región norte de Europa. Usamos la información de aplicaciones y Cosmos base de datos para el análisis de datos y el almacenamiento. Witivio usa MFA para todos los usuarios, incluidos los administradores. Los administradores tienen una cuenta de usuario (para la estación de trabajo) y una cuenta con privilegios para obtener acceso a recursos de Azure.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Witivio ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
