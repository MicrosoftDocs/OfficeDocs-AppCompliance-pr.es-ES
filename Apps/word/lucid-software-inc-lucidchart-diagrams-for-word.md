---
title: Información de la aplicación para diagramas de Diagramas de Diagramas de Lucidchart para Word de Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Diagramas de Diagramas de Gráficos de Lucidchart para Word, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9519dbcb549d7860856e6c310f68da8afad86819
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251569"
---
# <a name="lucidchart-diagrams-for-word"></a>Diagramas de Gráficos de Lucidchart para Word

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380118" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Lucid Software Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Diagramas de Gráficos de Lucidchart para Word |
| ID | WA104380118 |
| Office 365 clientes compatibles | Word 2016 o posterior en Mac, Word 2013 o posterior en Windows, Word en la Web |
| Nombre de la compañía asociada | Lucid Software Inc |
| Dirección URL del sitio web de partners | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| Dirección URL de la directiva de privacidad | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Lucid Software Inc sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |
>| OpenID | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |
>| perfil | delegado | Nombre y dirección de correo electrónico. | Los permisos de correo electrónico, openid y perfil permiten a Lucidchart generar un token openid para un usuario y obtener suficiente información básica sobre el usuario para registrar una cuenta de Lucidchart para ellos si es necesario. Para comprobar los datos que vienen de Microsoft, se realiza una solicitud para obtener la clave pública con la que se ha firmado su respuesta. No se reciben o envían otros datos a Microsoft como parte de nuestro flujo de SSO. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de JavaScript para Office | Sí | Usamos el SDK Office OneDrive javascript para abrir el OneDrive de archivos con OneDrive.open(). No generamos tokens de acceso y no hacemos ninguna solicitud a las API de OneDrive las api; el ONEDRIVE de elección de archivos hace eso por nosotros. Solo vemos los nombres de archivo que elige el usuario. |  | Si el usuario selecciona un archivo mediante el OneDrive de archivos, almacenamos el nombre de archivo. |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Los datos de Lucidchart se almacenan en AWS. |  | No usamos ninguna API de Microsoft. Usamos openID para obtener datos de usuario básicos para realizar SSO. Usamos su API de selector de archivos, pero eso no nos da acceso a los archivos del usuario que no son los que nos envían a través del selector. |



#### <a name="add-in-data-access"></a>Acceso a datos del complemento

Enumerar los permisos que requiere esta aplicación para obtener acceso a los datos de la organización, la justificación y el propósito de este permiso (¿para qué usa la aplicación esta información?) y si la aplicación almacena alguna de esta información en sus bases de datos.

>| **Permiso**  | **Descripción** |
>|:----------------|:----------------|
>| ReadWrite Document | Puede leer y realizar cambios en el documento |
>| Enviar datos | Puede enviar datos a través de Internet |

#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Registramos el correo electrónico y las direcciones IP por motivos de seguridad y soporte técnico. Todo el acceso a los registros es registrado &amp; los registros son realmente inmutables en un sistema de terceros. El acceso a los registros requiere MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos de Lucidchart se almacenan en AWS. Se cifra en reposo y en tránsito. Lucidchart usa las reglas de privilegios mínimos y MFA.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

