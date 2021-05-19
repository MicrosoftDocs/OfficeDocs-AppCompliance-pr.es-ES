---
title: Información de la aplicación de Go1 by Go1
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Go1, sus políticas de control de datos, su información de catálogo de aplicaciones Microsoft Cloud App Security e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f812e25e3e5b894d7b54da886637513cb677702a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553121"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 3 de junio de 2020</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Go1 a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Go1 |
| ID | WA200001484 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Go1 |
| URL del sitio web de socios | [https://www.go1.com/](https://www.go1.com/) |
| URL de la Política de Privacidad | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| URL de los Términos de uso | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Go1 ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | aplicación | aplicación no almacena datos de archivos | permite a los usuarios cargar y compartir archivos desde onedrive | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| Group.ReadWrite.All | aplicación | Teams y el nombre del canal y los identificadores únicos almacenados para admitir la aplicación que administra el entorno de aprendizaje | permite a la aplicación configurar dinámicamente Teams y canales para apoyar el aprendizaje estructurado en Teams entorno | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| User.Read.All | aplicación | nombre de los usuarios y correo electrónico y UPN almacenado para proporcionar experiencia directa de aprendizaje personal | permite los usos para firmar y apoyar el intercambio de recursos de aprendizaje entre los miembros del equipo | c859de61-8a6b-42e6-ba88-f639df33bc72 |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>| **Todo el OII no servicios Microsoft se transfiere a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Los usuarios de nombre y apellidos pueden compartirse con los proveedores de contenido de GO1 al reproducir contenido del curso. Esto solo se comparte cuando el proveedor de contenido requiere que se finan a fin de ofrecer una experiencia de aprendizaje personalizada. |  | N/D |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>GO1 minimiza el almacenamiento de cualquier información de identificación personal u organizativa. Los registros de aplicación de detalles que almacenan estos datos se eliminan dentro de los 90 días posteriores a la creación.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Se requiere 2FA para todos los sistemas de personal. Acceso al sistema GO1 administrado por rol. Solo los roles que requieren acceso para realizar sus trabajos tienen acceso a los sistemas de producción. Las directivas internas requieren que los datos siempre se cifran en tránsito y en reposo.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

