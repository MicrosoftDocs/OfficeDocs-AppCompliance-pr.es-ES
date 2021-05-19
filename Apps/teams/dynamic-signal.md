---
title: Información de la aplicación para señal dinámica por señal dinámica
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Dynamic Signal, sus políticas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552231"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Dynamic Signal a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Dynamic Signal |
| ID | WA200000102 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Dynamic Signal |
| URL del sitio web de socios | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL de Teams página de información de la aplicación | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL de la Política de Privacidad | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL de los Términos de uso | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

La señal dinámica ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegado | Dynamic Signal sincroniza al usuario de Azure AD con su plataforma para permitir la activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Señal dinámica para permitir a los usuarios usar esa aplicación mientras se lleva a cabo la sincronización. | Permisos de lectura de un usuario específico para sincronizar usuarios de plataforma de señal dinámica con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | Delegado | Dynamic Signal sincroniza al usuario de Azure AD con su plataforma para permitir la activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Señal dinámica para permitir a los usuarios usar esa aplicación mientras se lleva a cabo la sincronización. | Permisos de lectura de un usuario específico para sincronizar usuarios de plataforma de señal dinámica con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | Delegado | Dynamic Signal sincroniza al usuario de Azure AD con su plataforma para permitir la activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Señal dinámica para permitir a los usuarios usar esa aplicación mientras se lleva a cabo la sincronización. | Conservar el acceso a los grupos y equipos del inquilino. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| OpenID | Delegado | Dynamic Signal sincroniza al usuario de Azure AD con su plataforma para permitir la activación y desactivación optimizadas de los usuarios en tiempo real. Los datos se almacenan en Señal dinámica para permitir a los usuarios usar esa aplicación mientras se lleva a cabo la sincronización. | Autentique a los usuarios con la aplicación de señal dinámica. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid iniciar sesión con openid directory.readwrite.all acceso al dominio y grupos del inquilino, agregar una aplicación a un equipo offline_access conservar el acceso a los grupos y equipos del inquilino | openid Permitir autenticación independiente. directory.readwrite.all acceso al dominio y grupos del inquilino, agregue una aplicación a un equipo offline_access conservar el acceso a los grupos y equipos del inquilino Nota: La aplicación de Dynamic Signal usa el bot de equipos para aplicar grupos y permisos creados dentro de Dynamic Signal a Teams para que un usuario que esté activo en Señal dinámica tenga acceso a los mismos grupos y usuarios que dentro de Teams. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>La aplicación y la plataforma de señal dinámica utilizan la información del usuario para facilitar la integración con Microsoft Teams. Esta información está disponible para los usuarios con los permisos adecuados dentro de la plataforma de señal dinámica. La información relevante es Nombre, Nombre para mostrar y Correo electrónico. Esta información se almacena dentro de los registros de la plataforma de la señal dinámica de acuerdo con la directiva de la organización respectiva con la licencia de la señal dinámica.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos PII que se recopilan durante el registro y se almacenan dentro de la plataforma señal dinámica, incluyen: nombre, apellido, correo electrónico/identificador y cualquier campo personalizado configurado por la marca y/o los socios de agencia. Cuando los miembros usan Facebook o Twitter mediante oAuth Registration, algunos de los datos de usuario expuestos se presentan en la plataforma Dynamic Signal para rellenar previamente los datos. Estos datos incluyen nombre, ubicación y foto. Los usuarios tienen control sobre qué información y datos se presentan a los usuarios en las páginas biológicas de la comunidad. Los miembros pueden optar por cargar fotos personales o de marca, conectar cuentas sociales/canales y uso/puntos en el programa que se presentará en la página biológica.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

