---
title: Información de aplicaciones para myOKR por SOE Technologies
ms.author: elmalova
author: elenamalova
ms.date: 10/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para myOKR, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 71c27d24b0f93cafa4f899e845c8d056a55721eb
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434549"
---
# <a name="myokr"></a>myOKR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c0b70874-2c95-4be7-a0cb-0d893e25a2a3" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003308" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por SOE Technologies a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | myOKR |
| Id. | WA200003308 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | SOE Technologies |
| Dirección URL del sitio web de partners | [https://www.myokr.co](https://www.myokr.co) |
| Dirección URL de Teams de información de la aplicación | [https://www.myokr.co](https://www.myokr.co) |
| Dirección URL de la directiva de privacidad | [https://www.myokr.co/privacy](https://www.myokr.co/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.myokr.co/terms](https://www.myokr.co/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

SOE Technologies ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Obtener detalles del calendario de usuario para crear una reunión 1:1 en el calendario de usuario, actualizar o eliminar creada por la plataforma myOKR y mostrar franjas horarias libres | Almacenamos el identificador de calendario creado y la dirección URL de unión en la base de datos para las reuniones creadas en la plataforma myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read | delegado | Usamos el id. de objeto de azure del usuario para hacer que el usuario inicie sesión en la aplicación myOKR con la autenticación de Microsoft en el correo electrónico | correo electrónico del usuario e id. de objeto activo de Azure | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read.All | aplicación | Sincronice la información de usuario con la plataforma myOKR y muestre el análisis de aplicaciones de myOKR al administrador en función de varios recortes de usuario, como la ubicación, el jefe de &amp; departamento | Almacenamos el identificador de usuario, el nombre, el correo electrónico, el departamento, el título y la información del administrador en el sistema myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| offline_access | delegado | Id. de usuario de Azure Active Directory | Usamos el acceso sin conexión para crear reuniones periódicas en el calendario de usuario | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| OpenID | delegado | Usamos el id. de objeto de azure del usuario para hacer que el usuario inicie sesión en la aplicación myOKR con la autenticación de Microsoft | El id. de Azure activo del usuario se almacena en el correo electrónico | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El id. de Active Azure Directory de usuario se almacena en el correo electrónico del usuario para enviar mensajes proactivos por el bot. | Correo electrónico, nombre, información del administrador, título, id. Azure Active Directory usuario  | Esta información se usa en la aplicación myOKR para crear una cuenta de usuario, permitir al administrador ver sus detalles de reporte en platfrom, permitir que el administrador vea análisis e informes generales en función del departamento, la ubicación y el administrador. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El SPOC de la organización nos comunica para el cierre del servicio y sus datos se eliminan 30 días después de la intimación y se revierte de las copia de seguridad de la base de datos después de 30 días adicionales.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

SOE Technologies ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
