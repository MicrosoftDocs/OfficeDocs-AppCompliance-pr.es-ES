---
title: Información de la aplicación para bot de calendario por contacto aprobado
ms.author: elmalova
author: elenamalova
ms.date: 05/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para el BOT de calendario, sus directivas de control de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9314d7712249dbbd8ad507e8c81eb47ddaa49ca9
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527656"
---
# <a name="calendar-bot"></a>Calendar BOT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381271" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por contacto aprobado a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Calendar BOT |
| Id. | WA104381271 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Contacto aprobado |
| Dirección URL del sitio web de partners | [https://www.approvedcontact.com](https://www.approvedcontact.com) |
| Dirección URL de la directiva de privacidad | [https://approvedcontact.com/Privacy%20Policy%20Bot.pdf](https://approvedcontact.com/Privacy%20Policy%20Bot.pdf) |
| DIRECCIÓN URL de términos de uso | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Contacto aprobado acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Para el BOT de calendario, almacenamos a los usuarios tiempo de disponibilidad para buscar horas libres para varias personas.  | Leemos y comparamos el tiempo de disponibilidad y la programación de reuniones. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| Contacts.Read | delegado | Sí, almacenamos información de contacto. | Importar y sincronizar contactos. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.Read | delegado | Sí | Información básica del perfil. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.ReadBasic.All | delegado | No | Se usa para ver los perfiles de los compañeros de trabajo, comparar horarios gratuitos y programar salas de conferencias. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| offline_access | delegado | Sí, tiempos de disponibilidad para usuarios sin conexión. | Llama Graph cuando el usuario no usa activamente nuestro sitio. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| OpenID | delegado | No | Office 365 SSO. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Usamos la lista para comparar los tiempos de disponibilidad para que todos los miembros del equipo programen reuniones en un momento de apertura. | Solo almacenamos la dirección de correo electrónico. | Solo almacenamos la dirección de correo electrónico para poder comparar los tiempos de disponibilidad. |


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

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Contacto aprobado acerca de cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
