---
title: Información de la aplicación para Workboard by Workboard
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Revise toda la información de seguridad y cumplimiento disponible para Workboard, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ccf27f1fa0c6db96446fc0fa7afc686fe2a49e20
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688105"
---
# <a name="application-information-for-workboard"></a>Información de la aplicación para Workboard

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización del desarrollador: 4 de junio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">Visualización en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Workboard a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Workboard |
| ID | WA104381599 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | Workboard |
| Dirección URL del sitio web del asociado | [https://www.workboard.com](https://www.workboard.com) |
| Dirección URL de Teams página de información de la aplicación | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| Dirección URL de la directiva de privacidad | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| Dirección URL de los términos de uso | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Workboard ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado o aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegado | dirección de correo electrónico y los identificadores de los usuarios.  Se usa para asignar el usuario al identificador de usuario de WorkBoard | WorkBoard solo almacena la identidad del usuario en sus bases de datos. | [User.Read](/graph/permissions-reference#user-permissions) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>No se usan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellidos, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agregue. ¿Esta aplicación hace uso de esta funcionalidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Se almacena EUII en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El identificador de usuario se usa para las notificaciones proactivas enviadas a Teams por WorkBord | Id. y dirección de correo electrónico de usuario | Se usa para asignar el usuario al identificador de usuario de WorkBoard |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en los registros o telemetría de las aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>WorkBoard no almacena datos de la organización en los sistemas del asociado

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Workboard ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | WorkBoard ha implementado sus propias directivas de acceso que se aplican dentro de la aplicación.  La organización, el equipo y la identidad del usuario se usan para determinar los derechos de acceso. |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de versión preliminar? | No |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
