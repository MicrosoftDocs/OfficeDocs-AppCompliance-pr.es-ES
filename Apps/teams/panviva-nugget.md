---
title: Información de la aplicación para Nugget de Panviva
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
description: Toda la información de seguridad y cumplimiento disponible para Nugget, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 17eace1be8bdb102c76e72170fbfeca86519becc
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096333"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2020</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Panviva a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Nugget |
| Id. | WA200001737 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Panviva |
| Dirección URL del sitio web de partners | [https://www.panviva.com](https://www.panviva.com) |
| Dirección URL de la directiva de privacidad | [https://www.panviva.com/privacy-policy](https://www.panviva.com/privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Panviva ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí.
Teams id. de usuario se almacena: esto es necesario para que podamos recuperar información sobre el espacio empresarial en el que se encuentran y si el usuario es administrador o no.
Teams de organización: se almacena para que podamos recuperar los usuarios de un inquilino y recuperar los detalles de suscripción para ese inquilino en particular.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Usamos Azure CosmosDB para almacenar todos los datos de la aplicación. Para obtener acceso a los datos, necesita un punto de conexión y una clave, que se insertan en el servicio de configuración que se usa para obtener acceso a los datos. El servicio de configuración solo controla las solicitudes con un token portador que recibe en la solicitud de nuestro servicio de aplicaciones de bot. Okta creó originalmente este token cuando un usuario inicia sesión en el bot en la interfaz de equipo. A estos datos pueden acceder los administradores de Panviva que necesitan iniciar sesión en la plataforma Microsoft Azure con el uso de la autenticación de 2 factores. El correo electrónico y el nombre de usuario se almacenan en OKTA y solo se puede acceder a él con una clave privada que se almacena en un almacén de claves al que el servicio de configuración accede a continuación. Solo el servicio de configuración tiene acceso al almacén de claves mediante el uso de identidades administradas para que no se almacenen credenciales en la aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

