---
title: Información de la aplicación para SIGNL4 de Derdack SIGNL4
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SIGNL4, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 425c0738b5628f959ba81e5682c22afe6774cfba
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281332"
---
# <a name="signl4"></a>SIGNL4

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/bd19c878-00b7-47cd-9b65-74a2def84427" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001239" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Derdack SIGNL4 a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SIGNL4 |
| Id. | WA200001239 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Derdack SIGNL4 |
| Dirección URL del sitio web de partners | [https://www.derdack.com](https://www.derdack.com) |
| Dirección URL de la directiva de privacidad | [https://www.signl4.com/privacy-policy/](https://www.signl4.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.signl4.com/terms_of_use/](https://www.signl4.com/terms_of_use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Derdack SIGNL4 ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| De forma recursiva, se requiere dirección de correo electrónico, dirección de correo electrónico para enviar notificaciones de facturación al cliente cuando esté usando la aplicación. Twilio, números de teléfono, contenido de alerta para enviar alertas a través de mensajes de texto SMS |  | Api de administración de Azure, alertas de Azure Monitor se recopilan, la recopilación se produce porque los sistemas envían notificaciones para esas alertas |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>La información de la dirección de correo electrónico se encuentra en los registros. También se pueden incluir datos de contenido de alerta adicionales, enviados por la organización, en los registros. Para evitarlo, la organización puede terminar la cuenta en la aplicación.
Los datos de los registros son necesarios para los problemas de soporte técnico y solución de problemas que la mamá del cliente tiene con la aplicación.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos se almacenan en el centro de datos de Azure en Europa. El acceso a él es posible para los administradores. 2FA mediante la autenticación de AAD. Las claves de acceso a las cuentas de almacenamiento también se usan para administrar el acceso.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

