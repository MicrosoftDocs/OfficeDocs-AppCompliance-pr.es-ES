---
title: Información de la aplicación para TagTeam por Smarter Business Solution GmbH
ms.author: elmalova
author: elenamalova
ms.date: 04/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para TagTeam, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b4e3fcf89e816c115887fa5bd0df38cc95d4ae2f
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280952"
---
# <a name="tagteam"></a>TagTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: April 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6d7f01cb-cfa5-48d9-beed-363d381ae32b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002829" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Smarter Business Solution GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | TagTeam |
| Id. | WA200002829 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Smarter Business Solution GmbH |
| Dirección URL del sitio web de partners | [https://www.smarterbusiness.at](https://www.smarterbusiness.at) |
| Dirección URL de Teams de información de la aplicación | [https://www.smarterbusiness.at/en/tagteam-help](https://www.smarterbusiness.at/en/tagteam-help) |
| Dirección URL de la directiva de privacidad | [https://www.smarterbusiness.at/en/add-in-privacy-policy](https://www.smarterbusiness.at/en/add-in-privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.smarterbusiness.at/en/terms-of-use-for-tagteam](https://www.smarterbusiness.at/en/terms-of-use-for-tagteam) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Smarter Business Solution GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ChannelMessage.Read.All | delegado | No recopilamos estos datos: solo se usan para mostrar conversaciones etiquetadas. Nos encantaría cambiarla a la API de búsqueda, Graph la API actualmente no lo admite.  | Ninguno | 6d7f01cb-cfa5-48d9-beed-363d381ae32b |
>| User.Read | delegado | Mostrar User-Information (por ejemplo, Nombre) en nuestra pestaña | Ninguno | 6d7f01cb-cfa5-48d9-beed-363d381ae32b |
>| User.ReadBasic.All | delegado | Mostrar User-Avatars en nuestra pestaña | Ninguno | 6d7f01cb-cfa5-48d9-beed-363d381ae32b |
>| OpenID | delegado | Solo para SignIn: no se almacenan datos | Ninguno | 6d7f01cb-cfa5-48d9-beed-363d381ae32b |


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

>Solo almacenamos datos descritos en Azure Cosmos DB. No lo compartimos con otros sistemas de Parnter.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38164' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38164" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Smarter Business Solution GmbH acerca de cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
