---
title: Información de la aplicación para TELUS Empresa Conectar por RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para TELUS Business Conectar, sus directivas de tratamiento de datos, su información del catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 465b92171bb82a617d2369298037c06fce1fa84a
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413452"
---
# <a name="telus-business-connect"></a>TELUS Business Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5001eed-f63e-4a7d-9b49-bf8272c934cd" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002300" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por RingCentral, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | TELUS Business Connect |
| Id. | WA200002300 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | RingCentral, Inc. |
| Dirección URL del sitio web de partners | [https://www.ringcentral.com](https://www.ringcentral.com) |
| Dirección URL de Teams de información de la aplicación | [https://appsource.microsoft.com/en-us/product/office/WA2000...](https://appsource.microsoft.com/en-us/product/office/WA200002300) |
| Dirección URL de la directiva de privacidad | [https://www.telus.com/en/about/privacy/](https://www.telus.com/en/about/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://telus.com/BusinessConnect/ServiceTerms](https://telus.com/BusinessConnect/ServiceTerms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

RingCentral, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado |  Permite que la aplicación envíe el evento de invitaciones a reuniones a través de su calendario | Ninguno | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read | delegado |  Permite que la aplicación lea un perfil&#8217;de usuario (correo electrónico, nombre) para hacer coincidencias de contacto al final. Y permite al usuario iniciar sesión y vincular su cuenta de O365 con la cuenta ringcentral |  Correo electrónico, nombre, apellido | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read.All | delegado | Permite que la aplicación lea el perfil completo de un usuario con números de teléfono para realizar llamadas telefónicas con nuestros servicios. | Ninguno | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| offline_access | delegado |  Permite a la aplicación obtener y actualizar el token de oauth |  Token de acceso, token de actualización para obtener acceso a MS Graph API | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |


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

>Cuando usamos otra organización, aún controlamos su información personal. Y tenemos controles estrictos para asegurarnos de que&#8217;esté correctamente protegido. Por último, en la sección anterior se describen las situaciones en las que su información personal se comparte con otras organizaciones, organismos gubernamentales y organismos de aplicación de la ley.  Cuando compartamos su información con otras organizaciones,&#8217;nos aseguraremos de que&#8217;esté protegida, en la medida de lo razonable posible.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

RingCentral, Inc. ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

