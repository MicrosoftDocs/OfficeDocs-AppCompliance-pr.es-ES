---
title: Información de la aplicación para señal dinámica por señal dinámica
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Dynamic Signal, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a5839d8c5b8fbd1b27cdd014d82a3a41022738b
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096536"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Dynamic Signal a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Dynamic Signal |
| Id. | WA200000102 |
| Capacidades | Bot, pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Dynamic Signal |
| Dirección URL del sitio web de partners | [https://dynamicsignal.com](https://dynamicsignal.com) |
| Dirección URL de Teams de información de la aplicación | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| Dirección URL de la directiva de privacidad | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Dynamic Signal acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegado | Dynamic Signal sincroniza el usuario de Azure AD con su plataforma para permitir una activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Dynamic Signal para permitir que los usuarios usen esa aplicación mientras se realiza la sincronización. | Lea los permisos de un usuario específico para sincronizar los usuarios de la plataforma de señal dinámica con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegado | Dynamic Signal sincroniza el usuario de Azure AD con su plataforma para permitir una activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Dynamic Signal para permitir que los usuarios usen esa aplicación mientras se realiza la sincronización. | Lea los permisos de un usuario específico para sincronizar los usuarios de la plataforma de señal dinámica con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegado | Dynamic Signal sincroniza el usuario de Azure AD con su plataforma para permitir una activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Dynamic Signal para permitir que los usuarios usen esa aplicación mientras se realiza la sincronización. | Conservar el acceso a los grupos y equipos del inquilino. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| OpenID | delegado | Dynamic Signal sincroniza el usuario de Azure AD con su plataforma para permitir una activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Dynamic Signal para permitir que los usuarios usen esa aplicación mientras se realiza la sincronización. | Autenticar usuarios con la aplicación de señal dinámica. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid inicia sesión con openid directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams | openid Permitir la autenticación independiente. directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal's application uses the teams bot to apply groups and permissions created within Dynamic Signal to Teams so that a user that is active in Dynamic Signal will have access to the same groups and users that within Teams. |  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La aplicación y la plataforma de señal dinámica usan la información del usuario para facilitar la integración con Microsoft Teams. Esta información está disponible para los usuarios con los permisos adecuados dentro de la plataforma de señal dinámica. La información relevante es Nombre, Nombre para mostrar y Correo electrónico. Esta información se almacena en los registros de la plataforma de señal dinámica de acuerdo con la directiva de la organización respectiva con la licencia de señal dinámica.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de PII que se recopilan durante el registro y se almacenan en la plataforma de señal dinámica incluyen: nombre, apellido, correo electrónico/identificador y los campos personalizados configurados por la marca o los asociados de la agencia. Cuando los miembros usan Facebook o Twitter mediante el registro de oAuth, algunos de los datos de usuario expuestos se presentan en la plataforma de señal dinámica para rellenar previamente los datos. Estos datos incluyen nombre, ubicación y foto. Los usuarios tienen control sobre qué información y datos se presentan a los usuarios en las páginas bio de la comunidad. Los miembros pueden optar por cargar fotos personales o de marca, conectar cuentas o canales sociales y usar/puntos en el programa que se va a presentar en la página bio.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

