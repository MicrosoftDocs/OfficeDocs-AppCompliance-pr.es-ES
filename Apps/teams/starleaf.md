---
title: Información de la aplicación para StarLeaf por StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para StarLeaf, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8f9878d4de6e09c283c6d13ee7351de9fb5f0eb8
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528236"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por StarLeaf a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | StarLeaf |
| Id. | WA200000185 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | StarLeaf |
| Dirección URL del sitio web de partners | [https://www.starleaf.com](https://www.starleaf.com) |
| Dirección URL de la directiva de privacidad | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| DIRECCIÓN URL de términos de uso | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

StarLeaf ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | aplicación | almacenamos el iCalUId de las reuniones, la hora/fecha de la reunión, las direcciones de correo electrónico de los asistentes y una propiedad single-value-extended que leemos y escribimos en la reunión mediante la interfaz de propiedades personalizadas de Office.js. El iCalUId se usa para correlacionar la reunión en un calendario de outlook&#8217;usuario con la reunión de vídeo en nuestro servicio. La hora/fecha y los asistentes se usan para proporcionar una reunión de vídeo en el momento adecuado a las personas correctas en nuestro servicio. SVEP se usan con nuestro addin de O365 para proporcionar una interfaz para que los usuarios establezcan detalles sobre la reunión de vídeo en nuestro servicio, como la grabación. | se usa para suscribirse a notificaciones de webhook para realizar un seguimiento de los cambios de los usuarios en los eventos de sus calendarios y actualizar nuestro servicio para mantenerlo coherente. También se usa para crear eventos en su calendario cuando un usuario interactúa con nuestra Teams y programa una reunión en nuestro servicio. | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |
>| User.Read | aplicación | almacenamos el token de actualización de oauth para poder iniciar sesión. Almacenamos el id. de perfil de los usuarios para poder compararlos con futuros intentos de OAuth de ese usuario y nos aseguramos de&#8217;almacenar sus detalles dos veces.  | permitir a los usuarios iniciar sesión en la aplicación y permite a nuestra aplicación obtener la dirección de correo electrónico del usuario&#8217;para correlacionar su inicio de sesión con una cuenta en nuestro servicio.  | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Si surgen problemas de soporte técnico, los datos organizacionales se pueden transferir a SalesForce para la administración de casos. Si el usuario usa la característica de acceso telefónico RTC, la llamada fluirá a través de Twilio, Plivo o Voxbone |  | N/D |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| El bot tiene acceso a la lista del equipo para reservar una reunión en nombre del usuario/host que reserva la reunión a través del bot. Esto permite que StarLeaf proporcione una experiencia de unión sin problemas con un botón para unirse a reuniones. | Nombre, apellido, dirección de correo electrónico. Esto permite al bot starleaf reservar una reunión en nombre del usuario o host que ha interactuado con el bot e invitar a los demás miembros del equipo a la reunión. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Sí. Los registros incluyen nombres de usuario, direcciones IP, registros de detalles de llamadas, información sobre la calidad de la conexión (pérdida de paquetes, velocidad de bits), tipo de dispositivo, progreso de la llamada. La información está disponible para el equipo de soporte técnico y los desarrolladores sénior para diagnosticar problemas de servicio. Los datos se anonimizarán después de 90 días. Los controles para proteger estos datos se auditan con nuestra certificación ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos se almacenan en los propios servidores de registro de StarLeaf&#8217;en el centro de datos en el que se encuentra la cuenta del usuario&#8217;y se hace una copia de seguridad de uno o más centros de datos dentro de la misma jurisdicción. El acceso a los datos es por cuenta de usuario individual mediante contraseñas por usuario que se comprueban de forma segura. Las cuentas de usuario de servicio de StarLeaf&#8217;se auditan automáticamente en los sistemas de recursos humanos y los grupos corporativos de Active Directory para avisar al equipo de seguridad y cumplimiento si se encuentran anomalías.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

