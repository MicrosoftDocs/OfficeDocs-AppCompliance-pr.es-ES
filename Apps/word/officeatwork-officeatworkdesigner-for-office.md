---
title: Información de solicitud para | de oficina Diseñador para Office por oficina
ms.author: elmalova
author: elenamalova
ms.date: 12/08/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Toda la información de seguridad y cumplimiento disponible para officeatwork | Diseñador para Office, sus directivas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2df5ab4f69bd416e1c671818abda805b3e1350d3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552631"
---
# <a name="officeatwork--designer-for-office"></a>| Diseñador para Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última actualización por el desarrollador el: 8 de diciembre de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380518" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por officeatwork a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | oficina - Diseñador para Office |
| ID | WA104380518 |
| Office 365 clientes compatibles | Word 2016 o más tarde en Mac, Word en la Web, Word 2016 o posterior en Windows, Word on iPad |
| Nombre de la empresa asociada | officeatwork |
| URL del sitio web de socios | [https://links.officeatwork.com/officeatwork-home](https://links.officeatwork.com/officeatwork-home) |
| URL de la Política de Privacidad | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL de los Términos de uso | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por officeatwork sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.Read | Delegado | No se almacenan datos. | Contactos: para habilitar la lectura de todos los contactos del usuario que ha iniciado sesión. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read | Delegado | No se almacenan datos. | OneDrive - Archivos (Contenido): para permitir la lectura de los archivos del usuario que ha iniciado sesión. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read.All | Delegado | No se almacenan datos. | Teams - Archivos (Contenido): para habilitar la lectura de todos los archivos del usuario que ha iniciado sesión. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Group.Read.All | Delegado | No se almacenan datos. | Office 365 Usuarios: límite a grupo: para permitir la lectura de todos los grupos del usuario que ha iniciado sesión. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Sites.Read.All | Delegado | No se almacenan datos. | SharePoint En línea: para habilitar la lectura de datos de SharePoint Online. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read | Delegado | No se almacenan datos. | Sing-In: para permitir que la aplicación officeatwork lea las propiedades básicas del usuario. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read.All | Delegado | No se almacenan datos. | Office 365 Usuarios : todas las propiedades: para habilitar la lectura de todas las propiedades de todos los usuarios. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.ReadBasic.All | Delegado | No se almacenan datos. | Office 365 Usuarios - Propiedades básicas: para permitir la lectura de las propiedades básicas de todos los usuarios | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| offline_access | Delegado | No se almacenan datos. | Sing-In: para habilitar el inicio de sesión automático a través de tokens de actualización, como sin, los usuarios tendrían que iniciar sesión manualmente cada vez que inicien la aplicación officeatwork. Este ámbito solo es necesario para aplicaciones host no habilitadas para SSO. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| OpenID | Delegado | No se almacenan datos. | Sing-In: para permitir a los usuarios iniciar sesión en la aplicación officeatwork con su organización y/o cuenta Microsoft | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| perfil | Delegado | No se almacenan datos. | Sing-In: para mostrar al usuario que ha iniciado sesión en la aplicación officeatwork. Esto ayuda a asegurar/confirmar al usuario qué cuenta se usó para iniciar sesión en la aplicación officeatwork. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de REST de SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí, los eventos incluyen el oid y tenantId y se envían a Azure AppInsights. Los eventos se eliminan automáticamente después de 90 días. Si un cliente desea que se eliminen estos datos, puede utilizar el enlace proporcionado en la declaración de privacidad para iniciar la eliminación de esos datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos de configuración de aplicaciones (marcas de característica, nombre para mostrar de la organización, tenantId, lista de oids de administradores) se almacenan en una instancia de base de datos de Azure Cosmos (un archivo por inquilino). Los archivos de base de datos están cifrados y el acceso está restringido a los ingenieros de oficina y al personal de soporte técnico seleccionados. El cliente puede acceder y manipular los datos de configuración de la aplicación officeatwork mediante admin center web app.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por officeatwork sobre cómo esta aplicación controla la autenticación, autorización, prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumere los tipos de directivas admitidas | Valores predeterminados de seguridad |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | No |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | No |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
