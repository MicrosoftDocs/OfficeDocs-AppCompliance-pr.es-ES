---
title: Información de la aplicación para Lucidspark por Software Lúcido
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Lucidspark, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e79bed420b3081ae31a0abda25299610eeb1bc5f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287439"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Software lúcido a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Lucidspark |
| Id. | WA200002583 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Lucid Software |
| Dirección URL del sitio web de partners | [https://lucid.co](https://lucid.co) |
| Dirección URL de Teams de información de la aplicación | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| Dirección URL de la directiva de privacidad | [https://lucid.co/privacy](https://lucid.co/privacy) |
| DIRECCIÓN URL de términos de uso | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Software lúcido sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidspark generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidspark para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| OpenID | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidspark generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidspark para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| perfil | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidspark generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidspark para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Los datos de Lucidspark y lucidchart se almacenan en AWS y Copo de nieve | Nombre de la organización, información de contacto y nivel de licencia | No usamos ninguna API de Microsoft. Usamos openID para obtener datos de usuario básicos para realizar SSO. Usamos su API de selector de archivos, pero eso no nos da acceso a los archivos del usuario que no son los que nos envían a través del selector. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Registramos el correo electrónico y las direcciones IP por motivos de seguridad y soporte técnico. Todo el acceso a los registros es registrado &amp; los registros son realmente inmutables en un sistema de terceros. El acceso a los registros requiere MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de Lucidspark y lucidchart se almacenan en AWS. Se cifra en reposo y en tránsito. Lucid usa las reglas de privilegios mínimos y MFA.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Software lúcido sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
