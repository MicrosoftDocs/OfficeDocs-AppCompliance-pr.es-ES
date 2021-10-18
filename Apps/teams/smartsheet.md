---
title: Información de la aplicación para Smartsheet por Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 11/11/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Smartsheet, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8bbe31189a44c240bc648670a0a04e0b5fce6ec
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429067"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Smartsheet a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Smartsheet |
| Id. | WA104380975 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Smartsheet |
| Dirección URL del sitio web de partners | [https://www.smartsheet.com](https://www.smartsheet.com) |
| Dirección URL de Teams de información de la aplicación | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| Dirección URL de la directiva de privacidad | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| DIRECCIÓN URL de términos de uso | [https://Default Acuerdo de usuario: https://www.smartsheet.com/.. .](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Smartsheet ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegado | Ninguno. | Permite que nuestra aplicación instale aplicaciones en nombre del usuario. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Directory.Read.All | delegado | tenantId para recuperar información que se mostrará en la interfaz de usuario. | Nos permite leer las aplicaciones que usa este inquilino para poder comprobar si necesitamos instalar la aplicación para ellas. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.Read.All | delegado | teamId/groupId para la entrega de mensajes. | Permite que nuestra aplicación lea información básica sobre un grupo (o Teams equipo) así como conversaciones. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.ReadWrite.All | delegado | teamId/groupId para la entrega de mensajes. | Permite que nuestra aplicación inicie nuevas conversaciones en equipos. Este permiso también incluye el ámbito Read.All anterior, pero también lo necesitamos por motivos técnicos. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| User.Read.All | delegado | userId. | Nos permite leer información básica sobre un usuario durante el proceso de autenticación. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| offline_access | delegado | refreshToken. | Permite que nuestra aplicación reciba tokens de actualización y actualice el token de autenticación en nombre del usuario cuando use la aplicación. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API de Bot Framework | Sí | Usamos la API de Bot Framework para entregar mensajes como la aplicación para la aplicación de teams. Smartsheet almacena información de userId para realizar un seguimiento de con quién está hablando el bot de Smartsheet. |  | None |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Smartsheet almacena información en un estado cifrado en reposo dentro de nuestro entorno de centro de datos de producción hospedado con Equinix y en AWS S3, donde almacenamos datos adjuntos de clientes en cubos cifrados privados. |  | Usamos la API del marco de bots para entregar mensajes como la aplicación para la aplicación de teams. Smartsheet almacena información de userId para realizar un seguimiento de con quién está hablando el bot de Smartsheet. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Smartsheet lo usa para ayudar a realizar un seguimiento de quién habla el bot. Durante el flujo de autenticación inicial, creamos un registro bot para el usuario en el sistema de notificaciones de Smartsheet. | Para Smartsheet para Teams bot, almacenamos el correo electrónico del usuario y userId desde Teams para ayudar a realizar un seguimiento de con quién está hablando el bot.  Smartsheet almacena tenantIds para ayudar a enumerar grupos de los que el usuario forma parte en el directorio y groupIds para la entrega de mensajes. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Smartsheet cifra toda la información de usuario almacenada y nuestros administradores deben usar 2FA. Smartsheet funciona como un proveedor SaaS sin vista y, de forma predeterminada, no se revisa el contenido que los clientes eligen cargar o entrar en la plataforma.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

