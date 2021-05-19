---
title: Información de aplicación para el ecBooking de Expert Systems IVR(Asia) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para ecBooking, sus políticas de control de datos, su Microsoft Cloud App Security información de catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1cdd05e4acfb1c7720af1a2e22b2c6d29425ca60
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552181"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 28 de diciembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Expert Systems IVR(Asia) Co.Ltd. a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | ecBooking |
| ID | WA200002096 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Expert Systems IVR(Asia) Co.Ltd. |
| URL del sitio web de socios | [https://www.esi-asia.com/](https://www.esi-asia.com/) |
| URL de Teams página de información de la aplicación | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL de la Política de Privacidad | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL de los Términos de uso | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por expert systems IVR(Asia) Co.Ltd. sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicación | Se almacenan datos como correo electrónico de usuario, eventos de usuario. Los eventos de usuario se recopilan para comprobar la disponibilidad de las salas y crear eventos. | Se almacenarían el IDENTIFICADOR del evento de usuarios, el nombre de la ubicación y los detalles de otros eventos. Los datos se recopilan para comprobar la disponibilidad de las habitaciones y crear eventos. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| Mail.Send | aplicación | Datos como correo electrónico de usuario. El correo electrónico del usuario se recopila para enviar el correo electrónico de recordatorio de reserva de la habitación. | Datos como correo electrónico de usuario. El correo electrónico del usuario se recopila para enviar el correo electrónico de recordatorio de reserva de la habitación. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read | Delegado | Datos como ID de usuario, nombre y correo electrónico. Los datos de usuario se recopilan para iniciar sesión del usuario en la aplicación. | Datos como ID de usuario, nombre y correo electrónico. Los datos de usuario se recopilan para iniciar sesión del usuario en la aplicación. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read.All | aplicación | Datos como ID de usuario, nombre y correo electrónico. Los datos de usuario se recopilan para iniciar sesión del usuario en la aplicación. | Datos como ID de usuario, nombre y correo electrónico. Los datos de usuario se recopilan para iniciar sesión del usuario en la aplicación. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| email | Delegado | Datos como correo electrónico de usuario. Email del usuario se recopila para comprobar la disponibilidad del usuario y crear eventos. | Datos como correo electrónico de usuario. Email del usuario se recopila para comprobar la disponibilidad del usuario y crear eventos. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| OpenID | Delegado | Orden de openid del usuario para permitir que el usuario inicie sesión en la aplicación. | Orden de openid del usuario para permitir que el usuario inicie sesión en la aplicación. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Se almacenan datos como correo electrónico de usuario, eventos de usuario. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Datos almacenados en la base de datos.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Esta información ha sido proporcionada por expert systems IVR(Asia) Co.Ltd. acerca de cómo esta aplicación controla la autenticación, autorización, prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | No |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/><br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
