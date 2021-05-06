---
title: Información de la aplicación para SalesTim por SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para SalesTim, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 82ded2fc8555079ac3446d8446d261dbca5eed73
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250438"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: October 27, 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SalesTim a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SalesTim |
| ID | WA200001393 |
| Capacidades | Pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | SalesTim |
| Dirección URL del sitio web de partners | [https://www.salestim.com](https://www.salestim.com) |
| Dirección URL de la directiva de privacidad | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

SalesTim ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegado | NO | Permitir que la aplicación instale y actualice sus propios paquetes en el catálogo de aplicaciones corporativas. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | delegado | Solo&#8217;algunos de los usuarios, no los datos de perfil. | Permite a un usuario seleccionar otros usuarios en varios lugares de la aplicación, como seleccionar aprobadores en un flujo de trabajo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | delegado | Solo&#8217;de grupos o de equipos, no almacenamos&#8217;contenido de grupos o equipos. | Permite que la aplicación cree grupos, lea todas las propiedades y pertenencias del grupo en nombre del usuario que ha iniciado sesión. Además, permite a los propietarios del grupo que administren sus grupos y permite a los miembros del grupo que actualicen su contenido del grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | delegado | Se&#8217;los metadatos de esta acción, como la fecha de notificación, el destinatario (solo id.), el identificador de solicitud. | Permite que la aplicación envíe correos electrónicos de notificación por ejemplo durante un flujo de trabajo de aprobación. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | delegado | Estamos usando algunos servicios de Azure para almacenar datos, especialmente Redis en Azure y Cosmos DB | Permite que la aplicación administre las unidades (archivos y carpetas) asociadas con un equipo durante un proceso de aprovisionamiento de equipo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | delegado | Solo&#8217;algunos de los usuarios, no los datos de perfil. | Permite que la aplicación lea el conjunto completo de propiedades de perfil, informes y administradores de cualquier usuario. Se usa especialmente durante el proceso de selección de audiencia para filtrar algunos contenidos en función del perfil de usuario actual. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offlineaccess | delegado | No | Permite que la aplicación realice algunas operaciones y acciones en segundo plano como usuario. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando El intercomunicador como nuestra aplicación de soporte técnico principal. El intercomunicador puede contener información básica de perfil de usuario, como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Estamos usando las API GitHub para generar problemas automáticamente desde nuestro entorno de producción. También almacenamos algunos registros técnicos en GitHub (como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Estos problemas y registros pueden contener información básica de perfil de usuario. Estos problemas y registros se eliminan automáticamente cada 15 días. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Aquí se describen todos los datos recopilados: como se describe, los registros se almacenan temporalmente durante 15 días y, a https://developers.salestim.com/platform/datamanagement.html#application-data continuación, se eliminan automáticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>La mayoría de los datos se almacenan en Azure Cosmos DB.
El acceso al entorno de producción está restringido a dos personas y estas cuentas de administrador se aplican a MFA.
Estas cuentas son dedicadas y diferentes de nuestras cuentas corporativas.
Los datos se cifran en reposo en todos los servicios de Azure que estamos usando.
Las implementaciones en entornos de producción se automatizan a través de una rama protegida dedicada en nuestro entorno de GitHub, donde solo dos personas pueden aprobar cambios.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

