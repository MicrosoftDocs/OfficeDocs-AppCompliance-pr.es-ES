---
title: Información de la aplicación para Wunder365 por JiJi Technologies Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Wunder365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 81f30170d7aed41a9038a31512b62f4eea24b42d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410173"
---
# <a name="wunder365"></a>Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 15, 2020</p>

* <a href="https://teams.microsoft.com/l/app/7e8f9ad5-07d9-4259-8713-d316f451cbf3" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000742" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por JiJi Technologies Pvt Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Wunder365 |
| Id. | WA200000742 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | JiJi Technologies Pvt Ltd |
| Dirección URL del sitio web de partners | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.wunder365.com/wunder365-for-office](https://www.wunder365.com/wunder365-for-office) |
| Dirección URL de la directiva de privacidad | [https://www.wunder365.com/teams-app-privacy-policy](https://www.wunder365.com/teams-app-privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

JiJi Technologies Pvt Ltd ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | No hay datos almacenados. | Para obtener/actualizar tareas de Planner, publique actualizaciones de tareas en el canal de grupo | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| Mail.Send | delegado | No hay datos almacenados. | Permitir que la aplicación envíe notificaciones por correo electrónico a los usuarios | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| offline_access | delegado | No hay datos almacenados. | Para mantener la sesión iniciada por el usuario. | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| OpenID | delegado | No hay datos almacenados. | Permite a los usuarios iniciar sesión con una cuenta organizativa | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| perfil | delegado | UPN, id. de usuario, id. de correo electrónico, id. de inquilino para la verificación de licencias, licencia gratuita. | Permite a los usuarios iniciar sesión con una cuenta organizativa | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API de REST de SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Estamos iniciando sesión en Azure Application Ideas. Estamos registrando el identificador de inquilino y el identificador de correo electrónico del usuario para identificar problemas y ayudar a los clientes a resolver problemas.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todas las aplicaciones web y Storage se encuentran en una suscripción que no está conectada a nuestra empresa AAD solo con administradores que tienen acceso a los recursos. Se requiere 2FA para estos administradores. 


#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

JiJi Technologies Pvt Ltd ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Requerir autenticación multifactor para usuarios con roles administrativos, Requerir autenticación multifactor para tareas de administración de Azure, Bloquear inicios de sesión para usuarios que intenten usar protocolos de autenticación heredados, Requerir ubicaciones de confianza para un registro de autenticación multifactor, Bloquear o conceder acceso Azure AD desde ubicaciones específicas, Bloquear el comportamiento de inicio de sesión arriesgado |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

