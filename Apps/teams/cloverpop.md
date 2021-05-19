---
title: Información de la aplicación Cloverpop por Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Cloverpop, sus políticas de gestión de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553231"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cloverpop a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Cloverpop |
| ID | WA200001803 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Cloverpop |
| URL del sitio web de socios | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL de la Política de Privacidad | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL de los Términos de uso | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Cloverpop ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegado | almacenar datos de usuario como. correo electrónico, oid, givenName, familyName, avatar de usuario, id. id. de organización id(tenantId), nombre para mostrar de la organización, También almacenamos en nuestros equipos/canales secundarios nombres, identificadores, miembros del equipo. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario amigable con el ser humano, por lo tanto, están almacenando información de visualización, por ejemplo, el usuario&#8217;s avatar. | permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso&#8221; - correo electrónico, nombre, oid, tid, givenName, apellidos, familyName, avatar de usuario (foto), displayName de la organización | 1040474b-572d-4575-a423-95dd262a8b8a |
>| OpenID | Delegado | Almacenar datos de usuario como. correo electrónico, oid, givenName, familyName, avatar de usuario, id. id. de organización id(tenantId), nombre para mostrar de la organización, También almacenamos en nuestros equipos/canales secundarios nombres, identificadores, miembros del equipo. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario amigable con el ser humano, por lo tanto, están almacenando información de visualización, por ejemplo, el usuario&#8217;s avatar. | Para implementar &#8220;inicie sesión con Teams&#8221; en nuestra aplicación web. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| perfil | Delegado | Almacenar datos de usuario como. correo electrónico, oid, givenName, familyName, avatar de usuario, id. id. de organización id(tenantId), nombre para mostrar de la organización, También almacenamos en nuestros equipos/canales secundarios nombres, identificadores, miembros del equipo. Cuando los usuarios crean e interactúan con las decisiones, asociamos estos datos con el usuario, el equipo y la organización que los creó. También necesitamos mostrar esta propiedad en una experiencia de usuario amigable con el ser humano, por lo tanto, están almacenando información de visualización, por ejemplo, el usuario&#8217;s avatar. | Para implementar &#8220;inicie sesión con Teams&#8221; en nuestra aplicación web. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Accedemos a los datos de nombre/apellido/nombre de visualización con el fin de mostrar con precisión qué acciones realizaron usuarios específicos relacionados con una decisión. Utilizamos la dirección de correo electrónico como identificador único para cada usuario de nuestra base de datos, ya que permitimos que cada usuario pertenezca a varias organizaciones. Solo accedemos a estos datos cuando interactúan con nuestra aplicación, por ejemplo, si responden a una encuesta. | Almacenamos los datos de nombre/apellido/nombre de visualización con el fin de mostrar con precisión qué acciones fueron tomadas por usuarios específicos relacionados con una decisión.  Almacenamos la dirección de correo electrónico porque la usamos como identificador único para cada usuario de nuestra base de datos, ya que permitimos que cada usuario pertenezca a varias organizaciones. Solo almacenamos estos datos cuando interactúan con nuestra aplicación, por ejemplo, si responden a una encuesta. Se supone que nuestros datos de decisión son un sistema de registro de decisiones, por lo que es importante que almacenemos los datos para identificar cómo cada usuario involucrado en una decisión contribuyó a esa decisión. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí.
El ID de equipo se muestra en nuestros registros cuando nuestra aplicación se interactúa con un equipo.
Tenemos acceso limitado a nuestros registros de producción a nuestros tres fundadores que tienen su sede en los EE. UU.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>La aplicación Cloverpop se crea con Ruby on Rails y se aloja en el Heroku PaaS (plataforma como servicio) que utiliza AWS para su infraestructura en la nube. Tanto Heroku como AWS tienen informes SOC a los que se puede acceder. Nuestra aplicación utiliza PostgreSQL para cifrar en el almacenamiento de datos de reposo y es un entorno multiinquilino.
 
Todo nuestro código tiene pruebas automatizadas escritas para él que cubren la seguridad del acceso a los datos. Cada compilación se somete a un riguroso proceso de revisión de código para la seguridad y un proceso manual de prueba de control de calidad que también incluye comprobaciones de autenticación de usuario y acceso a datos a través de las acciones de usuario disponibles. Existe una clara separación entre nuestro entorno de producción y todos los demás entornos, como el desarrollo y las pruebas.
 
Solo el personal selecto tiene acceso al entorno de producción y a la base de datos: fundadores de empresas y un pequeño puñado de empleados examinados que han sido sometidos a verificaciones de antecedentes y tienen una necesidad cuantificada (como el servicio de atención al cliente).

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

