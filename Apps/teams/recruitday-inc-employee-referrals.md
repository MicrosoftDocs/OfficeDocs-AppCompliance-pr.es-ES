---
title: Información de la aplicación para referencias de empleados por Recruitday Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para referencias de empleados, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 2aa10a6034260c3774a134eeace4e677f29c83ba
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286935"
---
# <a name="employee-referrals"></a>Recomendaciones de empleados

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c179cdf6-f93d-4aa3-9e2d-e934e5a81846" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002708" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Recruitday Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Recomendaciones de empleados |
| Id. | WA200002708 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Recruitday Inc. |
| Dirección URL del sitio web de partners | [https://www.recruitday.com](https://www.recruitday.com) |
| Dirección URL de Teams de información de la aplicación | [https://employer.recruitday.com/solutions/employee-referral...](https://employer.recruitday.com/solutions/employee-referrals/microsoft-teams) |
| Dirección URL de la directiva de privacidad | [https://www.recruitday.com/privacy-policy](https://www.recruitday.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.recruitday.com/terms-of-use](https://www.recruitday.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Recruitday Inc. sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | ambos | Nombre y apellido (del usuario de la aplicación, es decir, empleado) se usarán principalmente por el usuario de recursos humanos para identificar fácilmente al empleado que hizo referencia a un candidato para el seguimiento de aplicaciones de referencia y el pago de recompensas. También se usará para dirigirse correctamente al empleado cuando se envíen notificaciones por correo electrónico generadas por el sistema. | Nombre y apellido (del usuario de la aplicación, es decir, empleado) se usarán principalmente por el usuario de recursos humanos para identificar fácilmente al empleado que hizo referencia a un candidato para el seguimiento de aplicaciones de referencia y el pago de recompensas. También se usará para dirigirse correctamente al empleado cuando se envíen notificaciones por correo electrónico generadas por el sistema. | [7414b436-87d1-4904-9d52-ff47885b89f1](https://docs.microsoft.com/microsoft-365-app-certification/azure/7414b436-87d1-4904-9d52-ff47885b89f1) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Para ser procesado por Recruitday con los siguientes fines: 1.1. Crear cuenta de empleado 1.2. Enviar notificaciones generadas por el sistema relativas a transacciones y avisos 2. Para ser procesado por la organización del usuario con los siguientes fines: 2.1. Identificar el origen de una referencia 2.2. Determinar a quién se le dará la recompensa de referencia por la referencia correcta 2.3. Determinar qué empleados no tendrán acceso al sistema (es decir, bloquear el acceso) | Nombre, apellido, dirección de correo electrónico | 1. Para ser procesado por Recruitday con los siguientes fines: 1.1. Crear cuenta de empleado 1.2. Enviar notificaciones generadas por el sistema relativas a transacciones y avisos 2. Para ser procesado por la organización del usuario con los siguientes fines: 2.1. Identificar el origen de una referencia 2.2. Determinar a quién se le dará la recompensa de referencia por la referencia correcta 2.3. Determinar qué empleados no tendrán acceso al sistema (es decir, bloquear el acceso) |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El administrador puede archivar los datos del usuario a través del portal. Otras funciones, como eliminar, actualizar, etc., se realizarán mediante solicitud a Recruitday.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Recruitday Inc. sobre cómo esta aplicación controla la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
