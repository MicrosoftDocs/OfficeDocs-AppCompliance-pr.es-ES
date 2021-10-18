---
title: Información de la aplicación para POPP Cloud VoIP Connector de POPP Communications
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para POPP Cloud VoIP Connector, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c13790c3baa08d584343e9d504251e3920204b22
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60438729"
---
# <a name="popp-cloud-voip-connector"></a>Conector de voz sobre IP (VoIP) en la nube de POPP

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 20, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por POPP Communications a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Conector de voz sobre IP (VoIP) en la nube de POPP |
| Id. | WA200003306 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Comunicaciones de POPP |
| Dirección URL del sitio web de partners | [https://popp.com](https://popp.com) |
| Dirección URL de la directiva de privacidad | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

POPP Communications ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegado | Id. de usuario y nombres para mostrar de los miembros del canal actual. La aplicación lo usa para presentar al usuario una lista de miembros del canal a los que llamar. | Metaswitch no almacena estos datos. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | delegado |  ¿Qué datos se recopilan o usan? Agregue una justificación para recopilar o usar los datos. Id. de usuario y nombres para mostrar de los miembros del chat actual. La aplicación lo usa para presentar al usuario una lista de miembros de chat a los que llamar. | Metaswitch no almacena estos datos. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | delegado | Id. de usuario y nombres para mostrar de los miembros del equipo actual. La aplicación lo usa para presentar al usuario una lista de miembros del equipo a los que llamar. | Metaswitch no almacena estos datos. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | delegado |  ¿Qué datos se recopilan o usan? Agregue una justificación para recopilar o usar los datos. Los números de teléfono móvil y de empresa de los usuarios. Esto es necesario para que se puedan iniciar las llamadas telefónicas a estos números. |   Metaswitch no almacena estos datos | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| OpenID | delegado | Un token de autorización para el usuario, que autoriza a la aplicación a tener acceso a los demás puntos de conexión de la API Graph en su nombre. | Metaswitch no almacena estos datos. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plataforma de identidad de Microsoft | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Redes de metaswitch y comunicaciones POPP | La siguiente OII se transfiere al servidor de bot hospedado de MCT Azure AD: también se transfieren los contenidos del mensaje de id. de grupo de identificadores de equipo de id. de inquilino de MCT, que podría incluir OII El siguiente OII se puede transferir Teléfono la API JSON de CommPortal: números de usuarios de un grupo empresarial Los dominios de direcciones de correo electrónico Direcciones IP de usuario | Agregue la justificación de por qué necesita transferir OII El objetivo principal de&#8217;aplicación es facilitar las llamadas telefónicas. Si un usuario intenta realizar una llamada telefónica, esta información debe proporcionarse para iniciar sesión en su cuenta commPortal y correlacionar la llamada con el usuario correcto.  La OII que se transfiere al servidor de bots hospedados de MCT está integrada en la API de Bot Framework que se usa para integrar con Teams y no se puede evitar. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El objetivo&#8217;aplicación es facilitar las llamadas telefónicas. Si un usuario intenta realizar una llamada telefónica, se debe proporcionar EUII para todas las partes de la llamada para establecer la llamada entre los usuarios de telefonía correctos. | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Metaswitch and POPP does not store the data for longer than the immediate need to load the MCT web pages from CommPortal Web. Los datos no se conservan y se quitan inmediatamente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por POPP Communications sobre cómo esta aplicación controla la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | No |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Directivas de acceso condicional en la medida en que dicha compatibilidad se proporciona automáticamente mediante la biblioteca MSAL usada para la autenticación.  |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/> |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
