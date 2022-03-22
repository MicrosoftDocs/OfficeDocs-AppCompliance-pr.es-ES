---
title: Información de aplicación para absentify de BrainCore Solutions GmbH
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/07/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para absentify, sus directivas de tratamiento de datos, su Microsoft Cloud App Security de catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 0bf3b44455bd598b532f0708654252f6620c60c6
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/17/2022
ms.locfileid: "63546118"
---
# <a name="absentify"></a>absentify

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 1, 2022</p>

* <a href="https://teams.microsoft.com/l/app/fbd349eb-146f-4e94-af76-df4754f40749" target="_blank">Ver en Teams tienda</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003833" target="_blank">Ver en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por BrainCore Solutions GmbH a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | absentify |
| ID | WA200003833 |
| Office 365 clientes compatibles | Microsoft Teams |
| Nombre de la compañía asociada | BrainCore Solutions GmbH |
| Sitio web de la compañía | [https://braincore.solutions](https://braincore.solutions) |
| Términos de uso de la aplicación | [https://absentify.com/terms-and-conditions](https://absentify.com/terms-and-conditions) |
| Funcionalidad principal de la aplicación | La forma más sencilla de controlar el tiempo libre de los empleados: en Microsoft Teams |
| Ubicación central de la empresa | Suiza |
| Página de información de la aplicación | [https://absentify.com](https://absentify.com) |
| ¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación? | Paas |
| ¿Qué proveedores de nube de hospedaje usa la aplicación? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo administra la aplicación los datos

BrainCore Solutions GmbH ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que la organización tendrá sobre los datos que recopila la aplicación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Procesa la aplicación o la infraestructura subyacente algún dato relacionado con un cliente de Microsoft o su dispositivo? | Sí |
| ¿Qué datos procesa la aplicación? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| ¿La aplicación admite TLS 1.1 o posterior? | Sí |
| ¿La aplicación o la infraestructura subyacente almacenan datos de clientes de Microsoft? | Sí |
| ¿Qué datos se almacenan en las bases de datos? | Id. de usuario de Microsoft,Correo electrónico,DisplayName |
| Si la infastructure subyacente procesa o almacena datos de clientes de Microsoft, ¿dónde se almacenan geográficamente estos datos? | Alemania |
| ¿Tiene un proceso de arrendamiento y eliminación de datos establecido? | Sí |
| ¿Cuánto tiempo se conservan los datos después de la finalización de la cuenta? | Menos de 30 días |
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
| ¿Realiza el examen trimestral de vulnerabilidades en la aplicación y la infastructure que la admite? | Sí |
| ¿Tiene un firewall instalado en el límite de red externa? | Sí |
| ¿Tiene un proceso de administración de cambios establecido para revisar y aprobar solicitudes de cambio antes de implementarse en producción? | Sí |
| ¿Una persona adicional revisa y aprueba todas las solicitudes de cambio de código enviadas a producción por el desarrollador original? | Sí |
| ¿Las prácticas de codificación segura tienen en cuenta clases de vulnerabilidad comunes como OWASP Top 10? | No |
| Autenticación multifactor (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
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
| ¿Cumple la aplicación con la Ley de portabilidad y contabilidad del seguro de salud (HIPAA)? | N/D |
| ¿Cumple la aplicación con Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 1)? | N/D |
| Fecha de certificación SOC1 más reciente |   |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 2)? | No |
| ¿Qué certificación SOC 2 ha logrado? | |
| Fecha de certificación SOC2 más reciente | |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 3)? | No |
| Fecha de certificación SOC3 más reciente | |
| ¿Realiza evaluaciones anuales de PCI DSS en la aplicación y su entorno de soporte? | N/D |
| ¿Está certificada la aplicación Organización internacional para la normalización (ISO 27001) | No |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27018)? | N/D |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27017)? | No |
| ¿Cumple la aplicación con la Organización Internacional para la Normalización (ISO 27002)? | No |
| ¿La aplicación es compatible con el Programa federal de administración de riesgos y autorización (FedRAMP) | No |
| ¿La aplicación cumple con la Ley de privacidad y derechos educativos de la familia (FERPA)? | No aplicable |
| ¿Cumple la aplicación con la Ley de protección de privacidad en línea (COPPA)? | N/D |
| ¿La aplicación cumple con Sarbanes-Oxley Act (SOX)? | No aplicable |
| ¿La aplicación cumple con NIST 800-171? | N/D |
| ¿La aplicación ha sido certificada por Cloud Security Alliance (CSA Star) | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Tiene RGPD u otros requisitos u obligaciones de privacidad o protección de datos (como CCPA)? | Sí |
| ¿La aplicación tiene un aviso de privacidad externo que describe cómo recopila, usa, comparte y almacena datos de clientes? | Sí |
| Dirección URL de la directiva de privacidad | https://absentify.com/privacy-policy |
| ¿Realiza la aplicación la toma de decisiones automatizada, incluida la generación de perfiles que podría tener un efecto legal o similar? | No |
| ¿La aplicación procesa los datos de los clientes con un propósito secundario que no se describe en el aviso de privacidad (por ejemplo, marketing, análisis)? | Sí |
| ¿Procesa categorías especiales de datos confidenciales (es decir, origen racial o étnico, opinión política, creencias religiosas o filosóficas, datos genéticos o biométricos, datos de salud) o categorías de datos sujetos a leyes de notificación de infracciones? | No |
| ¿La aplicación recopila o procesa datos de menores (es decir, personas menores de 16 años)? | No |
| ¿La aplicación tiene capacidades para eliminar los datos personales de una persona a petición? | Sí |
| ¿La aplicación tiene capacidades para restringir o limitar el procesamiento de los datos personales de una persona a petición? | N/D |
| ¿La aplicación proporciona a los usuarios la capacidad de corregir o actualizar sus datos personales? | Sí |
| ¿Se realizan revisiones periódicas de privacidad y seguridad de datos (por ejemplo, evaluaciones de impacto de protección de datos o evaluaciones de riesgos de privacidad) para identificar riesgos relacionados con el procesamiento de datos personales para la aplicación? | N/D |

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
| Las aplicaciones y complementos para Microsoft 365 pueden usar API de Microsoft adicionales fuera de Microsoft Graph. ¿La aplicación o el complemento usan API de Microsoft adicionales? | No |

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos con Microsoft Graph

>|   **Graph permiso**  | **Tipo de permiso** |          **Justificación**          | **Azure AD de aplicación** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| TeamsActivity.Send | aplicación | Opcional. Para enviar notificaciones a Microsoft Teams. | [0f5eabc0-89bf-4cc6-80d1-10094b5919d2](../azure/0f5eabc0-89bf-4cc6-80d1-10094b5919d2.md) |
>| Calendars.ReadWrite | delegado | Opcional: para crear automáticamente una entrada Outlook de calendario para ausencias. | [3dbcb38b-8d2f-4e97-9bd1-975fb770b31c](../azure/3dbcb38b-8d2f-4e97-9bd1-975fb770b31c.md) |
>| User.Read | delegado | Para inicio de sesión | [4dce2abf-3f8e-4281-9f7a-d602fc391886](../azure/4dce2abf-3f8e-4281-9f7a-d602fc391886.md) |
>| User.ReadBasic.All | delegado | Opcional: para ver las imágenes de perfil de Microsoft de los usuarios. | [4dce2abf-3f8e-4281-9f7a-d602fc391886](../azure/4dce2abf-3f8e-4281-9f7a-d602fc391886.md) |

>Esta aplicación no tiene API adicionales.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

