---
title: Información de la aplicación para Medxnote MT de Medxnote
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Medxnote MT, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 35f038dcfc9a7ee49153c585741465f444a4e1a4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411595"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Medxnote a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Medxnote MT |
| Id. | WA200001823 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Medxnote |
| Dirección URL del sitio web de partners | [https://medxnote.com/](https://medxnote.com/) |
| Dirección URL de la directiva de privacidad | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Medxnote ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read.All | aplicación | estamos almacenando en caché el nombre y el correo electrónico, que se usan en el lado del hospital para comprobar los privilegios de los usuarios | al enviar mensajes algunas veces se agrega nombre y dirección de correo electrónico, estamos almacenando en caché esos datos en el lado del servidor, también se usa para la comprobación de privilegios opcional en el lado del hospital | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |
>| OpenID | delegado | estamos almacenando en caché el identificador de sesión, el id. de usuario, el token de portador y el correo electrónico, usados para iniciar sesión en usuarios en el módulo Tarea | us it to sign in users in Task module, we are storing session id, userid, email, bearer tokens | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>dirección de correo electrónico, Nombre, identificador de inquilino, id. de canal pueden aparecer en los registros Todos los datos de registro se eliminan automáticamente después de 1 mes como máximo.
El acceso a estos está restringido a un puñado de administradores de la organización que tienen acceso obligatorio a 2FA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El acceso está restringido a un puñado de administradores de la organización que tienen acceso obligatorio a 2FA.
solo se puede obtener acceso a los sistemas críticos desde determinadas direcciones IP

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


