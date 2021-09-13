---
title: Información de la aplicación para ClipTraining por ClipTraining
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para ClipTraining, sus directivas de control de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5d59d4cbd2d28f1c906e541e7ffc78311c12ffb6
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59285935"
---
# <a name="cliptraining"></a>ClipTraining

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6cb4b701-2a4f-4080-8a8a-d99f93905e15" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001687" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ClipTraining a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ClipTraining |
| Id. | WA200001687 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ClipTraining |
| Dirección URL del sitio web de partners | [https://www.cliptraining.com](https://www.cliptraining.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.cliptraining.com](https://www.cliptraining.com) |
| Dirección URL de la directiva de privacidad | [https://www.cliptraining.com/privacy-policy/](https://www.cliptraining.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.cliptraining.com/eula/](https://www.cliptraining.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ClipTraining ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| offline_access | delegado | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| OpenID | delegado | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| perfil | delegado | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | Dirección de correo electrónico, nombre, apellido para el inicio de sesión y la correspondencia del usuario.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| servicio de hospedaje que no es de Microsoft, que no Microsoft CRM | Nombre, apellido, dirección de correo electrónico | Obligatorio para el uso empresarial |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nombre, apellido, dirección de correo electrónico. Retención y eliminación por directiva de ClipTraining, disponible a petición

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los sistemas asociados a los que ClipTraining usa y tiene acceso, se siguen las directivas de ClipTraining. 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ClipTraining ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
