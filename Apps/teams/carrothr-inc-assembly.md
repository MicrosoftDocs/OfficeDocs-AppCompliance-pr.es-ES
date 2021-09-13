---
title: Información de la aplicación para el ensamblado de CarrotHR Inc.
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Assembly, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f8d63c77c3fd9b52353ce22954dfa4dadb8dea2f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59289409"
---
# <a name="assembly"></a>Ensamblado

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3e674b5f-ba5d-41cc-8b06-e065b4394aeb" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002271" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por CarrotHR Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Ensamblado |
| Id. | WA200002271 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | CarrotHR Inc. |
| Dirección URL del sitio web de partners | [https://www.joinassembly.com](https://www.joinassembly.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.joinassembly.com/about](https://www.joinassembly.com/about) |
| Dirección URL de la directiva de privacidad | [https://joinassembly.com/privacy-policy](https://joinassembly.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://joinassembly.com/terms-of-service](https://joinassembly.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por CarrotHR Inc. sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegado | Permitir que el usuario asigne la aplicación a un canal recién creado desde nuestra aplicación | Almacenamos el id. de canal para mantener nuestra aplicación sincronizada con el canal correcto | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Directory.Read.All | aplicación | Mantenga nuestros perfiles sincronizados para que los miembros puedan buscar correctamente en Assembly | Cualquier información de perfil adicional que pueda estar disponible para que los miembros puedan buscar en assembly | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Group.Read.All | delegado | Observamos los datos para asegurarnos de que pueden asignar nuestra aplicación al grupo correcto | No almacenamos grupos | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Teams.ReadBasic.All | aplicación | Capacidad para asignar nuestra aplicación a la pestaña de equipo correcta | No almacenamos equipos que esperan el que se nos anexa  | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| TeamsTab.Create | aplicación | Usamos esto para permitir que nuestra aplicación se anexe correctamente a un canal o equipo | No estamos recopilando ni almacenando datos de pestañas | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| email | delegado | Correo electrónico del usuario para que podamos concederles acceso a su cuenta específica | Correo electrónico del usuario para que podamos concederles acceso a su cuenta específica e identidades de coincidencia | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| perfil | delegado | Nombre de usuario para rellenar automáticamente assembly y mantener la sincronización con los cambios en Microsoft Teams | Nombre completo del usuario | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |


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

>eliminación, retención, auditoría, archivado

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por CarrotHR Inc. sobre cómo esta aplicación controla la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
