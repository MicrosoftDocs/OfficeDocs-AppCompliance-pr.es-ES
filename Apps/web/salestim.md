---
title: Información de la aplicación para SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SalesTim, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222441"
---
# <a name="application-information-for-salestim-by-salestim"></a>Información de la aplicación para SalesTim by SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 24 de junio de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SalesTim a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SalesTim |
| ID | salestim.salestim |
| Nombre de la empresa asociada | SalesTim |
| Dirección URL del sitio web del asociado | [https://salestim.com](https://salestim.com) |
| Dirección URL de la directiva de privacidad | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| Dirección URL de los términos de uso | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

SalesTim ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegado | NO | Permitir que la aplicación instale y actualice sus propios paquetes en el catálogo de aplicaciones corporativo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegado | Solo se&#8217;almacenar algunos identificadores de usuarios, no datos de perfil. | Permite a un usuario seleccionar otros usuarios en varios lugares de la aplicación, como seleccionar aprobadores en un flujo de trabajo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegado | Solo&#8217;almacenar los identificadores de grupos o equipos,&#8217;no almacenar ningún contenido de grupos o equipos. | Permite a la aplicación crear grupos, leer todas las propiedades y pertenencias del grupo en nombre del usuario que ha iniciado sesión. Además, permite a los propietarios del grupo que administren sus grupos y permite a los miembros del grupo que actualicen su contenido del grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegado | Se&#8217;volver a almacenar los metadatos de esta acción, como la fecha de notificación, el destinatario (solo identificador), el identificador de solicitud. | Permite a la aplicación enviar correos electrónicos de notificación por ejemplo durante un flujo de trabajo de aprobación. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegado | Estamos usando algunos servicios de Azure para almacenar datos, especialmente Redis en Azure y Cosmos DB. | Permite a la aplicación administrar las unidades (archivos y carpetas) asociadas a un equipo durante un proceso de aprovisionamiento de equipos. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegado | Solo se&#8217;almacenar algunos identificadores de usuarios, no datos de perfil. | Permite que la aplicación lea el conjunto completo de propiedades de perfil, informes y administradores de cualquier usuario. Se usa especialmente durante el proceso de selección de destino de la audiencia, para filtrar algunos contenidos en función del perfil de usuario actual. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | Delegado | No | Permite que la aplicación realice algunas operaciones y acciones en segundo plano como usuario. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>| **Todas las OII que no sean servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando Intercom como nuestra principal aplicación de soporte técnico. Intercom puede contener información básica de perfil de usuario, como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#support-data | Nombre de la compañía | Estamos usando GitHub API para generar problemas automáticamente desde nuestro entorno de producción. También almacenaremos algunos registros técnicos en GitHub (como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data). Estos problemas y registros pueden contener información básica del perfil de usuario. Estos problemas y registros se eliminan automáticamente cada 15 días. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Todos los datos recopilados se describen aquí: https://developers.salestim.com/platform/datamanagement.html#application-data como se describe, los registros se almacenan temporalmente durante 15 días y, a continuación, se eliminan automáticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>La mayoría de los datos se almacenan en Azure Cosmos DB.
El acceso al entorno de producción está restringido a dos personas y estas cuentas de administrador se aplican a MFA.
Estas cuentas son dedicadas y diferentes de nuestras cuentas corporativas.
Los datos se cifran en reposo en todos los servicios de Azure que estamos usando.
Las implementaciones en entornos de producción se automatizan a través de una rama protegida dedicada en nuestro entorno de GitHub, donde solo dos personas pueden aprobar los cambios.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

SalesTim ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | MFA, condiciones de ubicación |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evita usar? | ,<br/>- Flow implícita de OAuth2, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de versión preliminar? | No |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
