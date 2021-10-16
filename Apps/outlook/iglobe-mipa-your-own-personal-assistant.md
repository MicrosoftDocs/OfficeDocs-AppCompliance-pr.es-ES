---
title: 'Información de la aplicación para MIPA: su propio asistente personal de iGlobe'
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 'Toda la información de seguridad y cumplimiento disponible para MIPA: su propio asistente personal, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.'
zone_pivot_groups: app-info-data-mcas-identity-certification
ms.openlocfilehash: 186699e37129b4fa0576c340c712cff319c51f96
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412650"
---
# <a name="mipa---your-own-personal-assistant"></a>MIPA: su propio asistente personal

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000062" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por iGlobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | MIPA: su propio asistente personal |
| Id. | WA200000062 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en la Web |
| Nombre de la compañía asociada | iGlobe |
| Dirección URL del sitio web de partners | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| Dirección URL de la directiva de privacidad | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| DIRECCIÓN URL de términos de uso | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

IGlobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Contacts.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Directory.AccessAsUser.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, actualizar, crear tareas panner. Para comprobar que el usuario tiene consentimiento y tiene acceso a la API. | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Directory.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Para obtener la tarea de Outlook To Do, marca los correos electrónicos y actualizándolos. Para crear una nueva tarea de Planner. | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Files.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en SharePoint listas. | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Group.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en SharePoint listas. | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Group.ReadWrite.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer, Actualizar, Crear tareas panner, Leer los archivos recientes y compartidos de los usuarios, Para obtener SharePoint lista, bibliotecas y archivos. Para guardar archivos en SharePoint listas. Integración con iGlobe CRM Office 365 | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Mail.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar correo marcado | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| MailboxSettings.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar correo marcado, Leer y actualizar Outlook To Do completos | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| Tasks.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| User.Read | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| User.Read.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| User.ReadBasic.All | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| User.ReadWrite | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| email | delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación lea la dirección de correo electrónico principal de los usuarios ( para SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| offline_access | delegado | No se almacenan datos en bases de datos de aplicaciones. | Permite que la aplicación vea y actualice los datos a los que le dio acceso, incluso cuando los usuarios no estén usando actualmente la aplicación. Esto no proporciona a la aplicación permisos adicionales ( para SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| OpenID | delegado | No se almacenan datos en la base de datos de aplicaciones | Permite a los usuarios iniciar sesión en la aplicación con sus cuentas laborales o educativas y permite que la aplicación vea información básica de perfil de usuario( para SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |
>| perfil | delegado | No se almacenan datos en bases de datos de aplicaciones. | Leer y actualizar todo el calender, Leer y actualizar Outlook a Do Entreies, Read, Update, Create Panner Tasks | [e854ea05-68ab-4204-babe-db4a784fb4d8](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d8) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange: Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange: EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange- Mail.Read | No |  |  |  |  |
>| Exchange- Mail.ReadWrite.All | No |  |  |  |  |
>| Exchange- MailboxSettings.Read | No |  |  |  |  |
>| Exchange- MailboxSettings.ReadWrite | No |  |  |  |  |
>| Exchange- Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint- MyFiles.Read | No |  |  |  |  |
>| SharePoint: MyFiles.Write | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>iGlobe recopila datos para funcionar eficazmente y proporcionarle las mejores experiencias con nuestros productos y servicios. Para licencias: los datos recopilados para administrar la cuenta de licencia de&#8217;organización, como cuando implementas complementos gratuitos, creas una suscripción de prueba o compras una suscripción. Se recopila la siguiente información. - Con fines financieros: nombre de la compañía y dirección: usuarios suscritos: nombre de usuario y correo electrónico

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todos los datos están en el propio inquilino del cliente. No se almacenan datos de aplicación. Un complemento moderno se ejecuta en un explorador de espacio aislado, &#8220;fuera de proceso&#8221;. Interactúa con los datos de los usuarios mediante servicios Microsoft. El complemento solo puede tener acceso a los datos con los que trabaja el usuario.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

IGlobe ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Valores predeterminados de seguridad y cualquier otra de las directivas comunes como Bloquear autenticación heredada* Requerir MFA para administradores* Requerir MFA para administración de Azure* Requerir MFA para todos los usuarios* |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | No |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>Información de certificación

| **Control** | **Microsoft 365 Resultado de certificación** |
|:------------|:---------------------------------------|
| [**SEGURIDAD DE LA APLICACIÓN**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#application-security) | **N/A** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pruebas de penetración | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisión de evaluación de vulnerabilidad (DAST/SAST/Prueba de penetración) | N/D |
| [**SEGURIDAD OPERATIVA**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#operational-security) | **N/A** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protección contra malware: antivirus | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protección contra malware: control de aplicaciones | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Administración de revisiones: clasificación de riesgos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Administración de revisiones: revisión | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Análisis de vulnerabilidades | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall: firewalls (o tecnologías equivalentes) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall: firewalls de aplicaciones web (WAFs) (opcional) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Control De cambios | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Desarrollo e implementación de software seguro | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Administración de cuentas | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Detección y prevención de intrusiones (opcional) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Registro de eventos de seguridad | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisión (datos de registro) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alertas de eventos de seguridad | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Administración de riesgos de seguridad de la información | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Respuesta a incidentes | N/D |
| [**PRIVACIDAD DE SEGURIDAD DE CONTROL DE &amp; DATOS**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#data-handling-security-and-privacy) | **N/A** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Datos en tránsito | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Datos en reposo | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Retención y eliminación de datos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Administración de acceso a datos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RGPD | N/D |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
