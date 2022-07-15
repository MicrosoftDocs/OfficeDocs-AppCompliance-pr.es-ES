---
title: Información de la aplicación para ice Contact Center by ComputerTalk
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 02/01/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para ice Contact Center, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 06a7e536f486ecc5b3e6ba90824f5baab12831ae
ms.sourcegitcommit: ac75dd8bb815bc9e8b1d5b39a2d2dbe46e65f680
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/15/2022
ms.locfileid: "66806341"
---
# <a name="ice-contact-center"></a>Centro de contactos de hielo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 31 de enero de 2022</p>

* <a href="https://appsource.microsoft.com/product/web-apps/computertalk.ice-contact-center" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por ComputerTalk a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Centro de contactos de hielo |
| ID | computertalk.ice-contact-center |
| Nombre de la empresa asociada | ComputerTalk |
| Sitio web de la empresa | [https://www.computer-talk.com](https://www.computer-talk.com) |
| Términos de uso de la aplicación | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| Funcionalidad básica de la aplicación | ice proporciona el centro de contactos como una funcionalidad de servicio, incluido el enrutamiento de llamadas, la grabación, la supervisión y la generación de informes. |
| Ubicación de la sede central de la empresa | Canada |
| Página de información de la aplicación | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| ¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

ComputerTalk ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Procesa la aplicación o la infraestructura subyacente algún dato relacionado con un cliente de Microsoft o su dispositivo? | Sí |
| ¿Qué datos procesa la aplicación? | AzureADGuid (vinculación de cuenta).  Email dirección y número de teléfono pueden importarse desde AAD. |
| ¿La aplicación admite TLS 1.1 o posterior? | Sí |
| ¿La aplicación o la infraestructura subyacente almacenan datos de clientes de Microsoft? | Sí |
| ¿Qué datos se almacenan en las bases de datos? | AzureADGuid (vinculación de cuenta).  Email dirección y número de teléfono pueden importarse desde AAD. |
| Si la inestructura subyacente procesa o almacena datos de clientes de Microsoft, ¿dónde se almacenan geográficamente estos datos? | Canada |
| ¿Tiene un proceso establecido de alquiler y eliminación de datos? | Sí |
| ¿Cuánto tiempo se conservan los datos después de la terminación de la cuenta? | Menos de 30 días |
| ¿Tiene un proceso de administración de acceso a datos establecido? | Sí |
| ¿Transfiere datos de clientes o contenido de clientes a terceros o subprocesadores? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Realiza pruebas de penetración anuales en la aplicación? | Sí |
| ¿La aplicación tiene un plan de recuperación ante desastres documentado, incluida una estrategia de copia de seguridad y restauración? | Sí |
| ¿Su entorno usa la protección antimalware tradicional o los controles de aplicación? | TraditionalAntiMalware |
| ¿Tiene un proceso establecido para aplicar sangría y clasificación de riesgos a las vulnerabilidades de seguridad? | Sí |
| ¿Tiene una directiva que gobierne el contrato de nivel de servicio (SLA) para aplicar revisiones? | Sí |
| ¿Lleva a cabo actividades de administración de revisiones de acuerdo con los acuerdos de nivel de servicio de la directiva de aplicación de revisiones? | Sí |
| ¿Su entorno tiene software o sistemas operativos no admitidos? | No |
| ¿Lleva a cabo el examen trimestral de vulnerabilidades en la aplicación y la infaestructura que la admite? | Sí |
| ¿Tiene un firewall instalado en el límite de red externo? | Sí |
| ¿Tiene un proceso de administración de cambios establecido que se usa para revisar y aprobar solicitudes de cambio antes de implementarlas en producción? | Sí |
| ¿Una persona adicional está revisando y aprobando todas las solicitudes de cambio de código enviadas a producción por el desarrollador original? | Sí |
| ¿Las prácticas de codificación seguras tienen en cuenta clases de vulnerabilidad comunes, como OWASP Top 10? | Sí |
| Autenticación multifactor (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| ¿Tiene un proceso establecido para aprovisionar, modificar y eliminar cuentas de empleados? | Sí |
| ¿Tiene el software de detección y prevención de intrusiones (IDPS) implementado en el perímetro del límite de red que admite la aplicación? | Sí |
| ¿Tiene el registro de eventos configurado en todos los componentes del sistema compatibles con la aplicación? | Sí |
| ¿Se revisan todos los registros con una cadencia regular mediante herramientas humanas o automatizadas para detectar posibles eventos de seguridad? | Sí |
| Cuando se detecta un evento de seguridad, ¿las alertas se envían automáticamente a un empleado para la evaluación de prioridades? | Sí |
| ¿Tiene establecido un proceso formal de administración de riesgos de seguridad de la información? | Sí |
| ¿Tiene un proceso formal de respuesta a incidentes de seguridad documentado y establecido? | Sí |
| ¿Informa de infracciones de datos de aplicaciones o servicios a las autoridades de supervisión y a las personas afectadas por la infracción en un plazo de 72 horas después de la detección? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿La aplicación cumple con la Ley de portabilidad y contabilidad de seguros de salud (HIPAA)? | Sí |
| ¿La aplicación cumple con Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Sí |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 1)? | N/D |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 2)? | Sí |
| ¿Qué certificación SOC 2 logró? | type2 |
| Fecha de certificación de SOC2 más reciente | 2021-10-15 |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 3)? | No |
| ¿Lleva a cabo evaluaciones anuales de PCI DSS en la aplicación y su entorno auxiliar? | Sí |
| ¿Está certificada la aplicación International Organization for Standardization (ISO 27001)? | No |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27018)? | No |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27017)? | No |
| ¿Cumple la aplicación la Organización Internacional de Normalización (ISO 27002)? | No |
| ¿Cumple la aplicación el Programa Federal de Administración de Riesgos y Autorización (FedRAMP)? | No |
| ¿La aplicación cumple con la Ley de Derechos Educativos y Privacidad Familiares (FERPA)? | N/D |
| ¿La aplicación cumple con la Ley de protección de la privacidad en línea de los niños (COPPA)? | N/D |
| ¿La aplicación cumple con Sarbanes-Oxley Act (SOX)? | N/D |
| ¿La aplicación cumple con NIST 800-171? | Sí |
| ¿Se ha certificado la aplicación Cloud Security Alliance (CSA Star)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Tiene RGPD u otros requisitos o obligaciones de privacidad o protección de datos (como CCPA)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿La aplicación se integra con Microsoft Identity Platform (Azure AD) para el inicio de sesión único, el acceso a la API, etc.? | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft? | Sí |
| ¿La aplicación usa la versión más reciente de MSAL (Biblioteca de autenticación de Microsoft) o Microsoft Identity Web para la autenticación? | Sí |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación admite la evaluación continua de acceso (CAE) | No |
| ¿La aplicación almacena alguna credencial en el código? | No |
| Las aplicaciones y complementos para Microsoft 365 pueden usar API de Microsoft adicionales fuera de Microsoft Graph. ¿La aplicación o el complemento usan API de Microsoft adicionales? | No |

>Esta aplicación no usa Microsoft Graph.

>Esta aplicación no tiene API adicionales.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

