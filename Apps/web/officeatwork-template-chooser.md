---
title: Información de la aplicación para el elegidor de plantillas por officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Template Chooser, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 48f491b41cec663c07f11645f02cb495f248d765
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288487"
---
# <a name="template-chooser"></a>Template Chooser

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 22, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.template-chooser" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por officeatwork a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Template Chooser |
| Id. | officeatwork-ag.template-chooser |
| Nombre de la compañía asociada | officeatwork |
| Dirección URL del sitio web de partners | [https://www.officeatwork.com](https://www.officeatwork.com) |
| Dirección URL de la directiva de privacidad | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| DIRECCIÓN URL de términos de uso | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Officeatwork ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | delegado | No se almacenan datos. | Favoritos: para poder leer y escribir datos en los usuarios OneDrive; OneDrive: para poder leer y escribir datos en los usuarios OneDrive. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Group.ReadWrite.All | delegado | No se almacenan datos. | Teams: para poder leer y escribir datos en un grupo. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| GroupMember.Read.All | delegado | No se almacenan datos. | SharePoint En línea: permiso de usuario para habilitar la lectura de datos desde SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Sites.Read.All | delegado | No se almacenan datos. | SharePoint En línea: para habilitar la lectura de datos desde SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read | delegado | No se almacenan datos. | Sing-In: para permitir que la aplicación officeatwork lea las propiedades básicas del usuario. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read.All | delegado | No se almacenan datos. | Teams: para averiguar a qué grupos pertenece un usuario. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| offline_access | delegado | No se almacenan datos. | Sing-In: para habilitar el inicio de sesión automático a través de tokens de actualización, como sin él, los usuarios tendrían que iniciar sesión manualmente cada vez que inicien la aplicación officeatwork. Este ámbito solo es necesario para aplicaciones host no habilitadas para SSO. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| OpenID | delegado | No se almacenan datos. | Sing-In: para permitir que los usuarios inicien sesión en la aplicación officeatwork con su organización o cuenta de Microsoft | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| perfil | delegado | No se almacenan datos. | Sing-In: para mostrar al usuario que ha iniciado sesión en la aplicación officeatwork. Esto ayuda a asegurar y confirmar al usuario qué cuenta se usó para iniciar sesión en la aplicación officeatwork. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de REST de SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí, los eventos incluyen oid y tenantId y se envían a Azure AppInsights. Los eventos se eliminan automáticamente después de 90 días. Si un cliente desea eliminar estos datos, puede usar el vínculo proporcionado en la declaración de privacidad para iniciar la eliminación de los datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de configuración de aplicaciones (marcas de características, nombre para mostrar de la organización, tenantId, lista de oides de administradores) se almacenan en una instancia de base de datos de Azure Cosmos (un archivo por inquilino). Los archivos db están cifrados y el acceso está restringido a los ingenieros de officeatwork seleccionados y al personal de soporte técnico. El cliente puede acceder y manipular los datos de configuración de la aplicación officeatwork mediante la aplicación web del Centro de administración.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Officeatwork ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Valores predeterminados de seguridad |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
