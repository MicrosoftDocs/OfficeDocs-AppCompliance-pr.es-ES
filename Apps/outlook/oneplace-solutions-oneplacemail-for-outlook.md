---
title: Información de la aplicación para OnePlaceMail para Outlook soluciones de OnePlace
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para OnePlaceMail para Outlook, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 18dc1ab4ba71102564c1c85f7ed3846d9f4f1700
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287112"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 31, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por OnePlace Solutions a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | OnePlaceMail para Outlook |
| Id. | WA104380723 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en iOS, Outlook en Android, Outlook en la Web |
| Nombre de la compañía asociada | Soluciones de OnePlace |
| Dirección URL del sitio web de partners | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| Dirección URL de la directiva de privacidad | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| DIRECCIÓN URL de términos de uso | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

OnePlace Solutions ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Id. de aplicación de Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | Necesario para determinar Teams es miembro del usuario actual. | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | delegado | Necesario para tener acceso a las propiedades de correo para establecer SharePoint columnas y agregar la categoría Transfer to SharePoint en el elemento de correo | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | delegado | Sin datos recopilados o usados, se usa para agregar una categoría a la lista de categorías maestras en un buzón de usuarios | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | delegado | Necesario para establecer propiedades en los elementos que la aplicación ha cargado en SharePoint. | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | delegado | Necesario para la autenticación en microsoft Graph. | La aplicación almacena los siguientes datos en una base de datos y se usan para el seguimiento de la suscripción y la licencia de usuario: Id. de usuario, Correo electrónico, nombre, apellido. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegado | Necesario para mostrar la imagen de perfil de usuario en el campo selector de personas. | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegado | Necesario para mostrar la imagen de perfil de usuario en el campo selector de personas. | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | delegado | Necesario para determinar si el servicio Teams está habilitado dentro de los usuarios Office 365 arrendamiento. | Ninguno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos con otras API de Microsoft

Las aplicaciones y complementos integrados en Microsoft 365 pueden usar API de Microsoft adicionales que no sean Microsoft Graph para recopilar o procesar información identificable de la organización (OII). Enumerar cualquier API de Microsoft que no sea Microsoft Graph usa esta aplicación.

>| **API** |  **¿Se recopila OII?** |  **¿Qué OII se recopila?** | **¿Justificación para recopilar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Sí | SharePoint Direcciones URL, nombres de biblioteca/lista/carpeta | La información organizativa a la que se accede se usa para facilitar el proceso de guardar el correo electrónico y los datos adjuntos de Exchange a SharePoint. Estos datos adicionales no se almacenan en reposo y se cifran en tránsito. Algunos ejemplos de estos datos incluyen SharePoint de columna, como valores de columna De elección, Valores de taxonomía, Nombres de tipo de contenido, Nombres de carpeta, Nombres de sitio.  | Aunque la aplicación no almacena o recopila estos datos, puede aparecer en telemetría o registros donde se conservan durante 90 días. | Los datos no se almacenan |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| El servicio Chargify se usa para la administración de suscripciones y la facturación. Para la creación de suscripciones desde la aplicación (gratuita), el nombre, el apellido y la dirección de correo electrónico del usuario se comparten con Chargify. Para las suscripciones compradas (que admiten varios usuarios con licencia), los detalles de usuario individuales no se comparten con el servicio Chargify. | Dirección de correo electrónico | Para poder comunicar eventos de ciclo de vida de suscripción al usuario |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>EUII y OII aparecen en telemetría. Esta información se almacena en application Ideas, encrypted at rest, access controlled and deleted after 90 days

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los datos almacenados en la aplicación se cifran en tránsito y en reposo. Nos basamos en Office 365 credenciales para nuestras aplicaciones, por lo que no almacenamos contraseñas de usuario en nuestro sistema. El acceso a datos almacenados,registros/telemetría se controla estrechamente al personal de administración interna con la necesidad de obtener acceso a la información con el fin de ejecutar y supervisar el estado de la aplicación. Two-Factor autenticación obligatoria para todo el personal de administración interna.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

OnePlace Solutions ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, los procedimientos recomendados de registro de aplicaciones y otros criterios de identidad.

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
| Para tu aplicación, ¿qué evitas usar? | - URI de redireccionamiento comodín,<br/>- OAuth2 Implicit Flow, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña de propietario de recursos (ROPC) |
| ¿Expone la aplicación alguna API web? | Sí |
| ¿El modelo de permisos solo permite que las llamadas se puedan realizar correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa las API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
