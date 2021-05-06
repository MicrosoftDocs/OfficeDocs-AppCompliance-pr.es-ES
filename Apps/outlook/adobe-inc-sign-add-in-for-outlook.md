---
title: Información de la aplicación para Adobe Sign Add-In para Outlook por Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Adobe Sign Add-In para Outlook, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 530bd74a0c74561545c4e7076cec5f6bc0eb5aa4
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251809"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In para Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Adobe Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Adobe Sign Add-In para Outlook |
| ID | WA104381158 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la web |
| Nombre de la compañía asociada | Adobe Inc. |
| Dirección URL del sitio web de partners | [https://www.adobe.com/](https://www.adobe.com/) |
| Dirección URL de la directiva de privacidad | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| DIRECCIÓN URL de términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Adobe Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | aplicación | Necesitamos datos del correo electrónico para extraer el historial de Adobe Sign y el informe de seguimiento de auditoría de cada transacción. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | Para rellenar el documento adjunto, los correos electrónicos del remitente y el receptor, y el contenido de los mensajes de correo electrónico a Adobe sign para enviar para la firma. Esto es para ahorrar tiempo al usuario para volver a escribir esos campos en Adobe Sign. Después de firmar un contrato, redactemos automáticamente un nuevo correo electrónico para que el usuario envíe un correo electrónico para informar a sus destinatarios de que la transacción se ha realizado. |  |
>| People.Read | delegado |  | Para rellenar automáticamente la dirección de correo electrónico en la experiencia Enviar para la firma, escribiendo algunas letras iniciales, no es necesario que los usuarios &quot; &quot; escriban los correos electrónicos completos. |  |
>| User.Read | delegado |  | Para leer el perfil de usuario y hacer coincidir su perfil (básicamente, su correo electrónico) con nuestra base de datos para que puedan usar Adobe Sign. |  |
>| offline_access | delegado |  | Para actualizar el token de acceso, cuando el actual ha expirado. Por ejemplo, cuando el usuario está en una ventana de envío de firma y lo deja inactivo durante demasiado tiempo, necesitamos actualizar un nuevo token cuando el usuario &quot; &quot; está activo. |  |
>| OpenID | delegado | El correo electrónico es el identificador único para los usuarios de Adobe Sign. Almacenamos el identificador de correo electrónico para poder asignar todas las actividades de ese usuario a su registro de Adobe Sign.  | Para iniciar sesión con el usuario para garantizar su consentimiento para el permiso de usar la aplicación Adobe Sign. |  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| Buzón de ReadWrite | Este complemento puede leer o modificar el contenido de cualquier elemento del buzón y crear nuevos elementos. Puede tener acceso a información personal (como el cuerpo, el asunto, el remitente, los destinatarios o los datos adjuntos) en cualquier mensaje o elemento del calendario. Puede enviar estos datos a un servicio de terceros. |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Ninguno. No registramos ningún EUII o OII en registros o telemetría de salida. El proceso son nuestras propias revisiones de seguridad que validan que no lo estamos haciendo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No tenemos ninguna interacción de administrador de clientes en nuestro sistema para Microsoft Teams aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

