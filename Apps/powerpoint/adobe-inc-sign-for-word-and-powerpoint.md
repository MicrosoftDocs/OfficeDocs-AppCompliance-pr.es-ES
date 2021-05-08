---
title: Información de la aplicación para Adobe Sign para Word y PowerPoint por Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Adobe Sign para Word y PowerPoint, sus directivas de tratamiento de datos, su información del catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3ac861b6472b9c96483ea3e8a9ad8fd4d7f02834
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258947"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign para Word y PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: February 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Adobe Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Adobe Sign para Word y PowerPoint |
| ID | WA104381155 |
| Office 365 clientes compatibles | Word 2016 o posterior en Mac, PowerPoint 2013 Service Pack 1 o posterior en Windows, Word 2013 Service Pack 1 o posterior en Windows, Word en la Web, PowerPoint en la Web, PowerPoint 2016 o posterior en Mac |
| Nombre de la compañía asociada | Adobe Inc. |
| Dirección URL del sitio web de partners | [https://www.adobe.com/](https://www.adobe.com/) |
| Dirección URL de la directiva de privacidad | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| DIRECCIÓN URL de términos de uso | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Adobe Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | delegado | Para rellenar el documento adjunto, los correos electrónicos del remitente y el receptor, y el contenido de los mensajes de correo electrónico a Adobe sign para enviar para la firma. Esto es para ahorrar tiempo al usuario para volver a escribir esos campos en Adobe Sign. Después de firmar un contrato, redactemos automáticamente un nuevo correo electrónico para que el usuario envíe un correo electrónico para informar a sus destinatarios de que la transacción se ha realizado. | Adobe Sign guardará los datos adjuntos como archivos temporales, que tiene un vencimiento de 24 horas. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| People.Read | delegado | Para rellenar automáticamente la dirección de correo electrónico en la experiencia Enviar para la firma, escribiendo algunas letras iniciales, no es necesario que los usuarios &quot; &quot; escriban los correos electrónicos completos. | Adobe Sign solo almacenará el correo electrónico de los destinatarios y displayName en los acuerdos. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| User.Read | delegado | Para leer el perfil de usuario y hacer coincidir su perfil (básicamente, su correo electrónico y userId) con nuestra base de datos para que puedan usar Adobe Sign. | Para leer el perfil de usuario y hacer coincidir su perfil (básicamente, su correo electrónico y userId) con nuestra base de datos para que puedan usar Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| offline_access | delegado | Para actualizar el token de acceso, cuando el actual ha expirado. Por ejemplo, cuando el usuario está en una ventana de envío de firma y lo deja inactivo durante demasiado tiempo, necesitamos actualizar un nuevo token cuando el usuario &quot; &quot; está activo. | Para actualizar el token de acceso, cuando el actual ha expirado. Por ejemplo, cuando el usuario está en una ventana de envío de firma y lo deja inactivo durante demasiado tiempo, necesitamos actualizar un nuevo token cuando el usuario &quot; &quot; está activo. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| OpenID | delegado | Correo electrónico y UserId. Para iniciar sesión con el usuario para garantizar su consentimiento para el permiso de usar la aplicación Adobe Sign.  | El correo electrónico es el identificador único para los usuarios de Adobe Sign. Almacenamos el identificador de correo electrónico para poder asignar todas las actividades de ese usuario a su registro de Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| ReadWrite Document | Puede leer y realizar cambios en el documento |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nuestros registros contienen información suficiente para poder identificar y solucionar los problemas de los clientes. Los registros se conservan durante 90 días y el acceso está restringido. Nuestra base de datos almacena información de identificación hash para la autenticación mientras el usuario está sin conexión. La directiva de retención de bases de datos es de 30 días desde la última vez que se usó

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No tenemos ninguna interacción de administrador de clientes en nuestro sistema para Microsoft Teams aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Adobe Inc. ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- Flujo implícito de OAuth2, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
