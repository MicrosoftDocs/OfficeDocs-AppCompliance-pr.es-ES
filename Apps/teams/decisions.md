---
title: Información de aplicación para decisiones por decisiones
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Decisiones, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 99e01d0ad5874c62f51a3f78b5b612766f397ea1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415147"
---
# <a name="decisions"></a>Decisions

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Decisions a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Decisions |
| Id. | WA104381880 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Decisions |
| Dirección URL del sitio web de partners | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| Dirección URL de la directiva de privacidad | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Decisions acerca de cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Se usa para leer información del calendario&#8217;usuario para habilitar características como la lista de reuniones y la búsqueda. También ofrece al usuario la opción de eliminar reuniones específicas del calendario cuando el elemento se elimina de Decisions. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | delegado | Se usa para enviar decisiones para votar y crear listas de orador para elementos de la agenda individuales directamente al chat de Microsoft Teams reunión. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | delegado | Se usa para recopilar información básica sobre el Office 365 inquilino cuando se registra, como el nombre del inquilino y los dominios comprobados. También es necesario para comprobar las pertenencias a grupos. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | delegado | Se usa para leer archivos que se comparten con el usuario con el fin de combinar esos archivos en el Libro de reuniones de PDF. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | delegado | Se usa para proporcionar a los usuarios compatibilidad con anotaciones de archivos personales. Los archivos anotados se almacenan de forma privada en el&#8217;de OneDrive para la Empresa. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | delegado | Se usa para crear estructuras de carpetas en Office 365 grupo&#8217;sitio SharePoint para agendas de reuniones, archivos relacionados y conversaciones de grupo.   Nota: Los usuarios de Decisiones nunca tendrán acceso a los recursos (por ejemplo, grupos) a los que aún no tengan acceso en el espacio empresarial de Office 365 organización. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | delegado | Se usa para permitir que los usuarios de Decisions envíen notificaciones a los participantes de la reunión, como actualizaciones de la agenda y vínculos a la reunión para coautores. Los correos electrónicos van a los participantes de la reunión o a la lista de distribución seleccionada por el propietario de la reunión. Todos los mensajes de correo electrónico y notificaciones enviados lo hacen activamente los usuarios de Decisions.  Nota: Esto no proporciona al usuario acceso a su bandeja de entrada a través de Decisions. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | delegado | Se usa para identificar las preferencias de idioma&#8217;usuario. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | delegado | Se usa para configurar blocs de notas privados para reuniones para tomar notas y preparar comentarios y preguntas. También permite que los minutos de reunión de grupo se almacenen en su bloc de notas OneNote, en caso de que el grupo opte por usar OneNote. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | delegado | Se usa para crear estructuras de carpetas en canales privados para información de reuniones. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | delegado | Se usa para sincronizar tareas y decisiones con Microsoft Planner. También permite a los usuarios exportar tareas y decisiones para Excel. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | delegado | Necesario para instalar mediante programación Decisions App en el chat. Esto es necesario antes de agregar la pestaña Decisiones para la experiencia en la reunión. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | delegado | Necesario para instalar mediante programación Decisions App en el chat. Esto es necesario antes de agregar la pestaña Decisiones para la experiencia en la reunión. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | delegado | Requerir agregar la pestaña En reunión/Canal en Teams. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | delegado | Necesario para comprobar si la pestaña está instalada o no. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | delegado | Se usa para mostrar el nombre y apellidos, la foto y la dirección de correo electrónico de los miembros del grupo y los participantes externos. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| perfil | delegado | Se usa para iniciar sesión. | Los datos del cliente se almacenan en el&#8217;de Office 365 cliente y que todos los datos del cliente se procesan solo en dispositivos del cliente. La base de datos Decisions solo mantiene referencias a objetos de los clientes Office 365 inquilino, no los datos reales. Para https://www.meetingdecisions.com/security-and-privacy obtener más información, consulte. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos proporcionados por el Cliente durante el uso del Software solo están disponibles para el cliente.  El servicio se entrega en Microsoft Office 365 Cloud Services y Microsoft Azure. Todos los datos del cliente se almacenan en el inquilino Microsoft Office 365 cliente. Todos los datos almacenados o procesados en el servicio son anónimos y no son rastreables para personas individuales. Por lo tanto, Decisions no almacenará, recopilará ni procesará datos personales en nombre del Cliente.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Decisions acerca de cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Todo |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

