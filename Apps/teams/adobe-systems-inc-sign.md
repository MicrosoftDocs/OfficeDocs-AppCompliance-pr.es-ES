---
title: Información de la aplicación Adobe Sign de Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para Adobe Sign, sus políticas de gestión de datos, su Microsoft Cloud App Security información de catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7cb238a768ae020e13865748be5d0df96ebb35ca
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552431"
---
# <a name="adobe-sign"></a>Adobe Sign

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 1 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/0f56a9d1-f502-40f9-a9e8-816d7adbb68b" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381233" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Adobe Systems Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Adobe Sign |
| ID | WA104381233 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Adobe Systems Inc. |
| URL del sitio web de socios | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| URL de Teams página de información de la aplicación | [https://helpx.adobe.com/sign/help/adobesign_microsoft_teams...](https://helpx.adobe.com/sign/help/adobesign_microsoft_teams.html) |
| URL de la Política de Privacidad | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL de los Términos de uso | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Adobe Systems Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Delegado | Para rellenar el documento adjunto, los correos electrónicos del remitente y del receptor y el contenido del mensaje de los correos electrónicos a Adobe, para enviarlo a la firma. Esto es para ahorrar tiempo al usuario para reescribir esos campos en Adobe Sign. Después de firmar un acuerdo, redactamos automáticamente un nuevo correo electrónico para que el usuario envíe un correo electrónico para informar a sus destinatarios de que la transacción está realizada. | Adobe Sign guardará los archivos adjuntos como archivos temporales, que tienen una expiración de 24 horas. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| People.Read | Delegado | Para rellenar automáticamente la dirección de correo electrónico en la &quot; experiencia Enviar para &quot; firma, escribiendo algunas letras iniciales, no es necesario que los usuarios escriban todos los correos electrónicos. | Adobe Sign solo almacenará el correo electrónico y el displayName de los destinatarios en los acuerdos. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| User.Read | Delegado | Para leer el perfil de usuario y hacer coincidir su perfil (básicamente, su correo electrónico y userId) en nuestra base de datos para que puedan utilizar Adobe Sign. | Para leer el perfil de usuario y hacer coincidir su perfil (básicamente, su correo electrónico y userId) en nuestra base de datos para que puedan utilizar Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| offline_access | Delegado | Para actualizar el token de acceso, cuando el actual ha caducado. Por ejemplo, cuando el usuario está en un &quot; envío para la ventana de firma y lo deja inactivo durante demasiado &quot; tiempo, necesitamos actualizar un nuevo token para mantener al usuario activo | Para actualizar el token de acceso, cuando el actual ha caducado. Por ejemplo, cuando el usuario está en una &quot; ventana de envío para la firma y la deja &quot; inactiva durante demasiado tiempo, necesitamos actualizar un nuevo token para mantener activo al usuario.. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| OpenID | Delegado | Correo electrónico y UserId. Para iniciar sesión con el usuario para garantizar su consentimiento para obtener el permiso de uso de la aplicación Adobe Sign.  | El correo electrónico es el identificador único para los usuarios de Adobe Sign. Almacenamos el ID de correo electrónico para que podamos asignar todas las actividades de ese usuario a su registro de Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Teams API | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para la personalización de mensajes de chat y autenticación | UserPrincipalName, nombre, correo electrónico y objectId | Almacenamos esta información para la personalización de respuestas asincrónicas y propósitos de autenticación |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Nuestros registros contienen suficiente información para poder identificar y solucionar problemas con el cliente. Los registros se conservan durante 90 días y el acceso está restringido. Nuestro almacén de bases de datos hashed información de identificación para la autenticación mientras el usuario está fuera de línea. La directiva de retención de bases de datos es de 30 días desde el último uso

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>No tenemos ninguna interacción de administración de clientes en nuestro sistema para Microsoft Teams aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Adobe Systems Inc. ha proporcionado esta información sobre cómo esta aplicación gestiona la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
