---
title: Información de solicitud para SecretaryBot por MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SecretaryBot, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bff3e6ebffc94861dc4112375ac943124b4fe386
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551890"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por MySecretary a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SecretaryBot |
| ID | WA104381085 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | MySecretary |
| URL del sitio web de socios | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL de Teams página de información de la aplicación | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL de la Política de Privacidad | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL de los Términos de uso | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

MySecretary ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | Delegado |  | Obtenga información de tiempo libre de los usuarios y sus colegas. |  |
>| Calendars.ReadWrite | Delegado |  | Enviar solicitud de reunión en lugar de usuario. |  |
>| MailboxSettings.Read | Delegado | Almacenar el idioma para mostrar la langostino correcto. Guarde la zona horaria para llamar correctamente a ms Graph API de calendario | Obtenga la configuración de idioma y zona horaria del usuario. |  |
>| People.Read | Delegado |  | Trate de encontrar colegas que tengan relaciones sólidas con el usuario. |  |
>| User.Read | Delegado | Almacene el nombre de usuario, la ciudad, el país y langauge para obtener análisis de usuario. Almacene el correo electrónico para ponerse en contacto con el cliente. Nunca hemos utilizado la dirección de correo electrónico, pero podemos usar para el soporte. | Trate de encontrar el país del usuario y el idioma preferido. Se usa para la copia de seguridad de MailboxSettings.Read. |  |
>| email | Delegado | Ver arriba. | Para almacenar correo electrónico. |  |
>| OpenID | Delegado |  | Para la autenticación OpenID. |  |
>| perfil | Delegado | Guarde OID para identificar el id único del usuario en el sistema de identidad de MS. | Obtención de nombre de usuario y OID. Trate de utilizar OID para conectar Outlook Addin en el futuro. |  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Utilice esta infromation para programar la reunión del equipo | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Los datos OII o EUII aparecen en la telemetría o los registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Todavía no proporcionamos control administrativo a los usuarios finales, pero si los usuarios finales nos solicitan que eliminemos datos, podemos seguir su solicitud.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

