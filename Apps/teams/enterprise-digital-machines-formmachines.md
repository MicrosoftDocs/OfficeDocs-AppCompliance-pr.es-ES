---
title: Información de la aplicación para FormMachines mediante Enterprise Digital Machines
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para FormMachines, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 943c2329556e38941b4b699cb803bea22a05dcfe
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096526"
---
# <a name="formmachines"></a>FormMachines

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/54d8b826-3e30-4589-a77a-ed99cfbbb4c9" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001217" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Enterprise Digital Machines a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | FormMachines |
| Id. | WA200001217 |
| Capacidades | Pestaña, conector |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Enterprise Digital Machines |
| Dirección URL del sitio web de partners | [https://www.formmachines.com](https://www.formmachines.com) |
| Dirección URL de la directiva de privacidad | [https://www.formmachines.com?dirKey=fm-privacy](https://www.formmachines.com?dirKey=fm-privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.formmachines.com?dirKey=fm-terms-of-use](https://www.formmachines.com?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Enterprise Digital Machines acerca de cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegado | (inicio de sesión, correo electrónico, Guid de Azure, displayName, first_login_date_time) | permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso, nos permite identificar de forma única a cada usuario | 8c87660f-d36f-41f6-b0ae-025253f380aa |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>. Solo registramos errores . En nuestro registro de errores, solo registramos información relacionada con errores. No se recopila qué cliente o cliente desencadenó un error concreto. Solo los ingenieros de soporte técnico tienen acceso a los registros de errores . Los registros de errores se ven en línea, no se descargan ni se ven . Los registros de errores se eliminan automáticamente después de 30 días

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>. Los datos se almacenan en centros de datos basados en Azure US . Los datos proporcionados por el cliente, como plantillas y envíos, se cifran en la base de datos . Los datos adjuntos de archivos se almacenan en contenedores BLOB de Azure privados, los usuarios deben autenticarse antes de obtener acceso a ellos. Tenemos un máximo de dos administradores que pueden acceder a nuestros activos de producción para solucionar problemas e implementarlos. Estas dos cuentas de administrador se particiona de forma diferente a las demás cuentas. El número de acceso de administrador nunca superará los dos

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

