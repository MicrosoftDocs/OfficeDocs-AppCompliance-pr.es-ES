---
title: Información de la aplicación Caja fuerte spaces de eCare Vault Inc.
ms.author: elmalova
author: elenamalova
ms.date: 07/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Caja fuerte Spaces, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 16c1adeb63cf8004df70293c8e4a188dde811250
ms.sourcegitcommit: 90e6c1e10d55dc337c0884b63782cc14cf71b3c8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/31/2021
ms.locfileid: "58836211"
---
# <a name="safe-spaces"></a>Caja fuerte Espacios

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ec321cf7-ae3e-4ed4-a707-ff5c18e77313" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002691" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por eCare Vault Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Caja fuerte Espacios |
| Id. | WA200002691 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | eCare Vault Inc. |
| Dirección URL del sitio web de partners | [https://ecarevault.com](https://ecarevault.com) |
| Dirección URL de Teams de información de la aplicación | [https://ecarevault.com/ecare-vault-for-teams](https://ecarevault.com/ecare-vault-for-teams) |
| Dirección URL de la directiva de privacidad | [https://ecarevault.com/ecare-vault-privacy-policy](https://ecarevault.com/ecare-vault-privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://downloads.ecarevault.com/downloads/eCare+Vault+-+Te...](https://downloads.ecarevault.com/downloads/eCare+Vault+-+Terms+of+Service.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

ECare Vault Inc. proporciona esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| EduRoster.Read | delegado | El nombre y la fecha de nacimiento se usan para rellenar previamente los campos de entrada | Ninguno: todos los datos almacenados son enviados por el usuario (los datos solo se han prepoblado en campos y, a continuación, se envía el usuario) | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| Group.Read.All | delegado | Se usa para obtener información sobre canales disponibles para mostrar en la aplicación | Ninguno de este permiso | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| GroupMember.Read.All | delegado | Id. de AAD de miembros del grupo usados para generar una lista de equipos de eCare Vault | El id. de usuario de AAD se almacena para asociarse con una cuenta de usuario de eCare Vault para cada miembro | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read | delegado | dirección de correo electrónico e id. de AAD Se usa para registrar a los usuarios y asociarlos a cuentas de usuario &amp; de eCare Vault | dirección de correo electrónico e id. de AAD para cuentas de usuario y envío de notificación al usuario a través de Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read.All | delegado | Nombre y, id. de AAD y dirección de correo electrónico, solo para los usuarios que son miembros de un canal donde Caja fuerte spaces está instalado | Nombre, id. de AAD y dirección de correo electrónico almacenadas en cuentas de usuario de eCare Vault | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| email | delegado | Solo dirección de correo electrónico | Ninguno: el usuario decide enviar un formulario que  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| OpenID | delegado | dirección de correo electrónico e id. de AAD Se usa para registrar a los usuarios y asociarlos a cuentas de usuario &amp; de eCare Vault | dirección de correo electrónico e id. de AAD para cuentas de usuario y envío de notificación al usuario a través de Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| perfil | delegado | El nombre del usuario se usa para rellenar la pantalla de registro del usuario. | Ninguno directamente: el usuario elige enviar su nombre al sistema cuando se registra | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| MSAL (puntos de conexión de autenticación de Microsoft) | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| eCare Vault | Información de inquilino/empresa, nombre de dominio de inicio de sesión de usuario, información de inicio de sesión de Microsoft Teams identificadores de &amp; canal de grupo. | Caja fuerte Spaces es una aplicación complementaria a la plataforma de eCare Vault. La OII es necesaria para vincular usuarios de Microsoft Teams a usuarios de eCare Vault para la compañía. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos que van a los sistemas asociados (no incluyen ninguna OII, PII o PHI) se transfieren en un BAA para garantizar el cumplimiento de hipaa.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

ECare Vault Inc. ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
