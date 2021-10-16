---
title: Información de la aplicación para Aster por Aster
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Aster, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 11edf7f1d092a565b0c69155a1c2be4213c206e2
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415267"
---
# <a name="aster"></a>Aster

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2021</p>

* <a href="https://teams.microsoft.com/l/app/2d8e8042-66df-4605-8c3a-9ca8962f3e99" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002379" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Aster a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Aster |
| Id. | WA200002379 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Aster |
| Dirección URL del sitio web de partners | [https://asterapp.co](https://asterapp.co) |
| Dirección URL de Teams de información de la aplicación | [https://asterapp.co/solution/](https://asterapp.co/solution/) |
| Dirección URL de la directiva de privacidad | [https://asterapp.co/politique-de-confidentialite/](https://asterapp.co/politique-de-confidentialite/) |
| DIRECCIÓN URL de términos de uso | [https://asterapp.co/conditions-generales/](https://asterapp.co/conditions-generales/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Aster ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que tendrá su organización sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Lista de directorios para enviar tareas de Planner de documentos de Sharepoint | Ninguno | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Group.ReadWrite.All | delegado | Lista de grupos para enviar tareas de Planner de documentos de Sharepoint en grupos existentes o creados | Ninguno | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Notes.ReadWrite.All | delegado | Notas contenido para escribir en OneNote | Ninguno | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Tasks.ReadWrite.Shared | delegado | Tareas, asignación, plazos | Todos estos datos para sincronizar las tareas Graph API con tareas de Aster | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| User.Read | delegado | Correo electrónico del usuario para identificar al usuario | Por ejemplo, el correo electrónico del usuario en las asignaciones | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| offline_access | delegado | No se recopilan datos, solo para actualizar el token sin parecer | Ninguno | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para comunicarse con el usuario de forma humana y personnalizada | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Todos los accesos se registran, se identifican con los mensajes de correo electrónico de los usuarios

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Contrato RGPD

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Aster ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

