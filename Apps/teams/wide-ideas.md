---
title: Información de la aplicación para ideas extensas por Wide Ideas
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Wide Ideas, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: be8d85cf26bcd153e4e72777bea65968eb858407
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096430"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Wide Ideas a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wide Ideas |
| Id. | WA200000819 |
| Capacidades | Bot, pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Wide Ideas |
| Dirección URL del sitio web de partners | [https://getwideideas.com](https://getwideideas.com) |
| Dirección URL de la directiva de privacidad | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Wide Ideas ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicación | Guardamos el identificador de grupo y los usuarios a los que pertenecen los grupos | Permite que la aplicación lea datos en el directorio de nuestra organización Clientes, como usuarios y grupos.  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | aplicación | Guardamos el identificador de canal que está asociado al grupo. | Permite al usuario crear equipos, canales y pestañas dentro de Microsoft Teams desde el Portal de clientes. Esto también permite al usuario sincronizar equipos existentes en Microsoft Teams en el Portal de clientes. | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | delegado | Guardamos el correo electrónico de &amp; nombre | Permite a los usuarios iniciar sesión y dar acceso a Microsoft Graph en su nombre | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Correo electrónico mailjet que se usa para las notificaciones por correo electrónico. |  | N/A |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para crear usuarios en nuestro back-end y conceder permisos para tener acceso al contenido vinculado al equipo. | Almacenamos: Nombre: para mostrar el nombre del usuario, dirección de correo electrónico: para identificar al usuario |  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Solo almacenamos el número IP en nuestros registros. 

La organización puede enviarnos una solicitud como proveedor si quiere que se eliminen los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Almacenamiento de datos: todos los datos del cliente se almacenan en Microsoft Azure servicios. Los usuarios deben ser autenticados con 2 factores a través de Azure AD. El acceso basado en roles (RBAC) está en su lugar. Todo el acceso a Microsoft Azure se realiza estrictamente a través de conexiones cifradas. Todos los datos se cifran en reposo. Todos los servicios están protegidos por la práctica recomendada del Centro de seguridad de Azure. 

También tenemos una directiva de acceso en su lugar de acuerdo con el principio de privilegios mínimos. 


#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

