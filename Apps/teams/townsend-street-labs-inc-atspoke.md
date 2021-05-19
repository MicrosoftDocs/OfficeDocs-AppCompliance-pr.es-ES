---
title: Información de solicitud de atSpoke por Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para atSpoke, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
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
<p>Última actualización por el desarrollador el: 3 de junio de 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Townsend Street Labs, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | atSpoke |
| ID | WA200001454 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Townsend Street Labs, Inc. |
| URL del sitio web de socios | [https://www.atspoke.com](https://www.atspoke.com) |
| URL de la Política de Privacidad | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL de los Términos de uso | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Townsend Street Labs, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegado | atSpoke almacena el ID de grupo de Microsoft | Permite la capacidad de leer y escribir información de grupo entre atSpoke y Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | Delegado | atSpoke almacena el correo electrónico del usuario y el ID de usuario | Permite la capacidad de leer y escribir información de usuario entre atSpoke y Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | Delegado | atSpoke no está almacenando ningún dato para esto. | Esto se utiliza para la sincronización en segundo plano. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sí, utilizamos servicios de terceros para la eficiencia operativa. Google, Inc.: Datos almacenados en volúmenes lógicos, copias de seguridad de almacenamiento en redes nativas de Google Cloud, registros de servicios y API o registros de aplicaciones. Los eventos transaccionales registrados pueden contener identificadores de usuario, información de contacto y contenido del cliente. MongoDB, Inc.: Datos almacenados en colecciones de bases de datos basadas en la nube. - Contenido del cliente que incluye solicitudes presentadas por los usuarios, respuestas a las solicitudes añadidas por los usuarios y artículos de conocimientos añadidos por los usuarios. - Identificadores de usuario (nombre, correo electrónico, avatar y número de teléfono utilizados para crear una cuenta de usuario spoke). Mailgun Technologies, Inc.: Identificador de usuario e información de contacto para enviar comunicaciones por correo electrónico (es decir, nombre y correo electrónico). Twilio, Inc.: Número de teléfono del usuario y contenido del cliente: contenido intercambiado mediante el uso de los Servicios de Twilio&#8217;s, como texto, cuerpos de mensajes, medios de voz y vídeo, imágenes y sonido. Mixpanel, Inc.: Los datos personales transferidos incluyen nombre, correo electrónico, dirección IP y datos personales incluidos en el contenido del mensaje. Cloudinary, Inc.: Contenido de cliente basado en archivos enviado por los usuarios finales. Elasticsearch, Inc.: Los eventos transaccionales de aplicaciones registradas pueden contener texto truncado del contenido del cliente. Stitch, Inc.: Información de contacto, información de uso, identificadores no tradicionales de los Usuarios Autorizados del Suscriptor y cualquier otro Dato Personal que el Suscriptor o sus Usuarios Autorizados envíen a la Plataforma. Mode Analytics, Inc.: Información de identificadores de usuario para proporcionar análisis por usuario. DataDog: Los eventos transaccionales de aplicaciones registradas pueden contener texto truncado del contenido del cliente; la retención de registros es de 14 días. Fullstory, Inc.: Grabaciones de acciones tomadas en nuestra interfaz de usuario web; incluye la cuenta de usuario de Spoke con fines de identificación. |  | Estamos usando bot framework REST API. Usamos esta API para enviar y recibir mensajes al servicio de bots askSpoke. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Permite a atSpoke sincronizar usuarios de Microsoft Teams para crear usuarios y definir permisos. | atSpoke solo almacena el correo electrónico para que Microsoft Teams usuarios puedan iniciar sesión en atSpoke como usuario válido. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Contenido en nuestros registros de aplicaciones, hay el nombre y apellidos de un usuario, la dirección de correo electrónico del usuario y el identificador de objeto asignado de Azure para usuarios y grupos. Los registros solo se conservan durante 14 días, momento en el que caducan automáticamente. El acceso de registro está protegido de la manipulación y solo cierto personal tiene acceso para ver los registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos de la aplicación se almacenan en una instancia administrada de MongoDB. El acceso al servicio administrado Atlas MongoDB Database se aprovisiona a través de un proceso estandarizado de solicitud de acceso de usuario que requiere aprobaciones. Las revisiones periódicas de acceso de los usuarios se realizan con la firma de administración. Restringimos el número de personal con acceso a datos confidenciales de los clientes y no permitimos modificar los datos de ninguna máquina directamente.&#8232; El acceso remoto a esta base de datos requiere autenticación multifactor. La base de datos y todas las copias de seguridad se cifran en reposo mediante cifrado de bits AES-256.


#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

