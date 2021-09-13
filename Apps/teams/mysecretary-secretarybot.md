---
title: Información de la aplicación para SecretaryBot por MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SecretaryBot, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8d7e2fce37cf43fe52cb050e85aa9e4fd5e00802
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287376"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por MySecretary a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SecretaryBot |
| Id. | WA104381085 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | MySecretary |
| Dirección URL del sitio web de partners | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| Dirección URL de Teams de información de la aplicación | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| Dirección URL de la directiva de privacidad | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

MySecretary ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | delegado |  | Recupera la información de tiempo libre del usuario y sus compañeros. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | delegado |  | Enviar solicitud de reunión en lugar de usuario. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | delegado | Idioma de la tienda para mostrar el langage correcto. Guardar zona horaria para llamar a MS Graph API de calendario correctamente | Capturar la configuración de idioma y zona horaria del usuario. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | delegado |  | Intente encontrar compañeros que tengan relaciones sólidas con el usuario. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegado | Almacenar nombre de usuario, ciudad, país y langauge para análisis de usuarios. Almacenar el correo electrónico para ponerse en contacto con el cliente. Nunca hemos usado la dirección de correo electrónico, pero se puede usar para soporte técnico. | Intenta buscar el país del usuario y el idioma preferido. Se usa para la copia de seguridad de MailboxSettings.Read. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | delegado | Vea arriba. | Para almacenar correo electrónico. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| OpenID | delegado |  | Para la autenticación OpenID. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| perfil | delegado | Guarde OID para identificar el identificador único del usuario en el sistema de identidad de MS. | Obtener el nombre de usuario y OID. Intente usar OID para conectar Outlook Addin en el futuro. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Use esta información para programar reuniones de equipo | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Los datos de OII o EUII aparecen en los registros o telemetría.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todavía no proporcionamos control administrativo a los usuarios finales, pero si los usuarios finales nos solicitan que eliminemos datos, podemos seguir su solicitud.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

