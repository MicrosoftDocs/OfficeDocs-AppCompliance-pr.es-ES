---
title: Información de la aplicación para firmas de correo electrónico codeTwo Office 365 por CodeTwo
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para las firmas de correo electrónico codeTwo para Office 365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 79db12fe65495df15e21b46e810abd8bbd017359
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/13/2021
ms.locfileid: "58245371"
---
# <a name="codetwo-email-signatures-for-office-365"></a>Firmas de correo electrónico codeTwo para Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por CodeTwo a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Firmas de correo electrónico codeTwo para Office 365 |
| Identificador | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| Nombre de la compañía asociada | CodeTwo |
| Dirección URL del sitio web de partners | [https://www.codetwo.com](https://www.codetwo.com) |
| Dirección URL de la directiva de privacidad | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

CodeTwo ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permission**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Permite a los usuarios iniciar sesión en la aplicación y permite que la aplicación lea el perfil de los usuarios que han iniciado sesión. También permite que la aplicación lea información básica de la organización de los usuarios que han iniciado sesión. | No se almacenan datos. | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | delegado | Permite a los usuarios iniciar sesión en la aplicación y permite a la aplicación leer el perfil de los usuarios que han iniciado sesión. También permite que la aplicación lea la información empresarial básica de los usuarios que han iniciado sesión. | No se almacenan datos. | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | delegado | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | No se almacenan datos. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | ambos | Permite que la aplicación lea datos en el directorio de&#8217;, como usuarios, grupos y aplicaciones. | No se almacenan datos. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | delegado | Permite a la aplicación leer un conjunto básico de propiedades del perfil de otros usuarios de su organización en nombre del usuario que inició la sesión. Esto incluye el nombre para mostrar, el nombre y el apellido, la dirección de correo electrónico y la foto. La información se usa para personalizar automáticamente las firmas de correo electrónico de los usuarios. | No se almacenan datos. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | delegado | Permite a los usuarios iniciar sesión en la aplicación y permite que la aplicación lea el perfil de los usuarios que han iniciado sesión. También permite que la aplicación lea información básica de la empresa de los usuarios que han iniciado sesión. Se usa para registrar al usuario en el servicio CodeTwo. | No se almacenan datos. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| email | delegado | Permite que la aplicación lea la dirección de correo electrónico principal de los usuarios. Se usa para registrar al usuario en el servicio CodeTwo. | No se almacenan datos. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | delegado | Permite que la aplicación vea y actualice los datos a los que le dio acceso, incluso cuando los usuarios no estén usando actualmente la aplicación. Esto no concede a la aplicación permisos adicionales. | No se almacenan datos. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| OpenID | delegado | Permite que los usuarios inicien sesión en la aplicación con sus cuentas profesionales o educativas y permite que la aplicación vea la información básica del perfil del usuario. Se usa para registrar al usuario en el servicio CodeTwo. | No se almacenan datos. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| perfil | delegado | Permite que la aplicación vea el perfil básico de los usuarios (nombre, imagen, nombre de usuario). Se usa para registrar al usuario en el servicio CodeTwo. | No se almacenan datos. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los clientes pueden acceder y rectificar sus datos de la organización de contacto y la configuración del servicio a través del &amp; Panel de administración de CodeTwo. También pueden ponerse en contacto con el equipo de seguridad de la información de CodeTwo a través de un formulario dedicado ( para ejercer cualquiera de los derechos descritos en Términos y privacidad de CodeTwo ( , es decir: acceso a datos, rectificación de datos, eliminación y restricción del procesamiento, retirada del consentimiento y derecho a oponerse al https://www.codetwo.com/form/security-officer/) https://www.codetwo.com/regulations/privacy) procesamiento.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

CodeTwo ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
