---
title: Información de la aplicación para Workbench Intelligence de Temporall
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Workbench Intelligence, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4aaa94f3a1319a2eb06e332e1f23d4c5a1f07439
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429027"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Temporall a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Workbench Intelligence |
| Id. | WA200002705 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Temporall |
| Dirección URL del sitio web de partners | [https://www.temporall.com](https://www.temporall.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| Dirección URL de la directiva de privacidad | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Temporall ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegado | Obtiene una lista de aplicaciones de teams instaladas para poder obtener el identificador de aplicación local del identificador externo conocido. | El identificador de la aplicación local. Necesario para poder identificar la aplicación cuando se instala en un inquilino diferente. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | aplicación | Nombre del &amp; id. de canal. Justificación: permitir que unirse o salir del canal sincronice la actividad del mensaje.  | El objeto de datos sin procesar devuelto al obtener canal. Justificación: Temporall Workbench permite a los usuarios filtrar y clasificar los datos según los canales. Estos datos sin procesar se guardan para tener referencia al objeto original | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | aplicación | El tipo de actividad &amp; de mensaje, junto con el destino del &amp; remitente. Datos recibidos de estas rutas: /teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}. Justificación: para poder calcular el informe de &amp; métricas sobre la actividad del mensaje. Esto constituye el núcleo de nuestro módulo de análisis de red organizativa para poder dibujar un diagrama de actividad entre equipos de &amp; usuarios. | Detectamos la cantidad de mensajes/respuestas/reacciones/menciones nuevos almacenamos estas métricas junto con &amp; el objeto de mensaje sin procesar devuelto. Los datos son necesarios, ya que forman parte de nuestras características principales. Ejecutar el análisis en los datos del mensaje requiere que se guarde en la base de datos para obtener un rendimiento óptimo, lo que también reduce la necesidad de realizar llamadas de seguimiento para los mismos datos | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | aplicación | ClientId, Lista de usuarios, lista de organizaciones y sub canales. Justificación: necesario para leer &amp; la sincronización de usuarios con Temporall Workbench | Nombre de usuario, Correo electrónico, Icono, Referencia de conversación. Justification:&#160;Temporall Workbench permite a los usuarios filtrar y clasificar los datos según los canales. Los datos de la organización se almacenan para volver a conectarse a los equipos después de la instalación | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | aplicación | Nombre del &amp; id. de grupo. Justificación: para instalar la aplicación en cada grupo o canal | Nombre de &amp; id. de grupo junto con el objeto de datos sin procesar de referencia. Justificación: Temporall Workbench permite a los usuarios filtrar y clasificar los datos según grupos o equipos. Estos datos sin procesar se guardan para tener referencia al objeto original | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | aplicación | Pertenencia de usuario al equipo. Justificación: permite la sincronización de todos los usuarios Teams con Temporall Workbench | Dirección de correo electrónico, nombre y apellido. Justificación: permitir la coincidencia de usuarios en equipos con usuarios en Temporall Workbench para permitir la sincronización de usuarios por correo electrónico. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | aplicación | Lee la lista de aplicaciones instaladas para Team. Justificación: compruebe si nuestra aplicación ya está instalada de lo contrario la instala para poder obtener actividad de mensajes a través de la api de gráficos | N/D | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | aplicación | Lea la lista de aplicaciones instaladas. Comprueba si nuestra aplicación ya está instalada de lo contrario la instala para interactuar con el usuario a través de un cuestionario | N/D | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | delegado | Información básica de &amp; la empresa del usuario. Justificación: se usa para clasificar la actividad de mensajes por usuario, permite al bot participar en la mensajería proactiva. | Nombre de usuario, Correo electrónico, Icono, Referencia de conversación. Justificación: permite que nuestro bot envíe mensajes de forma proactiva a los usuarios con información relevante. Agrupar usuarios para mostrar datos | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | Información LDAP | Nuestra plataforma reside en la plataforma de Google Cloud |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Temporall ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
