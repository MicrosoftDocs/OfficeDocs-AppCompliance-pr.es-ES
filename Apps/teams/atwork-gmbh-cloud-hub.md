---
title: Información de aplicaciones para Cloud Hub de atwork GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Cloud Hub, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 386875fbf14ddd7409590a93462c333510b6a229
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404674"
---
# <a name="cloud-hub"></a>Cloud Hub

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 7, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c46172d-7923-422d-902e-f27aaad6994d" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003034" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por atwork GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Cloud Hub |
| Id. | WA200003034 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | atwork GmbH |
| Dirección URL del sitio web de partners | [https://www.atwork-it.com](https://www.atwork-it.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.atwork-it.com/solutions/cloudhub/](https://www.atwork-it.com/solutions/cloudhub/) |
| Dirección URL de la directiva de privacidad | [https://www.atwork-it.com/privacystatement](https://www.atwork-it.com/privacystatement) |
| DIRECCIÓN URL de términos de uso | [https://www.atwork-it.com/eula](https://www.atwork-it.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Atwork GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | aplicación | Leer los nombres y la descripción de todos los canales | Nothing | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| Mail.Send | aplicación | Compartir un mensaje a un equipo Microsoft Teams por correo electrónico. | Nothing | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| TeamSettings.Read.All | aplicación | Se usa para compartir en un Microsoft Teams equipo. | Nothing | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read | delegado | Iniciar sesión y leer el perfil del usuario | Nothing | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read.All | aplicación | Se usa para el selector de personas para compartir mensajes. | Nothing | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API de administración de Office 365 | Sí | ActivityFeed.Read y ServiceHealth.Read | Hacer que la fuente de actividad y el estado del servicio estén disponibles para usuarios que no son administradores | Datos de ActivityFeed y ServiceHealth | Para optimizar el rendimiento  |

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

>La aplicación lee datos y los almacena en un almacenamiento de datos de cliente, que se proporciona como SaaS. Además, los usuarios tienen la posibilidad de enviar mensajes como correos o enviarlos a grupos. 

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

Atwork GmbH ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Aplicación multiinquilino, depende de la configuración&#180;del cliente |
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
