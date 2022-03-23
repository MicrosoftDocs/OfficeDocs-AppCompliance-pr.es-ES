---
title: Información de la aplicación para EasyLife 365 por EasyLife 365 AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/21/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para EasyLife 365, sus directivas de tratamiento de datos, su información de catálogo de aplicaciones de Microsoft Cloud App Security e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 1bbd4661f847866ed0d9094f641ba7d34fefd8c0
ms.sourcegitcommit: af065aeee2812a85ead9e0de968fc474204a6e8a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2022
ms.locfileid: "63696512"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 21, 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por EasyLife 365 AG a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | EasyLife 365 |
| ID | WA200003697 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | EasyLife 365 AG |
| Sitio web de la compañía | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Términos de uso de la aplicación | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Funcionalidad principal de la aplicación | ¡Facilita el gobierno! |
| Ubicación central de la empresa | Suiza |
| Página de información de la aplicación | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| ¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación? | Paas |
| ¿Qué proveedores de nube de hospedaje usa la aplicación? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

EasyLife 365 AG ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Procesa la aplicación o la infraestructura subyacente algún dato relacionado con un cliente de Microsoft o su dispositivo? | Sí |
| ¿Qué datos procesa la aplicación? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| ¿La aplicación admite TLS 1.1 o posterior? | Sí |
| ¿La aplicación o la infraestructura subyacente almacenan datos de clientes de Microsoft? | Sí |
| ¿Qué datos se almacenan en las bases de datos? | Metadatos de grupo (id, nombre) e información de usuario (id, mail) en nuestro registro durante 90 días |
| Si la infastructure subyacente procesa o almacena datos de clientes de Microsoft, ¿dónde se almacenan geográficamente estos datos? | Países Bajos (el) |
| ¿Tiene un proceso de arrendamiento y eliminación de datos establecido? | Sí |
| ¿Cuánto tiempo se conservan los datos después de la finalización de la cuenta? | Menos de 90 días |
| ¿Tiene un proceso de administración de acceso a datos establecido? | Sí |
| ¿Transfiere datos de clientes o contenido de cliente a terceros o subprocesadores? | No |
| ¿Tiene acuerdos de uso compartido de datos con cualquier servicio de terceros con el que comparta datos de clientes de Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

La información del [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparece a continuación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Realizas pruebas de penetración anuales en la aplicación? | Sí |
| ¿La aplicación tiene un plan de recuperación ante desastres documentado, incluida una estrategia de copia de seguridad y restauración? | Sí |
| ¿Su entorno usa controles de aplicación o protección antimalware tradicionales? | TraditionalAntiMalware, ApplicationControls |
| ¿Tiene un proceso establecido para la sangría y las vulnerabilidades de seguridad de clasificación de riesgos? | Sí |
| ¿Tiene una directiva que rega el contrato de nivel de servicio (SLA) para aplicar revisiones? | Sí |
| ¿Lleva a cabo actividades de administración de revisiones según sus SLA de directiva de revisión? | Sí |
| ¿El entorno tiene algún software o sistemas operativos no compatibles? | No |
| ¿Realiza el examen trimestral de vulnerabilidades en la aplicación y la infastructure que la admite? | No |
| ¿Tiene un firewall instalado en el límite de red externa? | No |
| ¿Tiene un proceso de administración de cambios establecido para revisar y aprobar solicitudes de cambio antes de implementarse en producción? | Sí |
| ¿Una persona adicional revisa y aprueba todas las solicitudes de cambio de código enviadas a producción por el desarrollador original? | Sí |
| ¿Las prácticas de codificación segura tienen en cuenta clases de vulnerabilidad comunes como OWASP Top 10? | Sí |
| Autenticación multifactor (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| ¿Tiene un proceso establecido para aprovisionar, modificar y eliminar cuentas de empleados? | Sí |
| ¿Tiene implementado el software de detección y prevención de intrusiones (IDPS) en el perímetro del límite de red que admite la aplicación? | N/D |
| ¿Tienes configurado el registro de eventos en todos los componentes del sistema compatibles con la aplicación? | Sí |
| ¿Se revisan todos los registros en una cadencia regular mediante herramientas humanas o automatizadas para detectar posibles eventos de seguridad? | Sí|
| Cuando se detecta un evento de seguridad, ¿se envían automáticamente alertas a un empleado para su triaje? | Sí |
| ¿Tiene establecido un proceso formal de administración de riesgos de seguridad de la información? | Sí |
| ¿Tiene un proceso formal de respuesta a incidentes de seguridad documentado y establecido? |  |
| ¿Reporta infracciones de datos de aplicación o servicio a las autoridades de supervisión y a las personas afectadas por la infracción en un plazo de 72 horas después de la detección?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Cumple la aplicación con la Ley de portabilidad y contabilidad del seguro de salud (HIPAA)? | No |
| ¿Cumple la aplicación con Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 1)? | No |
| Fecha de certificación SOC1 más reciente |   |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 2)? | No |
| ¿Qué certificación SOC 2 ha logrado? | |
| Fecha de certificación SOC2 más reciente | |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 3)? | No |
| Fecha de certificación SOC3 más reciente | |
| ¿Realiza evaluaciones anuales de PCI DSS en la aplicación y su entorno de soporte? | No |
| ¿Está certificada la aplicación Organización internacional para la normalización (ISO 27001) | No |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27018)? | No |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27017)? | No |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27002)? | No |
| ¿La aplicación es compatible con el Programa federal de administración de riesgos y autorización (FedRAMP) | No |
| ¿La aplicación cumple con la Ley de privacidad y derechos educativos de la familia (FERPA)? | No |
| ¿Cumple la aplicación con la Ley de protección de privacidad en línea (COPPA)? | No |
| ¿La aplicación cumple con Sarbanes-Oxley Act (SOX)? | No |
| ¿La aplicación cumple con NIST 800-171? | No |
| ¿La aplicación ha sido certificada por Cloud Security Alliance (CSA Star) | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Tiene RGPD u otros requisitos u obligaciones de privacidad o protección de datos (como CCPA)? | Sí |
| ¿La aplicación tiene un aviso de privacidad externo que describe cómo recopila, usa, comparte y almacena datos de clientes? | Sí |
| Dirección URL de la directiva de privacidad | https://www.easylife365.cloud/web/privacy |
| ¿Realiza la aplicación la toma de decisiones automatizada, incluida la generación de perfiles que podría tener un efecto legal o similar? | No |
| ¿La aplicación procesa los datos de los clientes con un propósito secundario que no se describe en el aviso de privacidad (por ejemplo, marketing, análisis)? | No |
| ¿Procesa categorías especiales de datos confidenciales (es decir, origen racial o étnico, opinión política, creencias religiosas o filosóficas, datos genéticos o biométricos, datos de salud) o categorías de datos sujetos a leyes de notificación de infracciones? | No |
| ¿La aplicación recopila o procesa datos de menores (es decir, personas menores de 16 años)? | No |
| ¿La aplicación tiene capacidades para eliminar los datos personales de una persona a petición? | No |
| ¿La aplicación tiene capacidades para restringir o limitar el procesamiento de los datos personales de una persona a petición? | No |
| ¿La aplicación proporciona a los usuarios la capacidad de corregir o actualizar sus datos personales? | No |
| ¿Se realizan revisiones periódicas de privacidad y seguridad de datos (por ejemplo, evaluaciones de impacto de protección de datos o evaluaciones de riesgos de privacidad) para identificar riesgos relacionados con el procesamiento de datos personales para la aplicación? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Se integra la aplicación con Microsoft Identity Platform (Azure AD) para el inicio de sesión único, el acceso a la API, etc.? | Sí |
| ¿Ha revisado y cumplido con todos los procedimientos recomendados aplicables descritos en la lista Plataforma de identidad de Microsoft integración? | Sí |
| ¿La aplicación usa la versión más reciente de MSAL (Biblioteca de autenticación de Microsoft) o Microsoft Identity Web para la autenticación? | Sí |
| Si la aplicación no usa una de las bibliotecas anteriores, ¿qué bibliotecas o bibliotecas de autenticación usa? |  |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación es compatible con la evaluación continua de acceso (CAE) | No |
| ¿La aplicación almacena credenciales en el código? | No |
| Las aplicaciones y complementos para Microsoft 365 pueden usar API de Microsoft adicionales fuera de Microsoft Graph. ¿La aplicación o el complemento usan API de Microsoft adicionales? | Sí |

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

