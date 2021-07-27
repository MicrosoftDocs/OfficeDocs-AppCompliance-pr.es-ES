---
title: Información de la aplicación para vídeo prezi de Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Prezi Video, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e7e9c70ee848fd284e3297a915ec9847d3ef1ee
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521271"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Prezi a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Prezi Video |
| Id. | WA200001577 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Prezi |
| Dirección URL del sitio web de partners | [https://prezi.com](https://prezi.com) |
| Dirección URL de la directiva de privacidad | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Prezi ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Para obtener más información, visite https://prezi.com/privacy-policy/ |  | Las siguientes API/SDK se usan para la integración junto con la 1. Botbuilder-SDK (python): con este SDK almacenamos el identificador de objeto Azure Active Directory (denominado por la API como aad_object_id). Necesitamos esta información para asignar un usuario Microsoft Teams a cualquier contenido relacionado con Prezi Video creado en prezi.com.  2. Botbuilder-js (javascript): no se recopilan Microsoft Teams datos específicos con este SDK. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El bot no tiene acceso a la información de lista mencionada. | El bot no tiene acceso a la información de lista mencionada. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen EUII ni OII en los registros de la aplicación.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Almacenamos la siguiente información en una base de datos de RDS:

1. Azure Active Directory identificador de objeto (denominado por la API como aad_object_id) se almacena para capturar un Microsoft Teams usuario&#8217;vídeos. El aad_object_id se recupera de forma segura mediante el sdk oficial de botbuilder de Microsoft&#8217;en nuestros servidores.

2. Vínculos de vídeo creados en prezi.com. El contenido creado en prezi.com se almacena según la sección 14 en la siguiente dirección URL: https://prezi.com/privacy-policy/ 

Los derechos de acceso a sistemas externos de alto riesgo (como AWS) se administran a través de una plataforma de administración de acceso y identidad unificada de terceros (OneLogin).

La directiva de contraseña y la autenticación multifactor se aplican para el personal de la plataforma de administración de acceso y identidad unificada. Caso por caso, la autenticación multifactor no es necesaria en las direcciones IP de office.

Los servicios y bases de datos hospedados por AWS, de forma predeterminada, no son accesibles desde cualquier lugar; Las reglas de entrada explícitas deben agregarse manualmente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

