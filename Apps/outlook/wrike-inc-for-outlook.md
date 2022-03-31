---
title: Información de la aplicación para Wrike para Outlook por Wrike Inc.
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Wrike para Outlook, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a41e823a577a22418691489bd5009d8d310772ad
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/25/2022
ms.locfileid: "64461393"
---
# <a name="wrike-for-outlook"></a>Wrike para Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381120" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Wrike Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wrike para Outlook |
| Id. | WA104381120 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en iOS, Outlook en la Web, Outlook en Android |
| Nombre de la compañía asociada | Wrike Inc. |
| Dirección URL del sitio web de partners | [https://www.wrike.com/](https://www.wrike.com/) |
| Dirección URL de la directiva de privacidad | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Wrike Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | El complemento usa la API de Office.js para integrarse con la Office aplicación. |  | No se almacenan datos de la organización en las bases de datos de Wrike. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Se transfieren servicios Microsoft OII que no son de servicios Microsoft** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike tiene las integraciones con los siguientes proveedores que tienen acceso a algunos datos: Marketo es servicios de captura de clientes potenciales de correo electrónico: solo se les proporcionan nombres y correos electrónicos. El alcance es una interacción de ventas basada en la nube: solo se les proporcionan nombres y correos electrónicos. Sistema CRM de Salesforce: tiene información de contacto y facturación (sin datos confidenciales) de los clientes. Zuora: clientes de facturación y facturación. Hay un DPA en su lugar para todos los proveedores. |  | Usamos la API Office JS, pero no recopilamos, procesamos ni almacenamos información organizativa. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Wrike tiene una arquitectura multiinquilino que separa lógicamente los&#8217; datos a través del control de acceso basado en metadatos del cliente. Estos metadatos están asociados con el inquilino específico y sus derechos de acceso de acuerdo con las reglas de acceso basadas en roles dentro de la cuenta de Wrike específica. Los datos están aislados y segregados lógicamente y el acceso a los datos solo está disponible a través de la aplicación para garantizar la seguridad y privacidad. La seguridad en el nivel de aplicación impide que los inquilinos accedan o modifiquen los datos de la aplicación propiedad de otro inquilino. La aplicación de Wrike tiene una amplia autenticación, control de acceso basado en roles, autorización y mecanismos de control y uso compartido de datos ( https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) vea y que permiten el acceso a datos solo para usuarios autorizados. Además, el cifrado en reposo se aplica a los archivos de usuario cargados en servidores Wrike en el almacenamiento de archivos a través de la api y la aplicación web; los archivos se cifran automáticamente mediante cifrado AES de 256 bits. Además, todos los servidores se cifran en reposo mediante el cifrado del sistema de archivos y, además, Wrike ofrece el complemento Wrike Lock para la clave de cifrado administrada por un cliente, https://www.wrike.com/add-on-wrike-lock/ vea y https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. Como capa adicional de seguridad de datos, Wrike ofrece funciones de auditoría e informes que permiten a los administradores realizar revisiones de seguridad completa mientras pueden aumentar la visibilidad de lo que está sucediendo en su cuenta de Wrike, https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reportsse pueden encontrar más detalles en . Por último, Wrike proporciona funcionalidad que permite el seguimiento granular de roles de acceso para ayudar a los clientes a auditar completamente el uso compartido de datos existente ver detalles en https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
El acceso a los datos del cliente puede considerarse en dos casos:
- Acceso del equipo de soporte técnico de Wrike: en caso de solucionar el problema o comprobarlo, es necesario que el soporte técnico acceda a su cuenta; que el acceso solo puede concederse por usted. Esto se habilita mediante un token de seguridad generado por el sistema que proporcionas fuera de banda a nuestro equipo de soporte técnico, lo que permite al soporte técnico profundizar en la solución del problema durante un período de tiempo limitado. Este enfoque sistémico garantiza la confidencialidad adicional de los datos almacenados en Wrike.
- Acceso por parte del equipo operativo de Wrike: el equipo operativo de Wrike es responsable de mantener y admitir el entorno de producción, incluidos la supervisión, la revisión y la actualización, la entrega de las nuevas compilaciones a la producción, etc. En este caso, el acceso está estrictamente prohibido tanto en aspectos de procedimiento como técnicos, y hay controles de autorización fuertes, incluidos, entre otros, VPN, 2FA y certificado personal, además, se supervisa en detalles con HIDS (sistema de detección de intrusiones basado en host) y se revisa por el equipo de seguridad operativa de Wrike. En el caso de Amazon KMS (funcionalidad de bloqueo de Wrike), los datos del cliente se almacenan cifrados en la base de datos de Wrike, por lo que los datos no están disponibles directa o indirectamente por el equipo operativo de Wrike, ya que los datos se pueden descifrar mediante el acceso a Amazon KMS del cliente, administrado y controlado únicamente por el cliente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

