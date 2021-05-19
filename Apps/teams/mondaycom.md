---
title: Información de la aplicación monday.com por monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para monday.com, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552931"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 28 de septiembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por monday.com a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | monday.com |
| ID | WA200001798 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | monday.com |
| URL del sitio web de socios | [https://monday.com](https://monday.com) |
| URL de la Política de Privacidad | [https://monday.com/privacy](https://monday.com/privacy) |
| URL de los Términos de uso | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Monday.com ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com utiliza los siguientes subprocesadores para el rendimiento de su servicio:&#160;https://monday.com/terms/subprocessors |  | monday.com no utiliza API. Utilizamos los siguientes marcos de Microsoft para el rendimiento de nuestro servicio (como se detalla en nuestra respuesta anterior): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>monday.com almacena los registros de aplicaciones que contienen contenido generado por los usuarios durante un período de tiempo limitado con el fin de permitir que nuestro personal de R &amp; D solucione problemas de errores y problemas notificados por el usuario. Los registros de seguridad que contienen direcciones IP se conservan durante un período de tiempo más prolongado, según nuestra política de retención de datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>monday.com servicio se hospeda en la infraestructura de AWS en el norte de Virginia en varias zonas de disponibilidad, con un sitio de recuperación ante desastres establecido en una región diferente. Ciertos datos de copia de seguridad se almacenan en GCP (EE. UU., multiregión). El acceso al servicio monday.com está controlado por los administradores de la organización del usuario y se logra utilizando las siguientes características:
- Tipos de usuario
- Permisos a nivel de cuenta
- Workspaces
- Tipos de junta
- Permisos a nivel de placa
- Los permisos de nivel de columna monday.com admiten los siguientes métodos de autenticación:
- Credenciales
- Google SSO (para Pro plan)
- Okta, OneLogin y SAML 2.0 personalizado (para el plan de Enterprise) 2FA a través de SMS o a través de una aplicación de autenticación pueden ser habilitados opcionalmente por los administradores de cuentas a través del panel de administración de la plataforma.
Todos los datos en reposo se cifran mediante AES-256. Todos los datos en tránsito a través de redes abiertas se cifran mediante TLS 1.3 (TLS 1.2 como mínimo).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

