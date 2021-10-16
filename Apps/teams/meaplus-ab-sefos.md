---
title: Información de la aplicación para SEFOS de Meaplus AB
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para SEFOS, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 14da720eee4a70152a3239d43154f0b47b0c56ea
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414556"
---
# <a name="sefos"></a>SEFOS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9b13f17-540f-4b08-a48c-75051b68677e" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003219" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Meaplus AB a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | SEFOS |
| Id. | WA200003219 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Meaplus AB |
| Dirección URL del sitio web de partners | [https://www.meaplus.com](https://www.meaplus.com) |
| Dirección URL de Teams de información de la aplicación | [https://sefos.se/en/sefos-i-teams/](https://sefos.se/en/sefos-i-teams/) |
| Dirección URL de la directiva de privacidad | [https://www.meaplus.com/privacy-policy/](https://www.meaplus.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-...](https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-end_user_agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Meaplus AB ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Crear reunión en nombre del usuario | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| Mail.Send | delegado | Envío de invitaciones a reuniones | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| MailboxSettings.Read | delegado | Recopilar zona horaria para el usuario autenticado | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| People.Read | delegado | Buscar en un libro de instrucciones de usuario autenticado | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| User.Read | delegado | Iniciar sesión y leer el perfil del usuario | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| email | delegado | Dirección de correo electrónico para identificar al usuario en SEFOS. | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| OpenID | delegado | Iniciar sesión del usuario | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| perfil | delegado | Leer perfil de usuario | ninguno | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |


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

>No es aplicable, se trata de un sistema distribuido donde cada organización controla su propia información en una instalación local. . 

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Meaplus AB ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

