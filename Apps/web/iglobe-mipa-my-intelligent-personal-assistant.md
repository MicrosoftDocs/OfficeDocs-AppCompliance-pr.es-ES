---
title: 'Información de la aplicación para MIPA: Mi asistente personal inteligente'
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para MIPA- My Intelligent Personal Assistant, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d7afb4021dfb969d4dca3a6171ad4710d5138488
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225034"
---
# <a name="mipa---my-intelligent-personal-assistant-by-iglobe"></a>MIPA - My Intelligent Personal Assistant by iGlobe

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 22 de junio de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.mipa" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | MIPA: Mi asistente personal inteligente |
| ID | 17859280.mipa |
| Nombre de la empresa asociada | iGlobe |
| Dirección URL del sitio web del asociado | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| Dirección URL de la directiva de privacidad | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| Dirección URL de los términos de uso | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

iGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Azure AD id. de aplicación** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar la totalidad de calender | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Contacts.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar la totalidad de calender | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Directory.AccessAsUser.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer, actualizar, crear tareas de panner, leer los archivos recientes y compartidos de los usuarios. Para comprobar que el usuario tiene consentimiento y tiene acceso para usar la API. | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Directory.ReadWrite.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer, actualizar, crear tareas panner, leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en listas de SharePoint. | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Files.ReadWrite.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer, actualizar, crear tareas panner, leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en listas de SharePoint. | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Group.Read.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer, actualizar, crear tareas panner, leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en listas de SharePoint. | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Group.ReadWrite.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer, actualizar, crear tareas panner, leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en listas de SharePoint. Integración con iGlobe CRM Office 365 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Mail.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar el correo marcado | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| MailboxSettings.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de Calender, Leer y actualizar correo marcado, Leer y actualizar Outlook To Do enteros | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Tasks.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.Read | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.Read.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.ReadBasic.All | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.ReadWrite | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| correo electrónico | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Permite que la aplicación lea la dirección de correo electrónico principal de los usuarios ( para sso). | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| offline_access | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Permite que la aplicación vea y actualice los datos a los que le ha dado acceso, incluso cuando los usuarios no usan la aplicación actualmente. Esto no proporciona a la aplicación ningún permiso adicional ( para el inicio de sesión único). | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| OpenID | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Permite a los usuarios iniciar sesión en la aplicación con sus cuentas profesionales o educativas y permite que la aplicación vea información básica sobre el perfil de usuario (para sso). | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| perfil | Delegado | No se almacenan datos en las bases de datos de la aplicación. | Leer y actualizar los elementos completos de calender, leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d8 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph para recopilar o procesar información de identificación de la organización (OII). Enumere las API de Microsoft distintas de Microsoft Graph que use esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para la recopilación de OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange: Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange- Mail.Read | No |  |  |  |  |
>| Exchange- Mail.ReadWrite.All | No |  |  |  |  |
>| Exchange: MailboxSettings.Read | No |  |  |  |  |
>| Exchange: MailboxSettings.ReadWrite | No |  |  |  |  |
>| Exchange: Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint: MyFiles.Read | No |  |  |  |  |
>| SharePoint: MyFiles.Write | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación para por qué la aplicación necesita transferir esta información.

>No se usan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información de identificación de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describir qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>iGlobe recopila datos para operar de forma eficaz y proporcionarle las mejores experiencias con nuestros productos y servicios. Para licencias: datos recopilados para administrar la organización&#8217;cuenta de licencia, como al implementar complementos gratuitos, crear una suscripción de prueba o comprar una suscripción. Se recopila la siguiente información. 
- Para fines financieros: nombre y dirección de la empresa
- Usuarios suscritos: nombre de usuario y correo electrónico

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por asociado

¿Cómo los administradores de la organización pueden controlar su información en los sistemas asociados? Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos están en el propio inquilino del cliente. No se almacenan datos de la aplicación. Un complemento moderno se ejecuta en un explorador de espacio aislado, &#8220;&#8221; fuera de proceso. Interactúa con los datos de los usuarios mediante servicios Microsoft. El complemento solo puede acceder a los datos con los que trabaja el usuario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Están involucrados los seres humanos en la revisión o el análisis de datos de información de identificación organizativa (OII) recopilados o almacenados por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='información de Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Ver en una nueva pestaña</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

iGlobe ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Valores predeterminados de seguridad y cualquier otra de las directivas comunes, como Bloquear la autenticación heredada* Requerir MFA para administradores* Requerir MFA para la administración de Azure* Requerir MFA para todos los usuarios* |
| ¿La aplicación solicita permisos con privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Posee todo el identificador de recursos unificado (URI) de redirección registrado para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de versión preliminar? | No |
| ¿La aplicación usa las API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
