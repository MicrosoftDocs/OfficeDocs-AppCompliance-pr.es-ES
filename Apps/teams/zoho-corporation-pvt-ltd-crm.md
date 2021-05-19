---
title: Información de solicitud de Zoho CRM by Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Zoho CRM, sus políticas de gestión de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5448307eeccd20e77b25282f299b52b094077b82
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550510"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Pvt Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zoho CRM |
| ID | WA104382094 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Zoho Corporation Pvt Ltd |
| URL del sitio web de socios | [https://www.zoho.com/](https://www.zoho.com/) |
| URL de Teams página de información de la aplicación | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL de la Política de Privacidad | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL de los Términos de uso | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Zoho Corporation Pvt Ltd ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | El identificador de carpeta de calendario se almacena para sincronizar los contactos de Zoho CRM a Microsoft &amp; viceversa. Se almacena información de calendario como event_name, event_location, participant_details. | Permite al usuario sincronizar eventos de Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegado | El identificador de carpeta de contactos se almacena para sincronizar los contactos de Zoho CRM a Microsoft &amp; viceversa. Se almacena información de contacto como first_name, last_name, dirección de correo electrónico. | Permite al usuario sincronizar contactos de Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegado |  | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Delegado |  | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegado | UserPrincipalName se almacena para la identificación del usuario | Permite al usuario importar el archivo de Office365 a Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegado | Propiedades de usuario como first_name, last_name, dirección de correo electrónico. | Leer perfiles básicos de todos los usuarios | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegado | UserPrincipaName se almacena para la sangría del usuario | Ver la dirección de correo electrónico del usuario | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegado |  | Mantener el acceso a los datos a los que se le ha concedido acceso | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | Delegado |  | Ver el perfil básico del usuario | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts en su lugar para buscar y alertar para la fijación de dichos datos que sean visibles

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>El cliente puede seleccionar los datos que deben cifrarse a través de EAR (Cifrado en reposo) con restricciones de certaat. Las contraseñas se verán hash de forma predeterminada. El acceso lógico a los servidores se proporciona a través de una red dedicada aislada &amp; y está altamente protegido y


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

