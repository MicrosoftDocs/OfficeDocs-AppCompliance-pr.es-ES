---
title: Información de la aplicación para ezTeam por EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para ezTeam, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553181"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por EnterprizID Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ezTeam |
| ID | WA200002546 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | EnterprizID Inc |
| Dirección URL del sitio web de partners | [https://enterprizid.com](https://enterprizid.com) |
| Dirección URL de Teams de información de la aplicación | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| Dirección URL de la directiva de privacidad | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

EnterprizID Inc ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | delegado | Lista de aplicaciones disponibles en Teams para que podamos mostrarla en el Teams de creación de solicitudes | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | delegado | Permite que la aplicación lea las aplicaciones y entidades de servicio en nombre del usuario que ha iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | delegado | Permite que la aplicación tenga el mismo acceso a la información del directorio que el usuario que ha iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | delegado | Permite que la aplicación lea los datos del directorio de su organización, como los usuarios, los grupos y las aplicaciones. | Teams Información de pertenencia y propiedad  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | aplicación | Permite que la aplicación lea los datos del directorio de su organización, como los usuarios, los grupos y las aplicaciones sin iniciar sesión con ningún usuario. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | delegado | Permite que la aplicación lea y escriba datos en el directorio de la organización, como usuarios y grupos | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | aplicación | Permite que la aplicación lea y escriba los datos del directorio de su organización, como los usuarios y los grupos sin iniciar sesión con ningún usuario. No se permite la eliminación de un usuario o un grupo. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | aplicación | Permite que la aplicación lea todos los archivos de todas las colecciones de sitios sin la necesidad de que un usuario haya iniciado sesión. | Cantidad de datos bajo el gobierno del usuario final en GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | aplicación | Permite que la aplicación cree grupos sin un usuario que haya iniciado sesión. | Nuevos detalles de propiedades de grupo. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | delegado | Permite que la aplicación enumere grupos y lea sus propiedades y todas las pertenencias a los grupos en nombre del usuario que ha iniciado sesión. Se usa para determinar Mi Teams  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | aplicación | Permite que la aplicación lea las propiedades y pertenencias del grupo y lea el calendario y las conversaciones de todos los grupos, sin que un usuario haya iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | delegado | Permite que la aplicación cree grupos y lea todas las propiedades de los grupos y las pertenencias en nombre del usuario que ha iniciado sesión.  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | aplicación | Permite a la aplicación crear grupos, leer todas las propiedades y pertenencias del grupo, actualizar las propiedades y pertenencias del grupo y eliminar grupos. También permite que la aplicación lea y escriba el calendario de grupo y las conversaciones.  | Última actividad del equipo. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | aplicación | Permite que la aplicación lea pertenencias y propiedades de grupo básicas para todos los grupos sin un usuario que haya iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | aplicación | Permite que la aplicación enumere grupos, lea propiedades básicas, lea y actualice la pertenencia a los grupos a los que tiene acceso esta aplicación sin un usuario que haya iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | aplicación | Permite que la aplicación lea la lista puntuada de personas relevantes de cualquier usuario, sin que un usuario haya iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | delegado | Permite a una aplicación leer todos los informes de uso de servicio en nombre del usuario que ha iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | aplicación | Permite a una aplicación leer todos los informes de uso de servicio sin necesidad de que un usuario haya iniciado sesión. | Última actividad de usuario por grupo | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | aplicación | Permite que la aplicación cree, lea, actualice y elimine documentos y elementos de lista de todas las colecciones de sitios sin necesidad de que un usuario haya iniciado sesión. | Top 10 sites by size for each user | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | delegado | Permite a los usuarios iniciar sesión en la aplicación y permite que la aplicación lea el perfil de los usuarios que han iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | aplicación | Permite que la aplicación lea los perfiles de usuario sin que un usuario haya iniciado sesión. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | delegado | Permite que la aplicación vea y actualice los datos a los que le dio acceso, incluso cuando los usuarios no estén usando actualmente la aplicación.  | Notificaciones de bot | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| OpenID | delegado | Permite que los usuarios inicien sesión en la aplicación con sus cuentas profesionales o educativas y permite que la aplicación vea la información básica del perfil del usuario. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| perfil | delegado | Permite que la aplicación vea el perfil básico de los usuarios (nombre, imagen, nombre de usuario) | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Mensajes de bienvenida, aprobación y notificaciones de procesos de atestación | Almacenamos el nombre para mostrar de las identidades  | Nuestra herramienta permite a los usuarios finales crear solicitudes para distintos elementos de servicio y almacenamos el nombre para mostrar del solicitante. Una solicitud seguiría un flujo de trabajo de aprobación y necesitamos el nombre para mostrar del aprobador para mostrar en los detalles de la solicitud. Además, en los miembros de un proceso de certificación de equipo enumeramos el nombre para mostrar de los miembros. |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>EndUser y Nombre completo de la organización. Las directivas de retención y eliminación se pueden encontrar en https://enterprizid.com/privacy-policy la sección Retención de sus datos &quot; &quot; personales

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Hemos habilitado Privileged Access Management (PMA) en Azure y las identidades con privilegios para conectarse a los recursos usan 2FA para aumentar la seguridad. Usamos Azure como nuestro proveedor de partners en la nube y estamos sujetos a la privacidad y los términos de uso de Azure

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

EnterprizID Inc ha proporcionado esta información sobre cómo esta aplicación administra la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
