---
title: Información de la aplicación para la llamada webex de Cisco
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Webex Call, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c6552bd7b266f4c35d35dabefe3abbf7e407ea1
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281963"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cisco a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Webex Call |
| Id. | WA200001495 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Cisco |
| Dirección URL del sitio web de partners | [https://www.cisco.com](https://www.cisco.com) |
| Dirección URL de la directiva de privacidad | [https://www.cisco.com/c/en/us/about/legal/privacy.html](https://www.cisco.com/c/en/us/about/legal/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Cisco ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.Read | delegado | Obtener miembros de chat para poder llamar al otro miembro en chat privado con Cisco WebEx | La aplicación NO almacenaría datos en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| Contacts.Read | delegado | Obtener contactos de usuario, para que el usuario pueda llamar a contactos con Cisco WebEx | La aplicación NO almacenaría datos en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.Read | delegado | obtener correo electrónico del usuario, teléfonos para que puedan iniciar Cisco WebEx para llamar a teléfonos o correo electrónico | La aplicación NO almacenaría datos en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadBasic.All | delegado | obtener correo electrónico del usuario, teléfonos para que puedan iniciar Cisco WebEx para llamar a teléfonos o correo electrónico | La aplicación NO almacenaría datos en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadWrite | delegado | Este permiso es almacenar información de marcado rápido en la extensión de usuario | La aplicación NO almacenaría datos en sus bases de datos  | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Esta extensión de mensaje leería el correo electrónico o los teléfonos de los miembros del chat para que el usuario pueda llamarlos con Cisco WebEx | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Esta aplicación no almacenaba datos de usuario

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Cisco ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
