---
title: Información de la aplicación SalesTim por SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para SalesTim, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553921"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 27 de octubre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SalesTim a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SalesTim |
| ID | WA200001393 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | SalesTim |
| URL del sitio web de socios | [https://www.salestim.com](https://www.salestim.com) |
| URL de la Política de Privacidad | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL de los Términos de uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

SalesTim ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegado | NO | Permita que la aplicación instale y actualice sus propios paquetes en el catálogo de aplicaciones corporativas. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegado | &#8217;almacenamos solo algunos IDs de usuarios, no datos de perfil. | Permite a un usuario seleccionar otros usuarios en varios lugares de la aplicación, como seleccionar aprobadores en un flujo de trabajo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegado | Solo&#8217;almacenamos equipos y grupos,&#8217;no almacenamos ningún contenido de grupos o equipos. | Permite a la aplicación crear grupos, leer todas las propiedades del grupo y pertenencias en nombre del usuario que ha iniciado sesión. Además, permite a los propietarios del grupo que administren sus grupos y permite a los miembros del grupo que actualicen su contenido del grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegado | &#8217;volver a almacenar los metadatos de esta acción, como la fecha de notificación, el destinatario (solo id.) y el identificador de solicitud. | Permite a la aplicación enviar correos electrónicos de notificación, por ejemplo, durante un flujo de trabajo de aprobación. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegado | Estamos usando algunos servicios de Azure para almacenar datos, especialmente Redis en Azure y Cosmos DB | Permite a la aplicación administrar las unidades (archivos y carpetas) asociadas a un equipo, durante un proceso de aprovisionamiento de equipo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegado | &#8217;almacenamos solo algunos IDs de usuarios, no datos de perfil. | Permite a la aplicación leer el conjunto completo de propiedades de perfil, informes y administradores de cualquier usuario. Se utiliza especialmente durante el proceso de segmentación de audiencia, para filtrar algunos contenidos basados en el perfil de usuario actual. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| acceso fuera de línea | Delegado | No | Permite a la aplicación realizar algunas operaciones y acciones en segundo plano como usuario. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando Intercom como nuestra principal aplicación de soporte. Intercomunicador puede contener alguna información básica del perfil de usuario, como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Estamos usando GitHub API para generar problemas automáticamente desde nuestro entorno de producción. También almacenamos algunos registros técnicos en GitHub (como se describe aquí: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Estos problemas y registros pueden contener información básica del perfil de usuario. Estos problemas y registros se eliminan automáticamente cada 15 días. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Todos los datos recopilados se describen aquí: https://developers.salestim.com/platform/datamanagement.html#application-data Como se describe, los registros se almacenan temporalmente durante 15 días y luego se eliminan automáticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>La mayoría de los datos se almacenan en Azure Cosmos DB.
El acceso al entorno de producción está restringido a dos personas y estas cuentas de administrador se aplican.
Estas cuentas son dedicadas y diferentes de nuestras cuentas corporativas.
Los datos se cifran en reposo en todos los servicios de Azure que estamos usando.
Las implementaciones en entornos de producción se automatizan a través de una rama protegida dedicada en nuestro entorno de GitHub, donde solo dos personas pueden aprobar cambios.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

