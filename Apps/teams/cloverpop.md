---
title: Información de la aplicación para Cloverpop de Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Cloverpop, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3865c07aca73134fd9029ee0550559d9a4f93fd2
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521873"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cloverpop a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Cloverpop |
| Id. | WA200001803 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Cloverpop |
| Dirección URL del sitio web de partners | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| Dirección URL de la directiva de privacidad | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Cloverpop sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | almacenar datos de usuario como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario fácil de usar, por lo tanto, almacenamos información de presentación, por ejemplo, el usuario&#8217;avatar. | permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso&#8221;: correo electrónico, nombre, oid, tid, givenName, apellido, familyName, avatar de usuario(foto), organization displayName | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| OpenID | delegado | Almacenar datos de usuario como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario fácil de usar, por lo tanto, almacenamos información de presentación, por ejemplo, el usuario&#8217;avatar. | Para implementar &#8220;inicio de sesión con Teams&#8221; en nuestra aplicación web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| perfil | delegado | Almacenar datos de usuario como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario fácil de usar, por lo tanto, almacenamos información de presentación, por ejemplo, el usuario&#8217;avatar. | Para implementar &#8220;inicio de sesión con Teams&#8221; en nuestra aplicación web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Accedemos a los datos de nombre primero/último/para mostrar para mostrar con precisión las acciones realizadas por usuarios específicos relacionados con una decisión. Usamos la dirección de correo electrónico como identificador único para cada usuario de nuestra base de datos, ya que permitimos que cada usuario pertenezca a varias organizaciones. Solo accedemos a estos datos cuando interactúan con nuestra aplicación, por ejemplo, si responden a un sondeo. | Almacenamos los datos de nombre primero/último/para mostrar con el fin de mostrar con precisión qué acciones tomaron usuarios específicos relacionados con una decisión.  Almacenamos la dirección de correo electrónico porque la usamos como identificador único para cada usuario de nuestra base de datos, ya que permitimos que cada usuario pertenezca a varias organizaciones. Solo almacenamos estos datos cuando interactúan con nuestra aplicación, por ejemplo, si responden a un sondeo. Se supone que nuestros datos de decisión son un sistema de registro para las decisiones, por lo que es importante que almacenemos los datos para identificar cómo cada usuario participó en una decisión contribuyó a esa decisión. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí.
El identificador de equipo se muestra en nuestros registros cuando nuestra aplicación está interactuando en un equipo.
Tenemos acceso limitado a nuestros registros de producción a nuestros tres fundadores que están todos basados en los Estados Unidos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>La aplicación Cloverpop se ha creado con Ruby on Rails y se hospeda en la Heroku PaaS (plataforma como servicio) que usa AWS para su infraestructura en la nube. Heroku y AWS tienen informes SOC a los que se puede tener acceso. Nuestra aplicación usa PostgreSQL para el almacenamiento de datos cifrados en reposo y es un entorno multiinquilino.
 
Todo nuestro código tiene pruebas automatizadas escritas para él que cubren la seguridad del acceso a datos. Cada compilación se somete a un riguroso proceso de revisión de código para la seguridad y un proceso manual de prueba de control de calidad que también incluye comprobaciones de autenticación de usuario y acceso a datos a través de acciones de usuario disponibles. Hay una separación clara entre nuestro entorno de producción y todos los demás entornos, como el desarrollo y las pruebas.
 
Solo el personal selecto tiene acceso al entorno de producción y a la base de datos: los fundadores de la compañía y un pequeño puñado de empleados que han sido sometidos a comprobaciones de antecedentes y tienen una necesidad cuantificada (como el soporte al cliente).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

