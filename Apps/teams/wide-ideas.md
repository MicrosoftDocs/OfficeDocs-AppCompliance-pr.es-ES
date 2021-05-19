---
title: Información de la aplicación para ideas amplias por ideas amplias
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Ideas amplias, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f1fc5d97736ba587595ef6c742b14ce75c0b1863
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550900"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 3 de junio de 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Wide Ideas a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wide Ideas |
| ID | WA200000819 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Wide Ideas |
| URL del sitio web de socios | [https://getwideideas.com](https://getwideideas.com) |
| URL de la Política de Privacidad | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| URL de los Términos de uso | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Wide Ideas ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicación | Guardamos group ID y qué usuarios pertenecen a qué grupos | Permite a la aplicación leer datos en el directorio de nuestra organización customers, como usuarios y grupos.  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | aplicación | Guardamos el ID de canal asociado al grupo. | Permite al usuario crear equipos, canales y pestañas dentro de Microsoft Teams desde el Portal del Cliente. Esto también permite al usuario sincronizar los equipos existentes en Microsoft Teams en el Portal de clientes. | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | Delegado | Guardamos el correo electrónico del nombre &amp; | Permite a los usuarios iniciar sesión y dar acceso a Microsoft Graph en su nombre | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Mailjet Email que se utiliza para notificaciones por correo electrónico. |  | N/D |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Con el fin de crear usuarios en nuestro back-end y dar permisos para acceder al contenido vinculado al equipo. | Almacenamos: Nombre - Para mostrar el nombre del usuario, Dirección de correo electrónico - Para identificar al usuario |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Solo almacenamos el número IP en nuestros registros. 

La organización puede enviarnos una solicitud como proveedor si desea que se eliminen los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Almacenamiento de datos: todos los datos de los clientes se almacenan en Microsoft Azure servicios. Los usuarios deben autenticarse en 2 factores a través de Azure AD. El acceso basado en roles (RBAC) está en su lugar. Todo el acceso a Microsoft Azure se realiza estrictamente a través de conexiones cifradas. Todos los datos se cifran en reposo. Todos los servicios están protegidos por la mejor práctica de Azure Security Center. 

También tenemos una Política de Acceso en vigor de acuerdo con el principio de privilegio menor. 


#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

