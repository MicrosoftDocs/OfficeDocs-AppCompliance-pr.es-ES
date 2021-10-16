---
title: Información de la aplicación para RingCentral por RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para RingCentral, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 74b9fdc5cedc126fb613e244badac7cc728418f2
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413442"
---
# <a name="ringcentral"></a>RingCentral

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/2f285d77-896a-4c5f-901e-0902316003b5" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000135" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por RingCentral, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | RingCentral |
| Id. | WA200000135 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | RingCentral, Inc. |
| Dirección URL del sitio web de partners | [https://www.ringcentral.com](https://www.ringcentral.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.ringcentral.com/apps/ringcentral-for-microsoft-...](https://www.ringcentral.com/apps/ringcentral-for-microsoft-teams) |
| Dirección URL de la directiva de privacidad | [https://www.ringcentral.com/legal/privacy-notice.html](https://www.ringcentral.com/legal/privacy-notice.html) |
| DIRECCIÓN URL de términos de uso | [https://www.ringcentral.com/legal/last-update-October-15-20...](https://www.ringcentral.com/legal/last-update-October-15-2019/eulatos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

RingCentral, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado |  Permite que la aplicación envíe el evento de invitaciones a reuniones a través de su calendario | Ninguno | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| offline_access | delegado |  Permite a la aplicación obtener y actualizar el token de oauth |  Token de acceso, token de actualización para obtener acceso a MS Graph API | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read | delegado |  Permite que la aplicación lea un perfil&#8217;de usuario (correo electrónico, nombre) para hacer coincidencias de contacto al final. Y permite al usuario iniciar sesión y vincular su cuenta de O365 con la cuenta ringcentral |  Correo electrónico, nombre, apellido | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read.All | delegado | Permite que la aplicación lea el perfil completo de un usuario con números de teléfono para realizar llamadas telefónicas con nuestros servicios. | Ninguno | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |


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

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833" target="_blank">Ver en una pestaña nueva</a>

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

