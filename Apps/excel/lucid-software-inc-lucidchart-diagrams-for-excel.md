---
title: Información de la aplicación Lucidchart Diagrams for Excel by Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para diagramas de Lucidchart para Excel, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5481ed9ce5f8e589fe5ea8703fb48b53c5dab488
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548800"
---
# <a name="lucidchart-diagrams-for-excel"></a>Diagramas de Lucidchart para Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Lucid Software Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Diagramas de Lucidchart para Excel |
| ID | WA104380194 |
| Office 365 clientes compatibles | Excel 2016 o posterior en Mac, Excel 2013 o más tarde en Windows, Excel en la Web |
| Nombre de la empresa asociada | Lucid Software Inc |
| URL del sitio web de socios | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| URL de la Política de Privacidad | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL de los Términos de uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Lucid Software Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Con el fin de verificar los datos que regresan de Microsoft, hacemos una solicitud para obtener la clave pública con la que está firmada su respuesta. No se reciben ni envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |
>| OpenID | Delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Con el fin de verificar los datos que regresan de Microsoft, hacemos una solicitud para obtener la clave pública con la que está firmada su respuesta. No se reciben ni envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |
>| perfil | Delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Con el fin de verificar los datos que regresan de Microsoft, hacemos una solicitud para obtener la clave pública con la que está firmada su respuesta. No se reciben ni envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | Utilizamos el SDK de javascript Office OneDrive para abrir el selector de archivos OneDrive mediante OneDrive.open(). No generamos ningún token de acceso y no hacemos ninguna solicitud a las API de OneDrive nosotros mismos; el SDK de selector de archivos OneDrive hace eso por nosotros. Solo vemos los nombres de archivo que el usuario elige. |  | Si el usuario selecciona un archivo mediante el selector de archivos OneDrive, almacenamos el nombre de archivo. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Los datos de Lucidchart se almacenan en AWS. |  | No usamos ninguna API de Microsoft. Usamos openID para obtener datos básicos de usuario para realizar SSO. Usamos su API de selector de archivos, pero eso no nos da acceso a los archivos del usuario que no sean los que nos envían a través del selector. |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Registramos direcciones IP y correo electrónico por razones de seguridad y soporte. Todo el acceso a los registros es &amp; registrado los registros son realmente inmutables en un sistema de terceros. El acceso a los registros requiere MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos de Lucidchart se almacenan en AWS. Se cifra en reposo y en tránsito. Lucidchart utiliza las reglas de privilegios mínimos y MFA.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

