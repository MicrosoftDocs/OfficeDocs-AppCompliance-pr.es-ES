---
title: Información de la aplicación para Asana de Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Asana, sus directivas de tratamiento de datos, su Microsoft Cloud App Security del catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 14ec3eee9b8ae673565ef91a017019d23d524619
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525884"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 2, 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Asana a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Asana |
| Id. | WA200001727 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Asana |
| Dirección URL del sitio web de partners | [https://asana.com](https://asana.com) |
| Dirección URL de la directiva de privacidad | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| DIRECCIÓN URL de términos de uso | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Asana sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| El complemento transfiere información básica de correo electrónico (remitente, recepient, asunto, cuerpo) y datos adjuntos a Asana cuando lo solicita el usuario. |  | Correo electrónico: lee el correo electrónico abierto actualmente cuando se muestra en un panel de tareas. - Lee los datos adjuntos de correo electrónico abiertos actualmente para cargarlos en tareas de Asana. - Esto proporciona a los usuarios la capacidad de realizar tareas rápidamente en Asana con información de correos electrónicos. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Nuestra aplicación solo registra información relacionada con los datos de Asana. La única vez que registramos cualquier cosa relacionada con la información de usuario de Outlook es cuando el usuario adjunta explícitamente un correo electrónico o carga datos adjuntos en Asana, e incluso entonces no registramos el contenido. Los registros a corto plazo existen en servidores que pueden incluir algunos datos de usuario, pero son efímeros y se limitan a períodos inferiores a 72 horas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Enterprise clientes tienen cifrado garantizado en reposo con AES-256. Los datos se almacenan en Amazon Web Services y AWS administra las claves de cifrado mediante su sistema de administración de claves. Tenemos 2FA para todos los administradores. El acceso se da en el principio de privilegios mínimos.
Los administradores de la organización de Asana tienen la capacidad de configurar SAML, SCIM, cuentas de servicio y tener una vista general de los datos que se ponen en la herramienta. Los administradores pueden solicitar una exportación organizativa completa desde la consola de administración y auditar según sea necesario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

