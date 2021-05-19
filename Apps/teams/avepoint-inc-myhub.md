---
title: Información de la aplicación para MyHub by AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para MyHub, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ccf5367ea692731bafcdc03d04ab4dad2e76c976
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553391"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 21 de diciembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por AvePoint, inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | MyHub |
| ID | WA200000726 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | AvePoint, inc. |
| URL del sitio web de socios | [https://www.avepoint.com](https://www.avepoint.com) |
| URL de la Política de Privacidad | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL de los Términos de uso | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

AvePoint, inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | ambos | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Leer datos del directorio | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | ambos | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Leer y escribir en todos los grupos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | Delegado | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Enviar correo como usuario | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | aplicación | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Leer todos los informes de uso | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | aplicación | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Tomar el control total de todas las colecciones de sitios | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | aplicación | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Leer los elementos de todas las colecciones de sitios  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | Delegado | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Editar o eliminar elementos en todas las colecciones de sitios | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | ambos | los datos de configuración de la aplicación se almacenan desde un punto de vista de control de datos | Leer todos los usuarios&#8217; perfiles completos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, el correo electrónico del usuario y el identificador de inquilino aparecerán en los registros. Los registros se almacenan en una ubicación segura y solo el personal autorizado puede acceder durante la solución de problemas. Los registros se archivarán después de 60 días con fines de auditoría de seguridad y se eliminarán después de un año.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos de la aplicación se almacenan en Azure SQL Database y Azure Storage. Azure SQL y Azure Storage cifrado están habilitados.
Solo los administradores autorizados pueden acceder a los datos. Se requiere MFA para que los administradores inicien sesión. Las operaciones se auditan. La lista blanca IP también se utiliza para restringir el acceso a los datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

