---
title: Información de la aplicación para el explorador selector de plantillas
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Template Chooser Browser, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f6ec449ba2c90ebebaa662a3adca01d211a225fb
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65221081"
---
# <a name="application-information-for-template-chooser-browser-by-officeatwork"></a>Información de la aplicación para Template Chooser Browser by officeatwork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 22 de junio de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.template-chooser-browser" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por officeatwork a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Explorador del selector de plantillas |
| ID | officeatwork-ag.template-chooser-browser |
| Nombre de la empresa asociada | officeatwork |
| Dirección URL del sitio web del asociado | [https://www.officeatwork.com](https://www.officeatwork.com) |
| Dirección URL de la directiva de privacidad | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| Dirección URL de los términos de uso | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Officeatwork ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | Delegado | No se almacenan datos. | Favoritos: para poder leer y escribir datos a los usuarios OneDrive; OneDrive: para poder leer y escribir datos en los usuarios OneDrive. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Group.ReadWrite.All | Delegado | No se almacenan datos. | Teams: para poder leer y escribir datos en un grupo. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| GroupMember.Read.All | Delegado | No se almacenan datos. | SharePoint Online: permiso de usuario para habilitar la lectura de datos de SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Sites.Read.All | Delegado | No se almacenan datos. | SharePoint Online: para habilitar la lectura de datos de SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read | Delegado | No se almacenan datos. | Sing-In: para permitir que la aplicación officeatwork lea las propiedades básicas del usuario. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read.All | Delegado | No se almacenan datos. | Teams: para averiguar a qué grupos pertenece un usuario. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| offline_access | Delegado | No se almacenan datos. | Sing-In: para habilitar el inicio de sesión automático a través de tokens de actualización, como sin él, los usuarios tendrían que iniciar sesión manualmente cada vez que inicien la aplicación officeatwork. Este ámbito solo es necesario para aplicaciones host no habilitadas para SSO. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| OpenID | Delegado | No se almacenan datos. | Sing-In: para permitir que los usuarios inicien sesión en la aplicación officeatwork con su organización o cuenta microsoft | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| perfil | Delegado | No se almacenan datos. | Sing-In: para mostrar el usuario que ha iniciado sesión en la aplicación officeatwork. Esto ayuda a garantizar o confirmar al usuario qué cuenta se usó para iniciar sesión en la aplicación officeatwork. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph para recopilar o procesar información de identificación de la organización (OII). Enumere las API de Microsoft distintas de Microsoft Graph que use esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para la recopilación de OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de REST de SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>No se usan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, los eventos incluyen el valor oid y tenantId y se envían a Azure AppInsights. Los eventos se eliminan automáticamente después de 90 días. Si un cliente desea eliminar estos datos, puede usar el vínculo proporcionado en la declaración de privacidad para iniciar la eliminación de esos datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de configuración de aplicaciones (marcas de características, nombre para mostrar de la organización, tenantId, lista de administradores oid) se almacenan en una instancia de Azure Cosmos base de datos (un archivo por inquilino). Los archivos de base de datos están cifrados y el acceso está restringido a los ingenieros de officeatwork y al personal de soporte técnico seleccionados. El cliente puede acceder a los datos de configuración de la aplicación officeatwork y manipularlos mediante la aplicación web del Centro de administración.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Officeatwork ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Valores predeterminados de seguridad |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evita usar? | - URI de redireccionamiento comodín,<br/>- Flow implícita de OAuth2, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de versión preliminar? | No |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
