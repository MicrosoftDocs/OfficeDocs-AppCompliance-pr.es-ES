---
title: Información de la aplicación para la nube de confluencia de Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Confluence Cloud, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f73952983dd6b9788bcd61d71e55e5815de5f937
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411154"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Atlassian a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Confluence Cloud |
| Id. | WA200003113 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Atlassian |
| Dirección URL del sitio web de partners | [https://www.atlassian.com](https://www.atlassian.com) |
| Dirección URL de la directiva de privacidad | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Atlassian ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | delegado |  - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | delegado | - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| email | delegado | - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | delegado | - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| OpenID | delegado |  - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| perfil | delegado |  - Leemos la lista de miembros de chat en una reunión, por lo que conocemos la lista de invitados a la reunión.   - Leemos los nombres&#8217; y las direcciones de correo electrónico que se muestran condicionalmente en nuestra aplicación de reunión. Por ejemplo, muestre el nombre del usuario actual que toma notas de reunión.   - Nuestra aplicación lee el evento de calendario&#8217;el usuario donde se agregó nuestra aplicación a una reunión, por lo que tenemos información básica sobre la reunión como el título de la reunión. | Algunos ejemplos de contenido que recopilamos y almacenamos son: el resumen y la descripción agregados a un problema jira, las páginas que creas en Confluencia, los repositorios y las solicitudes de extracción en Bitbucket, los comentarios que escribes en relación con un incidente en Statuspage y los comentarios que nos proporciones. El contenido también incluye los archivos y vínculos que carga en los Servicios. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


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

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Atlassian ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

