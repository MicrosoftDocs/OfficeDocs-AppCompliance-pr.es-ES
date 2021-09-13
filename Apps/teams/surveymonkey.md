---
title: Información de la aplicación para SurveyMonkey por SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SurveyMonkey, sus directivas de control de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f4898e476e0848ba728d07d0d851fc09f239aecf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287304"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SurveyMonkey a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SurveyMonkey |
| Id. | WA104381088 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | SurveyMonkey |
| Dirección URL del sitio web de partners | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| Dirección URL de Teams de información de la aplicación | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| Dirección URL de la directiva de privacidad | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

SurveyMonkey ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | No | Para proporcionar una lista de grupos o canales con los que compartir una encuesta | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Solo el identificador de usuario de MS se almacena en SurveyMonkey para asociar respuestas y encuestas con el usuario del equipo. |  | Para los equipos, usamos el SDK Microsoft Teams javascript en el módulo de tareas crear, realizar encuestas y resultados de encuestas. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Hacemos una llamada a v3/conversations/{id}/pagedmembers para comprobar que la aplicación se agrega a un equipo y obtener el número de miembros. Es para el seguimiento interno del uso, solo miramos el tamaño de la lista de chat, se omite otra información. | Sí, el tamaño del chat se almacena (un único entero) |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>EUII: se crea un registro de error o éxito siempre que una encuesta obtiene una respuesta y tratamos de enviar esa respuesta a Teams a través del conector, este registro incluye user_id, survey_id, integration_id (que en la base de datos se puede usar para buscar MS Team ID, MS User ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Nuestro centro de datos principal se encuentra en Las Vegas, NV y nuestro centro de datos secundario se encuentra en Santa Clara, CA. SurveyMonkey es propietario y opera todos sus servidores e infraestructura en estas ubicaciones. También tenemos la residencia de datos canadiense disponible para ciertos clientes de SurveyMonkey Enterprise ubicados en Canadá. Todos los datos se cifran en reposo con TDE con AES256 y los datos en tránsito se cifran mediante TLS 1.2.

SurveyMonkey usa la autenticación de usuario central para mantener la administración de identidades y acceso. Este sistema administra toda la autenticación y autorización para cualquier infraestructura, sistemas y servicios corporativos y de producción. Las directivas de acceso estrictas se mantienen y revisan trimestralmente. Las revisiones incluyen, entre otras: listas de acceso de usuarios, grupos de directivas y revisiones de acceso de terceros. Para obtener acceso a nuestro entorno de producción (es decir, para obtener una cuenta con privilegios), es necesario obtener la aprobación del administrador, completar una serie de cursos necesarios y obtener la aprobación de nuestro equipo de seguridad. En ese momento, se aprovisiona una cuenta VPN adicional, que diferencia &#8216;cuenta de&#8217; normal de una cuenta &#8216;con privilegios&#8217; cuenta.

Solo los dispositivos emitidos por la empresa pueden acceder a nuestra red de producción. Todos los valores predeterminados del proveedor inalámbrico se cambian antes de la instalación, incluidas, entre otras, las claves de cifrado inalámbrica predeterminadas, las contraseñas y las cadenas de comunidad SNMP. 2FA y VPN son necesarios para hacerlo de forma remota. Tenemos una red wifi independiente para el acceso de invitados en nuestras oficinas corporativas.

Todos los servicios, protocolos y puertos permitidos deben tener una justificación y aprobación empresarial documentada, incluido el uso de características de seguridad implementadas para esos protocolos considerados inseguros. Los enrutadores y firewalls están configurados para limitar la divulgación de IP a partes no autorizadas o no intencionadas y limitar el acceso entrante a Internet a las direcciones IP dentro del Firewall de DMZ y los conjuntos de reglas de enrutador se revisan al menos cada seis meses.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

