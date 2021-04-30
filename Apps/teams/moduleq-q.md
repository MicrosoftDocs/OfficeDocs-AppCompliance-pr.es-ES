---
title: Información de la aplicación para preguntas por moduleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para preguntas, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf5a29e08636c40635dd7e40c768f56cac35c096
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096351"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ModuleQ a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Q |
| Id. | WA104381433 |
| Capacidades | Bot, pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ModuleQ |
| Dirección URL del sitio web de partners | [https://moduleq.com](https://moduleq.com) |
| Dirección URL de la directiva de privacidad | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ModuleQ ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | aplicación | almacena datos de reunión, excepto para el cuerpo del mensaje y los datos adjuntos | Permite que la aplicación lea los eventos del calendario de un usuario para comprender de forma inteligente las prioridades empresariales del usuario. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | delegado | Ninguno | Permite que la aplicación interactúe en un equipo para compartir contenido. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | aplicación | almacena datos de correo electrónico, excepto para el cuerpo del mensaje y los datos adjuntos | Permite que la aplicación lea el correo de un usuario para comprender de forma inteligente las prioridades empresariales del usuario | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | delegado | tokens de autenticación y correo electrónico del usuario | Permite al usuario iniciar sesión y vincular su Office 365 con su cuenta ModuleQ | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | delegado | Ninguno | Permitir que la aplicación obtenga la lista de Teams de la que el usuario forma parte. Solo se usa para compartir  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Registramos un GUID de usuario interno y nombres de organización y dominios. No hay controles de archivo o eliminación en este momento.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos se almacenan en la nube Microsoft Azure varios microservicios según su función. Todos los datos identificables por el usuario se cifran en el lado cliente con el cifrado AES-256 antes de transmitirse para su almacenamiento. Los ingenieros pueden ver los datos con fines de depuración con la aprobación de nuestra administración superior. El acceso a los datos se controla mediante VPN interna.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

