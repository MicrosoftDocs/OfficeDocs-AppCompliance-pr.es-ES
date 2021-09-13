---
title: Información de la aplicación para Nulia Works de Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Nulia Works, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4d176b18a8089d9107f30b7581bcca69daf0871e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288080"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Nulia a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Nulia Works |
| Id. | WA200002051 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Nulia |
| Dirección URL del sitio web de partners | [https://nulia.com](https://nulia.com) |
| Dirección URL de Teams de información de la aplicación | [https://nulia.com/product](https://nulia.com/product) |
| Dirección URL de la directiva de privacidad | [https://nulia.com/privacy](https://nulia.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Nulia ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, se cuenta el número de eventos de calendario que tiene un usuario. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Contacts.Read | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, se cuenta el número de contactos que ha creado un usuario. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Files.Read.All | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, contamos el número de archivos que un usuario está sincronizando con su equipo. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Group.Read.All | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, recuperamos de los grupos cuántos Teams pertenece un usuario. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Mail.Read | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, contamos el número de carpetas de correo personalizadas que ha creado un usuario. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| MailboxSettings.Read | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, vemos si un usuario tiene un conjunto de respuestas fuera de la oficina. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Notes.Read | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, contamos el número de blocs de notas que un usuario ha compartido. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Reports.Read.All | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, recuperamos de los informes de usuario cuántos Teams mensajes enviados en un día. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Sites.Read.All | aplicación | Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Usamos estos datos para puntuar a los usuarios en la habilidad y el progreso de resultados. Por ejemplo, se cuenta el número de colecciones de sitios que el usuario ha creado. Ese valor afecta a su progreso de habilidad. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| User.Read | aplicación | Se muestra el nombre para mostrar, el departamento y la imagen de perfil del usuario. | Guardamos el nombre para mostrar y el departamento en nuestra base de datos para que no necesitemos ir al Graph cada vez. No almacenamos la imagen de perfil. | [Creamos un nuevo identificador de aplicación para cada cliente. Por ejemplo, nuestro inquilino de Nulia usa el identificador de aplicación: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Organization.Read.All | aplicación | Recopilamos el nombre del espacio empresarial y Yammer dirección URL base. Lo usamos para iniciar Yammer cuando el usuario hace clic en un botón Pruébalo en nuestra aplicación relacionado con &quot; &quot; Yammer actividades. | Almacenamos todos los datos que recopilamos en el almacenamiento de blobs. Por ejemplo, lo usamos para iniciar Yammer cuando el usuario hace clic en un botón Pruébalo en nuestra aplicación relacionado con &quot; &quot; Yammer actividades. | [Usamos los datos recopilados para puntuar el progreso del usuario en habilidades y resultados. Recopilamos recuentos de uso en varias cargas de trabajo de O365.](https://docs.microsoft.com/microsoft-365-app-certification/azure/We use the data collected to score user progress on skills and Outcomes. We collect usage counts across multiple O365 workloads.) |


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

>No controlamos datos en sistemas asociados

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Nulia ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
