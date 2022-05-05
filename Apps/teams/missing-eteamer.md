---
title: Información de la aplicación para eTeamer
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para eTeamer, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b267347dde74bf0f60f26d728073b36e4e105706
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225604"
---
# <a name="application-information-for-eteamer"></a>Información de la aplicación para eTeamer

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 25 de mayo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/5b4afbd0-a5ff-49c8-a0c7-c28eb5e87ef8" target="_blank">Visualización en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001621" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | eTeamer |
| ID | WA200001621 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; |
| Dirección URL del sitio web del asociado | [https://ecms2.edensoft.com.cn/#/Eden](https://ecms2.edensoft.com.cn/#/Eden) |
| Dirección URL de la directiva de privacidad | [https://ecms2.edensoft.com.cn/#/Privacy](https://ecms2.edensoft.com.cn/#/Privacy) |
| Dirección URL de los términos de uso | [https://ecms2.edensoft.com.cn/#/Service](https://ecms2.edensoft.com.cn/#/Service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Esta información la ha proporcionado &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado o aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.ReadWrite.All | Ambos | El identificador de aplicación de inquilino y la contraseña de la aplicación se recopilan para la autorización implícita de OAuth 2.0 para sincronizar la información de usuario. | El identificador de inquilino, el identificador de aplicación de inquilino, la contraseña de la aplicación y la información de usuario se almacenan en la base de datos, que se usa para obtener la información del archivo de canal de los usuarios de Teams y operar en los archivos. | [3407e97c-3eed-4eca-add5-2549ed881269](../azure/3407e97c-3eed-4eca-add5-2549ed881269.md) |


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

>La aplicación consta de 6 módulos, subdivididos en 55 Configuración de permisos, que admiten la autorización de un solo archivo, así como la autorización de un único usuario o rol.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40122' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40122" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información la ha proporcionado &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; sobre cómo controla esta aplicación la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evita usar? | ,<br/>- Flow implícita de OAuth2, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de versión preliminar? | Sí |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
