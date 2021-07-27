---
title: Información de aplicaciones para Berrycast por Technologies Openmind Inc, Les
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Berrycast, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 714db08e839b60403a567b2cab1af888c4cb7b6f
ms.sourcegitcommit: c545fba57f8ca821caf6ef55f5b4b068b5f35984
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/24/2021
ms.locfileid: "53578236"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Technologies Openmind Inc, Les a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Berrycast |
| Id. | WA200002798 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Technologies Openmind Inc, Les |
| Dirección URL del sitio web de partners | [https://www.berrycast.com](https://www.berrycast.com) |
| Dirección URL de la directiva de privacidad | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Technologies Openmind Inc, Les ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegado | Para obtener todos los contactos de usuario | El correo electrónico de contactos, el nombre del puño, el apellido y la imagen se almacenan para dar acceso compartido rápido a los registros | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| User.Read | delegado | Para identificar al usuario con información básica (nombre y apellido e imagen) | Para mostrar el nombre. apellido e imagen en la aplicación | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| email | delegado | Para identificar al usuario | Para identificar al usuario para el registro y el envío de notificaciones | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| offline_access | delegado | Mantener el acceso a los datos a los que se le ha concedido acceso | N/D | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| OpenID | delegado | Para identificar al usuario | Para identificar al usuario para el registro | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, Intercom, MixPanel, Amplitude | correo electrónico, identificación única del usuario, nombre, apellido  | Procesar el pago seguro, realizar campañas de marketing, tener un servicio de atención al cliente eficaz y realizar un seguimiento del análisis del usuario para mejorar el producto |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Correo electrónico, nombre, apellido y quitamos todos los datos si el usuario elimina su cuenta 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Eliminamos todos los datos relacionados con un usuario si elimina su cuenta.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Technologies Openmind Inc, Les ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
