---
title: Información de la aplicación para TackleBox por Insiten
ms.author: elmalova
author: elenamalova
ms.date: 01/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para TackleBox, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a40a1d6e1acb87917956766be21b0d6b364dfcba
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413772"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Insiten a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | TackleBox |
| Id. | WA200002310 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Insiten |
| Dirección URL del sitio web de partners | [https://insiten.com](https://insiten.com) |
| Dirección URL de Teams de información de la aplicación | [https://tacklebox.app](https://tacklebox.app) |
| Dirección URL de la directiva de privacidad | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| DIRECCIÓN URL de términos de uso | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Insiten ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | delegado | Permite a los usuarios examinar sus OneDrive, carpetas y archivos; vincular archivos a TackleBox; leer Excel para extraer automáticamente gráficos, gráficos, tablas, áreas de impresión y rangos con nombre; crear y actualizar archivos PowerPoint con estos Excel visuales | Id. de unidad, id. de carpeta, id. de archivo, vínculo de vista, creado por, fecha de creación, modificado por, fecha de modificación, id. de versión, nombre de archivo | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| Sites.Read.All | delegado | Permitir a los usuarios examinar y vincular Excel archivos ubicados en canales de Teams privados | Ninguno | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| User.Read | delegado | Permite a la aplicación leer el perfil de los usuarios que han iniciado sesión y volver a enviar su dirección de correo electrónico para las notificaciones | Correo electrónico | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| OpenID | delegado | Permite a los usuarios iniciar sesión en nuestra aplicación con Microsoft 365 cuenta | Id. de inquilino e id. de objeto para usuario | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| perfil | delegado | Permite que la aplicación muestre el perfil básico de los usuarios (nombre, nombre de usuario) para facilitar la colaboración | UPN, First Name, Last Name | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Direcciones de correo electrónico y nombres de cuenta. Las cuentas desactivadas y los detalles del usuario asociado se purgan después de 3 meses.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>No aplicable: todos los datos se almacenan en Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Insiten ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

