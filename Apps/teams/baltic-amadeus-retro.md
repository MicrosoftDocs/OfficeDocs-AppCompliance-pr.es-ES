---
title: Información de aplicación para Retro de Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Retro, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2ccca5bd5160eb1772245841df037d2033f58881
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527626"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Baltic Amadeus a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Retro |
| Id. | WA200001892 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Baltic Amadeus |
| Dirección URL del sitio web de partners | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| Dirección URL de la directiva de privacidad | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| DIRECCIÓN URL de términos de uso | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Baltic Amadeus sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| La aplicación retro tiene su propia API web que no se considera un servicio de Microsoft. Como se mencionó anteriormente, almacena correo electrónico y Fullname para la identificación y los fines de presentación de contenido adecuados. Estos datos no se envían a ningún otro lugar. Además, Retro tiene una funcionalidad opcional para exportar datos de sprint al espacio de confluencia atlassiana. Para ello, el usuario debe escribir su nombre de usuario y contraseña de confluencia. Estos datos solo se usan para realizar solicitudes autenticadas a la api de confluencia en nombre del usuario y no se almacenan ni registran en ningún lugar. |  | Retro tiene su propia API web que también está registrada en azure. Para usarlo, el usuario debe autenticarse a través de Microsoft Identity Platform. El usuario debe autenticarse para que la aplicación Retro pueda servidor de contenido específico del usuario |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot tiene acceso a la lista para comprobar qué miembro se unió o abandonó el equipo. En función de esto, agrega o desactiva ese usuario del proyecto para que el usuario ya no se muestre en la lista de participantes de sprint. | El correo electrónico y FullName se vinculan y se almacenan en la base de datos. El correo electrónico se usa para la identificación del usuario con el fin de mostrar el contenido adecuado para el usuario que ha iniciado sesión. FullName se usa para mostrar las puproses, de modo que otros usuarios puedan saber para quién evalúan o escriben comentarios.  |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No. El único proceso que genera telemetría/registros en la aplicación retro es el registro de errores. Los registros de errores no incluyen EUII ni OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos se almacenan en la base de datos de sql Server de Azure. Se almacena a través de la aplicación Retro y el bot Retro.
De forma predeterminada, la base de datos sql de Azure tiene habilitado el cifrado de datos transparente.
La base de datos está bloqueada detrás de la autenticación básica.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

