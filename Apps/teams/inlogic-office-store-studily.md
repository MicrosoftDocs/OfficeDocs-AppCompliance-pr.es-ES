---
title: Información de la aplicación Studi.ly por inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Studi.ly, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bc3307db955cf9f124442f08fc315c1cd8158659
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281242"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por inLogic-Office Store a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Studi.ly |
| Id. | WA200001668 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | inLogic-Office Store |
| Dirección URL del sitio web de partners | [https://www.inlogic.dk](https://www.inlogic.dk) |
| Dirección URL de la directiva de privacidad | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| DIRECCIÓN URL de términos de uso | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por la Tienda de inLogic-Office sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Escribir directorio en los grupos para asignaciones y materiales. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | aplicación | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Escribir directorio en los grupos para asignaciones y materiales. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | aplicación | Almacenamos clases, escuelas, miembros y términos de la api de educación en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Lea Clases educativas, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Lea Clases educativas, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | aplicación | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Lea Clases educativas, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | ReadWrite Files from One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Este permiso permitía a la aplicación obtener diferentes eventos de claender para grupos del inquilino.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | ambos | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Este permiso permitía a la aplicación obtener diferentes eventos de claender para grupos del inquilino.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | aplicación |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | ambos | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | ReadWrite Files from One Drive | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Leer información del usuario | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | delegado | Almacenamos clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtienemos cada vez desde la api de gráficos que hace que nuestra aplicación funcione con lentitud. Lo sincronizamos en un evento basado en tiempo desde la api de educación a nuestra base de datos. | Leer información del usuario | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Estos datos no aparecen en los registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Se almacena en la base de datos de Azure cosmos y cualquier cifrado y almacenamiento que esté disponible de forma predeterminada con la base de datos de cosmos es aplicable a esta aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

