---
title: Información de la aplicación para Studi.ly por inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Studi.ly, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553061"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por inLogic-Office Store a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Studi.ly |
| ID | WA200001668 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | inLogic-Office Store |
| URL del sitio web de socios | [https://www.studi.ly](https://www.studi.ly) |
| URL de la Política de Privacidad | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL de los Términos de uso | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por inLogic-Office Store sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Directorio de escritura en los grupos para asignaciones y materiales. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | aplicación | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Directorio de escritura en los grupos para asignaciones y materiales. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | aplicación | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Lea Clases de educación, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Lea Clases de educación, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | aplicación | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Lea Clases de educación, Escuela, Miembros y Términos.Obtenga todas las clases y escuelas de un inquilino para la sincronización en la base de datos de aplicaciones. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Leer archivos de una unidad | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Este permiso permitió a la aplicación obtener diferentes eventos claender para grupos del inquilino.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | ambos | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Este permiso permitió a la aplicación obtener diferentes eventos claender para grupos del inquilino.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | aplicación |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | ambos | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Leer archivos de una unidad | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Lectura de información del usuario | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | Delegado | Estamos almacenando clases, escuelas y miembros y la información de términos de la api educativa en nuestra api y la necesitamos porque si la obtenemos cada vez de graph api eso hace que nuestra aplicación funcione lentamente. Lo sincronizamos en un evento basado en el tiempo desde la api educativa hasta nuestra base de datos. | Lectura de información del usuario | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Dichos datos no aparecen en los registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Se almacena en la base de datos de Cosmos de Azure y cualquier cifrado y almacenamiento que esté disponible de forma predeterminada con cosmos database es aplicable a esta aplicación.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

