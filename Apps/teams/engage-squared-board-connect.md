---
title: Información de la aplicación para la Conectar por Engage Squared
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para board Conectar, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 52e165955fa07fb7720edaf33156c15b179f551c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429167"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Engage Squared a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Board Connect |
| Id. | WA200001955 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Engage Squared |
| Dirección URL del sitio web de partners | [https://engagesq.com](https://engagesq.com) |
| Dirección URL de Teams de información de la aplicación | [https://boardconnect.app](https://boardconnect.app) |
| Dirección URL de la directiva de privacidad | [https://boardconnect.app/privacy/](https://boardconnect.app/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Engage Squared ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Para permitir que la aplicación actualice los calendarios de los usuarios para reflejar las respuestas de asistencia a la reunión del directorio enviadas a través de la aplicación. | No hay datos almacenados en nuestro almacenamiento de tablas de Azure | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Group.ReadWrite.All | delegado | Para permitir que la aplicación cree, actualice y elimine eventos de calendario de grupo. | Almacenamos el identificador del grupo, junto con el identificador de inquilino: se almacena y se usa desde una perspectiva de licencia para que podamos validar que la organización tiene licencia para la administración Conectar. También lo usamos para realizar un seguimiento de cuántas instalaciones de las aplicaciones hay en el espacio empresarial, ya que esto está en línea con nuestro modelo de licencias | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Sites.Manage.All | delegado | Para permitir que la aplicación cree listas y bibliotecas, administre elementos de lista y administre documentos en una colección de sitios de grupo. | Ninguno | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.Read | delegado | Para permitir que los usuarios inicien sesión en la aplicación y permitir que la aplicación lea el perfil del usuario que ha iniciado sesión actualmente. | No se almacenan datos de este punto de conexión en el almacenamiento de tablas de Azure | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.ReadBasic.All | delegado | Para que la aplicación lea un conjunto básico de propiedades de perfil de otros usuarios en nombre del usuario que ha iniciado sesión, para mostrarlo en la aplicación. Esto incluye el nombre para mostrar, el nombre y el apellido, la dirección de correo electrónico y la foto. | Ninguno, los datos no se almacenan en nuestro almacenamiento de tablas de Azure | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| offline_access | delegado | Para habilitar la aplicación para obtener un token de actualización, que puede usar para obtener un nuevo token de acceso cuando expire el actual. | Ninguno, los datos no se almacenan en nuestro almacenamiento de tablas de Azure | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |


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

>2FA para todos los administradores, solo pueden acceder dos usuarios al cuadrado

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Engage Squared ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
