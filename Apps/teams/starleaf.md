---
title: Información de la aplicación starleaf de StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para StarLeaf, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9dc0761fa00e94d97f3d29b4ac85e1d607498288
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553841"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por StarLeaf a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | StarLeaf |
| ID | WA200000185 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | StarLeaf |
| URL del sitio web de socios | [https://www.starleaf.com](https://www.starleaf.com) |
| URL de la Política de Privacidad | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| URL de los Términos de uso | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

StarLeaf ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicación | almacenamos el iCalUId de reuniones, hora/fecha de la reunión, direcciones de correo electrónico de asistentes y una propiedad extendida de un solo valor que leemos y escribimos en la reunión mediante la interfaz de propiedades personalizadas Office.js. El iCalUId se utiliza para correlacionar la reunión en un calendario de Outlook de&#8217;usuario con la reunión de vídeo en nuestro servicio. La hora/fecha y los asistentes se utilizan para proporcionar una reunión de video en el momento adecuado a las personas adecuadas en nuestro servicio. SVEP están acostumbrados a nuestro complemento O365 para proporcionar una interfaz para que los usuarios establezcan detalles sobre la reunión de vídeo en nuestro servicio, como la grabación. | solía suscribirse a las notificaciones de webhook para realizar un seguimiento de los cambios de usuario en los eventos de sus calendarios y actualizar nuestro servicio para mantenerlo coherente. También se utiliza para crear eventos en su calendario cuando un usuario interactúa con nuestra aplicación Teams y programa una reunión en nuestro servicio. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | aplicación | almacenamos el token de actualización de oauth para poder iniciar sesión. Almacenamos el id de perfil de los usuarios para poder compararlo con futuros intentos de OAuth de ese usuario y nos aseguramos de que no&#8217;almacenar sus datos dos veces.  | permitir a los usuarios iniciar sesión en la aplicación y permite a nuestra aplicación obtener que el usuario&#8217;dirección de correo electrónico para correlacionar su inicio de sesión con una cuenta en nuestro servicio.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Si surgen problemas de soporte técnico, los datos organizativos pueden transferirse a SalesForce para la gestión de casos. Si el usuario hace uso de la función de acceso telefónico PSTN, la llamada fluirá a través de Twilio, Plivo o Voxbone |  | N/D |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| El bot accede a la lista del equipo para reservar una reunión en nombre del usuario/anfitrión que reserva la reunión a través del bot. Esto permite a StarLeaf proporcionar una experiencia de unión perfecta con un solo botón para unirse a las reuniones. | Nombre, apellido, dirección de correo electrónico. Esto permite al bot StarLeaf reservar una reunión en nombre del usuario/host que ha interactuado con el bot e invitar a los demás miembros del equipo a la reunión. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>Sí. Los registros incluyen nombres de usuario, direcciones IP, registros de detalles de llamadas, información sobre la calidad de la conexión (pérdida de paquetes, velocidad de bits), tipo de dispositivo, progreso de la llamada. La información está disponible para el equipo de soporte técnico y los desarrolladores sénior para diagnosticar problemas de servicio. Los datos se anoniman después de 90 días. Los controles para proteger estos datos se auditan bajo nuestra certificación ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos se almacenan en starleaf&#8217;propios servidores de registro en el centro de datos en el que se encuentra la cuenta de&#8217;s del usuario y se realiza una copia de seguridad de uno o varios centros de datos dentro de la misma jurisdicción. El acceso a los datos es por cuenta de usuario individual utilizando contraseñas por usuario que están marcadas con fuerza. Las cuentas de usuario de servicio de StarLeaf&#8217;s se auditan automáticamente con los sistemas hr y los grupos corporativos de Active Directory para alertar al equipo de seguridad y cumplimiento si se encuentran anomalías.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

