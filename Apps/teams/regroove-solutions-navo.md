---
title: Información de la aplicación para Navo de Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Navo, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6d6853c82a5da9425cbfd237494d51f769006398
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251149"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Regroove Solutions a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Navo |
| ID | WA200001047 |
| Capacidades | Pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Regroove Solutions |
| Dirección URL del sitio web de partners | [https://getnavo.com](https://getnavo.com) |
| Dirección URL de la directiva de privacidad | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Regroove Solutions ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicación | Almacenamos el recuento de usuarios y lo consultamos una vez por ciclo de facturación. También usamos el identificador de arrendamiento como identificador de la organización. | Nos permite contar cuántos usuarios hay en el arrendamiento, que usamos para fines de facturación. También nos permite consultar en qué grupos se encuentra un usuario, de modo que podamos usar el recorte de seguridad para proteger determinados datos. También consultamos el identificador de arrendamiento de la organización. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | delegado | Sin datos almacenados | Iniciar sesión y leer el perfil del usuario | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Almacenamos el identificador de arrendamiento y el número de usuarios en Stripe. |  | User.Read | Delegado | Iniciar sesión y leer el perfil de usuario: no hay datos almacenados |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí, en Application Insights almacenamos el id. autenticado del usuario y el id. de cuenta de usuario (id. de arrendamiento).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos que almacenamos nosotros mismos (no a través de un servicio como Stripe o Application Insights) se almacenan en una base de datos Cosmos Azure. Todos los administradores usan 2FA y el acceso está restringido a un subconjunto de nuestros empleados.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

