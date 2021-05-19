---
title: Información de la aplicación para la llamada de Webex por Cisco
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Webex Call, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8cd5499529eb41a5a840c9a7792e9b47f9a6c877
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552291"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 4 de enero de 2021</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Cisco a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Webex Call |
| ID | WA200001495 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Cisco |
| URL del sitio web de socios | [https://www.cisco.com/c/en/us/solutions/collaboration/webex...](https://www.cisco.com/c/en/us/solutions/collaboration/webex-teams.html) |
| URL de Teams página de información de la aplicación | [N/D](N/A) |
| URL de la Política de Privacidad | [https://www.cisco.com/c/en/us/about/legal/privacy-full.html](https://www.cisco.com/c/en/us/about/legal/privacy-full.html) |
| URL de los Términos de uso | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por Cisco sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que la aplicación recopila.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.Read | Delegado | Obtener miembros de chat para poder llamar al otro miembro en chat privado con Cisco WebEx | La aplicación NO almacenaría ningún dato en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| Contacts.Read | Delegado | Obtenga contactos de usuario, para que el usuario pueda llamar a contactos con Cisco WebEx | La aplicación NO almacenaría ningún dato en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.Read | Delegado | obtener correo electrónico del usuario, teléfonos para que pudieran lanzar Cisco WebEx para llamar al correo electrónico o a los teléfonos | La aplicación NO almacenaría ningún dato en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadBasic.All | Delegado | obtener correo electrónico del usuario, teléfonos para que pudieran lanzar Cisco WebEx para llamar al correo electrónico o a los teléfonos | La aplicación NO almacenaría ningún dato en sus bases de datos | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadWrite | Delegado | Este permiso es almacenar información de marcación rápida a la extensión de usuario | La aplicación NO almacenaría ningún dato en sus bases de datos  | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Esta extensión de mensaje leería el correo electrónico / teléfonos de los miembros del chat para que el usuario pudiera llamarlos con Cisco WebEx | No |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No aparece ninguna OII o EUII en la telemetría o registros de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Esta aplicación no almacenaba ningún dato de usuario

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Cisco sobre cómo esta aplicación maneja la autenticación, la autorización, las mejores prácticas del registro de la aplicación, y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
