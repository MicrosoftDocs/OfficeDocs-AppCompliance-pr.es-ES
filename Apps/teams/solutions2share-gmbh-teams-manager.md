---
title: Información de aplicaciones para Teams manager de Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Teams Manager, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bd7be587324879df814c495f4f88d2ed8deddf30
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423102"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Solutions2Share GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Teams Manager |
| Id. | WA200000764 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Solutions2Share GmbH |
| Dirección URL del sitio web de partners | [https://teams-manager.com](https://teams-manager.com) |
| Dirección URL de Teams de información de la aplicación | [https://teams-manager.com](https://teams-manager.com) |
| Dirección URL de la directiva de privacidad | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Solutions2Share GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | ambos | Almacenamos tenantID y TeamId para asignar las plantillas.  | Permitir enumerar todos los Teams y también crear Teams. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| Notes.ReadWrite.All | aplicación | Ninguno | Permite que la aplicación agregue blocs de notas a un equipo aprobado. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read | delegado | Ninguno | Permite al usuario iniciar sesión y da acceso a la aplicación a su UPN para habilitar el inicio de sesión silencioso. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read.All | ambos | Guardamos el identificador del usuario que se ha escrito en la sección aprobador/administrador. | Enumerar todos los usuarios para mostrarlos en el selector de personas dentro de la aplicación. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.ReadBasic.All | delegado | Ninguno | Enumerar todos los usuarios para mostrarlos en el selector de personas dentro de la aplicación. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Estamos iniciando sesión en Azure Log Analytics y estamos usando sus directivas de retención/archivo.
Estamos registrando el identificador de inquilino y el identificador de equipo para identificar problemas y ayudar a los clientes a resolver problemas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Tenemos un proceso de cumplimiento y operación para el control de acceso. Todos los datos y tokens relacionados con el usuario están cifrados. Los datos se almacenan en un Azure SQL Database. Estamos usando el Firewall para permitir solo conexiones de ip específicas (intervalos IP protegidos entre sistemas). Hemos habilitado Privileged Access Management (PMA) en Azure.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Solutions2Share GmbH ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/><br/> |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
