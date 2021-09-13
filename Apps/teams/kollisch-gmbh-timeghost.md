---
title: Información de la aplicación para timeghost de K&#246;llisch GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para timeghost, sus directivas de control de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c024080e1471388a5c3803f685a136052cb56d44
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288128"
---
# <a name="timeghost"></a>timeghost

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e3956558-7399-4ec1-848a-c61a2aa95bc1" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001532" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por K&#246;llisch GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | timeghost |
| Id. | WA200001532 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | K&#246;llisch GmbH |
| Dirección URL del sitio web de partners | [https://timeghost.io](https://timeghost.io) |
| Dirección URL de Teams de información de la aplicación | [https://timeghost.io](https://timeghost.io) |
| Dirección URL de la directiva de privacidad | [https://timeghost.io/privacy-policy/](https://timeghost.io/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://timeghost.io/terms-and-conditions/](https://timeghost.io/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

K&#246;llisch GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Titel, Startdatum, Enddatum, ID | Kalenderdaten werden beim Buchen eines Kalendereintrages auf ein Projekt gespeichert. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| People.Read | delegado | E-Mail-Adresse | Die Daten werden gespeichert um weitere Team-Mitglieder hinzuzuf&#252;gen und die Avatare der Nutzer anzuzeigen. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| User.Read | delegado | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| User.ReadBasic.All | delegado | Um das Profilbild anzuzeigen. | Keine Daten werden gespeichert. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| OpenID | delegado | Id.  | Speicherung der ID des Users zur Zuordnung des Users. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| perfil | delegado | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Sentry.io, Chargebee | Vorname, Nachname, E-Mail-Adresse, Firmenname  | Zur Fehlerermittlung, Zahlungs&#252;bermittlung |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>E-Mail-Adresse, Id. de usuario

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Auditoría

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

K&#246;llisch GmbH proporciona esta información sobre cómo esta aplicación administra la autenticación, autorización, procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/> |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | Sí |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
