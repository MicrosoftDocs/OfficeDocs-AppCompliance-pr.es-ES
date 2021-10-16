---
title: Información de la aplicación para PandaDoc de PandaDoc
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para PandaDoc, sus directivas de tratamiento de datos, su información del catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8d3a04daba9ebcbcf435f46beb6313c22310fe22
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408985"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por PandaDoc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | PandaDoc |
| Id. | WA200002927 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | PandaDoc |
| Dirección URL del sitio web de partners | [https://www.pandadoc.com](https://www.pandadoc.com) |
| Dirección URL de Teams de información de la aplicación | [https://www.pandadoc.com](https://www.pandadoc.com) |
| Dirección URL de la directiva de privacidad | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por PandaDoc sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | ambos | para obtener una lista de identificadores de canales para cada comando recibido anteriormente y obtener los identificadores de unidades de archivo para cada canal. | Los datos no se almacenan | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | ambos | para obtener una lista de identificadores de canales para cada comando recibido anteriormente y obtener los identificadores de unidades de archivo para cada canal.  | Los datos no se almacenan | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | ambos | para obtener una lista de identificadores de canales para cada comando recibido anteriormente y obtener los identificadores de unidades de archivo para cada canal. | Los datos no se almacenan | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | ambos | Para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | ambos | Para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | ambos | para obtener una lista de identificadores de canales para cada comando recibido anteriormente y obtener los identificadores de unidades de archivo para cada canal. Documentación: https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | ambos | para obtener una lista de identificadores de canales para cada comando recibido anteriormente y obtener los identificadores de unidades de archivo para cada canal. Documentación: https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | ambos | para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. Para obtener los id. del almacén de archivos, primero debe obtener una lista de los equipos que ha escrito el usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | ambos | Para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. Para obtener los id. del almacén de archivos, primero debe obtener una lista de los equipos que ha escrito el usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | ambos | o obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. Para obtener los id. del almacén de archivos, primero debe obtener una lista de los equipos que ha escrito el usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | ambos | necesario para instalar la aplicación en un usuario en Team e instalar el bot en el chat. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | ambos | necesario para instalar la aplicación en un usuario en Team e instalar el bot en el chat. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | ambos |  para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. Para obtener los id. del almacén de archivos, primero debe obtener una lista de los equipos que ha escrito el usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | ambos |  para obtener los id. de los equipos Microsoft Teams de los que el usuario es miembro directo. Después de eso, los canales de recepción para cada identificador de comando. Para obtener los id. del almacén de archivos, primero debe obtener una lista de los equipos que ha escrito el usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| OpenID | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| perfil | ambos | para el usuario de sso de Tab (ejemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necesario para obtener un token de usuario con acceso a Microsoft Graph obtener más archivos de usuario. | Los datos no se almacenan. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| PandaDoc API | No |  |  |  |  |
>| MS Graph | No |  |  |  |  |
>| Elementor | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Nuestros acuerdos de proveedor abordan las obligaciones respectivas de nuestros proveedores y nuestros proveedores con respecto a la privacidad y la seguridad de los datos, y se someten a revisiones de seguridad y privacidad de nuestros proveedores clave cada año.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por PandaDoc sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | No |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | No |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

