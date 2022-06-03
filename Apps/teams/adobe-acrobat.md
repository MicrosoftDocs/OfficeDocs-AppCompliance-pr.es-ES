---
title: Información de la aplicación para Adobe Acrobat de Adobe
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Toda la información de seguridad y cumplimiento disponible para Adobe Acrobat, sus directivas de control de datos, su Microsoft Cloud App Security información del catálogo de aplicaciones e información de seguridad y cumplimiento en el registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: c87e0fadffed9b801f57668eae3d63285dd6a716
ms.sourcegitcommit: 4ceff6ef6aa0bae1075da646773b852970bb4049
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/03/2022
ms.locfileid: "65874279"
---
# <a name="adobe-acrobat"></a>Adobe Acrobat

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última actualización del desarrollador el 6 de marzo de 2022</p>

* <a href="https://teams.microsoft.com/l/app/10aea93d-20cf-44c2-b4a5-284c5ef2e6a5" target="_blank">Visualización en Teams almacén</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002564" target="_blank">Vista en AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Información general

Información proporcionada por Adobe a Microsoft:

| **Information** | **Respuesta** |
|:----------------|:-------------|
| Nombre de la aplicación | Adobe Acrobat |
| ID | WA200002564 |
| Office 365 clientes admitidos | Microsoft Teams |
| Nombre de la empresa asociada | Adobe |
| Sitio web de la empresa | [https://www.adobe.com](https://www.adobe.com) |
| Términos de uso de la aplicación | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |
| Funcionalidad básica de la aplicación | Con Adobe Acrobat para Microsoft Teams, los creadores del formato de archivo PDF proporcionan una manera de colaborar con todos los usuarios de su canal y recopilar comentarios en un solo &#8211; PDF sin tener que salir del entorno Teams. Reciba notificaciones de actividad cuando otros realicen acciones en sus documentos. Los revisores pueden ver y comentar entre sí&#8217;comentarios, por lo que&#8217;dedicará menos tiempo a administrar conflictos. |
| Ubicación de la sede central de la empresa | Estados Unidos de América |
| Página de información de la aplicación | [https://helpx.adobe.com/document-cloud/help/microsoft-teams...](https://helpx.adobe.com/document-cloud/help/microsoft-teams.html) |
| ¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación? | Paas |
| ¿Qué proveedores de nube de hospedaje usa la aplicación? | Azure, Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Cómo controla la aplicación los datos

Adobe ha proporcionado esta información sobre cómo esta aplicación recopila y almacena los datos de la organización y el control que su organización tendrá sobre los datos que recopila la aplicación.

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Procesa la aplicación o la infraestructura subyacente algún dato relacionado con un cliente de Microsoft o su dispositivo? | Sí |
| ¿Qué datos procesa la aplicación? | UserInfo, recurso de OAuth, recurso de usuario,  |
| ¿La aplicación admite TLS 1.1 o posterior? | Sí |
| ¿La aplicación o la infraestructura subyacente almacenan datos de clientes de Microsoft? | Sí |
| ¿Qué datos se almacenan en las bases de datos? | tenant_id, upn_hash, profile_and_token_info, oauth_state, ims_login_changed_at, preference_data, updated_at, created_at, expires_at |
| Si la inestructura subyacente procesa o almacena datos de clientes de Microsoft, ¿dónde se almacenan geográficamente estos datos? | Estados Unidos de América |
| ¿Tiene un proceso establecido de alquiler y eliminación de datos? | Sí |
| ¿Cuánto tiempo se conservan los datos después de la terminación de la cuenta? | Menos de 30 días |
| ¿Tiene un proceso de administración de acceso a datos establecido? | Sí |
| ¿Transfiere datos de clientes o contenido de clientes a terceros o subprocesadores? | Sí |
| ¿Tiene acuerdos de uso compartido de datos con cualquier servicio de terceros con el que comparta los datos de los clientes de Microsoft? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

A continuación se muestra información del catálogo [de Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Realiza pruebas de penetración anuales en la aplicación? | Sí |
| ¿La aplicación tiene un plan de recuperación ante desastres documentado, incluida una estrategia de copia de seguridad y restauración? | Sí |
| ¿Su entorno usa la protección antimalware tradicional o los controles de aplicación? | ApplicationControls, TraditionalAntiMalware |
| ¿Tiene un proceso establecido para aplicar sangría y clasificación de riesgos a las vulnerabilidades de seguridad? | Sí |
| ¿Tiene una directiva que gobierne el contrato de nivel de servicio (SLA) para aplicar revisiones? | Sí |
| ¿Lleva a cabo actividades de administración de revisiones de acuerdo con los acuerdos de nivel de servicio de la directiva de aplicación de revisiones? | Sí |
| ¿Su entorno tiene software o sistemas operativos no admitidos? | No |
| ¿Lleva a cabo el examen trimestral de vulnerabilidades en la aplicación y la infaestructura que la admite? | Sí |
| ¿Tiene un firewall instalado en el límite de red externo? | Sí |
| ¿Tiene un proceso de administración de cambios establecido que se usa para revisar y aprobar solicitudes de cambio antes de implementarlas en producción? | Sí |
| ¿Una persona adicional está revisando y aprobando todas las solicitudes de cambio de código enviadas a producción por el desarrollador original? | Sí |
| ¿Las prácticas de codificación seguras tienen en cuenta clases de vulnerabilidad comunes, como OWASP Top 10? | Sí |
| Autenticación multifactor (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
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
| ¿La aplicación cumple con la Ley de portabilidad y contabilidad de seguros de salud (HIPAA)? | No |
| ¿La aplicación cumple con Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 1)? | No |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 2)? | Sí |
| ¿Qué certificación SOC 2 logró? | type2 |
| Fecha de certificación de SOC2 más reciente | 2021-11-22 |
| ¿La aplicación cumple con los controles de organización de servicio (SOC 3)? | No |
| ¿Lleva a cabo evaluaciones anuales de PCI DSS en la aplicación y su entorno auxiliar? | No |
| ¿Está certificada la aplicación International Organization for Standardization (ISO 27001)? | Sí |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27018)? | No |
| ¿Cumple la aplicación la Organización Internacional para la Normalización (ISO 27017)? | No |
| ¿Cumple la aplicación la Organización Internacional de Normalización (ISO 27002)? | No |
| ¿Cumple la aplicación el Programa Federal de Administración de Riesgos y Autorización (FedRAMP)? | Sí |
| ¿La aplicación cumple con la Ley de Derechos Educativos y Privacidad Familiares (FERPA)? | Sí |
| ¿La aplicación cumple con la Ley de protección de la privacidad en línea de los niños (COPPA)? | Sí |
| ¿La aplicación cumple con Sarbanes-Oxley Act (SOX)? | No |
| ¿La aplicación cumple con NIST 800-171? | Sí |
| ¿Se ha certificado la aplicación Cloud Security Alliance (CSA Star)? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿Tiene RGPD u otros requisitos o obligaciones de privacidad o protección de datos (como CCPA)? | Sí |
| ¿Tiene la aplicación un aviso de privacidad externo que describe cómo recopila, usa, comparte y almacena los datos de los clientes? | Sí |
| Dirección URL de la directiva de privacidad | https://business.adobe.com/privacy/general-data-protection-regulation.html |
| ¿La aplicación realiza la toma de decisiones automatizada, incluida la generación de perfiles que podría tener un efecto legal o un impacto similar? | No |
| ¿La aplicación procesa los datos del cliente para un propósito secundario no descrito en el aviso de privacidad (es decir, marketing, análisis)? | No |
| ¿Procesa categorías especiales de datos confidenciales (es decir, origen racial o étnico, opinión política, creencias religiosas o filosóficas, datos genéticos o biométricos, datos de salud) o categorías de datos sujetos a leyes de notificación de infracciones? | No |
| ¿Recopila o procesa la aplicación datos de menores de edad (es decir, personas menores de 16 años)? | No |
| ¿La aplicación tiene capacidades para eliminar los datos personales de una persona a petición? | No |
| ¿La aplicación tiene capacidades para restringir o limitar el procesamiento de los datos personales de un individuo a petición? | No |
| ¿Proporciona la aplicación a los usuarios la capacidad de corregir o actualizar sus datos personales? | Sí |
| ¿Se realizan revisiones periódicas de privacidad y seguridad de datos (por ejemplo, evaluaciones de impacto de protección de datos o evaluaciones de riesgos de privacidad) para identificar riesgos relacionados con el procesamiento de datos personales para la aplicación? | Sí |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Respuesta** |
|:----------------|:-------------|
| ¿La aplicación se integra con Microsoft Identity Platform (Azure AD) para el inicio de sesión único, el acceso a la API, etc.? | Sí |
| ¿Ha revisado y cumplido todos los procedimientos recomendados aplicables descritos en la lista de comprobación de integración de Plataforma de identidad de Microsoft? | Sí |
| ¿La aplicación usa la versión más reciente de MSAL (Biblioteca de autenticación de Microsoft) o Microsoft Identity Web para la autenticación? | No |
| Si la aplicación no usa una de las bibliotecas anteriores, ¿qué biblioteca o bibliotecas de autenticación usa? | Sin usar ninguna biblioteca de autenticación, estamos usando directamente el protocolo OAuth 2.0 |
| ¿La aplicación admite directivas de acceso condicional? | No |
| ¿La aplicación admite la evaluación continua de acceso (CAE) | No |
| ¿La aplicación almacena alguna credencial en el código? | No |
| Las aplicaciones y los complementos para Microsoft 365 pueden usar API de Microsoft adicionales fuera de Microsoft Graph. ¿La aplicación o el complemento usan API de Microsoft adicionales? | No |

#### <a name="data-access-using-microsoft-graph"></a>Acceso a datos mediante Microsoft Graph

>|   **permiso Graph**  | **Tipo de permiso** |          **Justificación**          | **Identificador de aplicación de Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | Delegado | Para poder enumerar y navegar por los archivos y carpetas recientes, OneDrive y Teams canales del usuario. Permitimos a los usuarios acceder a estos archivos, usarlos para realizar operaciones en ellos y guardar archivos en su almacenamiento. | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| Team.ReadBasic.All | Delegado | Leer los nombres y descripciones de los equipos | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| User.Read | Delegado | Iniciar sesión y leer el perfil del usuario | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| correo electrónico | Delegado | Ver la dirección de correo electrónico de los usuarios | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| offline_access | Delegado | mantener el acceso a los datos a los que le ha dado acceso | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| OpenID | Delegado | Inicio de sesión de los usuarios | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| perfil | Delegado | ver el perfil básico de los usuarios | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |

>Esta aplicación no tiene API adicionales.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

