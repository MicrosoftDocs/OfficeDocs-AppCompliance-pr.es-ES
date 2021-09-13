---
title: Información de aplicaciones para Power BI colaboración de Ataira
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para la colaboración Power BI, sus directivas de tratamiento de datos, la información del catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 642ac51a231bf583b6cac3facb64ade94b772c3e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287527"
---
# <a name="power-bi-collaboration"></a>Colaboración de Power BI

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/90381cb0-998f-4ba3-9699-130201de5ddb" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381384" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Ataira a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Colaboración de Power BI |
| Id. | WA104381384 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Ataira |
| Dirección URL del sitio web de partners | [https://www.ataira.com](https://www.ataira.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.ataira.com/Microsoft/PowerBI/Collaboration](https://www.ataira.com/Microsoft/PowerBI/Collaboration) |
| Dirección URL de la directiva de privacidad | [https://www.ataira.com/PrivacyPolicy](https://www.ataira.com/PrivacyPolicy) |
| DIRECCIÓN URL de términos de uso | [https://www.ataira.com/TermsofUse](https://www.ataira.com/TermsofUse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Ataira ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | También permisos para ChannelMessage.Send Team.ReadBasic.All User.Read. Se usan para permitir al usuario seleccionar el grupo Teams y el canal para notificaciones | Supervisión de uso, error y licencia. [callback_group_id] ,[datetime_id] ,[session_id] ,[app_type] ,[raw_url] ,[user_id] ,[list_name] ,[user_name] ,[state] ,[priority] ,[user_domain] ,[url_text]] ,[group_name] ,[title_name] ,[comments] ,[file_name] ,[description] ,[group_pbi_name] ,[item_type] ,[organization_id] ,[user_objectid] ,[organization_displayName] ,[group_id] | [00738e07-f9a4-4bf5-b6f9-851ec7ea31d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/00738e07-f9a4-4bf5-b6f9-851ec7ea31d5) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://analysis.windows.net/powerbi/api/ | Sí | correo electrónico del usuario, nombre del área de trabajo, nombre del elemento, dirección URL de inserción | Se usa para rellenar informes y paneles en la interfaz SharePoint complemento | [api_pbi_id] ,[datetime_id] ,[session_id] ,[user_name] ,[user_domain] ,[WorkSpace_Name] ,[WorkSpace_Id] ,[item_Id] ,[item_type] ,[item_name] ,[webUrl] ,[embedUrl] ,[displayName] ,[item_title] ,[isOwnedByMe] | Supervisión de uso, error y licencia |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Metadatos necesarios para rellenar Power BI informes y paneles, autenticación para Graph Teams API. Puede encontrar más datos y directivas de privacidad en el sitio web. https://www.ataira.com/PrivacyPolicy Y, a continuación, también en la página configuración de la aplicación específicamente para la privacidad de datos. https://www.ataira.com/Microsoft/PowerBI/CollaborationSupport

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Ataira ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Autenticación multifactor que permite que solo los dispositivos inscritos en Intune accedan a servicios específicos Restringir ubicaciones de usuario e intervalos IP |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
