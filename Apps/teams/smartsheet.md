---
title: Información de la aplicación para Smartsheet por Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Smartsheet, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551530"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 16 de diciembre de 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Smartsheet a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Smartsheet |
| ID | WA104380975 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Smartsheet |
| URL del sitio web de socios | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL de Teams página de información de la aplicación | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL de la Política de Privacidad | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL de los Términos de uso | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Smartsheet ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos de organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegado | Ninguno. | Permite a nuestra aplicación instalar aplicaciones en nombre del usuario. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Delegado | tenantId para recuperar información para mostrar en la interfaz de usuario. | Nos permite leer qué aplicaciones está utilizando este inquilino para que podamos comprobar si necesitamos instalar la aplicación para ellas. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Delegado | teamId/groupId para la entrega de mensajes. | Permite que nuestra aplicación lea información básica sobre un grupo (o equipo Teams) así como conversaciones. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Delegado | teamId/groupId para la entrega de mensajes. | Permite que nuestra aplicación inicie nuevas conversaciones en equipos. Este permiso también incluye el ámbito Read.All anterior, pero también lo necesitamos por razones técnicas. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Delegado | userId. | Nos permite leer información básica sobre un usuario durante el proceso de autenticación. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Delegado | refreshToken. | Permite que nuestra aplicación reciba tokens de actualización y actualice el token de autenticación en nombre del usuario cuando usa la aplicación. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Acceso a datos mediante otras API de Microsoft

Las aplicaciones y complementos basados en Microsoft 365 pueden usar API de Microsoft adicionales distintas de Microsoft Graph recopilar o procesar información de identificación organizacional (OII). Enumere las API de Microsoft distintas de Microsoft Graph que usa esta aplicación.

>| **API** |  **¿Se recoge OII?** |  **¿Qué OII se recoge?** | **¿Justificación para cobrar OII?** | **¿Se almacena OII?** | **¿Justificación para almacenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API de Bot Framework | Sí | Usamos la API de Bot Framework para entregar mensajes como aplicación para la aplicación de equipos. Smartsheet almacena información userId para realizar un seguimiento de con quién está hablando el bot de Smartsheet. |  | Ninguno |  |

#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet almacena información en un estado cifrado en reposo dentro de nuestro entorno de centro de datos de producción hospedado con Equinix y en AWS S3, donde almacenamos archivos adjuntos de clientes en buckets cifrados privados. |  | Usamos la API de marco de bots para entregar mensajes como aplicación para la aplicación de equipos. Smartsheet almacena información userId para realizar un seguimiento de con quién está hablando el bot de Smartsheet. |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet lo utiliza para ayudar a realizar un seguimiento de quién es el bot también está hablando. Durante el flujo de autenticación inicial, creamos un registro de bot para el usuario en el sistema de notificación Smartsheet. | Para Smartsheet para Teams bot, almacenamos correo electrónico de usuario y userId desde Teams para ayudar a realizar un seguimiento de con quién está hablando el bot.  Smartsheet almacena tenantIds para ayudar a enumerar los grupos de los que el usuario forma parte en el directorio y groupIds para la entrega de mensajes. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Smartsheet cifra toda la información del usuario almacenada y nuestros administradores están obligados a usar 2FA. Smartsheet funciona como un proveedor SaaS sin visión y, de forma predeterminada, no revisamos el contenido que los clientes eligen cargar o entrar en la plataforma.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

