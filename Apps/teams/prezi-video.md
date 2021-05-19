---
title: Información de la aplicación para prezi video por Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Prezi Video, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8b689869b4c8799d396a61ccbecd0d1b4a4e5c51
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552841"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 23 de junio de 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Prezi a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Prezi Video |
| ID | WA200001577 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Prezi |
| URL del sitio web de socios | [https://prezi.com](https://prezi.com) |
| URL de la Política de Privacidad | [https://prezi.com/privacy-policy/201910_NL/](https://prezi.com/privacy-policy/201910_NL/) |
| URL de los Términos de uso | [https://prezi.com/terms-of-use/201910_NL/](https://prezi.com/terms-of-use/201910_NL/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Prezi ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Para obtener más información, visite https://prezi.com/privacy-policy/ |  | Las siguientes API/SDK se usan para la integración junto con la 1. Botbuilder-SDK (python): con este SDK almacenamos el identificador de objeto Azure Active Directory (denominado por la API como aad_object_id). Necesitamos esta información para asignar un usuario Microsoft Teams a cualquier contenido relacionado con Prezi Video creado en prezi.com.  2. Botbuilder-js (javascript): no se recopilan datos específicos Microsoft Teams mediante este SDK. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| El bot no accede a la información de la lista mencionada. | El bot no accede a la información de la lista mencionada. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparecen EUII u OII en los registros de la aplicación.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Almacenamos la siguiente información en una base de datos RDS:

1. Azure Active Directory identificador de objeto (denominado aad_object_id) de la API se almacena para obtener un Microsoft Teams&#8217;vídeos s del usuario. El aad_object_id se recupera de forma segura mediante el sdk oficial de Microsoft&#8217;botbuilder en nuestros servidores.

2. Enlaces de vídeo creados en prezi.com. El contenido creado en prezi.com se almacena según la sección 14 de la siguiente URL: https://prezi.com/privacy-policy/ 

Los derechos de acceso a sistemas externos de alto riesgo (como AWS) se gestionan a través de una plataforma unificada de administración de identidades y accesos (OneLogin) de terceros.

La directiva de contraseñas y la autenticación multifactor se aplican al personal de la plataforma unificada de administración de identidades y accesos. Caso por caso, no se requiere autenticación multifactor de las direcciones IP de la oficina.

Los servicios y bases de datos alojados por AWS, de forma predeterminada, no son accesibles desde ningún lugar; las reglas de entrada explícitas deben agregarse manualmente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

