---
ms.author: oromalle
title: 'Microsoft 365: Guía de envío de documentos iniciales'
author: orionomalley
description: Microsoft 365 granular guía de envío de certificación
keywords: Equipos de certificación de aplicaciones Microsoft 365 de cumplimiento de seguridad m365 envío inicial de documentos
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0f879ce6b02fb469b0210500e4706d468ccb4011
ms.sourcegitcommit: 3e72bc447a90cd8b0313dab55f6a9374be8ae358
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/01/2021
ms.locfileid: "61261682"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification: Guía de envío de documentos iniciales

El envío inicial del documento forma parte de la fase de evaluación previa de la certificación. La información proporcionada dará a los analistas de certificación los antecedentes necesarios para identificar qué controles y componentes del sistema estarán en el ámbito de su evaluación. Este documento está diseñado para servir solo como un ejemplo de lo que se espera del envío inicial del documento. La documentación que proporcione variará en función de cómo se diseñe, implemente y se administra la solución.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación?
- Infraestructura como servicio (IaaS) es un modelo de servicio en la nube donde el proveedor de servicios en la nube hospeda los componentes de la infraestructura, pero los ISV siguen siendo responsables de implementar y administrar los componentes individualmente, como máquinas virtuales/sistemas operativos, almacenes de datos y componentes de red. Ejemplos de esto son Azure Virtual Machine y Azure Disk Storage.
- Platform as a Service (PaaS) es un modelo de servicio en la nube donde los componentes de infraestructura son administrados por el proveedor de servicios en la nube. Los ISV solo son responsables de implementar sus propias aplicaciones y servicios. Ejemplos de esto son Azure App Services, Azure Functions y Azure CDN.
- Isv hospedado en este contexto significa que no se usa ningún proveedor de servicios en la nube. El ISV administra físicamente sus propios servidores, discos, redes de forma independiente local.
- Híbrido en este contexto significa que se usa uno de los modelos anteriores. Por ejemplo, algunos ISV pueden optar por usar una combinación de servicios iaas y servicios PaaS para admitir su aplicación, o pueden tener algunos componentes hospedados de ISV locales y subcontratar otros a un proveedor de servicios en la nube. Si usa uno de más modelos de servicio, seleccione híbrido.

## <a name="penetration-test-report"></a>Informe de prueba de penetración

Incluya el informe completo de pruebas de penetración con fechas que acrediten que se ha completado en los últimos 12 meses. 
-   Este informe debe producirse a partir de pruebas de penetración manuales, no puede ser el resultado de una herramienta automatizada de análisis y pruebas.
-   Este informe debe incluir el entorno que admite la implementación de la aplicación o la adición junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o los complementos.


## <a name="system-component-inventory"></a>Inventario de componentes del sistema

Un inventroy actualizado de todos los componentes del sistema usados por la infraestructura de soporte. Esto se usará para ayudar con el muestreo al realizar la fase de evaluación. Si el entorno incluye PaaS, sería útil proporcionar detalles de todos los servicios paaS consumidos.

**Nota:** IaaS/PaaS no tendría ningún hardware que esté bajo el control ISV.  En este caso, proporcione una lista o captura de pantalla de todos los recursos viruales.

**Ejemplo:**

|Nombre del activo|    Tipo de activo| Descripción|    Fabricante|   Model|
|-|-|-|-|-|
|D212|  Windows machine|   Máquina virtual|    N/D| N/D|
|LT101| Portátiles| Estación de trabajo|    Microsoft|  Surface 3|
|C2938| Modificador| Modificador|N/D|N/D|     
|LXM2|  Máquina linux|  Máquina de prueba|N/D|N/D|       


## <a name="software-inventory"></a>Inventario de software

Un inventario actualizado de todos los activos de software, incluidos todos los software usados en el entorno del ámbito, junto con las versiones.

**Ejemplo:**

|Software|  Publisher|  Versión|     Objetivo|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | Compilación 14393| Sistema operativo de servidor para el entorno de producción|.
|Linux Ubuntu|  N/D|    16.04 (Xenial)| Sistema operativo del servidor en uso dentro de la DMZ.|
|ESXi|  VMWare| 6.5.0 (Compilación 13004031)| Se usa para admitir los servidores virtuales.|
|Mysql (Windows)|   N/D|    8.0.2.1|    Servidor de base de datos para almacenar el historial de chat.|
|Tomcat|        Apache| 7.0.92| Portal de clientes.|
|IIS|   Microsoft|  10.0|   Admite las API.|


## <a name="third-party-dependencies"></a>Dependencias de terceros

Documentación que enumera todas las dependencias usadas por la aplicación o el complemento con las versiones en ejecución actuales.

**Ejemplo:**

|Dependencias web|  Versión actual en uso|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>Direcciones IP públicas

Detalle de todas las direcciones IP públicas y direcciones URL usadas por la infraestructura compatible. Esto debe incluir el intervalo IP enrutable completo asignado al entorno a menos que se haya implementado una segmentación adecuada para dividir el intervalo en uso (se requiere una evidencia adecuada de segmentación).

**Ejemplo:**

|Direcciones URL|  Dirección IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A (Jump Server)| 40.113.200.200|


## <a name="resource-endpoints"></a>Extremos de recursos

API Name Endpoint Address Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

Una lista completa de todos los puntos de conexión de API usados por la aplicación, incluidos los puntos de conexión de recursos externos y desarrollados internamente. Para ayudar a comprender el ámbito del entorno, proporcione ubicaciones de extremo de API dentro del entorno.

**Ejemplo:**

|Nombre de api|  Dirección de extremo|
|-|-|
|API de cliente de Contoso|  https://customerapi.contoso.com|
|Servicio de bot contoso|   https://bot.contoso.com|
|API de archivos contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagrama de arquitectura

Diagrama de arquitectura lógica que representa una descripción general de alto nivel de la infraestructura de soporte técnico de la aplicación/ complemento. Esto debe incluir todos los entornos de hospedaje y la infraestructura compatible con la aplicación o el complemento. Este diagrama DEBE representar todos los diferentes componentes del sistema de soporte en el entorno para ayudar a los analistas de certificación a comprender los sistemas en el ámbito y ayudar a determinar el muestreo. Indique también qué tipo de entorno de hospedaje se usa; ISV hospedado, IaaS, PaaS o híbrido. Donde se usa PaaS, indique los distintos servicios paaS que se usan para proporcionar los servicios de soporte técnico en el entorno.

![Diagrama de arquitectura](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagrama Flow datos

Flow diagramas que detallan lo siguiente:
-   Los datos fluyen hacia y desde la aplicación o el complemento (incluidos los datos del cliente).
-   Flujos de datos dentro de la infraestructura de soporte técnico (cuando corresponda)
-   Diagramas que destacan dónde y qué datos se almacenan, cómo se pasan los datos a terceros externos (incluidos los detalles de qué terceros) y cómo se protegen los datos en tránsito a través de redes públicas y abiertas y en reposo.

![Diagrama Flow datos](../media/Dataflowdiagram.png)



