---
title: Información de la aplicación para Zoho Sprints de Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Zoho Sprints, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ab4f76f0563b92d9e5ca6129ffba013069db37f1
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753140"
---
# <a name="zoho-sprints"></a>Zoho Sprints

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/153059f1-912e-45d6-a13a-037675d66974" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000188" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zoho Sprints |
| ID | WA200000188 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Zoho Corporation Private Limited |
| Dirección URL del sitio web de partners | [https://www.zoho.com/sprints/](https://www.zoho.com/sprints/) |
| Dirección URL de la directiva de privacidad | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD de aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | El id. de carpeta de alendar se almacena para sincronizar los contactos de Zoho Sprints con Microsoft &amp; viceversa. |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Contacts.ReadWrite | delegado | El identificador de carpeta de contactos se almacena para sincronizar los contactos. |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Files.Read.All | delegado |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| Files.Read.Selected | delegado | UserPrincipalName se almacena para la identificación del usuario. | Leer los archivos que el usuario selecciona | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| User.Read | delegado |  | Iniciar sesión y leer el perfil del usuario | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| User.ReadBasic.All | delegado |  | Permitir a los usuarios importar usuarios de Office365 a Zoho Sprints. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| correo electrónico | delegado |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |
>| offline_access | delegado |  | Mantener el acceso a los datos a los que se le ha concedido acceso | [f6d7187a-b437-4eca-bbc5-c1331609fe07](../azure/f6d7187a-b437-4eca-bbc5-c1331609fe07.md) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts en su lugar para buscar y alertar para corregir dichos datos que están visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El cliente puede seleccionar los datos que deben cifrarse mediante EAR (Cifrado en reposo) con restricciones de certaat. Las contraseñas se hasherán de forma predeterminada. El acceso lógico a los servidores se proporciona a través de una red &amp; dedicada aislada y está altamente protegido y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

