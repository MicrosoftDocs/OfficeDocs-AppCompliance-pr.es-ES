---
title: Información de la aplicación para Karma de Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Karma, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el Registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 69163a7c191e9a7e8d460a7f20623466d208042e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410914"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Ver en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Sliday LTD a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Karma |
| Id. | WA104381640 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | Sliday LTD |
| Dirección URL del sitio web de partners | [https://sliday.com](https://sliday.com) |
| Dirección URL de Teams de información de la aplicación | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| Dirección URL de la directiva de privacidad | [https://karmabot.readme.io/docs/privacy-policy-for-microsof...](https://karmabot.readme.io/docs/privacy-policy-for-microsoft-teams) |
| DIRECCIÓN URL de términos de uso | [https://karmabot.readme.io/docs/terms-and-conditions](https://karmabot.readme.io/docs/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

Sliday LTD ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

Enumerar [los permisos Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) requiere esta aplicación.

>| **Permiso**  | **Tipo de permiso (delegado/ aplicación)** | **¿Se recopilan datos? ¿Justificación para recopilarla?** | **¿Se almacenan los datos? ¿Justificación para almacenarla?** | **Azure AD Id. de la aplicación** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | aplicación | Nombre, apellidos y dirección de correo electrónico de la compañía. Nombre, apellido para el administrador que se enfrenta a informes. Dirección de correo electrónico para la comunicación con respecto a Karma, fines de facturación y herarquía. | Nombre para mostrar del consentimiento de administrador. Inicie sesión y lea el perfil de usuario. Descripción del consentimiento de administrador. Permite a los usuarios iniciar sesión en la aplicación y permite que la aplicación lea el perfil de los usuarios que han iniciado sesión. También permite que la aplicación lea información básica de la empresa de los usuarios que han iniciado sesión. Nombre para mostrar del consentimiento del usuarioSigne y lea su perfil. Descripción del consentimiento del usuario. Te permite iniciar sesión en la aplicación con tu cuenta organizativa y permitir que la aplicación lea tu perfil. También permite que la aplicación lea información básica de la empresa. | [9ff28b02-ccc5-4cac-9d17-4cf6987c371f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9ff28b02-ccc5-4cac-9d17-4cf6987c371f) |


#### <a name="non-microsoft-services-used"></a>No servicios Microsoft se usa

Si la aplicación transfiere o comparte datos de la organización con servicios que no son de Microsoft, enumera el servicio que no es de Microsoft que usa la aplicación, qué datos se transfieren e incluye una justificación de por qué la aplicación necesita transferir esta información.

>No se servicios Microsoft no se usan.

#### <a name="data-access-via-bots"></a>Acceso a datos a través de bots

Si esta aplicación contiene un bot o una extensión de mensajería, puede tener acceso a información de identificación del usuario final (EUII): la lista (nombre, apellido, nombre para mostrar, dirección de correo electrónico) de cualquier miembro del equipo o chat al que se agrega. ¿Esta aplicación usa esta funcionalidad?

>| **¿Justificación para acceder a EUII?**  | **¿EUII se almacena en bases de datos?** | **¿Justificación para almacenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nombre, apellidos y dirección de correo electrónico de la empresa Nombre, apellidos del administrador que se enfrenta a la dirección de correo electrónico de informes para la comunicación en relación con Karma. La lista es necesaria para fines de facturación y para dividir a los usuarios masivamente en departaments independientes. | Nombre, apellidos y dirección de correo electrónico de la empresa Nombre, apellidos para el administrador que hace frente a los informes. Dirección de correo electrónico para la comunicación con respecto a Karma, fines de facturación y jerarquía de usuarios de Karma. |  |


#### <a name="telemetry-data"></a>Datos de telemetría

¿Aparece información identificable de la organización (OII) o información de identificación del usuario final (EUII) en los registros o telemetría de esta aplicación? Si es así, describa qué datos se almacenan y cuáles son las directivas de retención y eliminación.

>Almacenamos los identificadores de inquilino y los de usuario en los registros. Ambos no son identificables.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizativos para los datos almacenados por el partner

Describir cómo los administradores de la organización pueden controlar su información en sistemas asociados. Por ejemplo, eliminación, retención, auditoría, archivado, directiva de usuario final, etc.

>1. **¿Hay alguna solución DLP en su lugar? ¿Qué se implementa para evitar pérdidas de datos?**

SÍ, los datos se cifran tanto en tránsito como en reposo.

2. **¿Qué tipo de mecanismos implementa para asegurarse de que la integridad de datos está protegida contra errores, daños o mal uso y la frecuencia con la que se controlan**

Todos los servidores ejecutan RAID de hardware con niveles RAID diferentes, pero en cada caso, requiere varios errores de unidad al mismo tiempo para que se produzca cualquier pérdida de datos. We go extra safe and have both automatic and manual backups. Las bases de datos se copian automáticamente todos los días y se almacenan durante siete días.
Las máquinas virtuales se copian automáticamente cada semana y se almacenan durante 1 mes.

**Las instantáneas y las copias de seguridad se almacenan en una red interna no visible públicamente.**

3. **Describa cómo asegurarse de que los datos del cliente se segregan correctamente de las soluciones multiinquilino de otros clientes y cómo controla que los datos de producción no se replican o se usan en entornos que no son de producción**

Almacenado en bases de datos diferentes.

4. **¿Qué tipo de cifrado propone (algoritmos, protocolos, longitudes de clave) para los datos en tránsito y los datos en reposo**

Todos los datos en tránsito se cifran mediante TLS o SSL. HTTP se cifra mediante TLS 1.2 o TLS 1.3 Tráfico de base de datos cifrado por SSL.

Los datos se almacenan en el Centro digital de nube oceánica en centros de datos de ESTADOS UNIDOS.

5. **Describir cómo administra claves de cifrado únicas (proceso, almacenamiento, uso, RACI, SOD) para su propio uso y para cada uno de sus inquilinos**

Se controla mediante Digital Ocean.

6. **Describa el proceso de administración de Access en su lugar al final del proveedor señalando cómo garantizar la eliminación a tiempo de los accesos que ya no son necesarios y cómo controla la idoneidad de los privilegios para el rol de trabajo. Describa también los procesos de revalidación y la frecuencia de su ejecución**

Usamos la autenticación en dos fases para tener acceso al panel de control. Solo 3 personas tienen acceso a esto, cambiamos las contraseñas cada mes, hacemos que los registros de acceso se auditen y nos aseguramos de que las personas que ya no trabajan con nosotros quiten sus cuentas de la plataforma.

7. **Proporcione el procedimiento implementado al final para administrar los identificadores compartidos (por ejemplo, raíz, Sys, Sistema, etc.), identificadores de grupo (cuentas genéricas usadas por varias personas que pertenecen al mismo equipo por ejemplo) y cuentas locales. Describir cómo restringir, registrar y supervisar el uso de cuentas con privilegios y el acceso a dispositivos de seguridad (por ejemplo, hipervisores, firewalls, escáneres de vulnerabilidades, sniffers de red, API, etc.), cómo garantizar que los usuarios que cambian de equipo o se van ya no pueden acceder al id. de grupo y cuál es el nivel de trazabilidad de dichos identificadores.**

Usamos 1Password para compartir identificadores&#8217;compartidos, tenemos una fuente de actividad independiente cada vez que se tiene acceso al recurso compartido desde un depositario de contraseñas compartido. A menos que sea absolutamente necesario, no usamos cuentas compartidas y usamos cuentas individuales en su lugar. No se pudo obtener acceso a ninguna información en la base de datos karma a través de un inicio de sesión compartido. 2FA se usa para obtener acceso a 1Password para recuperar un inicio de sesión individual.

8. **Describir el proceso para garantizar y supervisar que se respeta la segregación de deberes y la frecuencia con la que se controla**

Hemos ejecutado reuniones mensuales que cubren la segregación de derechos, la importancia del uso de inicio de sesión dedicado y 2FA cada inicio de sesión posible.

Nuestra SIEM contiene: registros de firewall, registros de servidor web y registros de aplicaciones. SIEM se analiza diariamente y al recibirlo. Los registros se conservan durante 1 mes y se quitan de forma segura después de eso.

#### <a name="human-review-of-organizational-information"></a>Revisión humana de la información de la organización

¿Los humanos participan en la revisión o análisis de cualquier información de identificación organizativa (OII) que esta aplicación recopila o almacena?

>Sí

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

<iframe height='1020' title='Microsoft Cloud App Security Información' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Ver en una pestaña nueva</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


