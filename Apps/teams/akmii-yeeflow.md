---
title: Información de la aplicación para Yeeflow de Akmii
ms.author: elmalova
author: elenamalova
ms.date: 11/25/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Yeeflow, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 21fd7c76495a2bc559cb93bd89e3a8977b28ff09
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096603"
---
# <a name="yeeflow"></a>Yeeflow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 25, 2020</p>

* <a href="https://teams.microsoft.com/l/app/7c10d6ae-b4ad-4221-b086-8518f5d4a1c4" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000089" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Akmii a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Yeeflow |
| Id. | WA200000089 |
| Capacidades | Bot, pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Akmii |
| Dirección URL del sitio web de partners | [https://www.yeeflow.com](https://www.yeeflow.com) |
| Dirección URL de Teams de información de la aplicación | [www.yeeflow.com](www.yeeflow.com) |
| Dirección URL de la directiva de privacidad | [https://www.yeeflow.com/privacy](https://www.yeeflow.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.yeeflow.com/terms](https://www.yeeflow.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Akmii ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Enviar un mensaje descriptivo e identificar al usuario. | nombre y correo electrónico del usuario | para enviar notificaciones de usuario y mostrar el nombre de usuario |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de la aplicación se almacenan en la base de datos. Solo los administradores de operaciones autorizados pueden tener acceso a los datos de office (restringidos por intervalos IP)

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35741' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35741" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Akmii ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,
<br />

<br />
 | | ¿Expone la aplicación alguna API web? | Sí | | ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí | | ¿La aplicación usa las API de vista previa? | Sin | | ¿La aplicación usa API en desuso? | Sin |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
