---
title: Información de aplicación para LawToolBox Matters for Outlook, Teams &amp; SharePoint by LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para LawToolBox Matters for Outlook, Teams SharePoint, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro &amp; CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b8264ca65796af344d5cba11a55afca6c2e42cc9
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411304"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>LawToolBox importa para Outlook, Teams &amp; SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por LawToolBox.com Inc. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | LawToolBox importa para Outlook, Teams &amp; SharePoint |
| Id. | WA200003103 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la Web |
| Nombre de la compañía asociada | LawToolBox.com Inc. |
| Dirección URL del sitio web de partners | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| Dirección URL de la directiva de privacidad | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por LawToolBox.com Inc. sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | este permiso tiene restringido el acceso al usuario&#8217;contactos a los que ya tienen acceso &#8211; lo usamos para permitir a los usuarios recuperar su propia información de calendario | [Opcional] Leer el calendario del usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | delegado | este permiso está restringido para obtener acceso a los contactos del usuario&#8217;que ya tienen acceso a &#8211; lo usamos para permitir a los usuarios recuperar su propia información de calendario y escribir en calendarios | Para crear una invitación de calendario al calendario del usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | delegado | este permiso tiene restringido el acceso al usuario&#8217;contactos a los que ya tienen acceso &#8211; lo usamos para permitir a los usuarios recuperar su propia información de calendario | Para crear una invitación de calendario al calendario compartido. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | delegado | este permiso tiene restringido el acceso al usuario&#8217;contactos a los que ya tienen acceso.  Usamos este permiso para permitir al usuario buscar en sus contactos de O365 y agregar a LawToolBox &#8211; no agregamos ningún contacto automáticamente (esto se puede revocar si no desea que esta característica y los contactos se puedan agregar manualmente | [Opcional]: para leer contactos de usuario y conectar usuarios de la lista de contactos al grupo. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | delegado | usamos este permiso para permitir al usuario buscar contactos compartidos de O365 y agregar a LawToolBox &#8211; no agregamos ningún contacto automáticamente | [Opcional]: para leer los contactos compartidos de los usuarios para servir la lista de contactos relevantes para el caso. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | delegado | que usamos en el portal de administración para recuperar la lista de usuarios del inquilino de O365 para agregar a su cuenta | [Opcional] Lea la información de grupos y usuarios como usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | delegado | que usamos en el portal de administración para recuperar la lista de usuarios del inquilino de O365 para agregar a su cuenta | [Opcional] Lea la información de grupos y usuarios como usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | delegado | esto permite al addin leer y enumerar los archivos de usuario a los que el usuario ya tiene acceso | [Opcional] Lea la información del OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | delegado | usamos este permiso para leer y enumerar los archivos de usuario a los que el usuario ya tiene acceso | [Optional]-Read user's OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | delegado | leemos archivos de Teams, grupos y OneDrive para reuniones (si lo revoca, impedirá que nuestro addin enumera los archivos de asunto en nuestras aplicaciones) | [Optional]-Read and modify files in a user's OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | delegado | leemos archivos de Teams, grupos y OneDrive para reuniones (si revocas esto impedirá que LTB enumera los archivos de materia en nuestras aplicaciones).  El usuario solo puede usar addin para leer y enumerar los archivos de usuario a los que el usuario ya tiene acceso | [Opcional] Archivo de lectura y escritura del usuario OneDrive asociado con el objeto Matter. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | delegado | GroupID, GroupName, GroupEmail | Creamos un grupo para cada asunto creado en nuestro sistema. Esto ayuda al usuario a almacenar información relacionada con la materia en el grupo, que a su vez guarda sus datos en su propio inquilino. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | delegado | usamos este permiso para leer correos electrónicos PACER en nuestro complemento de Outlook para abrir automáticamente ese asunto y también para leer los contactos de su correo electrónico para agregarlos a nuestro sistema de contactos  | [Opcional] [InProgress] Lea el correo electrónico del usuario para Asuntos. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | delegado | usamos este permiso para leer correos electrónicos PACER en nuestro complemento de Outlook para abrir automáticamente ese asunto y también para leer los contactos de su correo electrónico para agregarlos a nuestro sistema de contactos  | [Opcional] [InProgress] Correo electrónico de lectura y escritura para los usuarios. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | delegado | usamos este permiso para leer correos electrónicos PACER en nuestro complemento de Outlook para abrir automáticamente ese asunto y también para leer los contactos de su correo electrónico para agregarlos a nuestro sistema de contactos  | [Opcional] [InProgress] Correo electrónico de lectura y escritura para los usuarios. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | delegado | Usamos este envío de correos electrónicos como usuario para permitir que un usuario se envíe solo informes de los datos a los que ya tienen acceso en nuestro sistema | [Opcional] [InProgress] Enviar fechas límite en el correo electrónico como usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | delegado | este permiso está restringido para obtener acceso al usuario&#8217;tareas a las que ya tienen acceso &#8211; lo usamos para permitir que los usuarios recuperen y actualicen su propia información task.  | [Optional]-[InProgress] Read Write Deadlines as Task for users. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | delegado | se usa para sugerir contactos recientes para agregarlos a reuniones o contactos | Leer la información del usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | delegado | se usa para sugerir contactos recientes para agregarlos a reuniones o contactos | Información del usuario de lectura y escritura. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | delegado | esto es necesario para leer la API de Teams, crear Teams, crear evento Calendar, crear canales, Teams de uso compartido de archivos | Información del usuario de lectura y escritura. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | delegado | Correo electrónico, UserID de Office365, ObjectID, TenantID. | Lea la dirección de correo electrónico del usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| perfil | delegado | esto es necesario para la autenticación de SSO: también usamos este permiso para recuperar imágenes y nombres guardados en el inquilino de M365 para que el usuario sepa que están en el cuadro de herramientas correcto | Lea la información del perfil de usuario. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Correo electrónico del usuario, UserID, AccessToken, Información de grupos en nuestro registro de depuración

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Conservamos los registros de casos a menos que recibamos una solicitud para eliminar los datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por LawToolBox.com Inc. sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Para un mayor control, el administrador puede implementar permisos de aplicación |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | ,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

