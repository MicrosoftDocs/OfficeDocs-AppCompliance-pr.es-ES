---
title: Información de la aplicación para Workday por Workday
ms.author: elmalova
author: elenamalova
ms.date: 01/26/2021
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Workday, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4212a7ec1b03175d76626d6c0cb7d3f04696288c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096425"
---
# <a name="workday"></a>Workday

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 26, 2021</p>

* <a href="https://teams.microsoft.com/l/app/aa4981ef-635f-4066-b260-97445a4b2819" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001555" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Workday a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Workday |
| Id. | WA200001555 |
| Capacidades | Bot |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Workday |
| Dirección URL del sitio web de partners | [https://nw.myworkday.com/microsoftteams](https://nw.myworkday.com/microsoftteams) |
| Dirección URL de Teams de información de la aplicación | [https://nw.myworkday.com/microsoftteams/](https://nw.myworkday.com/microsoftteams/) |
| Dirección URL de la directiva de privacidad | [https://www.workday.com/en-us/privacy.html](https://www.workday.com/en-us/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://nw.myworkday.com/microsoftteams/post-license](https://nw.myworkday.com/microsoftteams/post-license) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Workday ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsAppInstallation.ReadWriteForUser.All | aplicación | Volver a obtener el id. de la aplicación, instalar la aplicación para el usuario, obtener Teams detalles de licencia de AAD | No almacenamos datos relacionados con esta característica.  Nos permite instalar la aplicación para el usuario. | 0209ae9c-8d92-4fb8-9c77-4dc29fd371e0 |
>| User.Read.All | aplicación | Recuperar usuarios AAID para enviar mensajes a los usuarios. | Solo el AAID y Teams AAID  | 0209ae9c-8d92-4fb8-9c77-4dc29fd371e0 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Los datos de la organización se comparten entre Workday Services y Microsoft. Consulte los términos de su contrato con Workday para obtener más detalles. | Los datos de la organización se comparten entre Workday Services y Microsoft. Consulte los términos de su contrato con Workday para obtener más detalles. | N/A |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Los datos de lista se usan para personalizar la interacción de un usuario con la aplicación Workday. | No |  |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Consulte los términos de su contrato con Workday.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36384' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36384" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Workday ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
