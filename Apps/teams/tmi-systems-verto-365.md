---
title: Información de aplicaciones para Verto 365 por TMI Systems
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Verto 365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d2df916918905ba719980d2ee70dbefd4921998a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429668"
---
# <a name="verto-365"></a>Verto 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b27c082b-9d45-490a-b8bb-8dcda46c73f3" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003230" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por TMI Systems a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Verto 365 |
| Id. | WA200003230 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Sistemas TMI |
| Dirección URL del sitio web de partners | [https://www.vertocloud.co.uk](https://www.vertocloud.co.uk) |
| Dirección URL de Teams de información de la aplicación | [https://www.vertocloud.com](https://www.vertocloud.com) |
| Dirección URL de la directiva de privacidad | [https://vertocloud.co.uk/privacy-policy/](https://vertocloud.co.uk/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://vertocloud.co.uk/terms-and-conditions/](https://vertocloud.co.uk/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

TMI Systems ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Información general del usuario, nombre, apellido &amp; email. Se usa para crear una cuenta. | Firstname, Surname, Email, OID. Se usa para crear una cuenta en la base de datos, OID se usa para asociar un inicio de sesión con una cuenta de Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| email | delegado | Información general del usuario, nombre, apellido &amp; email. Se usa para crear una cuenta. | Firstname, Surname, Email, OID. Se usa para crear una cuenta en la base de datos, OID se usa para asociar un inicio de sesión con una cuenta de Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| offline_access | delegado | Se usa para obtener tokens de actualización y conservar el inicio de sesión | N/D | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| OpenID | delegado | Información general del usuario, nombre, apellido &amp; email. Se usa para crear una cuenta. | Firstname, Surname, Email, OID. Se usa para crear una cuenta en la base de datos, OID se usa para asociar un inicio de sesión con una cuenta de Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| perfil | delegado | Información general del usuario, nombre, apellido &amp; email. Se usa para crear una cuenta. | Firstname, Surname, Email, OID. Se usa para crear una cuenta en la base de datos, OID se usa para asociar un inicio de sesión con una cuenta de Verto. | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nombre de la organización, nombre, apellido, dirección de correo electrónico corporativo. Las directivas de retención son flexibles en función de las directivas internas de los clientes, pero siempre dentro del RGPD.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Permisos de usuario final a través de la lista de control de acceso. Los administradores pueden eliminar u ocultar datos, los usuarios finales no pueden modificar el registro de auditoría.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

TMI Systems ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
