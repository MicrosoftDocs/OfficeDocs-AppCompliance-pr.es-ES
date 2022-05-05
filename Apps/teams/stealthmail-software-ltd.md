---
title: Información de la aplicación para StealthMail de Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para StealthMail, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a0a31e0eceafbaa4188587411503514692c4b743
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225574"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 31 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Visualización en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Stealthmail Software Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | StealthMail |
| ID | WA200001748 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | Stealthmail Software Ltd |
| Dirección URL del sitio web del asociado | [https://stealthmail.com](https://stealthmail.com) |
| Dirección URL de Teams página de información de la aplicación | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| Dirección URL de la directiva de privacidad | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| Dirección URL de los términos de uso | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Esta información ha sido proporcionada por Stealthmail Software Ltd sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado o aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | Delegado | La aplicación envía el mensaje al canal con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| ChannelMessage.Send | Delegado | La aplicación envía el mensaje al canal con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| Chat.ReadWrite | Delegado | La aplicación envía el mensaje para chatear con la referencia en el correo electrónico seguro creado | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| GroupMember.Read.All | Delegado | La aplicación obtiene miembros del canal para crear un correo electrónico seguro para ellos. | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.Read.All | Delegado | La aplicación obtiene miembros de chat para crear un correo electrónico seguro para ellos | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.ReadBasic.All | Delegado | La aplicación obtiene miembros de chat para crear un correo electrónico seguro para ellos | Ninguno | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| correo electrónico | Delegado | Autenticación del usuario | nada almacenado en la base de datos | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>No se usan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellidos, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agregue. ¿Esta aplicación hace uso de esta funcionalidad?

>No se accede a ninguna EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en los registros o telemetría de las aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No tenemos control sobre los datos de los asociados en sus sistemas.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Stealthmail Software Ltd sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evita usar? | - URI de redireccionamiento comodín,<br/>- Flow implícita de OAuth2, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de versión preliminar? | Sí |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
