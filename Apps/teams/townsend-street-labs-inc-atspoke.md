---
title: Información de la aplicación para atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para atSpoke, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551200"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Townsend Street Labs, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | atSpoke |
| ID | WA200001454 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Townsend Street Labs, Inc. |
| Dirección URL del sitio web de partners | [https://www.atspoke.com](https://www.atspoke.com) |
| Dirección URL de la directiva de privacidad | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Townsend Street Labs, Inc. sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegado | atSpoke almacena el identificador de grupo de Microsoft | Permite la capacidad de leer y escribir información de grupo entre atSpoke y Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | delegado | atSpoke almacena el correo electrónico del usuario y el id. de usuario | Permite la capacidad de leer y escribir información de usuario entre atSpoke y Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | delegado | atSpoke no almacena ningún dato para esto. | Esto se usa para la sincronización en segundo plano. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sí, usamos servicios de terceros para la eficiencia operativa. Google, Inc.: datos almacenados en volúmenes lógicos, copias de seguridad de almacenamiento en la red nativa de Google Cloud, registros de api y servicio o registros de aplicaciones. Los eventos transaccionales registrados pueden contener identificadores de usuario, información de contacto y contenido del cliente. MongoDB, Inc.: datos almacenados en colecciones de bases de datos basadas en la nube. - Contenido del cliente que incluye solicitudes de los usuarios, respuestas a solicitudes agregadas por usuarios y artículos de conocimientos agregados por los usuarios. - Identificadores de usuario (nombre, correo electrónico, avatar y número de teléfono usados para crear una cuenta de usuario spoke). Mailgun Technologies, Inc.: Identificador de usuario e información de contacto para enviar comunicaciones por correo electrónico (es decir, nombre y correo electrónico). Twilio, Inc.: Número de teléfono de usuario y contenido del cliente: contenido intercambiado mediante el uso de los Servicios de Twilio&#8217;, como texto, cuerpos de mensajes, medios de voz y vídeo, imágenes y sonido. Mixpanel, Inc.: Los datos personales transferidos incluyen el nombre, el correo electrónico, la dirección IP y los datos personales incluidos en el contenido del mensaje. Cloudinary, Inc.: Contenido de cliente basado en archivos enviado por los usuarios finales. Elasticsearch, Inc.: Los eventos transaccionales de aplicación registrados pueden contener texto truncado del contenido del cliente. Stitch, Inc.: información de contacto, información de uso, identificadores no tradicionales de los usuarios autorizados del suscriptor y cualquier otro dato personal que el suscriptor o sus usuarios autorizados envíen a la Plataforma. Mode Analytics, Inc.: información de identificadores de usuario para proporcionar análisis por usuario. DataDog: los eventos transaccionales de la aplicación registrados pueden contener texto truncado del contenido del cliente; la retención de registros es de 14 días. Fullstory, Inc.: grabaciones de acciones realizadas en nuestra interfaz de usuario web; incluye la cuenta de usuario de Spoke con fines de identificación. |  | Estamos usando la API de REST de Bot Framework. Usamos esta API para enviar y recibir mensajes al servicio de bot askSpoke. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Permite a atSpoke sincronizar usuarios desde Microsoft Teams para crear usuarios y definir permisos. | atSpoke solo almacena el correo electrónico para que Microsoft Teams usuarios puedan iniciar sesión en atSpoke como un usuario válido. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>En nuestros registros de aplicaciones, hay el nombre y apellidos de un usuario, la dirección de correo electrónico del usuario y el identificador de objeto asignado de Azure para usuarios y grupos. Los registros solo se conservan durante 14 días en los que expiran automáticamente. El acceso al registro está protegido contra la manipulación y solo determinados empleados tienen acceso para ver los registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de la aplicación se almacenan en una instancia de MongoDB administrada. El acceso al servicio administrado Atlas MongoDB Database se aprovisiona a través de un proceso de solicitud de acceso de usuario estandarizado que requiere aprobaciones. Las revisiones periódicas de acceso de usuario se realizan con el cierre de sesión de administración. Restringimos el número de personal con acceso a datos confidenciales de clientes y no permitimos modificar los datos de ninguna máquina directamente.&#8232; El acceso remoto a esta base de datos requiere autenticación multifactor. La base de datos y todas las copias de seguridad se cifran en reposo mediante cifrado de AES-256 bits.


#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

