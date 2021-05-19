---
title: Información de la aplicación OnePlaceMail para Outlook por OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para OnePlaceMail para Outlook, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552501"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 31 de enero de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por OnePlace Solutions a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | OnePlaceMail para Outlook |
| ID | WA104380723 |
| Office 365 clientes compatibles | Outlook 2013 o posterior en Windows, Outlook 2016 o posterior en Mac, Outlook en iOS, Outlook en Android, Outlook en la web |
| Nombre de la empresa asociada | Soluciones oneplace |
| URL del sitio web de socios | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL de la Política de Privacidad | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL de los Términos de uso | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

OnePlace Solutions ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegado | Necesario para determinar Teams el usuario actual es miembro de. | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | Delegado | Necesario para tener acceso a las propiedades de correo para establecer SharePoint columnas y agregar la categoría Transferido a SharePoint en el elemento de correo | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | Delegado | Sin datos recopilados o utilizados, esto se usa para agregar una categoría a la lista de categorías maestras en un buzón de usuario | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | Delegado | Necesario para establecer propiedades en los elementos que la aplicación ha cargado en SharePoint. | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | Delegado | Necesario para la autenticación en el Graph de Microsoft. | La aplicación almacena los siguientes datos en una base de datos y se utiliza para el seguimiento de suscripción y licencia de usuario: Id de usuario, Correo electrónico, Nombre, Apellido. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Delegado | Necesario para mostrar la imagen de perfil de usuario en el campo selector de personas. | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Delegado | Necesario para mostrar la imagen de perfil de usuario en el campo selector de personas. | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | Delegado | Necesario para determinar si el servicio de Teams está habilitado dentro de los usuarios Office 365 tenencia. | Ninguno | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Sí | SharePoint Urls, nombres de biblioteca/lista/carpeta | La información organizativa a la que se accede se utiliza para facilitar el proceso de guardar el correo electrónico y los archivos adjuntos de Exchange a SharePoint. Estos datos adicionales no se almacenan en reposo y se cifran en tránsito. Ejemplos de estos datos incluyen valores de columna SharePoint como valores de columna Choice, valores de Taxonomía, nombres de tipo de contenido, nombres de carpeta, nombres de sitio.  | Aunque esta aplicación no almacena ni recopila estos datos, puede aparecer en telemetría/registros donde se conserva durante 90 días. | Los datos no se almacenan |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| El servicio Chargify se utiliza para la administración y facturación de suscripciones. Para la creación de suscripciones en la aplicación (gratuita) el nombre, apellido, dirección de correo electrónico del usuario se comparten con Chargify. Para las suscripciones adquiridas (que admiten varios usuarios con licencia), los detalles individuales del usuario no se comparten con el servicio Chargify. | Dirección de correo electrónico | Para poder comunicar eventos del ciclo de vida de la suscripción al usuario |



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>EUII y OII aparecen en telemetría. Esta información se almacena en Application Insights, cifrada en reposo, controla y elimina el acceso después de 90 días

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos almacenados en la aplicación se cifran en tránsito y en reposo. Confiamos en Office 365 credenciales para nuestras aplicaciones, por lo que no almacenamos contraseñas de usuario en nuestro sistema. El acceso a los datos almacenados/ registros / telemetría se controla estrictamente al personal de administración interna con la necesidad de acceder a la información con el fin de ejecutar y supervisar el estado de la aplicación. Two-Factor Autenticación aplicada para todo el personal de administración interna.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

OnePlace Solutions ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación solicita permisos de privilegios mínimos para su escenario? | Sí |
| ¿Los permisos registrados estáticamente de la aplicación reflejan con precisión los permisos que la aplicación solicitará de forma dinámica e incremental? | Sí |
| ¿La aplicación admite multi-tenencia? | Sí |
| ¿La aplicación tiene un cliente confidencial? | Sí |
| ¿Es propietario de toda la redirección del identificador unificado de recursos (URI) registrado para la aplicación? | Sí |
| Para la aplicación, ¿qué evitas usar? | - Uris de redirección comodín,<br/>- OAuth2 Flow implícitas, a menos que sea necesario para un SPA<br/>- Flujo de credenciales de contraseña del propietario de recursos (ROPC) |
| ¿La aplicación expone alguna API web? | Sí |
| ¿Su modelo de permisos solo permite que las llamadas se realicen correctamente si la aplicación cliente recibe el consentimiento adecuado? | Sí |
| ¿La aplicación usa API de vista previa? | No |
| ¿La aplicación usa API en desuso? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
