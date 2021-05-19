---
title: Información de la aplicación para el alcance por LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Reach, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552001"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador el: 22 de marzo de 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por LiveTiles a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Reach |
| ID | WA200002045 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | LiveTiles |
| URL del sitio web de socios | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL de Teams página de información de la aplicación | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL de la Política de Privacidad | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL de los Términos de uso | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

LiveTiles ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | aplicación | ninguno | ninguno | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | Delegado | Nombre de usuario, Dirección de correo electrónico del usuario, UPN. Necesario para permitir que los usuarios inicien sesión en la aplicación y obtengan información básica del usuario que ha iniciado sesión, como el nombre para mostrar. La dirección de correo electrónico se utiliza para enviar notificaciones por correo electrónico.  | Nombre de usuario, Dirección de correo electrónico del usuario, UPN. Necesario para permitir que los usuarios inicien sesión en la aplicación y obtengan información básica del usuario que ha iniciado sesión, como el nombre para mostrar. La dirección de correo electrónico se utiliza para enviar notificaciones por correo electrónico.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | Delegado | DisplayName del usuario, Dirección de correo electrónico del usuario, UPN, Departamento de usuario, Título del trabajo del usuario, Número de Teléfono móvil del usuario, Número de Teléfono empresarial del usuario, Ubicación de Office del usuario. Necesario para permitir a los usuarios que buscan otros usuarios dentro de la aplicación (Phonebook) y ver el perfil básico de otros usuarios y la información de contacto.  | ninguno | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | aplicación | Pertenencia a grupos, grupos de AD en directorio. La pertenencia a grupos de usuarios se almacena en una memoria caché para minimizar las llamadas a microsoft Graph API. Necesario para permitir a los usuarios buscar grupos de Active Directory. Además, este permiso es necesario para que la aplicación resuelva la pertenencia al grupo de AD de usuarios en trabajos web del back-end. | Pertenencia a grupos de usuarios. La pertenencia a grupos de usuarios se almacena en una memoria caché para minimizar las llamadas a microsoft Graph API. Necesario para permitir a los usuarios buscar grupos de Active Directory. Además, este permiso es necesario para que la aplicación resuelva la pertenencia al grupo de AD de usuarios en trabajos web del back-end.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | aplicación | Los datos recuperados del perfil de usuario dependen de la configuración de la función de segmentación de público especificada en la aplicación. Necesario para permitir que la aplicación lea perfiles de usuario sin un usuario iniciado en sesión. Se necesitan datos de perfil de lectura para la característica de segmentación de información dentro de la aplicación, de modo que la información se muestre a usuarios específicos en función de un valor de propiedad de perfil específico.  | ninguno | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | dirección de correo electrónico, nombre para mostrar | Enviar notificación al usuario por correo electrónico y notificaciones push móviles |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>dirección de correo electrónico, UPN. máximo 60 días de retención, después de que se eliminan

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los administradores pueden ponerse en contacto con el soporte técnico para cualquier consulta

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

LiveTiles ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | No |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | Sí |
| Enumere los tipos de directivas admitidas | Autenticación multifactor, restricción de ubicaciones de usuarios y rangos IP |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
