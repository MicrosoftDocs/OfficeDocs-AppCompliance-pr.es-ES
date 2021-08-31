---
title: Información de aplicaciones para Project Migrator por FluentPro Software Corporation
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Project Migrator, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c36f0ed0642705518d18a88068cd67c54f752ede
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673223"
---
# <a name="project-migrator"></a>Project Migrator

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8cd35615-e306-4b3d-8e93-17520129b60a" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003160" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por FluentPro Software Corporation a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Project Migrator |
| Id. | WA200003160 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | FluentPro Software Corporation |
| Dirección URL del sitio web de partners | [https://projectmigrator.com](https://projectmigrator.com) |
| Dirección URL de Teams de información de la aplicación | [https://help.fluentpro.com/147404-project-migrator](https://help.fluentpro.com/147404-project-migrator) |
| Dirección URL de la directiva de privacidad | [https://projectmigrator.com/privacy-policy](https://projectmigrator.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://projectmigrator.com/terms-of-use](https://projectmigrator.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

FluentPro Software Corporation ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Lea los grupos y su pertenencia para migrar al otro inquilino. | No hay datos almacenados para este permiso.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Group.ReadWrite.All | delegado | Nombre del grupo, miembros, planes y tareas. Use información de grupos, planes y tareas para la migración de datos de Planner. | Nombre del grupo, Nombre del plan y Nombre de tarea. Se usa para resumen de información de migración.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Sites.ReadWrite.All | delegado | Migre SharePoint documentos adjuntos de tareas de MS Planner. | No hay datos almacenados para este permiso.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegado | UPN para almacenar la información de resumen de migración de MS Planner vinculada a la cuenta. | UPN. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.ReadBasic.All | delegado | Use la información de usuario para migrar las asignaciones de tareas de MS Planner y la pertenencia a grupos. | No hay datos almacenados para este permiso.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| offline_access | delegado | Los tokens de actualización y acceso se usan para obtener acceso a los datos de MS Planner. | El token de actualización cifrado se almacena para obtener acceso a los datos de MS Planner. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegado | Nombre, Apellido, Nombre de la compañía, Teléfono, Correo electrónico corporativo. Estos datos se usan para procesos de registro y autenticación. | Nombre, Apellido, Nombre de la compañía, Teléfono, Correo electrónico corporativo, UPN. | [c36d31a2-8de1-4eb5-9e7d-01da45244c04](https://docs.microsoft.com/microsoft-365-app-certification/azure/c36d31a2-8de1-4eb5-9e7d-01da45244c04) |


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

>https://projectmigrator.com/privacy-policy

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

FluentPro Software Corporation ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | No |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
