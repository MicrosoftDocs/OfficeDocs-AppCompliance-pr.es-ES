---
title: Herramienta de automatización de cumplimiento de aplicaciones para Microsoft 365
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Introducción a App Compliance Automation Tool para Microsoft 365
keywords: automatización de la certificación de aplicaciones Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: debd3c9e2ecd1538446d09f5019ea995260345fd
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433496"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Herramienta de automatización de cumplimiento de aplicaciones para Microsoft 365
En este artículo, aprenderá cuál es la herramienta de automatización de cumplimiento de aplicaciones para Microsoft 365 (ACAT) y cómo simplifica el cumplimiento y obtiene la certificación Microsoft 365.

> [!IMPORTANT]
> ACAT está en *versión preliminar privada* en este momento. Si desea unirse al programa de versión preliminar privada, póngase en contacto con [acatprivatepreview@microsoft.com](mailto:acatprivatepreview@microsoft.com).

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>¿Qué es la herramienta de automatización de cumplimiento de aplicaciones para Microsoft 365
App Compliance Automation Tool for Microsoft 365 (ACAT) es un servicio de Azure Portal que ayuda a simplificar el recorrido de cumplimiento de cualquier aplicación que consuma Microsoft 365 datos del cliente y se publique a través del Centro de partners. App Compliance Automation Tool para Microsoft 365 es una herramienta de automatización del cumplimiento centrada en la aplicación que le ayuda a completar la certificación de Microsoft 365 con mayor facilidad y comodidad. En versión preliminar privada, ACAT está disponible para las aplicaciones que se ejecutan en Azure.

Con esta herramienta, podrá definir rápidamente el límite de cumplimiento de las aplicaciones, supervisar los resultados de cumplimiento automáticamente y completar la auditoría de cumplimiento más fácilmente. El límite de cumplimiento es la infraestructura en la nube que admite la entrega de la aplicación y los sistemas back-end con los que la aplicación puede comunicarse.

Además de proporcionar un seguimiento más rápido hacia la certificación Microsoft 365, ACAT puede ayudarle en diversos escenarios de cumplimiento para aplicaciones Microsoft 365:

- Pasos detallados de visualización y corrección para Microsoft 365 responsabilidades de certificación.
- Informes diarios automáticos para ayudarle a obtener resultados de cumplimiento continuamente.
- Procedimientos recomendados de seguridad y cumplimiento que se pueden usar como guía en la primera fase del ciclo de vida de la aplicación.

## <a name="benefits-of-acat"></a>Ventajas de ACAT
Recorrido de cumplimiento centrado en la aplicación.
- ACAT informa diariamente del estado de cumplimiento del entorno en la nube de las aplicaciones, que puede integrar con la estrategia de cumplimiento de la infraestructura en la nube actual.
- Los desarrolladores pueden invocar ACAT incluso durante la fase de desarrollo de aplicaciones.

Acelera el proceso de certificación de Microsoft 365.
- ACAT automatiza completamente ciertos controles de certificación de Microsoft 365.
- Microsoft está desarrollando activamente una lista de automatización que crece continuamente.

Integración nativa con Microsoft 365 flujo de trabajo de certificación.
- ACAT está totalmente integrado con el Centro de partners para Microsoft 365 propósito de certificación.

## <a name="concepts-of-acat"></a>Conceptos de ACAT
### <a name="regulatory-compliance-report"></a>Informe de cumplimiento normativo 
En ACAT, puede auditar el estado de cumplimiento de la aplicación mediante la creación de un informe de cumplimiento para ella. Puede definir el límite de cumplimiento de la aplicación especificando los recursos de Azure que compilan la aplicación. Cree varios informes para una aplicación, en función de diferentes entornos de desarrollo y fases.

Una vez creado el informe, ACAT comenzará a recopilar los datos de cumplimiento en el tiempo de desencadenador predefinido y, a continuación, generará los resultados de cumplimiento como informe automáticamente. Mientras tanto, ACAT seguirá supervisando los cambios de cumplimiento del informe de cumplimiento continuamente, hasta que decida eliminar el informe.

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365 resultados del control de certificación
En el informe de cumplimiento normativo, los resultados de cumplimiento se organizan mediante controles con sus estados correspondientes marcados por ACAT:
- **Pasado**: no hay errores en los controles de certificación de Microsoft 365 totalmente automatizados.
- **Error**: se han detectado responsabilidades de clientes erróneas para los controles de certificación de Microsoft 365 totalmente automatizados.
- **Pasado: se necesitan pruebas adicionales**: no hay errores en los controles de certificación de Microsoft 365 *parcialmente automatizados*.
- **Error: se necesitan pruebas adicionales**: se han detectado responsabilidades erróneas del cliente para los controles de certificación de Microsoft 365 *parcialmente automatizados*.
- **Control manual**: ACAT no automatiza ninguna responsabilidad del cliente por los controles de certificación de Microsoft 365.

### <a name="customer-responsibility"></a>Responsabilidad del cliente
Hay un conjunto de responsabilidades del cliente asociadas a cada control que se deben cumplir. Son responsabilidades que usted retiene en las siguientes áreas: datos, puntos de conexión, cuenta, administración de acceso, etc.

ACAT recopila datos para cada responsabilidad del cliente y devuelve un resultado de evaluación para él. También le proporciona una acción de corrección, que es nuestra guía que le ayuda a alinearse con Microsoft 365 estándares de certificación.


## <a name="faq"></a>Preguntas más frecuentes
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>¿Qué son los controles manuales y los controles parcialmente automatizados?
Cada control de cumplimiento está asociado a un conjunto de responsabilidades del cliente para las que ACAT recopila datos de cumplimiento. Sin embargo, no todos los controles para la certificación de Microsoft 365 están cubiertos por ACAT a partir de ahora (hay un esfuerzo continuo para expandir la cobertura). Para el control parcialmente automatizado, ACAT automatiza partes de las responsabilidades del cliente. Puede usar el estado de cumplimiento de él como referencia, pero no puede usarlo para Microsoft 365 auditoría de certificación directamente. Para los controles manuales, ACAT actualmente no automatiza ninguna responsabilidad del cliente.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>Hice los cambios sugeridos en base a la sugerencia de corrección, pero el control sigue fallando
Después de tomar medidas para resolver el error, debe esperar a que ACAT recupere los resultados de la evaluación actualizada para actualizar el estado del control. Las evaluaciones se ejecutan cada 24 horas en el tiempo de desencadenador predefinido.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>¿Cómo se usa el informe de cumplimiento en el proceso de certificación?
ACAT se integra perfectamente con el [Centro de partners](https://partner.microsoft.com/dashboard) para completar el recorrido de certificación Microsoft 365. Durante la creación del informe de cumplimiento, puede editar la configuración de certificación de Microsoft 365, es decir, GUID de la oferta. Es opcional durante la creación y puede configurarla más adelante cuando empiece a publicar la aplicación.

## <a name="learn-more"></a>Más información

* [Introducción con ACAT](https://aka.ms/acat/getstarted)
* [Más información sobre la certificación Microsoft 365](https://aka.ms/acat/m365cert)
