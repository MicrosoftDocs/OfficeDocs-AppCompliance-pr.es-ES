---
title: Información de la aplicación SurveyMonkey por SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SurveyMonkey, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552731"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SurveyMonkey a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SurveyMonkey |
| ID | WA104381088 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | SurveyMonkey |
| URL del sitio web de socios | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL de Teams página de información de la aplicación | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL de la Política de Privacidad | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL de los Términos de uso | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

SurveyMonkey ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegado | No | Proporcionar una lista de grupos/canales para compartir una encuesta con |  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Solamente el id de usuario MS se almacena en SurveyMonkey para asociar las respuestas y las encuestas con el usuario del equipo. |  | Para los equipos, usamos el SDK de javascript Microsoft Teams en el módulo de tareas crear, realizar encuestas y resultados de encuestas modal. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Hacemos una llamada a v3/conversations/{id}/pagedmembers para comprobar que la aplicación se agrega a un equipo y obtener el recuento de miembros. Es para el seguimiento interno del uso, sólo miramos el tamaño de la lista de chat, otra información se ignora. | Sí, se almacena el tamaño del chat (un único entero) |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>EUII - Se crea un registro de éxito/error cada vez que una encuesta obtiene una respuesta, e intentamos enviar esa respuesta a Teams a través del conector, este registro incluye user_id, survey_id, integration_id (que en la base de datos se puede utilizar para buscar MS Team ID, MS User ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Nuestro centro de datos principal está ubicado en Las Vegas, NV y nuestro centro de datos secundario se encuentra en Santa Clara, CA. SurveyMonkey posee y opera todos sus servidores e infraestructura en estas ubicaciones. También tenemos residencia de datos canadiense disponible para ciertos clientes de SurveyMonkey Enterprise ubicados en Canadá. Todos los datos se cifran en reposo mediante TDE con AES256 y los datos en tránsito se cifran mediante TLS 1.2.

SurveyMonkey usa la autenticación de usuario central para mantener la administración de identidades y accesos. Este sistema administra toda la autenticación y autorización a todas y cada una de las empresas, así como la infraestructura de producción, los sistemas y los servicios. Las políticas de acceso estrictas se mantienen y revisan trimestralmente. Las opiniones incluyen, entre otras: listas de acceso de usuarios, grupos de políticas y revisiones de acceso a terceros. Para acceder a nuestro entorno de producción (es decir, para obtener una cuenta privilegiada), uno necesita obtener la aprobación del gerente, completar una serie de capacitaciones requeridas y obtener la aprobación de nuestro equipo de seguridad. En ese momento, se aprovisiona una cuenta VPN adicional, que diferencia la cuenta de&#8217; normal &#8216;de una cuenta&#8217; con privilegios &#8216;.

Solo los dispositivos emitidos por la empresa pueden acceder a nuestra red de producción. Todos los valores predeterminados del proveedor inalámbrico se cambian antes de la instalación, incluidas, entre otras, las claves de cifrado inalámbricas, contraseñas y cadenas de comunidad SNMP predeterminadas. 2FA y VPN están obligados a hacerlo de forma remota. Contamos con una red wifi separada para el acceso de los huéspedes en nuestras oficinas corporativas.

Todos los servicios, protocolos y puertos permitidos deben tener una justificación y aprobación empresarial documentada, incluido el uso de características de seguridad implementadas para aquellos protocolos considerados inseguros. Los enrutadores y firewalls están configurados para limitar la divulgación IP a partes no autorizadas o no deseadas y limitar el acceso entrante a Internet a las direcciones IP dentro del Firewall DMZ y los conjuntos de reglas del router se revisan al menos cada seis meses.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

