---
title: Información de la aplicación CalendarHero by CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para CalendarHero, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553336"
---
# <a name="calendarhero"></a>CalendarioHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 17 de marzo de 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por CalendarHero Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | CalendarioHero |
| ID | WA200000150 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | CalendarHero Inc |
| URL del sitio web de socios | [https://calendarhero.com](https://calendarhero.com) |
| URL de Teams página de información de la aplicación | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL de la Política de Privacidad | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL de los Términos de uso | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

CalendarHero Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | ambos | Las reuniones se almacenan en caché en nuestro mongoDB en Azure, pero las descripciones se cifran. | Acceso a los eventos de calendario del usuario. |  |
>| Contacts.ReadWrite | ambos | Nombre de contacto y dirección de correo electrónico. | Lea los contactos del usuario (para que podamos invitarlos a una reunión). |  |
>| Group.Read.All | ambos | Nombre del grupo y miembros. | (Opcional) leer grupos de usuarios corporativos (para programar con grupos). |  |
>| Mail.Read | ambos | Póngase en contacto con el correo electrónico/nombre, la frecuencia/recency de las interacciones. | (Opcional) se utiliza para leer los metadatos del correo electrónico a bajo quiénes son los contactos más importantes del usuario (a través de Machine Learning). |  |
>| MailboxSettings.ReadWrite | ambos | Zona horaria del usuario. | Zona horaria del usuario. |  |
>| User.Read.All | ambos | Correo electrónico de nombre del usuario &amp; (almacenado como contacto). | (Opcional) leer usuarios corporativos (para programar con compañeros de trabajo) |  |
>| offline_access | aplicación | No | Tenemos que leer y escribir a través de nuestro back-end en cualquier momento, sin que el usuario esté presente. |  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| importar nombres/correos electrónicos de compañeros de trabajo para que nuestro bot asistente de reunión pueda programar reuniones con ellos | nombre &amp; correo electrónico. ambos se almacenan en nuestra base de datos para una búsqueda rápida y para la búsqueda parcial de nombres (por ejemplo. reunirse con Joe P) |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>La dirección de correo electrónico de un usuario y/o contacto se utiliza para registrar eventos en LogDNA, nuestro proveedor de registro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Todos los datos se almacenan en el centro de datos en la nube de MS Azure ubicado en la ciudad de Quebec, Canadá. Varios campos se cifran con AES256. El acceso a la base de datos solo está disponible para los ingenieros y nuestros servidores back-end a través de credenciales de nivel de usuario/servicio.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

