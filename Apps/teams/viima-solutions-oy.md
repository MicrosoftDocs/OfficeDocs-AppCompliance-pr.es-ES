---
title: Información de la aplicación Viima by Viima Solutions Oy
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Viima, sus políticas de gestión de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 703c1bf3b2980fae538af764bfa1d2024a86a366
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553981"
---
# <a name="viima"></a>Viima

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización por el desarrollador el: 17 de noviembre de 2020</p>

* <a href="https://teams.microsoft.com/l/app/2bffa4e8-aac7-4d2e-976d-5a7db5c4b768" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001589" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Viima Solutions Oy a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Viima |
| ID | WA200001589 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la empresa asociada | Viima Solutions Oy |
| URL del sitio web de socios | [https://www.viima.com/](https://www.viima.com/) |
| URL de Teams página de información de la aplicación | [https://www.viima.com/product](https://www.viima.com/product) |
| URL de la Política de Privacidad | [https://www.viima.com/privacy-policy](https://www.viima.com/privacy-policy) |
| URL de los Términos de uso | [https://www.viima.com/terms](https://www.viima.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo maneja la aplicación los datos

Viima Solutions Oy ha proporcionado esta información sobre cómo esta aplicación recopila y almacena datos organizativos y el control que su organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

Enumere los [permisos de Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (Delegado/Aplicación)** | **¿Se recopilan datos? ¿Justificación para recogerlo?** | **¿Se almacenan los datos? ¿Justificación para almacenarlo?** | **Identificador de aplicación de Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegado |  Nombre y apellidos, UPN/dirección de correo electrónico, ubicación, localidad, departamento, ubicación de la oficina. Estos se utilizan para iniciar sesión al usuario y proporcionar información de perfil básica para ellos dentro de la aplicación. | permite al usuario iniciar sesión y da acceso a la aplicación a su UPN y a la información básica del perfil para habilitar el inicio de sesión silencioso | b8ea7030-ce4d-4ecd-98d7-dc16d8298d1b |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft utilizado

Si la aplicación transfiere o comparte datos de organización con servicios que no son de Microsoft, enumere el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluya una justificación de por qué la aplicación necesita transferir esta información.

>No se utilizan servicios Microsoft.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede acceder a la información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo de un equipo o chat al que se agrega. ¿Esta aplicación hace uso de esta capacidad?

>No se accede a LA UEII.


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece alguna información de identificación organizacional (OII) o información identificable por el usuario final (EUII) en la telemetría o los registros de esta aplicación? En caso afirmativo, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación?

>El nombre de la organización, el ID de organización de Viima, los correos electrónicos del usuario final y los ID aparecen en los registros. Iso27001 compatible 3ª parte auditó los controles en su lugar para el acceso restringido a, y archiving / eliminación de dichos datos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el socio

¿Describir cómo los administradores de la organización pueden controlar su información en los sistemas asociados? por ejemplo, eliminación, retención, auditoría, archivado, política de usuario final, etc.

>Los datos se almacenan en AWS (Irlanda). El acceso a los datos se limita únicamente al personal autorizado de mantenimiento y soporte técnico que ha recibido la formación adecuada y está protegido con una serie de medidas de seguridad, como 2FA, rango ip protegido (acceso sólo desde la red corporativa), etc. Las medidas son compatibles con ISO27001 y auditadas por una tercera parte.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información organizacional

¿Están los seres humanos involucrados en la revisión o análisis de cualquier información de identificación organizacional (OII) datos que es recogido o almacenado por esta aplicación?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

A continuación aparece información del catálogo [de Microsoft Cloud App Security.](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)

<iframe height='1020' title='Microsoft Cloud App Security información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Información de identidad

Viima Solutions Oy ha proporcionado esta información sobre cómo esta aplicación controla la autenticación, la autorización, las prácticas recomendadas de registro de aplicaciones y otros criterios de identidad.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra con Microsoft Identify Platform (Azure AD)?  | Sí |
| ¿Ha revisado y cumplido con todas las prácticas recomendadas aplicables descritas en la lista de verificación de integración de Plataforma de identidad de Microsoft?  | Sí |
| ¿La aplicación usa MSAL (Biblioteca de autenticación de Microsoft) para la autenticación? | No |
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
