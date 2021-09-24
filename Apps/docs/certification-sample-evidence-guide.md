---
title: 'Microsoft 365 Certificación: Guía de pruebas de ejemplo'
author: OrionOmalley
ms.author: oromalle
description: Microsoft 365 Introducción a la guía de ejemplo de envío de pruebas de certificación
keywords: atestación de certificación de Microsoft 365 appSource ejemplo de directrices de envío de pruebas
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: d246f1437a60dd3b55d51e22cb5701b4cb9f46bf
ms.sourcegitcommit: 1e461d44be2da90b41fdcb60b35a6a180d52c9d6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/23/2021
ms.locfileid: "59497157"
---
# <a name="microsoft-365-certification---sample-evidence-guide"></a>Microsoft 365 Certificación: Guía de pruebas de ejemplo

## <a name="overview"></a>Información general

Esta guía se ha creado para proporcionar a los ISV asistencia en el nivel de detalle necesario para los controles de Microsoft 365 certificación. Además, proporciona instrucciones sobre cómo estructurar el envío de pruebas, junto con ejemplos de los tipos de evidencia que podrían usarse potencialmente para satisfacer los controles de certificación. Los ejemplos compartidos en este documento no representan la única evidencia que se puede usar para proporcionar la seguridad de que se cumplen los controles, sino que actúan solo como una guía para el tipo de información que puede ayudar a proporcionar a los analistas de certificación las pruebas necesarias para ayudarles con esta aserción. Tenga en cuenta: - Las interfaces, capturas de pantalla y documentación reales que se usan para satisfacer los requisitos variarán en función del uso del producto, la configuración del sistema y los procesos internos. Además, tenga en cuenta que, cuando se requiera documentación de directiva o procedimiento, el ISV tendrá que enviar los documentos REALES y no capturas de pantalla como se muestra en algunos de los ejemplos. Se recomienda seguir estas directrices para evitar que la evaluación se retrase debido a la falta de pruebas. 

Hay dos secciones en la certificación que requieren envíos:
1. El envío inicial de documentos: un pequeño conjunto de documentos de alto nivel necesarios para el ámbito de la evaluación.
1. El envío de pruebas: el conjunto completo de pruebas necesarias para la evaluación de la certificación 


## <a name="initial-document-submission-guide"></a>Guía de envío de documentos inicial

## <a name="evidence-submission-sample-evidence-guide"></a>Guía de pruebas de muestra de envío de pruebas

### <a name="structure"></a>Estructura 

Esto se correlaciona directamente con las categorías que se den en la Guía Microsoft 365 envíos de certificación en línea. Tenga en cuenta que es mejor usar esta guía directamente junto con la hoja de cálculo de lista de comprobación de certificación de Microsoft 365 que se proporciona para evitar un error en el que el control establece cada uno de los ejemplos de esta directriz. Las instrucciones proporcionadas en este documento se detallan de la siguiente manera:
- Dominio de seguridad: los tres dominios de seguridad en los que se agrupan todos los controles: Seguridad de aplicaciones, Seguridad operativa y Seguridad de datos y Privacidad.
- Control(s): = Descripción de la actividad de evaluación: estos controles y el número asociado (No) se toman directamente de la lista de comprobación de certificación Microsoft 365 evaluación.  
- Intent: = The intent of why the security control is included within the program and the specific risk that it is aimed to mitigate.  La esperanza es que esta información proporcione a los ISV el razonamiento que hay detrás del control para comprender mejor los tipos de evidencias que deben recopilarse y qué ISV deben prestar atención y tener conciencia y comprensión al producir sus pruebas.
- Directrices de evidencia de ejemplo: = Dados para ayudar a guiar las tareas de recopilación de evidencias en la hoja de cálculo de lista de comprobación de certificación de Microsoft 365, esto permite a los ISV ver claramente ejemplos del tipo de evidencia que puede usar el analista de certificación que la usará para determinar con confianza que un control está en su lugar y se mantiene, ya que no es de ninguna manera exhaustivo en la naturaleza.
- Ejemplo de evidencia: = Esta sección proporciona capturas de pantalla de ejemplo e imágenes de posibles evidencias capturadas en cada uno de los controles de la hoja de cálculo de lista de comprobación de certificación de Microsoft 365, específicamente para los dominios de seguridad operativa y seguridad de datos y privacidad (pestañas dentro de la hoja de cálculo). Tenga en cuenta que cualquier información con flechas y cuadros rojos dentro de los ejemplos es para ayudar a comprender aún más los requisitos necesarios para cumplir con cualquier control.

### <a name="security-domain-application-security"></a>Dominio de seguridad: Seguridad de aplicaciones

El dominio Seguridad de aplicaciones se centra en garantizar que pueda generar un informe de prueba de penetración emitido en los últimos 12 meses que muestre que la aplicación no tiene vulnerabilidades pendientes. El único envío necesario es un informe limpio de una compañía independiente de confianza. 


### <a name="security-domain-operational-security--secure-development"></a>Dominio de seguridad: Seguridad operativa /Desarrollo seguro

El dominio de seguridad "Seguridad operativa/desarrollo seguro" está diseñado para garantizar que los ISV implementen un conjunto sólido de técnicas de mitigación de seguridad frente a una gran variedad de amenazas enfrentadas por actores de amenazas.  Esto está diseñado para proteger el entorno operativo y los procesos de desarrollo de software para crear entornos seguros.

#### <a name="malware-protection---anti-virus"></a>Protección contra malware: antivirus

**Control 1:** Proporcione las directivas y procedimientos documentados que promuevan prácticas recomendadas antivirus.
- Intención: el objetivo de este control es evaluar la comprensión de un ISV de los problemas a los que se enfrentan al considerar la amenaza de virus informáticos. Al establecer y usar procedimientos recomendados del sector para desarrollar una directiva y procesos antivirus, un ISV proporciona un recurso adaptado a la capacidad de su organización para mitigar los riesgos que enfrenta el malware, enumerar los procedimientos recomendados en la detección y eliminación de virus, y proporciona pruebas de que la directiva documentada proporciona instrucciones de seguridad sugeridas para la organización y sus empleados. Al documentar una directiva y un procedimiento de cómo el ISV implementa las decencies antimalware, esto garantiza la implementación y el mantenimiento coherentes de esta tecnología para reducir el riesgo de malware en el entorno.

- Directrices de evidencia de ejemplo: proporcione una copia de la directiva antivirus/antimalware que detalle los procesos y procedimientos implementados en la infraestructura para promover los procedimientos recomendados de Antivirus/Malware.
Ejemplo de evidencia

- Ejemplo de evidencia:

![Imagen](../media/AMWExample1.png) Aplicaciones/medios/AMWExample1.png
