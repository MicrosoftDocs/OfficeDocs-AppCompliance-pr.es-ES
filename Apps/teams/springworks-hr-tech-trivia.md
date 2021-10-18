---
title: Información de la aplicación para Trivia de Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Trivia, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: cb6a1e4c70135aff7286824373b441cb2b045c60
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60445192"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Springworks HR Tech a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Trivia |
| Id. | WA200001956 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Springworks HR Tech |
| Dirección URL del sitio web de partners | [https://www.springworks.in](https://www.springworks.in) |
| Dirección URL de Teams de información de la aplicación | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| Dirección URL de la directiva de privacidad | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| DIRECCIÓN URL de términos de uso | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Springworks HR Tech ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | delegado | No | Para obtener la lista de Teams de la que el usuario forma parte | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Team.ReadBasic.All | delegado | Sí, almacenar la lista de equipos en los que se ha agregado el bot | Para recopilar información básica sobre todos los equipos presentes en un área de trabajo | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| User.Read.All | delegado | Sí, para almacenar un aadObjectId único de un usuario. También varios detalles del usuario como nombre de usuario, correo electrónico, etc. y mostrarlo en el panel de preguntas y respuestas | Para obtener los detalles de todos los usuarios presentes en un área de trabajo | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| OpenID | delegado | Sí, para almacenar los usuarios que inician sesión en la aplicación. |  Para permitir que el usuario use la aplicación con su cuenta y la aplicación para usar los datos del usuario | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| perfil | delegado | Sí, para almacenar los id. de usuario y los nombres de los hosts de cuestionarios y otras características, e identificarlos de forma única | Para leer la información básica del perfil del usuario, como nombre de usuario, correo electrónico | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Mailchimp, Stripe.  | Nombre del cliente, correo electrónico, IP, información de pago | Usamos estos terceros para proporcionar la mejor experiencia de cliente a nuestros clientes |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Estos datos se usan para mostrar y almacenar la lista de participantes en un cuestionario y otras características de este tipo | Nombre, correo electrónico | Sí, almacenar los datos del host y los participantes de cuestionarios y otras características para análisis y comunicación con el host en caso de errores |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>OII: el nombre de la organización, el identificador de inquilino aparecen en los registros; EUII: el id. de objeto de aad, el nombre completo, el correo electrónico aparecen en los registros. tenemos una publicación de período de retención de 30 días que los registros se eliminan automáticamente. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Datos almacenados en RDS, AWS. está cifrado. El acceso es solo a un ingeniero DevOps, jefe de ingeniería y fundador

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Springworks HR Tech ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
