---
title: Información de la aplicación para researcHR por KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para researcHR, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229014"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador el 5 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Visualización en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por KBE&#26666;&#24335;&#20250;&#31038; a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | researcHR |
| ID | WA200002557 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | KBE&#26666;&#24335;&#20250;&#31038; |
| Dirección URL del sitio web del asociado | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Dirección URL de Teams página de información de la aplicación | [https://app.researchr.work](https://app.researchr.work) |
| Dirección URL de la directiva de privacidad | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| Dirección URL de los términos de uso | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

KBE ha proporcionado esta información&#26666;&#24335;&#20250;&#31038; sobre cómo recopila y almacena los datos de la organización y el control que tendrá la organización sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado o aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | aplicación | Usamos este ámbito para permitir que nuestro bot cree un nuevo canal en el cliente Teams. Vea: /graph/api/channel-post | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | aplicación | Usamos este ámbito para obtener los identificadores y nombres de canal para mostrar estos datos en nuestro sitio web. Consulte: /graph/api/channel-list | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | aplicación | Usamos este ámbito para obtener los identificadores y nombres de canal para mostrar estos datos en nuestro sitio web. Consulte: /graph/api/channel-list | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | aplicación | Usamos este ámbito para obtener los miembros del equipo para que los usuarios puedan ver a los miembros de su equipo en nuestro sitio web. Consulte: /graph/api/group-list-members | No almacenamos estos datos en la base de datos de salida. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | aplicación | Usamos este ámbito para obtener los canales unidos por el usuario para que los usuarios puedan ver sus equipos unidos en nuestro sitio web. Vea: /graph/api/user-list-joinedteams | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | Delegado | Usamos este ámbito para habilitar el inicio de sesión de OAuth y recopilar el identificador de AAD del usuario, el token de acceso y el token de actualización. Vea: /graph/auth-v2-user | Almacenamos el identificador de AAD del usuario, el token de acceso y el token de actualización en nuestra base de datos para que el usuario pueda iniciar sesión en nuestro sitio web con OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | Delegado | Usamos este ámbito para obtener el token de actualización de modo que podamos actualizar el token de acceso de los usuarios autenticados sin ninguna interacción del usuario. Consulte: /azure/active-directory/develop/v2-permissions-and-consent#offline_access | Almacenamos el token de actualización en nuestra base de datos para que podamos actualizar el token de acceso sin ninguna interacción del usuario. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


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

>Todos los datos de la base de datos están cifrados. Las copias de seguridad de los datos de la base de datos se tomarán y almacenarán durante un período de tiempo determinado de acuerdo con nuestra directiva operativa interna. En el caso de que un usuario cancele este servicio, eliminaremos la información de usuario del usuario sin demora, salvo en la medida necesaria para cumplir las obligaciones de almacenamiento estipuladas por la ley. Estos son los detalles. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información la ha proporcionado KBE&#26666;&#24335;&#20250;&#31038; sobre cómo controla esta aplicación la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
