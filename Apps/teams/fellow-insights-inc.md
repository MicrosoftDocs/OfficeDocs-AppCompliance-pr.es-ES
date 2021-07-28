---
title: Información de aplicación para becario por miembro Ideas Inc
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para el miembro, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 581b41bdf80bcbdd77bb3406b35556308a13b8f9
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525644"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Fellow Ideas Inc a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Fellow |
| Id. | WA200002576 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Fellow Insights Inc |
| Dirección URL del sitio web de partners | [https://fellow.app](https://fellow.app) |
| Dirección URL de la directiva de privacidad | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| DIRECCIÓN URL de términos de uso | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Esta información ha sido proporcionada por Fellow Ideas Inc sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | ambos | El compañero se conecta con los calendarios del usuario para proporcionarles la capacidad de tomar notas sobre los datos. | Los compañeros almacenan todos los datos de eventos del calendario principal del usuario. Los datos adjuntos no se almacenan. Esto se usa dentro de Fellow para proporcionar una experiencia de toma de notas basada en calendario. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | delegado | Recopilamos los nombres de canales de los que un usuario es miembro para mostrarles una lista de canales a los que pueden enviar notas. | Almacenamos en caché los nombres e id. de los canales de los que un usuario es miembro, para permitir que los usuarios envíen notas de Fellow al canal especificado. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | aplicación | Estos datos solo se recopilan si se realiza una instalación de administrador para toda la organización. Usamos los datos de directorio para sincronizar una lista de usuarios y aprovisionar cuentas automáticamente. | Si el administrador realiza una instalación en toda la organización desde dentro de la configuración del área de trabajo dentro de Fellow, los administradores tienen la opción de habilitar la sincronización automática de todos los usuarios de Azure AD en Fellow (aprovisionamiento automático). En este caso, almacenamos información de usuario, como id., nombre, correo electrónico y administrador, y pertenencias a grupos (para funcionalidades de administración de equipos). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | aplicación | Estos datos solo se recopilan si se realiza una instalación de administrador para toda la organización. Usamos los datos de directorio para sincronizar una lista de usuarios y aprovisionar cuentas automáticamente. | Si el administrador realiza una instalación en toda la organización desde dentro de la configuración del área de trabajo dentro de Fellow, los administradores tienen la opción de habilitar la sincronización automática de todos los usuarios de Azure AD en Fellow (aprovisionamiento automático). En este caso, almacenamos información de usuario, como id., nombre, correo electrónico y administrador, y pertenencias a grupos (para funcionalidades de administración de equipos). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | delegado | Los contactos del usuario se recopilan, en determinados contactos displayNames y direcciones de correo electrónico. Esto se usa dentro de Fellow para proporcionar una lista de usuarios con los que invitar a una nota o compartir una nota. | Los contactos del usuario se recopilan, en determinados contactos displayNames y direcciones de correo electrónico. Esto se usa dentro de Fellow para proporcionar una lista de usuarios con los que invitar a una nota o compartir una nota. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | aplicación | Estos datos solo se recopilan si se realiza una instalación de administrador para toda la organización. Los contactos del usuario se recopilan, en determinados contactos displayNames y direcciones de correo electrónico. Esto se usa dentro de Fellow para proporcionar una lista de usuarios con los que invitar a una nota o compartir una nota. | Si el administrador realiza una instalación en toda la organización desde dentro de la configuración del área de trabajo dentro de Fellow, los administradores tienen la opción de habilitar la sincronización automática de todos los usuarios de Azure AD en Fellow (aprovisionamiento automático). En este caso, se recopilan los contactos del usuario, en direcciones de correo electrónico y displayNames de contactos específicos. Esto se usa dentro de Fellow para proporcionar una lista de usuarios con los que invitar a una nota o compartir una nota. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | delegado | Se recopila una lista de equipos de los que forma parte el usuario. Esto se usa dentro del miembro con el fin de permitir que el usuario envíe notas de Miembro a un equipo. | Almacenamos en caché los nombres e id. de los equipos de los que un usuario es miembro, con el fin de permitir que los usuarios envíen notas de Miembro al canal de equipos especificado. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | delegado | Se recopila información básica del usuario. Nombre de usuario, correo electrónico, puesto de trabajo. Esta información se usa dentro de Fellow para crear cuentas de usuario y cuentas de empresa. | Se almacena la información básica del usuario. Nombre de usuario, correo electrónico, puesto de trabajo. Esta información se usa dentro de Fellow para mantener cuentas de usuario y cuentas de empresa. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | aplicación | Estos datos solo se recopilan si se realiza una instalación de administrador para toda la organización. Usamos los datos de directorio para sincronizar una lista de usuarios y aprovisionar cuentas automáticamente. | Si el administrador realiza una instalación en toda la organización desde dentro de la configuración del área de trabajo dentro de Fellow, los administradores tienen la opción de habilitar la sincronización automática de todos los usuarios de Azure AD en Fellow (aprovisionamiento automático). En este caso, almacenamos información de usuario, como id., nombre, correo electrónico y administrador, y pertenencias a grupos (para funcionalidades de administración de equipos). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | delegado | Token de actualización del usuario para mantener el acceso a los datos recopilados a través de otros ámbitos. | El token de actualización del usuario se almacena en la base de datos. Esto se usa en Miembro para sincronizar eventos en segundo plano para la experiencia de toma de notas basada en calendario, así como notificaciones para tomar notas sobre eventos programados. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Los compañeros almacenan información proporcionada directamente por el usuario, incluidos los datos personales. El miembro también almacena información de sistemas de terceros, como datos de OAuth, datos de calendario y PII, como el correo electrónico de &amp; nombre. Conservamos todos los datos de forma indefinida, durante el tiempo necesario y legalmente permitido para el propósito para el que se recopilaron. Eliminamos esta información de forma segura en una fecha anterior al recibir una solicitud de los usuarios. Los datos de registro se conservan durante 30 días.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Todas las transferencias de datos se producen a través de API protegidas a nuestros sistemas back-end. Fellow emplea muchos controles para garantizar la seguridad y confidencialidad de sus sistemas, según el marco SOC 2 definido por AICPA. Los controles del miembro se someten a una auditoría anual para garantizar el cumplimiento continuo. Se puede compartir un informe SOC 2 a petición y NDA.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por Fellow Ideas Inc sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para el escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará dinámica e incrementalmente? | Sí |
| ¿La aplicación admite multiinquilino? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de todos los identificadores de recursos unificados (URI) de redireccionamiento registrados para la aplicación? | Sí |
| Para tu aplicación, ¿qué evitas usar? | ,<br/><br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | No |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
