---
title: Información de la aplicación para Zignals de Alight
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Zignals, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9a9e3f1cd6456e1e3c943091325caaff8b934b98
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413121"
---
# <a name="zignals"></a>Zignals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a0b58ca7-958d-4343-a2dc-a75f2eeb0953" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003201" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Alight a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zignals |
| Id. | WA200003201 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Alight |
| Dirección URL del sitio web de partners | [https://www.alight.eu](https://www.alight.eu) |
| Dirección URL de Teams de información de la aplicación | [https://zignals.eu/zignals-support/](https://zignals.eu/zignals-support/) |
| Dirección URL de la directiva de privacidad | [https://www.zignals.eu/privacy-policy-zignals-for-teams/](https://www.zignals.eu/privacy-policy-zignals-for-teams/) |
| DIRECCIÓN URL de términos de uso | [https://zignals.eu/terms](https://zignals.eu/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Alight ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Para el área Mis reuniones, se obtienen las reuniones del &quot; &quot; usuario hoy y mañana. | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Sites.ReadWrite.All | delegado | Se obtienen todos los sitios SharePoint seguidos del usuario y se muestran en el área Mi trabajo en equipo y se obtienen todas las tareas de SharePoint del usuario y se muestran en el área &quot; &quot; Mis tareas &quot; &quot; . | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Tasks.ReadWrite | delegado | Leemos el Planner del usuario y To Do tareas y las mostrándolos en el área &quot; Mis tareas &quot; . | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Team.ReadBasic.All | delegado | Se obtienen los equipos unidos del usuario y se muestran en el &quot; área Mi trabajo en &quot; equipo. | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadBasic.All | delegado | En el &quot; área Mis &quot; documentos, se muestra la colaboración del usuario | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadWrite | delegado | Los documentos recientes del usuario se muestran en el área &quot; Mis documentos &quot; . Las aplicaciones favoritas del usuario se almacenan como una extensión de esquema en el MS Graph. Este nivel de permisos es necesario para leer y escribir datos en el gráfico. | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| email | delegado | Obtener el correo electrónico de los usuarios (ámbito Teams MS estándar) | No almacenado en nuestra base de datos | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| offline_access | delegado | Ámbito de Teams MS estándar | No almacenado en nuestra base de datos | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| OpenID | delegado | Usuarios de inicio de sesión. | No se almacena información en la base de datos de aplicaciones. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| perfil | delegado | Proceso de inicio de sesión MS Teams | No almacenado en nuestra base de datos | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos solo se almacenan en Azure. Aquí usamos la interfaz de administrador para controlar los datos (incluidos la eliminación, la auditoría, etc.)

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Alight ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

