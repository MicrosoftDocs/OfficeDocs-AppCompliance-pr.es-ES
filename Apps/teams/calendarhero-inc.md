---
title: Información de la aplicación para CalendarHero de CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para CalendarHero, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 41a7dd8a2cb7d900ac26b228c4cc2522d76da59c
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527596"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 17, 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por CalendarHero Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | CalendarHero |
| Id. | WA200000150 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | CalendarHero Inc |
| Dirección URL del sitio web de partners | [https://zoom.ai](https://zoom.ai) |
| Dirección URL de Teams de información de la aplicación | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| Dirección URL de la directiva de privacidad | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

CalendarHero Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | ambos | Las reuniones se almacenan en caché en nuestra mongoDB en Azure, pero las descripciones están cifradas. | Acceso a los eventos del calendario del usuario. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite | ambos | Nombre de los contactos y dirección de correo electrónico. | Lea los contactos del usuario (para poder invitarlos a una reunión). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | ambos | Nombre y miembros del grupo. | (Opcional) leer grupos de usuarios corporativos (para programación con grupos). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | ambos | Correo electrónico/nombre de contacto, frecuencia/recency de interacciones. | (Opcional) se usa para leer los metadatos de correo electrónico para saber quiénes son los contactos más importantes del usuario (a través de Machine Learning). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.ReadWrite | ambos | Zona horaria del usuario. | Zona horaria del usuario. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | ambos | Correo electrónico de nombre &amp; de usuario (almacenado como contacto). | (Opcional) leer usuarios corporativos (para programar con compañeros de trabajo) | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | aplicación | No | Debemos leer y escribir a través de nuestro back-end en cualquier momento, sin que el usuario esté presente. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| importar nombres/correos electrónicos de compañeros de trabajo para que nuestro bot asistente de reuniones pueda programar reuniones con ellos | nombre &amp; de correo electrónico. ambos se almacenan en nuestra base de datos para la búsqueda rápida y para la búsqueda parcial de nombres (por ejemplo. reunirse con Joe P) |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La dirección de correo electrónico de un usuario o contacto se usa para registrar eventos en LogDNA, nuestro proveedor de registro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos se almacenan en el centro de datos en la nube de MS Azure ubicado en la ciudad de Quebec, Canadá. Varios campos se cifran con AES256. El acceso a la base de datos solo está disponible para los ingenieros y nuestros servidores back-end a través de credenciales de usuario/nivel de servicio.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

