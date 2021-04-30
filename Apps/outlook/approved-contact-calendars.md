---
title: Información de la aplicación para calendarios de contactos aprobados por contacto aprobado
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para los calendarios de contactos aprobados, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 37da37f6e5cad32ce97c4da537bc9ff7bd9d81a4
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096717"
---
# <a name="approved-contact-calendars"></a>Calendarios de contactos aprobados

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por contacto aprobado a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Calendarios de contactos aprobados |
| Id. | WA104380294 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la compañía asociada | Contacto aprobado |
| Dirección URL del sitio web de partners | [https://approvedcontact.com/](https://approvedcontact.com/) |
| Dirección URL de la directiva de privacidad | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| DIRECCIÓN URL de términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Contacto aprobado acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado | Para el BOT de calendario, almacenamos a los usuarios tiempo de disponibilidad para buscar horas libres para varias personas.  | Leemos y comparamos el tiempo de disponibilidad y la programación de reuniones. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | delegado | Sí, almacenamos información de contacto. | Importar y sincronizar contactos. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | delegado | Sí | Información básica del perfil. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | delegado | No | Se usa para ver los perfiles de los compañeros de trabajo, comparar horarios gratuitos y programar salas de conferencias. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | delegado | Sí, tiempos de disponibilidad para usuarios sin conexión. | Llama Graph cuando el usuario no usa activamente nuestro sitio. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| OpenID | delegado | No | Office 365 SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Elemento ReadWrite | Este complemento puede tener acceso y modificar la información personal del mensaje activo, como el cuerpo, el asunto, el remitente, los destinatarios y la información de datos adjuntos. Puede enviar estos datos a un servicio de terceros. Otros elementos del buzón de correo&#8217;no se pueden leer ni modificar. |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí, registramos direcciones de correo electrónico para conectar compras de licencias a Commercial Appsource. Proporcionamos la capacidad de eliminar esta información de nuestros registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Solo los desarrolladores tienen acceso a nuestros registros. Aplicamos 2FA para el acceso a todas las plataformas de desarrollo.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

