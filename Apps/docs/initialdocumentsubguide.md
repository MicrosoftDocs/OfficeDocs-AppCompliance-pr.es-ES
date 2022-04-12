---
ms.author: oromalle
title: 'Certificación Microsoft 365: Guía de envío de documentos iniciales'
author: orionomalley
manager: tonybal
description: El envío inicial del documento forma parte de la fase de evaluación previa de la certificación.
keywords: equipos de certificación de aplicaciones Microsoft 365 envío de documentos iniciales de cumplimiento de seguridad m365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784509"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification: Guía de envío inicial de documentos

El envío inicial del documento forma parte de la fase de evaluación previa de la certificación. La información proporcionada proporcionará a los analistas de certificación los antecedentes necesarios para identificar qué controles y componentes del sistema estarán en el ámbito de la evaluación. Este documento está pensado para servir solo como un ejemplo de lo que se espera del envío inicial del documento. La documentación que proporcione variará en función de cómo se diseñe, implemente y administre la solución.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>¿Cuál es el entorno de hospedaje o el modelo de servicio que se usa para ejecutar la aplicación?
- Infraestructura como servicio (IaaS) es un modelo de servicio en la nube en el que el proveedor de servicios en la nube hospeda los componentes de infraestructura, pero los ISV siguen siendo responsables de implementar y administrar los componentes individualmente, como Virtual Machines o sistemas operativos, almacenes de datos y componentes de red. Ejemplos de esto son Azure Virtual Machine y Azure Disk Storage.
- Plataforma como servicio (PaaS) es un modelo de servicio en la nube en el que el proveedor de servicios en la nube administra los componentes de la infraestructura. Los ISV solo son responsables de implementar sus propias aplicaciones y servicios. Ejemplos de esto son App de Azure Services, Azure Functions y Azure CDN.
- ISV hospedado en este contexto significa que no se usa ningún proveedor de servicios en la nube. El ISV administra físicamente sus propios servidores, discos y redes de forma independiente local.
- Híbrido en este contexto significa que se usa uno de los modelos anteriores. Por ejemplo, algunos ISV pueden optar por usar una combinación de servicios IaaS y servicios PaaS para admitir su aplicación, o bien pueden tener algunos componentes hospedados de ISV local y externalizar otros a un proveedor de servicios en la nube. Si usa uno de los modelos de servicio más, seleccione híbrido.

## <a name="penetration-test-report"></a>Informe de pruebas de penetración

Incluya el informe completo de pruebas de penetración con fechas que acredite que se ha completado en los últimos 12 meses. 
-   Este informe debe generarse a partir de pruebas de penetración manuales, no puede ser la salida de una herramienta de análisis y pruebas automatizada.
-   Este informe debe incluir el entorno que admite la implementación de la aplicación o agregar junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o los complementos.


## <a name="system-component-inventory"></a>Inventario de componentes del sistema

Un invento actualizado de todos los componentes del sistema utilizados por la infraestructura auxiliar. Esto se usará para ayudar con el muestreo al realizar la fase de evaluación. Si el entorno incluye PaaS, sería útil si puede proporcionar detalles de todos los servicios de PaaS consumidos.

**Nota:** IaaS/PaaS no tendría ningún hardware que estuviera bajo el control ISV.  En este caso, proporcione una lista o captura de pantalla de todos los recursos viruales.

**Ejemplo:**

|Nombre del recurso|Tipo de recurso|Descripción|Fabricante|Model|
|---|---|---|---|---|
|D212|máquina Windows|Máquina virtual|N/D|N/D|
|LT101|Portátiles|Estación|Microsoft|Surface 3|
|C2938|Modificador|Modificador|N/D|N/D|
|LXM2|Máquina Linux|Máquina de prueba|N/D|N/D|


## <a name="software-inventory"></a>Inventario de software

Un inventario actualizado de todos los recursos de software, incluido todo el software usado en el entorno dentro del ámbito junto con las versiones.

**Ejemplo:**

|Software|Publisher|Versión|Finalidad|
|---|---|---|---|
|Windows Server|Microsoft 2016 |Compilación 14393|Sistema operativo del servidor para el entorno de producción|
|Linux Ubuntu|N/D|16.04 (Xenial)|Sistema operativo del servidor en uso dentro de la red perimetral.|
|Esxi|Vmware|6.5.0 (compilación 13004031)|Se usa para admitir los servidores virtuales.|
|Mysql (Windows)|N/D|8.0.2.1|Servidor de base de datos para almacenar el historial de chat.|
|Tomcat|Apache|7.0.92|Portal de clientes.|
|IIS|Microsoft|10.0|Admite las API.|


## <a name="third-party-dependencies"></a>Dependencias de terceros

Documentación que enumera todas las dependencias usadas por la aplicación o el complemento con las versiones en ejecución actuales.

**Ejemplo:**

|Dependencias web|Versión actual en uso|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|Bootstrap|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>Direcciones IP públicas

Detalles de todas las direcciones IP públicas y direcciones URL usadas por la infraestructura auxiliar. Esto debe incluir el intervalo ip enrutable completo asignado al entorno a menos que se haya implementado una segmentación adecuada para dividir el intervalo en uso (se necesitarán pruebas adecuadas de segmentación).

**Ejemplo:**

|Direcciones URL|Dirección IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A (Jump Server)|40.113.200.200|


## <a name="resource-endpoints"></a>Puntos de conexión de recursos

Dirección del punto de conexión de nombre de API Contoso Customer API https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com CONTOSO Files APIhttps://filesapi.contoso.com

Una lista completa de todos los puntos de conexión de API que usa la aplicación, incluidos los puntos de conexión de recursos externos y desarrollados internamente. Para ayudar a comprender el ámbito del entorno, proporcione ubicaciones de punto de conexión de API dentro del entorno.

**Ejemplo:**

|Nombre de LA API|  Dirección del punto de conexión|
|-|-|
|API de cliente de Contoso|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|API de archivos de Contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagrama de arquitectura

Diagrama de arquitectura lógica que representa una introducción de alto nivel de la infraestructura auxiliar de la aplicación o del complemento. Esto debe incluir todos los entornos de hospedaje y la infraestructura compatible con la aplicación o el complemento. Este diagrama DEBE representar todos los distintos componentes del sistema auxiliares dentro del entorno para ayudar a los analistas de certificación a comprender los sistemas en el ámbito y ayudar a determinar el muestreo. Indique también qué tipo de entorno de hospedaje se usa; Hospedado por ISV, IaaS, PaaS o híbrido. Cuando se use PaaS, indique los diversos servicios de PaaS que se usan para proporcionar los servicios auxiliares dentro del entorno.

![Diagrama de arquitectura](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagrama de Data Flow

Flow diagramas que detallan lo siguiente:
-   Los datos fluyen hacia y desde la aplicación o el complemento (incluidos los datos del cliente).
-   Flujos de datos dentro de la infraestructura auxiliar (si procede)
-   Diagramas que resaltan dónde y qué datos se almacenan, cómo se pasan datos a terceros externos (incluidos los detalles de qué terceros) y cómo se protegen los datos en tránsito a través de redes públicas y abiertas y en reposo.

![Diagrama de Data Flow](../media/Dataflowdiagram.png)



