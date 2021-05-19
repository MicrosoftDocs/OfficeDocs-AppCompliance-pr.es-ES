---
title: Información de solicitud para Tikit por Cireson
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Tikit, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: de10b787d3e4100972e46efe76050ed0c7df31fd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553251"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 11 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cireson a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Tikit |
| ID | WA200002602 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Cireson |
| URL del sitio web de socios | [https://tikit.ai](https://tikit.ai) |
| URL de Teams página de información de la aplicación | [https://tikit.ai](https://tikit.ai) |
| URL de la Política de Privacidad | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| URL de los Términos de uso | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Cireson ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | aplicación | Información del gráfico de usuario utilizada para el inicio de sesión único, a través de la comunicación de bots de equipos  | Almacenamos roles de usuario, apellidos, nombre de pila, correo electrónico, ID de AAD Teams ID de usuario. Esta información se utiliza para la autenticación de aplicaciones, la seguridad, RBAC, la integración de equipos, las notificaciones de equipos y la asignación de relaciones de usuario   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | Delegado | Nombres de grupo y roles para RBAC | Nombre del &amp; rol nombre de grupo, debe proporcionar un control de acceso asignado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | Delegado | Nombres de grupo y roles para RBAC | Nombre del &amp; rol nombre de grupo, debe proporcionar un control de acceso asignado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | ambos | Nombres de grupo y roles para RBAC | Nombres de grupo y roles para RBAC | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | Delegado | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | aplicación | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | Delegado | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | Roles de usuario, apellidos, nombre, correo electrónico, ID de AAD, ID de usuario Teams, utilizado para la autenticación  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| email | Delegado | Correo electrónico de usuario utilizado para el inicio de sesión y la identificación asociada de entidades relacionadas. &quot;Usuario asignado&quot; | Correo electrónico de usuario utilizado para el inicio de sesión y la identificación asociada de entidades relacionadas. &quot;Usuario asignado&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| OpenID | Delegado | utilizado para la autenticación a través de MSAL por requisitos  | utilizado para la autenticación a través de MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| perfil | Delegado | utilizado para la autenticación a través de MSAL por requisitos  | utilizado para la autenticación a través de MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Fabricante de QnA | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nombre y correo electrónico para las relaciones de entidad de usuario &quot; Ticket Requestor&quot;  | Nombre y correo electrónico  | para las relaciones de entidad de usuario &quot; Ticket Requestor&quot;  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Almacenamos nombre de empresa, identificador de inquilino, correo electrónico, identificador de cliente de bot en información de la aplicación, con una directiva de retención de 30 dat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>No tenemos datos en un sistema asociado.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Cireson ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
