---
title: Información de la aplicación monday.com por monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para monday.com, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 84654bbc7ebbcf5afd14522a3dbbcc728e9f317a
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251379"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por monday.com a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | monday.com |
| ID | WA200001798 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | monday.com |
| Dirección URL del sitio web de partners | [https://monday.com](https://monday.com) |
| Dirección URL de la directiva de privacidad | [https://monday.com/privacy](https://monday.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por monday.com sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com usa los siguientes subprocesadores para el rendimiento de su service:&#160;https://monday.com/terms/subprocessors |  | monday.com no usa API. Usamos los siguientes marcos de Microsoft para el rendimiento de nuestro servicio (como se detalla en nuestra respuesta anterior): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>monday.com almacena registros de aplicaciones que contienen contenido generado por los usuarios durante un período de tiempo limitado para permitir que nuestro personal de RD solucione errores y problemas notificados &amp; por el usuario. Los registros de seguridad que contienen direcciones IP se conservan durante un período de tiempo más prolongado, según nuestra directiva de retención de datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>monday.com servicio se hospeda en la infraestructura de AWS en el norte de Virginia en varias zonas de disponibilidad, con un sitio de recuperación ante desastres establecido en una región diferente. Ciertos datos de copia de seguridad se almacenan en GCP (EE. UU., varias regiones). El acceso al monday.com está controlado por los administradores de la organización de usuarios y se logra mediante las siguientes características:
- Tipos de usuario
- Permisos de nivel de cuenta
- Workspaces
- Tipos de tabla
- Permisos de nivel de junta
- Los permisos de nivel de columna monday.com admiten los siguientes métodos de autenticación:
- Credenciales
- SSO de Google (para Pro plan)
- Okta, OneLogin y SAML 2.0 personalizado (para el plan Enterprise) 2FA a través de SMS o a través de una aplicación de autenticación pueden habilitarse opcionalmente los administradores de cuentas a través del panel de administración de la plataforma.
Todos los datos en reposo se cifran con AES-256. Todos los datos en tránsito a través de redes abiertas se cifran con TLS 1.3 (TLS 1.2 como mínimo).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

