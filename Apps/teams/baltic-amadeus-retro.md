---
title: Información de solicitud de Retro by Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Retro, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553461"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 3 de noviembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Baltic Amadeus a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Retro |
| ID | WA200001892 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Baltic Amadeus |
| URL del sitio web de socios | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL de la Política de Privacidad | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL de los Términos de uso | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Esta información ha sido proporcionada por Baltic Amadeus sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>Esta aplicación no utiliza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| La aplicación Retro tiene su propia API web que no se considera un servicio de Microsoft. Como se mencionó anteriormente, almacena correo electrónico y nombre completo para su identificación y propósitos de visualización de contenido apropiados. Estos datos no se envían a ningún otro lugar. Además, Retro tiene una funcionalidad opcional para exportar datos sprint al espacio de confluencia atlassiano. Para hacerlo, el usuario tiene que ingresar su nombre de usuario y contraseña de confluencia. Estos datos solo se utilizan para realizar solicitudes autenticadas a la api de confluencia en nombre del usuario y no se almacenan ni registran en ningún lugar. |  | Retro tiene su propia API web que también está registrada en azure. Para usarlo, el usuario debe autenticarse a través de microsoft identity platform. El usuario tiene que ser autenticado para que la aplicación Retro pueda servidor de contenido específico del usuario |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>| **¿Justificación para acceder a la EUII?**  | **¿Euii se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot accede a la lista para comprobar qué miembro se unió o abandonó el equipo. En función de ello, agrega o desactiva a ese usuario del proyecto para que el usuario ya no se muestre en la lista de participantes de sprint. | El correo electrónico y FullName están vinculados entre sí y se almacenan en la base de datos. El correo electrónico se utiliza para la identificación del usuario para visualizar el contenido apropiado para el usuario que ha iniciado sesión. FullName se utiliza para mostrar puproses, por lo que otros usuarios pueden saber para quién están evaluando o escribiendo comentarios.  |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>No. El único proceso que genera telemetría/registros en la aplicación Retro es el registro de errores. Los registros de errores no incluyen ninguna EUII u OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos se almacenan en la base de datos de Azure Sql Server. Se almacena a través de la aplicación Retro y el bot Retro.
De forma predeterminada, azure sql Database tiene habilitado el cifrado de datos transparente.
La base de datos está bloqueada detrás de la autenticación básica.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

