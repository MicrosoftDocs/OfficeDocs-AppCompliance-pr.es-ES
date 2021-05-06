---
title: Información de la aplicación para MindMup de Sauf Pompiers Ltd
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para MindMup, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40075f99759ba0dae4cce2c2a37995076f1017c1
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252330"
---
# <a name="mindmup"></a>MindMup

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001759" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Sauf Pompiers Ltd a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | MindMup |
| ID | WA200001759 |
| Capacidades | Pestaña |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Sauf Pompiers Ltd |
| Dirección URL del sitio web de partners | [https://www.mindmup.com](https://www.mindmup.com) |
| Dirección URL de la directiva de privacidad | [https://www.mindmup.com/resources/privacy_policy.html](https://www.mindmup.com/resources/privacy_policy.html) |
| DIRECCIÓN URL de términos de uso | [https://www.mindmup.com/resources/terms_gold.html](https://www.mindmup.com/resources/terms_gold.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Sauf Pompiers Ltd ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>Esta aplicación no usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>| **Todos los OII que no servicios Microsoft se transfieren a** |  **¿Qué OII se transfiere?** | **¿Justificación para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sistemas de almacenamiento de AWS usados para conservar la información básica de perfiles de usuario, para admitir el uso compartido de documentos y el acceso seguro a documentos de usuario en MindMup |  | N/A |

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>No se tiene acceso a EUII.



#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Los registros de acceso de seguridad registran el identificador de usuario, el identificador de inquilino de Office 365 y las marcas de tiempo de acceso. Se conservan para evitar fraudes y abusos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>Los documentos de usuario se almacenan en AWS (us-east-1), se cifran en tránsito y se cifran en reposo. los datos están disponibles para los usuarios que crearon los documentos y para cualquier usuario con el que el propietario compartió explícitamente el documento.

Todo el acceso de operador/administrador está protegido por 2FA.

El acceso de administrador de usuario y cliente se proporciona mediante la autenticación integrada de Microsoft/Azure AD, con opciones de 2FA disponibles directamente a través de SSO.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

