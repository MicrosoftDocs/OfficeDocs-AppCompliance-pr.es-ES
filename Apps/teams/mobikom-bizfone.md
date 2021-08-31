---
title: Información de la aplicación para Bizfone por MobiKOM
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Bizfone, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 20f1497c8cb4541982082a6bfbccd0f4968a8663
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673233"
---
# <a name="bizfone"></a>Bizfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5be25d59-35cd-4318-83b0-2a5d5668ddcd" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000874" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por MobiKOM a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Bizfone |
| Id. | WA200000874 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | MobiKOM |
| Dirección URL del sitio web de partners | [https://mobikom.dk](https://mobikom.dk) |
| Dirección URL de Teams de información de la aplicación | [https://mobikom.dk/faq/](https://mobikom.dk/faq/) |
| Dirección URL de la directiva de privacidad | [https://mobikom.dk/privatlivs-og-cookiepolitik/](https://mobikom.dk/privatlivs-og-cookiepolitik/) |
| DIRECCIÓN URL de términos de uso | [https://mobikom.dk/salgs-og-leveringsbetingelser/](https://mobikom.dk/salgs-og-leveringsbetingelser/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

MobiKOM ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Los calendarios se usan para que los usuarios puedan mostrar su calandar a sus compañeros de trabajo y usar reuniones para configurar su telefonía | Los calendarios se usan para que los usuarios puedan mostrar su calandar a sus compañeros de trabajo y usar reuniones para configurar su telefonía | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| Contacts.Read | delegado | Los contactos de los usuarios se pueden almacenar si quieren mostrarlos en la aplicación para facilitar la marcación de contactos | Los contactos de los usuarios se pueden almacenar si quieren mostrarlos en la aplicación para facilitar la marcación de contactos | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegado | El usuario leído en esta aplicación se usa con fines de identificación. | El usuario leído en esta aplicación se usa con fines de identificación. | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegado | No almacenamos los datos. La aplicación se usa simplemente con fines de autenticación | No almacenamos los datos. La aplicación se usa simplemente con fines de autenticación | [fc8f7563-e8ea-4b6d-9622-82775a21a35a](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc8f7563-e8ea-4b6d-9622-82775a21a35a) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS. AccessAsUser.All | Sí | Nombre de la compañía, nombres de empleados y números de teléfono | Para poder mostrar los datos a los usuarios de la aplicación y usarlos | Nombre de la compañía, nombres de empleados y números de teléfono | Para poder mostrar los datos a los usuarios de la aplicación y usarlos |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Ribbon Communications, Voxbone, team.blue, Fakturaservice.dk A/S, Elastic | Nombre de la compañía, nombres de empleados y números de teléfono | La cinta proporciona nuestra Teams SBC. Voxbone se usa para números internacionales, pero solo si los tiene. team.blue es nuestro proveedor de hospedaje. FakturaService.dk A/S se usa para la facturación. Elastic se usa para el registro |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>No aparecen OII ni EUII en los registros o telemetría de aplicaciones.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Cada usuario es un empleado de una empresa que usa nuestros servicios. Tienen un administrador que puede eliminar y editar datos. Las DPA también están en su lugar antes de que los usuarios finales obtengan acceso

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

MobiKOM ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumerar los tipos de directivas admitidas | Autenticación multifactor |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
