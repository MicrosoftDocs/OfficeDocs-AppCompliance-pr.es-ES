---
title: Información de solicitud para Nulia Works por Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Nulia Works, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4471074b2e15b41894f709cb2a25dee1d0dc5187
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552901"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 11 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Nulia a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Nulia Works |
| ID | WA200002051 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Nulia |
| URL del sitio web de socios | [https://nulia.com](https://nulia.com) |
| URL de Teams página de información de la aplicación | [https://nulia.com/product](https://nulia.com/product) |
| URL de la Política de Privacidad | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL de los Términos de uso | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Nulia ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de eventos de calendario que tiene un usuario. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Contacts.Read | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de contactos que ha creado un usuario. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de archivos que un usuario está sincronizando con su equipo. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, recuperamos de los grupos a cuántos Teams pertenece un usuario. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de carpetas de correo personalizadas que ha creado un usuario. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| MailboxSettings.Read | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, vemos si un usuario tiene un conjunto de respuestas fuera de la oficina. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Notes.Read | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de Blocs de notas que un usuario ha compartido. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Reports.Read.All | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, recuperamos de los informes de usuario cuántos Teams mensajes enviaron en un día. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | aplicación | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. | Almacenamos todos los datos que recopilamos en blob storage. Utilizamos estos datos para puntuar a los usuarios sobre la habilidad y el progreso de resultados. Por ejemplo, contamos el número de colecciones de sitios que el usuario ha creado. Ese valor afecta su progreso de habilidad. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | aplicación | Mostramos el nombre para mostrar, el departamento y la imagen de perfil del usuario. | Guardamos el nombre para mostrar y el departamento en nuestra base de datos para que no tengamos que llegar a la Graph cada vez. No almacenamos la foto del perfil. | Creamos un nuevo ID de aplicación para cada cliente. Por ejemplo, nuestro inquilino nulia está utilizando el ID de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Organization.Read.All | aplicación | Recopilamos el nombre del inquilino y Yammer URL base. Usamos esto para iniciar Yammer cuando el usuario hace clic en un &quot; botón Probarlo &quot; en nuestra aplicación relacionada con actividades Yammer. | Almacenamos todos los datos que recopilamos en blob storage. Por ejemplo, usamos esto para iniciar Yammer cuando el usuario hace clic en un &quot; botón Probarlo &quot; en nuestra aplicación relacionada con Yammer actividades. | Utilizamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo O365. |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en la telemetría o registros de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>No controlamos los datos de los sistemas de socios

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Nulia ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
