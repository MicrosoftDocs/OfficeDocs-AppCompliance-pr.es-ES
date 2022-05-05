---
title: Introducción a Wrike para documentos Office
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Wrike para Office Documents, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c4407cdf68b92369e45c798ef76e051980e6c23a
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225624"
---
# <a name="wrike-for-office-documents-overview"></a>Introducción a Wrike para documentos Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización del desarrollador: 23 de marzo de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Wrike Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wrike para documentos Office |
| ID | WA104379841 |
| Office 365 clientes admitidos | Excel 2016 o posterior en Windows, Word 2013 o posterior en Windows, PowerPoint 2013 o posterior en Windows, Excel 2016 o versiones posteriores en Mac, Excel en la Web, Word 2016 o versiones posteriores en Mac, Word en la Web, PowerPoint 2016 o posterior en Mac, PowerPoint en la Web |
| Nombre de la empresa asociada | Wrike Inc. |
| Dirección URL del sitio web del asociado | [https://www.wrike.com/](https://www.wrike.com/) |
| Dirección URL de la directiva de privacidad | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| Dirección URL de los términos de uso | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Wrike Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph para recopilar o procesar información de identificación de la organización (OII). Enumere las API de Microsoft distintas de Microsoft Graph que use esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para la recopilación de OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | El complemento usa la API de Office.js para integrarse con la aplicación de Office. |  | No se almacenan datos de la organización en las bases de datos de Wrike. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>| **Todas las OII que no sean servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike tiene las integraciones con los siguientes proveedores que tienen acceso a algunos datos: Marketo es servicios de captura de clientes potenciales de correo electrónico: solo se les proporcionan nombres y correos electrónicos. El alcance es la interacción de ventas basada en la nube: solo se les proporcionan nombres y correos electrónicos. Sistema Salesforce CRM: tiene información de contacto y facturación (sin datos confidenciales) de los clientes. Zuora: clientes de facturación y facturación. Hay un DPA en su lugar para todos los proveedores. |  | Usamos JS Office API, pero no recopilamos, procesamos ni almacenamos información de la organización. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Wrike tiene una arquitectura multiinquilino que separa lógicamente a los clientes&#8217; datos a través del control de acceso en función de los metadatos del cliente. Estos metadatos están asociados con el inquilino específico y sus derechos de acceso según las reglas de acceso basadas en rol dentro de la cuenta de Wrike específica. Los datos están aislados y segregados lógicamente, y el acceso a los datos solo está disponible a través de la aplicación para garantizar la seguridad y la privacidad. La seguridad en el nivel de aplicación impide que los inquilinos accedan o modifiquen los datos de la aplicación propiedad de otro inquilino. La aplicación de Wrike tiene una amplia autenticación, control de acceso basado en rol, autorización y mecanismos de uso compartido y control de datos (consulte https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles y https://help.wrike.com/hc/en-us/articles/209602969) que permiten el acceso a datos solo para usuarios autorizados. Además, el cifrado en reposo se aplica a los archivos de usuario cargados en servidores wrike en el almacenamiento de archivos a través de la aplicación web y la API; los archivos se cifran automáticamente mediante el cifrado AES de 256 bits. Además, todos los servidores se cifran en reposo mediante el cifrado del sistema de archivos y, además, Wrike ofrece el complemento Wrike Lock para la clave de cifrado administrada por un cliente, vea https://www.wrike.com/add-on-wrike-lock/ y https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. Como capa adicional de seguridad de datos, Wrike ofrece funcionalidad de auditoría e informes que permite a los administradores realizar revisiones de seguridad completas, a la vez que pueden aumentar la visibilidad de lo que sucede en su cuenta de Wrike, se pueden encontrar más detalles en https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports. Por último, Wrike proporciona funcionalidad que permite el seguimiento pormenorizada de los roles de acceso para ayudar a los clientes a auditar completamente el uso compartido de datos existente, vea los detalles en https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
El acceso a los datos del cliente se puede tener en cuenta en dos casos:
- Acceso por parte del equipo de soporte técnico de Wrike: en caso de solucionar o comprobar el problema, es necesario que el soporte técnico acceda a su cuenta; que el acceso solo lo puede conceder usted. Esto se habilita mediante un token de seguridad generado por el sistema que proporciona fuera de banda a nuestro equipo de soporte técnico, lo que permite al soporte técnico profundizar en la resolución del problema durante un período de tiempo limitado. Este enfoque sistémico garantiza una confidencialidad adicional para los datos almacenados en Wrike.
- Acceso por parte del equipo operativo de Wrike: el equipo operativo de Wrike es responsable de mantener y admitir el entorno de producción, incluida la supervisión, la aplicación de revisiones y la actualización, la entrega de las nuevas compilaciones a producción, etc. En este caso, el acceso está estrictamente prohibido tanto en aspectos técnicos como de procedimientos, y existen controles de autorización seguros, como VPN, 2FA y certificado personal, además de que se supervisa en detalle mediante HIDS (Sistema de detección de intrusiones basado en host) y revisado por el equipo de seguridad operativa de Wrike. En el caso de Amazon KMS (funcionalidad de bloqueo de Wrike), los datos del cliente se almacenan cifrados en la base de datos wrike, por lo que los datos no están disponibles directa o indirectamente por el equipo operativo de Wrike, ya que los datos se pueden descifrar mediante el acceso a amazon KMS del cliente, que solo el cliente administra y controla.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

