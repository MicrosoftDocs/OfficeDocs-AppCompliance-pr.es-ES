---
title: Información de la aplicación para conmutación por conmutación
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Commuty, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ec9a5806126e5e8625d591985084b00f0a60c0fd
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411234"
---
# <a name="commuty"></a>Commuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 7, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003325" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Commuty a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Commuty |
| Id. | WA200003325 |
| Office 365 clientes compatibles | Outlook 2016 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la Web |
| Nombre de la compañía asociada | Commuty |
| Dirección URL del sitio web de partners | [https://www.commuty.net](https://www.commuty.net) |
| Dirección URL de la directiva de privacidad | [https://support.commuty.net/article/33-privacy-policy](https://support.commuty.net/article/33-privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://support.commuty.net/article/32-terms-conditions](https://support.commuty.net/article/32-terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Commuty ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Eventos de calendario | None, it is only used to synchronize Commuty's data to Calendario de Outlook. Los datos siempre se proporcionan en una interfaz de usuario conmutada (que puede ser a través de Outlook complemento). | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| email | delegado | Dirección de correo electrónico | None, this is only used to match a Commuty user with the AD identity | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| offline_access | delegado | N/D | N/D | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| OpenID | delegado | Autenticación | Ninguno | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| perfil | delegado | Identidad | Ninguno | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Datos personales comunes (correo electrónico principal, un correo electrónico secundario en el que pueden recibir notificaciones (opcional), nombre, apellido , número de Teléfono (opcional), imagen de perfil (opcional), idioma preferido, dirección personal (opcional, puede ser solo la ciudad)), datos de estacionamiento (placa de licencia), datos de movilidad: (pase de coche compartido, varios viajes de trabajo en casa, Departure-Return horas (opcional), Disponibilidad del coche (opcional), Desplazamientos, Días fuera de la oficina). Retención: al solicitar el usuario O al finalizar el contrato con nuestro cliente

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Cada cliente de Commuty firma nuestro DPA ( https://dpa.commuty.net) , que incluye una vista breve sobre esto.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Commuty ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
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

