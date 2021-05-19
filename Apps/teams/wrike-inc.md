---
title: Información de solicitud para Wrike por Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Wrike, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4ef844f9bf25ffa41a6054aa6ffcbebdb94be223
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550770"
---
# <a name="wrike"></a>Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 23 de marzo de 2020</p>

* <a href="https://teams.microsoft.com/l/app/05274a45-7312-4c23-8f64-d57fe4a28d6d" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381390" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Wrike Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wrike |
| ID | WA104381390 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Wrike Inc. |
| URL del sitio web de socios | [https://www.wrike.com](https://www.wrike.com) |
| URL de Teams página de información de la aplicación | [https://help.wrike.com/hc/en-us/articles/115001825869-Micro...](https://help.wrike.com/hc/en-us/articles/115001825869-Microsoft-Teams) |
| URL de la Política de Privacidad | [https://www.wrike.com/security/privacy/](https://www.wrike.com/security/privacy/) |
| URL de los Términos de uso | [https://www.wrike.com/security/terms/](https://www.wrike.com/security/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Wrike Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | El complemento utiliza la API de Office.js para integrarse con la aplicación Office. |  | No se almacenan datos organizativos en las bases de datos de Wrike. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike tiene las integraciones con los siguientes proveedores que tienen acceso a algunos datos: Marketo es servicios de captura de clientes potenciales por correo electrónico - sólo se les proporcionan nombres y correos electrónicos. La divulgación es una interacción de ventas basada en la nube: solo se les proporcionan nombres y correos electrónicos. Sistema Crm de Salesforce: tiene información de contacto e información de facturación (sin datos confidenciales) de los clientes. Zuora - facturación y facturación de clientes. Hay un DPA en su lugar para todos los proveedores. |  | Utilizamos JS Office API, sin embargo, no recopilamos, procesamos ni almacenamos ninguna información de la organización. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Wrike tiene una arquitectura multiinquilino que separa lógicamente a los clientes&#8217; datos a través del control de acceso en función de los metadatos del cliente. Estos metadatos están asociados con el inquilino específico y sus derechos de acceso de acuerdo con las reglas de acceso basadas en roles dentro de la cuenta específica de Wrike. Los datos están aislados y segregados lógicamente, y el acceso a los datos solo está disponible a través de la aplicación para garantizar la seguridad y la privacidad. La seguridad en el nivel de aplicación impide que los inquilinos accedan o modifiquen los datos de la aplicación propiedad de otro inquilino. La aplicación de Wrike tiene una amplia autenticación, control de acceso basado en roles, autorización y mecanismos de control y uso compartido de datos (ver https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles y permitir el acceso a datos solo para usuarios https://help.wrike.com/hc/en-us/articles/209602969) autorizados. Además, el cifrado en reposo se aplica a los archivos de usuario cargados en servidores Wrike en el almacenamiento de archivos a través de aplicaciones web y API; los archivos se cifran automáticamente mediante cifrado AES de 256 bits. Además, todos los servidores se cifran en reposo utilizando el cifrado del sistema de archivos, y además Wrike ofrece wrike lock complemento para clave de cifrado administrado por un cliente, ver https://www.wrike.com/add-on-wrike-lock/ y https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Como capa adicional de seguridad de datos, Wrike ofrece funcionalidad de auditoría e informes que permite a los administradores realizar revisiones de seguridad completas mientras son capaces de aumentar la visibilidad de lo que está sucediendo en su cuenta de Wrike, se pueden encontrar más detalles en https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Por último, Wrike proporciona funcionalidad que permite el seguimiento granular de los roles de acceso para ayudar a los clientes a auditar completamente el uso compartido de datos existente, ver detalles en https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
El acceso a los datos de los clientes se puede considerar en dos casos:
- Acceso por el equipo de soporte de Wrike: en caso de solucionar problemas o verificar el problema requiere soporte técnico para acceder a su cuenta; ese acceso sólo puede ser concedido por usted. Esto está habilitado por un token de seguridad generado por el sistema que proporciona fuera de banda a nuestro equipo de soporte, lo que permite que el soporte técnico profundiza en la resolución de su problema durante un período limitado de tiempo. Este enfoque sistémico garantiza una confidencialidad adicional para sus datos almacenados en Wrike.
- Acceso por el equipo operativo de Wrike: El equipo operativo de Wrike es responsable de mantener y apoyar el entorno de producción, incluyendo monitoreo, parcheo y actualización, entrega de las nuevas construcciones a la producción, etc. El acceso en este caso está estrictamente prohibido tanto desde aspectos procedimentales como técnicos, y existen controles de autorización sólidos, incluidos, entre otros, VPN, 2FA y certificado personal, además se supervisa en detalle utilizando HIDS (Host-based Intrusion Detection System) y revisado por el equipo de seguridad operativa de Wrike. En el caso de Amazon KMS (funcionalidad Wrike Lock), los datos del cliente se almacenan cifrados en la base de datos Wrike, por lo que los datos no están disponibles directa o indirectamente por el equipo de Wrike Operational, ya que los datos se pueden descifrar utilizando el acceso a amazon KMS del cliente, que es administrado y controlado únicamente por el cliente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

