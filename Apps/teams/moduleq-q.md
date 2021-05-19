---
title: Información de la aplicación para Q por ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Q, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3424ac372f46be0fc9834611fb1a0d57c69831a4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551910"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 17 de marzo de 2020</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ModuleQ a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Q |
| ID | WA104381433 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | ModuleQ |
| URL del sitio web de socios | [https://moduleq.com](https://moduleq.com) |
| URL de la Política de Privacidad | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL de los Términos de uso | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

ModuleQ ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | aplicación | almacena los datos de la reunión, excepto el cuerpo del mensaje y cualquier archivo adjunto | Permite a la aplicación leer los eventos de calendario de un usuario con el fin de comprender inteligentemente las prioridades empresariales del usuario. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | Delegado | Ninguno | Permite que la aplicación interactúe en un equipo para compartir contenido. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | aplicación | almacena los datos de correo electrónico, excepto el cuerpo del mensaje y cualquier archivo adjunto | Permite a la aplicación leer el correo de un usuario con el fin de comprender inteligentemente las prioridades empresariales del usuario | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | Delegado | correo electrónico del usuario y tokens de autenticación | Permite al usuario iniciar sesión y vincular su cuenta de Office 365 con su cuenta ModuleQ | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | Delegado | Ninguno | Permita que la aplicación obtenga la lista de Teams de la que forma parte el usuario. Solo se utiliza para compartir  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Registramos un GUID de usuario interno y nombres y dominios de organización. Por el momento no hay controles de archivado o eliminación.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos se almacenan en la nube de Microsoft Azure en varios microservicios según su función. Todos los datos identificables por el usuario se cifran en el lado cliente con el cifrado AES-256 antes de transmitir para el almacenamiento. Los datos pueden ser vistos por los ingenieros con fines de depuración con la aprobación de nuestra alta dirección. El acceso a los datos se controla a través de VPN interna.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

