---
title: Información de la aplicación para yuccaHR de Yucca Technologies GmbH
ms.author: elmalova
author: elenamalova
ms.date: 09/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para yuccaHR, sus directivas de tratamiento de datos, su información Microsoft Cloud App Security catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f97ff60095ef47effd6e1e4c741a5cecaba0c594
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412680"
---
# <a name="yuccahr"></a>yuccaHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c3c1cd11-5b38-4de4-9081-44573d9383bf" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003242" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Yucca Technologies GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | yuccaHR |
| Id. | WA200003242 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Yucca Technologies GmbH |
| Dirección URL del sitio web de partners | [https://www.yuccahr.com](https://www.yuccahr.com) |
| Dirección URL de la directiva de privacidad | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Yucca Technologies GmbH sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | aplicación |  Creación de citas para conocer a dos empleados, en función de las franjas horarias libres.  | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Channel.ReadBasic.All | aplicación | Configurar una campaña. (redes de empleados) | ObjectId. Para solicitar el recurso de canal. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| ChannelMember.Read.All | aplicación | ObjectIds de los miembros del canal para iniciar una campaña de realización de coincidencias. | ObjectId. Para realizar un seguimiento de la coincidencia entre empleados. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Group.Read.All | aplicación |   Configuración de la campaña (redes de empleados). | ObjectId. Para solicitar el recurso de equipo. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| MailboxSettings.Read | aplicación | Determinación del idioma y la navegación preferidos para chatear con el empleado correspondiente. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| User.Read.All | aplicación | Name, ObjectId, UserPrinzipalName. Navegación al chat con el empleado correspondiente. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Usar el correo electrónico para programar und buscando intervalos de horas gratuitos. | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El cliente puede solicitar la eliminación de los datos almacenados en el servicio enviando una solicitud a support@yuccahr.com. Los datos se eliminarán en una semana.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Yucca Technologies GmbH sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

