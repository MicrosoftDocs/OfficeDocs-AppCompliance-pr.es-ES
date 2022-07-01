---
title: Información de la aplicación para el diccionario EN-UA de Skyline Consulatnts
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/29/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para el diccionario EN-UA, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad/cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 9676a99e8d31b4cce5b5ab84a471add8007b047a
ms.sourcegitcommit: 2ae239376c807fa9223fc7e18daa1feed6e826aa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/30/2022
ms.locfileid: "66564628"
---
# <a name="en-ua-dictionary"></a>Diccionario EN-UA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador: 24 de mayo de 2022</p>

* <a href="https://teams.microsoft.com/l/app/1a24a3a3-1fda-4f70-abee-40bba8c638e8" target="_blank">Visualización en el almacén de Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004310" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Skyline Consulatnts a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Diccionario EN-UA |
| ID | WA200004310 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | Skyline Consulatnts |
| Sitio web de la empresa | [https://skylineconsultants.com](https://skylineconsultants.com) |
| Términos de uso de la aplicación | [https://skylineconsultants.com/terms-and-conditions/](https://skylineconsultants.com/terms-and-conditions/) |
| Funcionalidad básica de la aplicación | English-Ukrainian aplicación de diccionario de Skyline Consultants está totalmente organizada para que los usuarios busquen las palabras desconocidas mientras trabajan en Microsoft Teams. |
| Ubicación de la sede central de la empresa | Estados Unidos de América |
| Página de información de la aplicación | |
| ¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación? | Paas |
| ¿Qué proveedores de nube de hospedaje usa la aplicación? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Skyline Consulatnts ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Procesa la aplicación o la infraestructura subyacente algún dato relacionado con un cliente de Microsoft o su dispositivo? | Sí |
| ¿Qué datos procesa la aplicación? | Perfil de usuario |
| ¿La aplicación admite TLS 1.1 o posterior? | Sí |
| ¿La aplicación o la infraestructura subyacente almacenan datos de clientes de Microsoft? | Sí |
| ¿Qué datos se almacenan en las bases de datos? | Nuestra base de datos conserva información: dónde se detuvo el usuario en la aplicación y restaura esa ubicación la próxima vez que el usuario entra en la aplicación. Id. de usuario de Graph |
| Si la inestructura subyacente procesa o almacena datos de clientes de Microsoft, ¿dónde se almacenan geográficamente estos datos? | Estados Unidos de América |
| ¿Tiene un proceso establecido de alquiler y eliminación de datos? | No |
| ¿Cuánto tiempo se conservan los datos después de la terminación de la cuenta? | No se conserva |
| ¿Tiene un proceso de administración de acceso a datos establecido? | Sí |
| ¿Transfiere datos de clientes o contenido de clientes a terceros o subprocesadores? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Realiza pruebas de penetración anuales en la aplicación? | Sí |
| ¿La aplicación tiene un plan de recuperación ante desastres documentado, incluida una estrategia de copia de seguridad y restauración? | No |
| ¿Su entorno usa la protección antimalware tradicional o los controles de aplicación? | ApplicationControls |
| ¿Tiene un proceso establecido para aplicar sangría y clasificación de riesgos a las vulnerabilidades de seguridad? | No |
| ¿Tiene una directiva que gobierne el contrato de nivel de servicio (SLA) para aplicar revisiones? | No |
| ¿Lleva a cabo actividades de administración de revisiones de acuerdo con los acuerdos de nivel de servicio de la directiva de aplicación de revisiones? | No |
| ¿Su entorno tiene software o sistemas operativos no admitidos? | No |
| ¿Lleva a cabo el examen trimestral de vulnerabilidades en la aplicación y la infaestructura que la admite? | No |
| ¿Tiene un firewall instalado en el límite de red externo? | No |
| ¿Tiene un proceso de administración de cambios establecido que se usa para revisar y aprobar solicitudes de cambio antes de implementarlas en producción? | No |
| ¿Una persona adicional está revisando y aprobando todas las solicitudes de cambio de código enviadas a producción por el desarrollador original? | Sí |
| ¿Las prácticas de codificación seguras tienen en cuenta clases de vulnerabilidad comunes, como OWASP Top 10? | Sí |
| Autenticación multifactor (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
| ¿Tiene un proceso establecido para aprovisionar, modificar y eliminar cuentas de empleados? | Sí |
| ¿Tiene el software de detección y prevención de intrusiones (IDPS) implementado en el perímetro del límite de red que admite la aplicación? | N/D |
| ¿Tiene el registro de eventos configurado en todos los componentes del sistema compatibles con la aplicación? | Sí |
| ¿Se revisan todos los registros con una cadencia regular mediante herramientas humanas o automatizadas para detectar posibles eventos de seguridad? | Sí |
| Cuando se detecta un evento de seguridad, ¿las alertas se envían automáticamente a un empleado para la evaluación de prioridades? | Sí |
| ¿Tiene establecido un proceso formal de administración de riesgos de seguridad de la información? | Sí |
| ¿Tiene un proceso formal de respuesta a incidentes de seguridad documentado y establecido? | Sí |
| ¿Informa de infracciones de datos de aplicaciones o servicios a las autoridades de supervisión y a las personas afectadas por la infracción en un plazo de 72 horas después de la detección? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿La aplicación cumple con la Ley de portabilidad y contabilidad de seguros de salud (HIPAA)? | N/D |
| ¿La aplicación cumple con Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 1)? | N/D |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 2)? | No |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 3)? | No |
| ¿Lleva a cabo evaluaciones anuales de PCI DSS en la aplicación y su entorno auxiliar? | N/D |
| ¿Está certificada la aplicación International Organization for Standardization (ISO 27001)? | No |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27018)? | N/D |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27017)? | No |
| ¿Cumple la aplicación la Organización Internacional de Normalización (ISO 27002)? | No |
| ¿Cumple la aplicación el Programa Federal de Administración de Riesgos y Autorización (FedRAMP)? | No |
| ¿La aplicación cumple con la Ley de Derechos Educativos y Privacidad Familiares (FERPA)? | N/D |
| ¿La aplicación cumple con la Ley de protección de la privacidad en línea de los niños (COPPA)? | N/D |
| ¿La aplicación cumple con Sarbanes-Oxley Act (SOX)? | N/D |
| ¿La aplicación cumple con NIST 800-171? | N/D |
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
| ¿La aplicación usa la versión más reciente de MSAL (Biblioteca de autenticación de Microsoft) o Microsoft Identity Web para la autenticación? | No |
| Si la aplicación no usa una de las bibliotecas anteriores, ¿qué biblioteca o bibliotecas de autenticación usa? | Microsoft.Graph; Microsoft.TeamsFx; |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación admite la evaluación continua de acceso (CAE) | No |
| ¿La aplicación almacena alguna credencial en el código? | No |
| Las aplicaciones y complementos para Microsoft 365 pueden usar API de Microsoft adicionales fuera de Microsoft Graph. ¿La aplicación o el complemento usan API de Microsoft adicionales? | No |

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

>|   **Permiso graph**  | **Tipo de permiso** |          **Justificación**          | **Identificador de aplicación de Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.Read | Delegado | Para acceder al perfil de usuario | [2da850e4-5b9d-455c-ae32-bec270de4b60](../azure/2da850e4-5b9d-455c-ae32-bec270de4b60.md) |

>Esta aplicación no tiene API adicionales.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

