---
title: Información de la aplicación para agente virtual ahora por ServiceNow
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Now Virtual Agent, sus directivas de control de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ac2988c550894341d5933afbc59de6f63c51b68
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521003"
---
# <a name="now-virtual-agent"></a>Now Virtual Agent

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ServiceNow a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Now Virtual Agent |
| Id. | WA104381816 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ServiceNow |
| Dirección URL del sitio web de partners | [https://www.servicenow.com/](https://www.servicenow.com/) |
| Dirección URL de Teams de información de la aplicación | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| Dirección URL de la directiva de privacidad | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ServiceNow ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | El dominio se almacena en nuestro centro de datos para futuros fines de enrutamiento de mensajes. | Cuando el administrador de ServiceNow instala la integración con MS Teams, el administrador debe iniciar sesión en su cuenta Teams MS. Leemos el dominio desde la dirección de correo electrónico (no la dirección de correo electrónico completa). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>ServiceNow no está desoyéndolo. Los clientes pueden aprovechar el marco de agente virtual para crear capacidades adicionales que puedan tener acceso a la información de la organización o del usuario final. Los usuarios pueden escribir información de identificación personal durante la interacción con el bot y enviar la información a ServiceNow.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Consulte la sección [Cloud Security Alliance para](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa) obtener más información.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

