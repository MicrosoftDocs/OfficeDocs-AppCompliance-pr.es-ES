---
title: Información de la aplicación para researcHR de KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para researcHR, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5def12e783d15c3cbcaf02ec128301dd9f75bd01
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753780"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por KBE&#26666;&#24335;&#20250;&#31038; a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | researcHR |
| ID | WA200002557 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | KBE&#26666;&#24335;&#20250;&#31038; |
| Dirección URL del sitio web de partners | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Dirección URL de Teams de información de la aplicación | [https://app.researchr.work](https://app.researchr.work) |
| Dirección URL de la directiva de privacidad | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| DIRECCIÓN URL de términos de uso | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

KbE ha proporcionado esta información&#26666;&#24335;&#20250;&#31038; información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD de aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | aplicación | Usamos este ámbito para permitir que nuestro bot cree un nuevo canal en el Teams cliente. Vea: https://docs.microsoft.com/graph/api/channel-post | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | aplicación | Usamos este ámbito para obtener los nombres y los nombres de los canales para mostrar estos datos en nuestro sitio web. Vea: https://docs.microsoft.com/graph/api/channel-list | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | aplicación | Usamos este ámbito para obtener los nombres y los nombres de los canales para mostrar estos datos en nuestro sitio web. Vea: https://docs.microsoft.com/graph/api/channel-list | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | aplicación | Usamos este ámbito para obtener los miembros del equipo para que los usuarios puedan ver a sus miembros del equipo en nuestro sitio web. Vea: https://docs.microsoft.com/graph/api/group-list-members | No almacenamos estos datos en la base de datos externa. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | aplicación | Usamos este ámbito para obtener los canales unidos del usuario para que los usuarios puedan ver sus equipos unidos en nuestro sitio web. Vea: https://docs.microsoft.com/graph/api/user-list-joinedteams | No almacenamos estos datos en nuestra base de datos. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | delegado | Usamos este ámbito para habilitar el inicio de sesión de OAuth y recopilar el identificador de AAD, el token de acceso y el token de actualización del usuario. Vea: https://docs.microsoft.com/graph/auth-v2-user | Almacenamos el identificador de AAD, token de acceso y token de actualización del usuario en nuestra base de datos para que el usuario pueda iniciar sesión en nuestro sitio web con OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | delegado | Usamos este ámbito para obtener el token de actualización para que podamos actualizar el token de acceso de los usuarios autenticados sin ninguna interacción del usuario. Vea: https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Almacenamos el token de actualización en nuestra base de datos para que podamos actualizar el token de acceso sin ninguna interacción del usuario. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


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

>Todos los datos de la base de datos están cifrados. Las copias de seguridad de los datos de la base de datos se realizarán y almacenarán durante un período determinado de tiempo de acuerdo con nuestra directiva de operación interna. En caso de que un usuario cancele este servicio, eliminaremos la información del usuario sin demora, excepto en la medida necesaria para cumplir con las obligaciones de almacenamiento estipuladas por la ley. Estos son los detalles. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

KbE ha proporcionado esta información&#26666;&#24335;&#20250;&#31038; sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