>|   **Graph permiso**  | **Tipo de permiso** |          **Justificación**          | **Azure AD de aplicación** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | delegado | Permite leer Grupos o Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | delegado | Permite manipualar metadatos de grupos o Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | delegado | Lee miembros de un grupo | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | delegado | Permite recuperar metadatos de cuenta de invitado | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | delegado | Permite buscar miembros o cuentas de invitado en una organización | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | aplicación | Crea canales para un equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | aplicación | Lee los canales de un equipo existente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | aplicación | Obtener plantillas actuales de configuración de cuentas de grupo e invitado | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | aplicación | Aplicar la configuración de la cuenta de invitado para el grupo o el equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | aplicación | Crea un grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | ambos | Lee información de grupo y recupera alias de grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | aplicación | Manipula metadatos de grupo en el back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | aplicación | Recupera pertenencias de grupo o grupo en el back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | aplicación | Permite agregar o quitar miembros de un grupo o equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | aplicación | Permite manipular cuentas de invitado y sus metadatos | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | aplicación | Envía correos con un buzón compartido | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | aplicación | Recupera la configuración de idioma preferida de un usuario | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | aplicación | Recupera los datos de uso de grupos y Teams | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | aplicación | Recuperar información básica del equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | aplicación | Permite archivar y desarchisar un equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams. Crear | aplicación | Crea un equipo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | aplicación | Recupera pestañas de un equipo creado | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | aplicación | Permite crear o manipualr pestañas de un equipo creado | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | aplicación | Invita a un usuario al inquilino | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | delegado | Obtiene información de usuario e información de la organización | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | ambos | Recupera información de invitado y usuario | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | delegado | Leer todos los grupos de usuarios | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | delegado | Modificar los metadatos de grupo del usuario y manipular grupos y Teams | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | delegado | Permite que el propietario de un grupo lea la pertenencia a un grupo o equipo | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | delegado | Permite al propietario del grupo manipular la pertenencia a un grupo o equipo | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | delegado | Permite archivar o desarchisar un equipo | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | aplicación | Se usa para enviar Teams notificaciones en el back-end | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | aplicación | Comprueba si el usuario tiene instalada la aplicación EasyLife antes de enviar notificaciones a través de Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | delegado | Lee los datos de la organización y la información del usuario | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | delegado | Permite buscar otros miembros o cuentas de invitado en un directorio | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | delegado | Muestra las fotos del usuario | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| correo electrónico | delegado | Usado por la autenticación de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | delegado | Usado por la autenticación de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| OpenID | delegado | Usado por la autenticación de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| perfil | delegado | Usado por la autenticación de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>Esta aplicación no tiene API adicionales.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

