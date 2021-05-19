---
title: Información de solicitud para Zoho Sign por Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Zoho Sign, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 356c8755ee40269ef4efe844d22ebbc20e53937d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552721"
---
# <a name="zoho-sign"></a>Zoho Sign

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/7a22873b-81e6-48ed-aee3-6f0e7dd5a104" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382011" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Zoho Corporation Private Limited a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Zoho Sign |
| ID | WA104382011 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Zoho Corporation Private Limited |
| URL del sitio web de socios | [https://zoho.com](https://zoho.com) |
| URL de Teams página de información de la aplicación | [https://www.zoho.com/sign/help/teams-extension.html](https://www.zoho.com/sign/help/teams-extension.html) |
| URL de la Política de Privacidad | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL de los Términos de uso | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Zoho Corporation Private Limited ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.ReadWrite | Delegado |  | Tener acceso completo a los contactos de usuario. |  |
>| Contacts.ReadWrite.Shared | Delegado |  | Leer y escribir contactos de usuario y compartidos. |  |
>| Files.ReadWrite | Delegado |  | Tener acceso completo a los archivos de usuario. |  |
>| Files.ReadWrite.All | Delegado |  | Tener acceso completo a todos los archivos a los que el usuario pueda acceder. |  |
>| Files.ReadWrite.Selected | Delegado |  | Leer y escribir archivos que el usuario selecciona. |  |
>| User.ReadBasic.All | Delegado |  | Lea todos los perfiles básicos del usuario. |  |
>| email | Delegado |  | Ver la dirección de correo electrónico del usuario. |  |
>| offline_access | Delegado |  | Mantenga el acceso a los datos a los que le ha dado acceso. |  |
>| perfil | Delegado |  | Ver el perfil básico del usuario. |  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No recopilamos EUII / PII en telemetría y registros. Tenemos scripts en su lugar para buscar y alertar para la fijación de dichos datos que sean visibles.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los clientes como controlador de datos tienen acceso a los datos todo el tiempo. Los administradores pueden agregar o eliminar usuarios de Zoho Sign. Podrán ver toda la información almacenada en la aplicación, incluidos los seguimientos completos de auditoría, los informes de uso. Pueden eliminar datos y usuarios, transferir el control de datos entre usuarios.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

