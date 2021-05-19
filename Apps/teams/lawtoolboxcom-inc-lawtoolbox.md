---
title: Información de solicitud de LawToolBox by LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para LawToolBox, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553011"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por LawToolBox.com Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | LawToolBox |
| ID | WA104381656 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | LawToolBox.com Inc. |
| URL del sitio web de socios | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL de Teams página de información de la aplicación | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL de la Política de Privacidad | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL de los Términos de uso | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

LawToolBox.com Inc. ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegado |  | [Opcional] Lea el calendario del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | Delegado |  | Para crear una invitación de calendario al calendario del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | Delegado |  | Para crear la invitación de calendario en el calendario compartido. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | Delegado |  | [Opcional]- para leer contactos de usuario y conectar usuarios de lista de contactos a grupo. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | Delegado |  | [Opcional]- leer los contactos compartidos de los usuarios para servir la lista de contactos relevantes para el caso. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | Delegado |  | [Opcional] Lea la información de grupos y usuarios como usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | Delegado |  | [Opcional] Lea la información de grupos y usuarios como usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | Delegado |  | [Opcional] Lea la OneDrive del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | Delegado |  | [Opcional]-Leer OneDrive del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | Delegado |  | [Opcional]-Leer y modificar archivos en la OneDrive de un usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | Delegado |  | [Opcional] OneDrive archivo de OneDrive del usuario asociado a la materia. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | Delegado | GroupID, GroupName, GroupEmail | Creamos un Grupo para cada materia creada en nuestro sistema. Esto ayuda al usuario a almacena información relacionada con la materia en el grupo, que a su vez guarda sus datos en su propio inquilino. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | Delegado |  | [Opcional] [InProgress] Lea el correo electrónico del usuario para Asuntos. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | Delegado |  | [Opcional] [InProgress] Leer/Escribir correo electrónico para los usuarios. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | Delegado |  | [Opcional] [InProgress] Leer/Escribir correo electrónico para los usuarios. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | Delegado |  | [Opcional] [InProgress] Envíe plazos por correo electrónico como usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | Delegado |  | [Opcional]-[InProgress] Leer fechas límite de escritura como tarea para los usuarios. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | Delegado |  | Lea la información del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | Delegado |  | Leer/Escribir información del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | Delegado |  | Leer/Escribir información del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | Delegado | Correo electrónico, Id. de usuario de Office365, ObjectID, TenantID. | Lea la dirección de correo electrónico del usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| perfil | Delegado |  | Lea la información del perfil de usuario. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para identificar al usuario recién agregado en el equipo y comprobar si hay un cliente potencial | Correo electrónico, UserId |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Correo electrónico del usuario, UserID, AccessToken, información de grupos en nuestro registro de depuración

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Conservamos los registros de casos a menos que recibamos una solicitud para eliminar los datos.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

