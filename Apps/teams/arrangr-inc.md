---
title: Información de la aplicación para Arrangr by Arrangr, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Arrangr, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f4a5df023e906ad18e260debe09953351210d5bc
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427872"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Arrangr, Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Arrangr |
| Id. | WA200002975 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Arrangr, Inc. |
| Dirección URL del sitio web de partners | [https://arrangr.com](https://arrangr.com) |
| Dirección URL de Teams de información de la aplicación | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| Dirección URL de la directiva de privacidad | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| DIRECCIÓN URL de términos de uso | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Arrangr, Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Recopilamos nombres de calendarios de usuario y detalles sobre sus eventos de calendario para facilitar la programación de reuniones. | Almacenamos los nombres de los calendarios que han conectado, para que puedan ver y cambiar los calendarios que han conectado. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | delegado | Recopila una lista de canales disponibles para el usuario, de modo que podamos mostrarles una lista de sus canales para que elijan uno en el que compartir una invitación de Arrangr. | No almacenamos información en los canales del usuario | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | delegado | Este permiso se usa para enviar invitaciones de Arrangr a canales de equipo en nombre del usuario. No se usa para recopilar datos. | No se almacenan datos recopilados con este permiso. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | delegado | Este permiso se usa para enviar invitaciones de Arrangr a un Teams chat en nombre del usuario. Este permiso no se usa para recopilar datos. | No se almacenan datos recopilados con este permiso. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | delegado | Este permiso se usa para enviar invitaciones de Arrangr a chats de grupo y 1:1 en nombre del usuario. No se usa para recopilar datos. | No se almacenan datos recopilados con este permiso. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | delegado | Arrangr recopila Microsoft Teams de reunión en el proceso de generarlos con este permiso. Generamos Teams reuniones en nombre del usuario para que puedan organizar Teams llamadas en Arrangr. | Almacenamos los vínculos de reunión para que se puedan compartir con las partes correspondientes para unirse a la reunión. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | delegado | Recopilamos nombres y correos electrónicos de personas relevantes para el usuario. Esto es para que podamos facilitar al usuario seleccionarlos como destinatarios de las invitaciones de Arrangr. | Si el usuario termina seleccionando un destinatario ofrecido a través de esta API, guardamos el nombre y el correo electrónico de ese destinatario para llevar a cabo la reunión y para facilitar que el usuario pueda seleccionarlos de nuevo como destinatario en el futuro. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | delegado | Recopilamos los nombres del Teams del usuario, para que puedan seleccionar en qué Teams quieren conectarse a Arrangr y en qué equipo desean compartir una invitación de Arrangr. | Arrangr almacena los nombres de Teams que el usuario ha elegido vincular a Arrangr, de modo que podamos mostrar esos Teams en su configuración y permitir que seleccionen de esos Teams al decidir dónde compartir una invitación de Arrangr. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegado | Leemos si nuestra aplicación se ha instalado o no en la cuenta de Teams del usuario, de modo que podamos preguntarles si quieren instalar nuestra aplicación y para que podamos instalarla para ellos. | No almacenamos los datos recopilados a través de este permiso. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| perfil | delegado | Nombre y dirección de correo electrónico | Nombre y dirección de correo electrónico, con el fin de mostrar al usuario qué cuenta se ha conectado a nuestro servicio. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | Sí | Nombre, correo electrónico, nombres de calendario, información de eventos de calendario | Recopilamos esta información para permitir a los usuarios conectar su calendario a Arrangr para facilitar la programación de reuniones | Nombre, correo electrónico, nombres de calendario | Almacenamos esta información para que podamos mostrar a los usuarios qué cuentas y calendarios se han conectado a nuestro servicio |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | Google Cloud almacena todos los datos de usuario, nombres de usuario y correos electrónicos que se comparten con SendGrid para enviar correo electrónico a los usuarios, nombres de usuario de Stripe recibidos, correos electrónicos e información de pago para procesar pagos. Quaderno recibe nombres de usuario, correos electrónicos e información geográfica para ayudar con el cumplimiento de impuestos de ventas. | Google Cloud es necesario para almacenar datos para recordar a los usuarios y proporcionar la información que han elegido almacenar en Arrangr. Para enviar correos electrónicos a nuestros usos, debemos proporcionar sus direcciones de correo electrónico a SendGrid. Para recopilar pagos, debemos procesar su información de pago en Stripe, pero no almacenamos su información de pago en nuestros propios servidores. Quaderno es necesario para calcular los impuestos de ventas y asegurarnos de que cumplimos con las normativas de impuestos de ventas. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Los usuarios usarán nuestra extensión de mensajería para programar reuniones con otros usuarios. Debemos mostrar al usuario la cuenta en la que ha iniciado sesión y debemos poder asociar la invitación que envían con el usuario de Arrangr correcto. | Nombres de usuario, correos electrónicos e información de comunicación. | Esta información es necesaria para coordinar reuniones entre varias partes y compartir con los detalles para conectarse y con quién se reúnen. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Controlamos los datos almacenados en Google Cloud Datastore a través de su API y podemos eliminar los datos que necesitemos. Nuestros usuarios pueden solicitar la eliminación de sus cuentas y la eliminación de sus datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Arrangr, Inc. ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
