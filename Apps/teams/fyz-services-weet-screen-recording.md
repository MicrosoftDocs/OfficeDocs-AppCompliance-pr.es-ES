---
title: Información de la aplicación para la grabación de pantalla de Weet por FYZ SERVICES
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para weet Screen Recording, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fa9dee24b0953351451c92c553ac4f6e6426d87d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413001"
---
# <a name="weet-screen-recording"></a>Weet Screen Recording

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f0c0f156-329e-4083-a1a7-89649407a31b" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003284" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por FYZ SERVICES a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Weet Screen Recording |
| Id. | WA200003284 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | FYZ SERVICES |
| Dirección URL del sitio web de partners | [https://weet.co](https://weet.co) |
| Dirección URL de Teams de información de la aplicación | [https://weet.co/weet-teams-integration/](https://weet.co/weet-teams-integration/) |
| Dirección URL de la directiva de privacidad | [https://weet.co/privacy-policy/](https://weet.co/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://weet.co/terms-of-service/](https://weet.co/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

FYZ SERVICES ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsAppInstallation.ReadWriteSelfForUser.All | delegado | Permitir detectar si la aplicación weet ya está instalada | sin almacén de datos | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| User.Read | delegado | No recopilamos datos, pero solo usamos el correo electrónico para ayudar al usuario con la característica de autocompleción | No almacenamos información sobre el usuario, solo usamos el correo electrónico para la autocompleción | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| User.ReadBasic.All | delegado | No recopilamos datos, pero solo usamos el correo electrónico para ayudar al usuario con la característica de autocompleción | No almacenamos información sobre el usuario, solo usamos el correo electrónico para la autocompleción | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| offline_access | delegado | No recopilamos datos, pero solo usamos el correo electrónico para ayudar al usuario con la característica de autocompleción | No almacenamos información sobre el usuario, solo usamos el correo electrónico para la autocompleción | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| OpenID | delegado | No recopilamos datos, pero solo usamos el correo electrónico para ayudar al usuario con la característica de autocompleción | No almacenamos información sobre el usuario, solo usamos el correo electrónico para la autocompleción | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| perfil | delegado | No recopilamos datos, pero solo usamos el correo electrónico para ayudar al usuario con la característica de autocompleción | No almacenamos información sobre el usuario, solo usamos el correo electrónico para la autocompleción | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |


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

>Puede solicitar la eliminación de su información personal. Si nos pide que eliminemos su información personal, respetaremos su solicitud y eliminaremos su información personal, sujeto a determinadas excepciones proporcionadas por la ley, como (pero no limitado a) el ejercicio por otro consumidor de su derecho a la libertad de expresión, nuestros requisitos de cumplimiento resultantes de una obligación legal o cualquier procesamiento que pueda ser necesario proteger contra actividades ilegales.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

FYZ SERVICES ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

