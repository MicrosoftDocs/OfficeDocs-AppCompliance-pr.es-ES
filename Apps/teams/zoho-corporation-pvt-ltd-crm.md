---
title: Información de la aplicación para Zoho CRM de Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Zoho CRM, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4387faccb63299392acb23ab91f312d175d1524d
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251609"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Pvt Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zoho CRM |
| ID | WA104382094 |
| Capacidades | Bot, pestaña, extensión de mensajería |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Zoho Corporation Pvt Ltd |
| Dirección URL del sitio web de partners | [https://www.zoho.com/](https://www.zoho.com/) |
| Dirección URL de Teams de información de la aplicación | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| Dirección URL de la directiva de privacidad | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Zoho Corporation Pvt Ltd ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado | El identificador de carpeta de calendario se almacena para sincronizar los contactos de Zoho CRM con Microsoft &amp; viceversa. La información del calendario event_name, event_location, participant_details se almacenan. | Permite al usuario sincronizar eventos de Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | delegado | El identificador de carpeta de contactos se almacena para sincronizar los contactos de Zoho CRM con Microsoft &amp; viceversa. La información de contacto como first_name, last_name, dirección de correo electrónico se almacenan. | Permite al usuario sincronizar contactos de Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegado |  | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | delegado |  | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegado | UserPrincipalName se almacena para la identificación del usuario | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegado | Propiedades de usuario como first_name, last_name, dirección de correo electrónico. | Leer perfiles básicos de todos los usuarios | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegado | UserPrincipaName se almacena para la sangría del usuario | Ver la dirección de correo electrónico del usuario | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegado |  | Mantener el acceso a los datos a los que se le ha concedido acceso | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | delegado |  | Ver el perfil básico del usuario | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts para buscar y alertar para corregir los datos que están visibles

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>El cliente puede seleccionar los datos que deben cifrarse mediante EAR (Cifrado en reposo) con restricciones de certaat. Las contraseñas se hasherán de forma predeterminada. El acceso lógico a los servidores se proporciona a través de una red &amp; dedicada aislada y está altamente protegido y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

