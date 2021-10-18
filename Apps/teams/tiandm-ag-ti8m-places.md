---
title: Información de la aplicación para lugares ti8m por ti &amp; m AG
ms.author: elmalova
author: elenamalova
ms.date: 10/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para los lugares de ti8m, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security y la información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8a248b5b89f9672ea79101ea286ca5ea01d7a3b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429448"
---
# <a name="ti8m-places"></a>lugares de ti8m

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/9e384ce2-2db2-412e-8da7-08c5cf4c418e" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003311" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ti &amp; m AG a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | lugares de ti8m |
| Id. | WA200003311 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | ti &amp; m AG |
| Dirección URL del sitio web de partners | [https://www.ti8m.com/places](https://www.ti8m.com/places) |
| Dirección URL de Teams de información de la aplicación | [https://www.ti8m.ch/places](https://www.ti8m.ch/places) |
| Dirección URL de la directiva de privacidad | [https://ti8m.com/products/places/places-datenschutzerklaeru...](https://ti8m.com/products/places/places-datenschutzerklaerung) |
| DIRECCIÓN URL de términos de uso | [https://ti8m.com/products/places/places-nutzungsbedingungen](https://ti8m.com/products/places/places-nutzungsbedingungen) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Ti m AG ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que &amp; recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite.Shared | delegado | Cancelar eventos en calendarios de usuarios y lugares de trabajo  | Identificador de evento si se debe cancelar una entrada de calendario reservada | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Directory.ReadWrite.All | delegado | Instalación y creación de grupos de AAD administrativos: grupos de seguridad  | GroupNames y GroupIDs | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Place.ReadWrite.All | delegado | Lista de lugares de trabajo y nombres de mapa  | Workplace ID, Email Adresse of Workplace y Displayname. Se usa para la reserva de un lugar de trabajo | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| User.Read | delegado | Nombre de usuario, correo electrónico y displayname, necesarios para mostrar los datos de usuario en la aplicación | Nombre de usuario, correo electrónico y displayname, necesarios para mostrar los datos de usuario en la aplicación | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |


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

>archivado, eliminación

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Ti m AG ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones &amp; y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
