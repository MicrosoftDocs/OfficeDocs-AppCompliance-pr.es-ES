---
title: Información de la aplicación para Tryane Analytics de Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Tryane Analytics, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 474c7824163b9b457ca3df2e705dc2cb1ccb8845
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410824"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Tryane a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Tryane Analytics |
| Id. | WA200001827 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Tryane |
| Dirección URL del sitio web de partners | [https://www.tryane.com](https://www.tryane.com) |
| Dirección URL de Teams de información de la aplicación | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| Dirección URL de la directiva de privacidad | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| DIRECCIÓN URL de términos de uso | [https://analytics.tryane.com/docs/en/terms_of_use.html](https://analytics.tryane.com/docs/en/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Tryane ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | aplicación | nombres de canal y propiedades adicionales | All Enumerar todos los canales con nombres, descripciones | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| ChannelMessage.Read.All | aplicación | número de mensajes publicados por el usuario | Enumerar todos los mensajes de canales&#8217; metadatos | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Directory.Read.All | aplicación | lista de usuarios que tienen acceso a Ms Teams | Identificar usuarios con una licencia de equipo en el inquilino | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Member.Read.Hidden | aplicación | lista de miembros | Obtener una lista de todos los equipos, miembros de&#8217;y pertenencias ocultas | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Reports.Read.All | aplicación | actividad diaria del usuario en Teams | Leer todas las actividades de los usuarios en equipos | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Team.ReadBasic.All | aplicación | Id. de equipo, nombre del equipo, id. de canal, nombre del canal | Enumerar todos los canales y propiedades de teams | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| User.Read | delegado | Id. de usuario, nombre, dirección de correo electrónico, fecha de creación. Almacenamos estos datos para proporcionar análisis de uso en Teams | Identificar al usuario actual durante la suscripción | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La regla organizativa descrita en nuestra directiva de seguridad de IT y los estándares de codificación nos impiden que EUII y OII aparezcan en los registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Dónde/Cómo: Azure/Azure Database for PostgreSQL servers Quién puede tener acceso a ella: nuestra aplicación y el control de autorización de administradores de bases de datos: 
 - Control de autorización individual: RBAC
 - Control de autorización del sistema: puntos de conexión privados en redes virtuales de Azure

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Tryane ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

