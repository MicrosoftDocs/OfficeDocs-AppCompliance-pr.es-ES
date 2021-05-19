---
title: Información de solicitud para Medxnote MT por Medxnote
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Medxnote MT, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eca02f06a34c5a4d815bd2087826567cf4be27d6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551971"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 28 de septiembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Medxnote a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Medxnote MT |
| ID | WA200001823 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Medxnote |
| URL del sitio web de socios | [https://medxnote.com](https://medxnote.com) |
| URL de la Política de Privacidad | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| URL de los Términos de uso | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Medxnote ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read.All | aplicación | estamos en caché Nombre y correo electrónico, utilizado en el lado del hospital para comprobar los privilegios de los usuarios | al enviar mensajes algunas veces se agrega nombre y dirección de correo electrónico, estamos almacenamiento en caché que los datos en el lado del servidor, se utiliza también para la comprobación de privilegios opcional en el lado del hospital | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |
>| OpenID | Delegado | estamos registrando id de sesión, id de usuario, token portador y correo electrónico, utilizado para iniciar sesión a los usuarios en el módulo tarea | usarlo para iniciar sesión en los usuarios en el módulo Tarea, estamos almacenando id de sesión, userid, correo electrónico, tokens portadores | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>dirección de correo electrónico, nombre, identificador de inquilino, identificador de canal pueden aparecer en los registros Todos los datos de registro se eliminan automáticamente después de 1 mes como muy tarde.
El acceso a estos está restringido a un puñado de administradores de la organización que tienen acceso forzado a 2FA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>El acceso está restringido a un puñado de administradores de la organización que tienen acceso forzado a 2FA.
sólo se puede acceder a los sistemas críticos desde ciertas direcciones IP

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

