---
title: Información de la aplicación para Senso por Senso
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Senso, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c517e652c97ba8a74cbadd9b6121084dd40c5394
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414466"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Senso a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Senso |
| Id. | WA200002571 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Senso |
| Dirección URL del sitio web de partners | [https://www.senso.cloud](https://www.senso.cloud) |
| Dirección URL de Teams de información de la aplicación | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| Dirección URL de la directiva de privacidad | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Senso ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | aplicación | Lea los nombres y descripciones de canales de todos los canales para identificar dónde se marcó una infracción.   | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | aplicación | Lea la lista de miembros y los mensajes de chat de todos los canales. | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | aplicación | Leer todos los mensajes de canal | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | aplicación | Leer todos los mensajes de chat | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | aplicación | Leer datos de directorio | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | aplicación | Leer archivos en todas las colecciones de sitios | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | delegado | Iniciar sesión y leer el perfil del usuario | Se usa para inicio de sesión único | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | aplicación | Leer los perfiles completos de todos los usuarios | Cuando se produce una infracción, se registra el nombre del remitente (De), los nombres de los destinatarios (Para), el nombre del canal, la fecha, la hora y los mensajes de ese canal de chat para proporcionar contexto a una infracción.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud usa los siguientes subprocesadores para el rendimiento de su servicio: https://www.senso.cloud/privacy-policy/ Sección 5. Divulgación de sus datos personales. | Los tipos de datos que compartimos con cuentas de terceros y proveedores de terceros se establecen en la sección 5, columna derecha de la tabla ( https://www.senso.cloud/privacy-policy/) . | La base legal para procesar cada uno de ellos se basa en el cumplimiento de un contrato con usted o es necesario para nuestros intereses legítimos (para ejecutar nuestra empresa, archivar datos, proporcionar servicios de administración y TI, seguridad de red, para evitar fraudes e infracciones de datos. Por ejemplo, la dirección de correo electrónico de empresa, la dirección de correo electrónico es necesaria para enviar las notificaciones de contacto de facturación al cliente o, si se paga con tarjeta de crédito, se requiere información para generar un vale de soporte técnico cuando se accede al soporte técnico del cliente. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud usa los siguientes subprocesadores para el rendimiento de su servicio: https://www.senso.cloud/privacy-policy/ Sección 5. Divulgación de sus datos personales. | Los tipos de datos que compartimos con cuentas de terceros y proveedores de terceros se establecen en la sección 5, columna derecha de la tabla ( https://www.senso.cloud/privacy-policy/) . | La base legal para procesar cada uno de ellos se basa en el cumplimiento de un contrato con usted o es necesario para nuestros intereses legítimos (para ejecutar nuestra empresa, archivar datos, proporcionar servicios de administración y TI, seguridad de red, para evitar fraudes e infracciones de datos. Por ejemplo, la dirección de correo electrónico de empresa, la dirección de correo electrónico es necesaria para enviar las notificaciones de contacto de facturación al cliente o, si se paga con tarjeta de crédito, se requiere información para generar un vale de soporte técnico cuando se accede al soporte técnico del cliente. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Senso supervisa los mensajes de chat en las bibliotecas de detección de amenazas de imagen y palabras clave.  Si se produce una coincidencia, registramos la siguiente información en el desencadenador de infracción; Hora y fecha, Id. de sitio, Frase/Imagen, gravedad, From, To, Channel Name, Status y triggering Library para su revisión por parte del usuario final.  Solo conservaremos la PII durante el tiempo que sea necesario para cumplir con los fines para los que la recopilamos, incluso con el fin de satisfacer cualquier requisito legal, operativo, contable o de presentación de informes

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Acceso limitado a desarrolladores senior, IP bloqueada, autenticación de 2 factores y seguimientos de auditoría.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Senso ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Permisos de acceso basados en roles |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

