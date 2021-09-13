---
title: Información de la aplicación para MeasureUp de Media Interactiva Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para MeasureUp, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 066526334e1936de0348f06f56239eab3370d0e0
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59285783"
---
# <a name="measureup"></a>MeasureUp

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bb1f94be-57aa-452c-9073-7fbb6b8b1797" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003111" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Media Interactiva Solutions a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | MeasureUp |
| Id. | WA200003111 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Media Interactiva Solutions |
| Dirección URL del sitio web de partners | [https://www.measureup.com](https://www.measureup.com) |
| Dirección URL de Teams de información de la aplicación | [https://docs.measureup.com](https://docs.measureup.com) |
| Dirección URL de la directiva de privacidad | [https://www.measureup.com/privacy-policy](https://www.measureup.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.measureup.com/legal-notice](https://www.measureup.com/legal-notice) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Media Interactiva Solutions ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Información de perfil para registrar y permitir el inicio de sesión. Cuando los usuarios tienen acceso a la aplicación, los datos del perfil de Microsoft son necesarios para crear el perfil de usuario en nuestra plataforma. | La aplicación almacena los datos personales del usuario, como el nombre, el apellido y el correo electrónico para autenticar al usuario en nuestra plataforma. Además, cuando los usuarios inician nuestros productos, algunos informes se almacenan con el progreso de esos lanzamientos. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |
>| OpenID | delegado | Información de perfil para registrar y permitir el inicio de sesión. Cuando los usuarios tienen acceso a la aplicación, los datos del perfil de Microsoft son necesarios para crear el perfil de usuario en nuestra plataforma. | La aplicación almacena los datos personales del usuario, como el nombre, el apellido y el correo electrónico para autenticar al usuario en nuestra plataforma. Además, cuando los usuarios inician nuestros productos, algunos informes se almacenan con el progreso de esos lanzamientos. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |
>| perfil | delegado | Información de perfil para registrar y permitir el inicio de sesión. Cuando los usuarios tienen acceso a la aplicación, los datos del perfil de Microsoft son necesarios para crear el perfil de usuario en nuestra plataforma. | La aplicación almacena los datos personales del usuario, como el nombre, el apellido y el correo electrónico para autenticar al usuario en nuestra plataforma. Además, cuando los usuarios inician nuestros productos, algunos informes se almacenan con el progreso de esos lanzamientos. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |


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

>Retención, auditoría, archivado, directiva de usuario final.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Media Interactiva Solutions ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/> |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
