---
ms.author: oromalle
title: Guía de envío de certificación de Microsoft 365
author: orionomalley
description: Vista granular guía de envío de certificación de Microsoft 365
keywords: Equipos de certificación de aplicaciones Microsoft 365 security compliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071369"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guía de envío de certificación de Microsoft 365

**En este artículo:**
- [Introducción](#introduction)
- [Requisitos previos](#prerequisites) 
- [Actualizaciones de especificación de certificación de Microsoft 365](#microsoft-365-certification-specification-updates)
- [Ámbito de certificación](#certification-scope)
- [Proceso de certificación](#certification-process)
- [Evidencia de cumplimiento](#compliance-evidence) 
- [Envío de documento inicial](#initial-document-submission) 
- [Actividades de recolección y evaluación de evidencias](#evidence-collection-and-assessment-activities)
- [Criterios de certificación](#app-certification-criteria)
- [Application Security](#application-security)
- [Seguridad operativa](#operational-security) 
- [Seguridad y privacidad de tratamiento de datos](#data-handling-security-and-privacy)
- [Revisión de marcos de cumplimiento externo opcional](#optional-external-compliance-frameworks-review)
- [Apéndice A](#appendix-a)
- [Apéndice B](#appendix-b) 
- [Apéndice C](#appendix-c) 
- [Apéndice D](#appendix-d) 
- [Apéndice E](#appendix-e) 
- [Apéndice F](#appendix-f) 
- [Apéndice G ](#appendix-g)
- [Más información](#learn-more) 
- [Glosario](#glossary) 


## <a name="introduction"></a>Introducción

Como parte del programa de cumplimiento de aplicaciones de Microsoft 365, la certificación de Microsoft 365 ofrece garantía y confianza a las organizaciones empresariales de que los datos y la privacidad están protegidos y protegidos adecuadamente al integrar aplicaciones y complementos para desarrolladores de terceros en la plataforma de Microsoft 365. Las aplicaciones y complementos que pasen la validación se designarán Certificados de **Microsoft 365** en todo el ecosistema de Microsoft 365. 

Al participar en el programa de certificación de Microsoft 365, acepta estos términos complementarios y cumple con cualquier documentación que se aplique a su participación en el programa de certificación de Microsoft 365 con Microsoft Corporation ("Microsoft", "nosotros", "nos" o "nuestro"). Usted nos declara y nos garantiza que tiene la autoridad para aceptar estos términos complementarios de certificación de Microsoft 365 en su nombre, una empresa u otra entidad, según corresponda. Podemos cambiar, modificar o terminar estos términos complementarios en cualquier momento. Su participación continua en el programa de certificación de Microsoft 365 después de cualquier cambio o modificación significa que acepta los nuevos términos complementarios. Si no está de acuerdo con los nuevos términos complementarios o si terminamos estos términos complementarios, debe dejar de participar en el programa de certificación de Microsoft 365.

Este documento está dirigido a los ISV (proveedores de software independientes) para proporcionar información sobre el proceso de certificación de Microsoft 365, los requisitos previos para iniciar el proceso y los detalles de los controles de seguridad específicos que deben tener los ISV.  Puede encontrar información general del programa de cumplimiento de aplicaciones de Microsoft 365 en la página del programa de cumplimiento de aplicaciones [de](https://docs.microsoft.com/microsoft-365-app-certification/overview)Microsoft 365 . 

> [!IMPORTANT]
> Actualmente, la certificación de Microsoft 365 está limitada:
>* Aplicaciones de Microsoft Teams (pestañas, bots, etc.).
>* Aplicaciones/complementos de Sharepoint
>* Complementos de Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Requisitos previos

### <a name="publisher-attestation"></a>Atestación de editor

Antes de obtener el proceso de certificación de Microsoft 365, debe haber completado la Atestación de editor. Sin embargo, puede iniciar el proceso de certificación de Microsoft 365 antes de completar la atestación de publisher.  

### <a name="read-the-microsoft-365-certification-specification"></a>Leer la especificación de certificación de Microsoft 365

Microsoft recomienda que todos los ISV (proveedor de software independiente) lean esta especificación de certificación de Microsoft 365 en su totalidad para garantizar que el entorno del ámbito y la aplicación o el complemento cumplen todos los controles aplicables. Esto ayudará a garantizar un proceso de evaluación sin problemas.

## <a name="microsoft-365-certification-specification-updates"></a>Actualizaciones de especificación de certificación de Microsoft 365 

Las actualizaciones de la especificación de certificación de Microsoft 365 se prevén aproximadamente cada seis o doce meses. Estas actualizaciones pueden introducir nuevos dominios de seguridad de destino y/o controles de seguridad. Las actualizaciones se basarán en los comentarios de los desarrolladores, los cambios en el panorama de amenazas y para aumentar la línea base de seguridad del programa a medida que madura. 

Los ISV que ya han iniciado la evaluación de certificación de Microsoft 365 pueden continuar la evaluación con la versión de la especificación de certificación de Microsoft 365 que era válida cuando se inició la evaluación. Todos los nuevos envíos, incluida la recertificación anual, tendrán que evaluarse con respecto a la versión publicada.

> [!NOTE]
> No es necesario que cumpla con todos los controles de esta especificación de certificación de Microsoft 365 para obtener una certificación. Sin embargo, se han establecido umbrales de paso (que no se divulgarán) para cada uno de los dominios de seguridad analizados en esta especificación de certificación de Microsoft 365. Algunos controles se clasificarán como un **"error** duro", lo que significa que la falta de estos controles de seguridad dará como resultado una evaluación con errores. 

## <a name="certification-scope"></a>Ámbito de certificación

El **entorno en el** ámbito es el entorno que admite la entrega del código de aplicación o complemento y admite los sistemas back-end con los que la aplicación o el complemento se puedan comunicar. Los entornos conectados adicionales también se incluirán en el ámbito a menos que haya una segmentación adecuada y los entornos conectados no puedan afectar a la seguridad del entorno en el ámbito. Los entornos de recuperación ante desastres también tendrán que incluirse en el ámbito de la evaluación, ya que estos entornos tendrían que cumplir el servicio en caso de que algo sucediera en el entorno principal.  El término **componentes del sistema en el** ámbito hace referencia a TODOS los dispositivos y sistemas que se usan en el entorno del   ámbito.  Los componentes del ámbito incluyen, entre otros:
* Las aplicaciones web.
* Servidores.
* Firewalls (o equivalentes).
* Modificadores.
* Equilibradores de carga.
* Infraestructura virtual.
* Portales de administración web del proveedor de nube 

> [!IMPORTANT]
> El entorno en el ámbito, debe tener una DMZ y el entorno de soporte de la aplicación o complemento debe segmentarse desde los sistemas empresariales internos y los entornos corporativos, limitando así el ámbito de las actividades de evaluación a los sistemas de ámbito únicamente. Los analistas de certificación validarán técnicas de segmentación durante la evaluación junto con la revisión de informes de pruebas de penetración que deberían haber incluido pruebas para validar la eficacia de las técnicas de segmentación en uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infraestructura como servicio (IaaS), Plataforma como servicio (PaaS) y Software como servicio (SaaS) 
Cuando IaaS y/o PaaS se usen para admitir la infraestructura de la aplicación o la entrega de código de complemento en revisión, el proveedor de la plataforma en la nube será responsable de algunos de los controles de seguridad evaluados durante todo el proceso de certificación. Por lo tanto, el proveedor de la plataforma en la nube deberá proporcionar a [](bookmark://pci-dss)los analistas de certificación la comprobación externa independiente de los procedimientos recomendados de seguridad a través de informes de cumplimiento externos, como los informes de certificación de cumplimiento   (AOC), ISO27001 o [SOC 2](bookmark://soc-2)   Tipo II. 

El Apéndice F proporciona detalles sobre qué controles de seguridad probablemente se aplicarán en función de los siguientes tipos de implementación y en función de si la aplicación o el complemento filtra o no los datos de M365: 
* ISV hospedado 
* IaaS hospedado 
* PaaS/Serverless Hosted 
* Hosted híbrido 
* Hosted compartido 

Cuando se implemente IaaS o PaaS, deberá proporcionar pruebas del entorno que se hospeda en estos tipos de implementación.

### <a name="sampling"></a>Muestreo

Las solicitudes de prueba que admitan la evaluación de certificación deben basarse en una muestra de los componentes del sistema en el ámbito en consideración de los diferentes sistemas operativos, la función principal del dispositivo y los distintos tipos de dispositivo. Al principio del proceso de certificación se seleccionará una muestra adecuada. La siguiente tabla debe usarse como guía sobre el tamaño de la muestra:

|Tamaño de la población              | Muestra                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Si se identifican discrepancias entre los dispositivos incluidos en la muestra inicial, el tamaño de la muestra puede aumentar durante la evaluación. 

## <a name="certification-process"></a>Proceso de certificación

Antes de iniciar el proceso de certificación, tendrías que haber iniciado o completado correctamente la certificación de publisher. Las respuestas de atestación se usarán como soporte del proceso de certificación de Microsoft 365 y procede de la siguiente manera: 

1. Revise la documentación sobre la atestación de publisher para garantizar la alineación con el entorno actual 
2. Solicitud para avanzar a la certificación de Microsoft 365 por correo electrónico <AppCert@microsoft.com> 
3. Los analistas de certificación abrirán un diálogo antes de iniciar el proceso de certificación de Microsoft 365   
4. Enviar el [envío inicial del documento](#initial-document-submission)
5. El analista de certificación proporcionará una lista de los controles para los que se requiere evidencia, lo que inicia formalmente el proceso de certificación de Microsoft 365
6. Enviar pruebas que demuestren que todos los controles de certificación de Microsoft 365 en el ámbito se han cumplido en una ventana de 60 días para completar la certificación de Microsoft 365 

> [!IMPORTANT]
> **Período de tiempo de envío:** Se prevé que, en promedio, el proceso de evaluación tarde 15 días, siempre y cuando pueda responder a las solicitudes de prueba en tiempo y forma. Microsoft recomienda asegurarse de que se ha leído esta guía de envío de certificación y estar seguro de que puede cumplir con los controles establecidos en ella y puede proporcionar suficiente evidencia antes de iniciar el proceso de certificación. Al iniciar el proceso de certificación, se permite un máximo de 60 días para completar la evaluación, de lo contrario, la evidencia ya recopilada se vuelve obsoleta. Si, después del período de tiempo de 60 días, no se alcanza una evaluación correcta, se emitirá un error en el envío y el proceso debe iniciarse de nuevo. Si se produce un error debido a que microsoft 365 Certification Specification no cumple la especificación de certificación de Microsoft 365 o porque se alcanza el período de tiempo de 60 días y no se proporciona suficiente evidencia, Microsoft no hará públicos los resultados con errores. 

## <a name="compliance-evidence"></a>Evidencia de cumplimiento

Aunque no es necesario, si actualmente cumple con otros marcos de seguridad externos, puede optar por usar estas certificaciones para satisfacer algunos de los controles de certificación de Microsoft 365. Los analistas de certificación revisarán el ámbito y la cobertura de control de seguridad de los marcos de seguridad externos admitidos para determinar qué controles se pueden excluir de la evaluación de certificación de Microsoft 365, siempre que el ámbito de los marcos de seguridad externos incluya los entornos dentro del ámbito de la evaluación de certificación de Microsoft 365. 

Los analistas de certificación intentarán alinear los marcos de seguridad externos existentes con la especificación de certificación de Microsoft 365. Sin embargo, si la documentación de soporte no puede proporcionar garantías de que los controles de certificación de Microsoft 365 se evaluaron como parte de la auditoría y evaluación de marcos de seguridad externos, deberá proporcionar pruebas adicionales de la implementación de estos controles. 

Actualmente, los marcos de seguridad externos que se pueden usar como soporte de la evaluación de certificación de Microsoft 365 incluyen:

*  [ISMS](#isms) / [IEC:](#iec) especificación IS0/IEC 27001 
*  [PCI DSS](#pci-dss)
*  [SOC 2](#soc-2)

La documentación debe demostrar adecuadamente que el entorno en el ámbito de la certificación de Microsoft 365 se incluyó dentro del ámbito de estos marcos de seguridad externos. La validación de estos marcos de seguridad se cumplirá aceptando pruebas de certificaciones válidas realizadas por empresas externas de confianza. Estas empresas de confianza deben ser miembros de organismos internacionales de acreditación para los programas de cumplimiento relevantes.Consulte [Iso Certification and Conformy Standards](https://www.iso.org/certification.html) for ISO 27001 and Qualified Security [Assessors](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) for PCI DSS. 

En la siguiente tabla se destaca la documentación requerida por los analistas de certificación como parte de este proceso de validación:

| **Estándar** | **Requisitos**  |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Se requiere una versión pública de la **declaración** de aplicabilidad (SOA) y una copia del certificado ISO 27001 emitido.  El SOA resume su posición en cada uno de los 114 controles de seguridad de la información y se usará para identificar si alguna exclusión de controles que no se detalla satisfactoriamente en el certificado ISO 27001. Si esto no se puede determinar revisando la versión pública de la SOA, es posible que el analista necesite acceso al SOA completo si se usará ISO 27001 para validar algunos de los controles de especificación de certificación de Microsoft 365.  Además de validar el ámbito de las actividades de evaluación iso 27001, los analistas también confirmarán la validez de la compañía de auditoría como se describió anteriormente.|
|**[PCI DSS](#pci-dss)**| Debe **proporcionarse** un documento de certificación de cumplimiento (AOC) válido de nivel 1 que identifique claramente los componentes del sistema y la aplicación en el ámbito.  No se aceptará una **AOC** de autoevaluación como prueba de los procedimientos recomendados de seguridad de reuniones. La AOC se usará para determinar cuál de los controles de especificación de certificación de Microsoft 365 se ha evaluado y confirmado como parte de la evaluación de PCI DSS.|
|**[SOC 2](#soc-2)**|El informe **SOC 2 (tipo I** o tipo II) debe estar actual (emitido en los últimos 15 meses y el período de tiempo declarado iniciado en los últimos 27 meses) para usarse como prueba de conformidad con cualquiera de los controles de evaluación de esta especificación de certificación de Microsoft 365.|


## <a name="microsoft-365-certification"></a>Certificación de Microsoft 365

Los marcos de seguridad externos compatibles se pueden usar como prueba de cumplir algunos de los controles de certificación de Microsoft 365. Antes de que se puedan considerar los marcos de seguridad externos, los analistas de certificación revisarán el ámbito y la cobertura de control de seguridad del marco de seguridad externo mediante la documentación enviada anteriormente. 

Los apéndices siguientes se pueden usar para identificar dónde existen posibles diferencias entre el marco de seguridad externo y la especificación de certificación de Microsoft 365 de la siguiente manera: 

|**Marco** | **Consideraciones adicionales** |
|-------------- | --------------------|
|ISO 27001| [**Apéndice C**](#appendix-c): Colección de evidencias: deltas para ISO 27001.|
|PCI DSS | [**Apéndice D**](#appendix-d): Colección de evidencias: deltas para PCI DSS.|
|SOC 2| [**Apéndice E**](#appendix-e): Colección de evidencias: deltas para SOC 2.|

> [!NOTE]
> Aunque los estándares y marcos de seguridad externos mencionados anteriormente se pueden enviar como prueba para cumplir algunos de los controles de certificación de Microsoft 365, pasar la certificación de Microsoft 365 no significa que pase correctamente una auditoría con esos estándares o marcos. La especificación de certificación de Microsoft 365 es solo un pequeño subconjunto de esos estándares o marcos de seguridad que permite a Microsoft obtener un nivel de seguridad en referencia a su posición de seguridad.

## <a name="initial-document-submission"></a>Envío inicial de documentos

El envío inicial del documento ayudará a los analistas de certificación a realizar el ámbito y a determinar lo que estará en el ámbito de su evaluación. Después de lo cual tendrá que enviar la documentación de soporte y las pruebas usadas para llevar a cabo la evaluación. El envío inicial debe incluir la información especificada a continuación:

| **Introducción a &nbsp; la documentación**     |   **Detalles de la documentación**  |
| -------------------------| -----------------------------|
|**Descripción de la aplicación/complemento** | Una descripción del propósito y la funcionalidad de la aplicación/complemento. Esto debe proporcionar al analista de certificación una buena comprensión de cómo funciona la aplicación o el complemento y cuál es su uso previsto.
|**Informe de pruebas de penetración** |Un informe de pruebas de penetración completado en los últimos 12 meses. Este informe debe incluir el entorno que admite la implementación de la aplicación o la adición junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o el complemento. **Nota:** si no realiza pruebas de penetración anuales, puede elegir que se realicen a través del proceso de certificación.|
|**Diagramas de arquitectura**|Diagrama de arquitectura lógica que representa una descripción general de alto nivel de la infraestructura de soporte técnico de la aplicación/ complemento. Esto debe incluir todos **los entornos** de hospedaje y la infraestructura compatible con la aplicación o el complemento. Este diagrama DEBE representar todos los diferentes componentes del sistema de soporte en el entorno para ayudar a los analistas de certificación a comprender los sistemas en el ámbito y ayudar a determinar el muestreo. Indique también qué tipo de entorno de hospedaje se usa; ISV hospedado, IaaS, PaaS o híbrido. **Nota:** Donde se usa SaaS, indique los distintos servicios SaaS que se usan para proporcionar los servicios de soporte técnico en el entorno.|
|**Huella pública** | Detalle de **todas las** direcciones IP públicas y direcciones URL usadas por la infraestructura compatible. Esto debe incluir el intervalo IP enrutable completo asignado al entorno a menos que se haya implementado una segmentación adecuada para dividir el intervalo en uso (se requiere una evidencia adecuada de segmentación)|
|**Diagramas de flujo de datos** |Diagramas de flujo que detallan lo siguiente:
||&#x2713; M365 Los datos fluyen hacia y desde la aplicación o el complemento [(incluidos EUII](#euii) y [OII](#oii) ).|
||&#x2713; M365 Flujos de datos dentro de la infraestructura de soporte (cuando corresponda)|
||&#x2713; diagramas que resaltan dónde y qué datos se almacenan, cómo se pasan los datos a terceros externos (incluidos los detalles de qué terceros) y cómo se protegen los datos en tránsito a través de redes abiertas/públicas y en reposo.|
|**Detalles del extremo de la API**| Una lista completa de todos los puntos de conexión de API usados por la aplicación. Para ayudar a comprender el ámbito del entorno, proporcione ubicaciones de extremo de API dentro del entorno.                                
|**Permisos de api de Microsoft**| Proporcionar documentación que detalle **todas** las API de Microsoft que se usan junto con los permisos que se solicitan para que la aplicación o el complemento funcionen junto con una justificación de los permisos solicitados|
|**Tipos de almacenamiento de datos** |Almacenamiento de datos y tratamiento de documentos que describen:|
||&#x2713; En qué medida se reciben y almacenan sus clientes M365 Data [EUII](#euii) y [OII](#oii)|
||&#x2713; el período de retención de datos.|
||&#x2713; por qué se capturan los datos M365 del cliente.|
||&#x2713; donde se almacenan los datos M365 del cliente (debe incluirse en los diagramas de flujo de datos proporcionados anteriormente).|
|**Confirmación de cumplimiento**|Documentación de soporte técnico para marcos de seguridad externos incluidos en el envío de atestación de publisher o que se debe tener en cuenta al revisar los controles de certificación de Microsoft 365. Actualmente, se admiten los tres siguientes:|
||&#x2713; certificación de cumplimiento [(AOC) de PCI DSS.](#pci-dss)|
||&#x2713; [soc 2](#soc-2) tipo I/type II informes.|
||&#x2713; [ISMS](#isms)  /  [IEC-](#iec) 1S0/IEC 27001 Declaración de aplicabilidad (SoA) y certificación.|
|**Dependencias web**|Documentación que enumera todas las dependencias usadas por la aplicación o el complemento con las versiones en ejecución actuales.|
|**Inventario de software**|Un inventario de software actualizado que incluye todo el software usado en el entorno del ámbito junto con las versiones.|
|**Inventario de hardware**| Un inventario de hardware actualizado usado por la infraestructura de soporte técnico. Esto se usará para ayudar con el muestreo al realizar la fase de evaluación. Si el entorno incluye PaaS, proporcione detalles de los servicios consumidos.|

## <a name="evidence-collection-and-assessment-activities"></a>Actividades de recolección y evaluación de evidencias

A través de actividades sólidas de recopilación y evaluación de pruebas, los analistas de certificación podrán evaluar su posición de seguridad para obtener un nivel adecuado de seguridad de datos y cumplimiento de los controles de especificación de certificación de Microsoft 365. Los analistas de certificación lograrán esto de la siguiente manera: 

**Colección Evidence**

* Documentación inicial, resaltada en la sección [De envío de documentación](#initial-document-submission) inicial anterior 
* Documentos de directiva 
* Procesar documentos 
* Opciones de configuración del sistema 
* Cambiar vales 
* Cambiar registros de control 
* Informes del sistema

Se usarán varios métodos para recopilar las pruebas necesarias para completar el proceso de evaluación.  Esta colección de pruebas puede tener la forma de: 
* Documentos 
* Capturas de pantalla 
* Entrevistas 
* Screensharing 

Las técnicas de recolección de evidencias usadas se determinarán durante el proceso de evaluación. 

**Actividades de evaluación**

Los analistas de certificación revisarán las pruebas que proporcione para determinar si ha cumplido adecuadamente los controles dentro de esta especificación de certificación de Microsoft 365. 

Siempre que sea posible y para reducir la cantidad de tiempo necesaria para [](#initial-document-submission)completar la evaluación, se debe proporcionar con antelación toda o toda la documentación detallada en el envío   de documentación inicial.

Los analistas de certificación revisarán primero las pruebas proporcionadas en el envío de documentación inicial y la información de atestación del editor para identificar las líneas de investigación adecuadas, el tamaño del muestreo y la necesidad de obtener más pruebas como se ha detallado anteriormente.  Los analistas de certificación analizarán toda la información recopilada para extraer conclusiones sobre cómo y si va a cumplir los controles de esta especificación de certificación de Microsoft 365. 

## <a name="app-certification-criteria"></a>Criterios de certificación de aplicaciones

La aplicación, la infraestructura de soporte técnico y la documentación de soporte técnico se evaluarán en los siguientes dominios de seguridad:

1. [**Application Security**](#application-security)
1. [**Seguridad operativa /Implementación segura**](#operational-security)
1. [**Seguridad y privacidad de tratamiento de datos**](#data-handling-security-and-privacy)
1. [**Revisión opcional del marco de cumplimiento externo**](#optional-external-compliance-frameworks-review)

Cada uno de estos dominios de seguridad incluye controles clave específicos que abarcan uno o más requisitos específicos que se evaluarán como parte del proceso de evaluación. Para garantizar que la certificación de Microsoft 365 sea inclusiva para desarrolladores de todos los tamaños, cada uno de los cuatro dominios de seguridad se evalúa mediante un sistema de puntuación para determinar una puntuación general de cada uno de los dominios. Las puntuaciones de cada uno de los controles de certificación de Microsoft 365 se asignan entre 1 (bajo) y 3 (alto) en función del riesgo percibido de que ese control no se cumple. Cada uno de los cuatro dominios de seguridad tendrá una marca de porcentaje mínima que se considerará un pase. Algunos elementos de esta especificación incluyen algunos criterios de error automáticos:

- Los permisos de api no se apea al principio de privilegios mínimos (PoLP).  
- No hay informe de pruebas de penetración cuando es necesario.
- Sin defensas antimalware
- La autenticación multifactor no se usa para proteger el acceso administrativo.  
- No hay procesos de revisión.  
- No hay aviso [de privacidad del RGPD](#gdpr) adecuado.  

## <a name="application-security"></a>Application Security

El dominio de seguridad de la aplicación se centra en las tres áreas siguientes: 
* Validación de permisos de GraphAPI 
* Comprobaciones de conectividad externa
* Pruebas de seguridad de aplicaciones 

**Validación de permisos de GraphAPI**

La validación de permisos graphAPI se lleva a cabo para validar que la aplicación o el complemento no solicita permisos muy permisivos. Esto se lleva a cabo comprobando manualmente qué permisos se solicitan. Los analistas de certificación harán referencia a estas comprobaciones en el envío de la atestación de publisher y evaluarán el nivel de acceso que se solicita para garantizar que se cumplen las prácticas de "privilegios mínimos". Cuando los analistas de certificación creen que no se cumplen estas prácticas de "privilegios mínimos", los analistas de certificación tendrán una discusión abierta con usted para validar la justificación empresarial de los permisos que se solicitan. Las discrepancias con el envío de atestación de editor que se haya encontrado durante esta revisión también recibirán comentarios para que se pueda actualizar la Atestación del editor. 

**Comprobaciones de conectividad externa**

Como parte de la evaluación, un analista realizará un recorrido ligero por la funcionalidad de las aplicaciones para identificar conexiones fuera de M365.  Las conexiones que no se identifiquen como Microsoft o conexiones directas al servicio se marcarán y se analizarán durante la evaluación.

**Pruebas de seguridad de aplicaciones**

Una revisión adecuada de los riesgos asociados con la aplicación/complemento y el entorno de soporte técnico es esencial para proporcionar a los clientes garantías en la seguridad de la aplicación/complemento. Las pruebas de seguridad de aplicaciones en forma de pruebas de penetración DEBEN realizarse si la aplicación tiene conectividad con cualquier servicio no publicado por Microsoft. Si la aplicación funciona de forma independiente sin conectividad a ningún servicio o back-end que no sea de Microsoft, no es necesario realizar pruebas de penetración.


### <a name="penetration-testing-scope"></a>Ámbito de pruebas de penetración

Las actividades  de prueba de penetración DEBEN incluir el entorno que admite la implementación de la aplicación o el complemento (por ejemplo, donde se hospeda el código de aplicación o complemento que normalmente será el recurso dentro del archivo de manifiesto) junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o el complemento (por ejemplo, si la aplicación o el complemento habla con otras aplicaciones web fuera de Microsoft 365).  Al definir el ámbito, es necesario tener cuidado para asegurarse de que todos los sistemas o entornos "conectados" que puedan afectar a la seguridad del entorno en el ámbito también se incluyan en TODAS las actividades de prueba de penetración. 

Cuando se usan técnicas para segmentar los entornos del ámbito desde otros entornos, las actividades de prueba de penetración DEBEN validar la eficacia de estas técnicas de segmentación. Esto debe detallarse en el informe de pruebas de penetración. 
 

### <a name="testspecification"></a>Especificación de prueba 

|Prueba | Controles |
|-------|-----------|
|**Pruebas de penetración**| Las pruebas de penetración de aplicaciones e infraestructuras **DEBEN** realizarse anualmente (cada 12 meses) y realizadas por una compañía independiente de confianza. La corrección de las vulnerabilidades  críticas y de alto riesgo identificadas DEBE completarse en el plazo de un mes a la finalización de las pruebas de penetración, o antes, según el proceso de revisión documentado.La superficie externa completa (direcciones IP, direcciones URL, extremos de API, etc.) DEBE incluirse dentro del ámbito de las pruebas de penetración y debe estar documentado en el informe de pruebas de penetración. La superficie externa completa (direcciones IP, direcciones URL, extremos de API, etc.) **DEBE** incluirse dentro del ámbito de las pruebas de penetración y debe estar documentado en el informe de pruebas de penetración.                                                                                                                                                                           Las pruebas de penetración de aplicaciones web DEBEN incluir todas las clases de vulnerabilidad; por ejemplo, el OWASP top 10 o SANS top 25 CWE más actual.                                                                                                                                                                                No es necesario volver a probar las vulnerabilidades identificadas por la compañía de pruebas de  penetración: la corrección y la autoexaminación son suficientes, sin embargo, deben proporcionarse pruebas adecuadas para demostrar la corrección suficiente durante la evaluación.|

### <a name="application-security-testing-reportreview"></a>Revisión del informe de pruebas de seguridad de aplicaciones

Se revisarán los informes de pruebas de penetración para asegurarse de que no hay vulnerabilidades que cumplan los siguientes criterios **de error automático:**

* Presencia de un sistema operativo no compatible. 

* Presencia de cuentas administrativas predeterminadas, enumerables o adivinables.

* Presencia de SQL de inyección.*

* Presencia de scripting entre sitios.*

* Presencia de vulnerabilidades de recorrido de directorio (ruta de acceso de archivo).*

* Presencia de vulnerabilidades HTTP, por ejemplo, división de respuesta de encabezado, contrabando de solicitudes y ataques de desincronización.*

* Presencia de divulgación de código fuente [(incluida LFI](#lfi)).*

* Cualquier puntuación crítica o alta definida por las directrices de administración de revisiones de CVSS.

* Cualquier vulnerabilidad técnica significativa que se pueda aprovechar fácilmente para poner en peligro una gran cantidad de EUII o OUI.

*Independientemente de las vulnerabilidades cvss score

> [!IMPORTANT]
>Los informes deben poder proporcionar la suficiente garantía de que se puede demostrar todo lo que se detalla en la sección Application Security Test Specification.


### <a name="penetration-testing-requirements-and-cost"></a>Requisitos y costo de las pruebas de penetración

Para los ISV que actualmente no participan en pruebas de penetración, las pruebas de penetración se incluyen en la certificación de Microsoft 365. Microsoft organizará y cubrirá el costo de una prueba de penetración durante un máximo de 12 días de pruebas manuales. Los costos de las pruebas de penetración se calculan en función del número de días necesarios para probar el entorno. Los gastos que superen los 12 días de pruebas serán responsabilidad del ISV. The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.

Una vez que se organiza una prueba de penetración, el ISV es responsable de las tarifas asociadas con la reprogramación y las cancelaciones de la siguiente manera:

| **Rescheduling Fee Timescale** | **Proporciones pagaderas** |
|------------------|------------------------|
| Volver a programar la solicitud recibida más de 30 días antes de la fecha de inicio programada. | 0% pagadero |
| Volver a programar la solicitud recibida de 8 a 30 días antes de la fecha de inicio programada. | 25% pagadero |
| Vuelva a programar la solicitud recibida entre 2 y 7 días antes de la fecha de inicio programada con una fecha de reserva de empresa.| 50% pagadero |
| Volver a programar la solicitud recibida menos de 2 días antes de la fecha de inicio. | 100% pagadero |

| **Escala temporal de la cuota de cancelación** | **Proporciones pagaderas** |
|------------------|------------------------|
| Solicitud de cancelación recibida más de 30 días antes de la fecha de inicio programada. | 25% pagadero |
| Solicitud de cancelación recibida de 8 a 30 días antes de la fecha de inicio programada. | 50% pagadero |
| Solicitud de cancelación recibida dentro de los 7 días anteriores a la fecha de inicio programada. | 90% pagadero |

## <a name="operational-security"></a>Seguridad operativa

Este dominio mide la alineación de la infraestructura y los procesos de implementación compatibles de la aplicación con los procedimientos recomendados de seguridad.

### <a name="test-specification"></a>Especificación de prueba

|Prueba | Controles |
| ------------------------|------------------------------ |
| **Protección contra malware** | Debe implementar mecanismos de protección contra malware en todos los sistemas del ámbito que se ven afectados por el malware. Estos mecanismos de protección pueden incluir el uso de software antivirus o técnicas de control de aplicaciones que protegen contra malware. Cuando se usa software antivirus o control de aplicaciones, debe cumplir los siguientes criterios.                                                                                            Los antivirus (también incluidos los productos antimalware) DEBEN cumplir lo siguiente: |
||&#x2713; software antivirus se ejecuta en todos los componentes del sistema dentro del ámbito.|
||&#x2713; el software antivirus se mantiene actualizado (en un plazo de 30 días).|
||&#x2713; las firmas antivirus se mantienen actualizadas (en un plazo de 1 día).|
||&#x2713; debe configurarse el examen en tiempo real o los exámenes periódicos con notificaciones.  Cuando se usa el examen  en tiempo real, también deben configurarse los exámenes semanales, pero si el examen en tiempo real no está configurado, se debe configurar el examen diario.|
||&#x2713; el **software** antivirus debe configurarse de la siguiente manera.|
||&emsp;&#x25fc; bloquear el malware sospechoso.|
||&emsp;&#x25fc; cuarentena sospecha de malware.|
||&emsp;&#x25fc; proporcionar una alerta sobre el malware sospechoso.|
||&#x2713; el **software** antivirus debe configurarse para registrar todas las actividades.
||&#x2713; deben establecerse  directivas y procedimientos para promover prácticas antimalware seguras.|
||o|
||Los controles de aplicación DEBEN configurarse en todos los sistemas del ámbito para que cumplan lo siguiente:|
||&#x2713; Todas las aplicaciones permitidas para ejecutarse en componentes del sistema en el ámbito deben ser aprobadas formalmente por la organización.|
||&#x2713; La organización DEBE mantener una lista completa de aplicaciones aprobadas con justificación empresarial para la aplicación.|
||&#x2713; deben documentarse completamente los mecanismos de control de aplicaciones específicos: es decir, ubicaciones en la lista blanca; firma de código, etc.|
||&#x2713; control de aplicación debe configurarse como documento.|
||&#x2713; proceso documentado para las aprobaciones de aplicaciones debe estar en marcha y auditable.|
|**Administración de parches**|DEBE **tener** documentadas directivas y procedimientos de revisión que garanticen que la revisión se realice de forma oportuna. Debe haber  un proceso sólido que identifique, clasifice y parchee nuevas vulnerabilidades de seguridad según las puntuaciones de clasificación de riesgos recomendadas de CVSS V3.1 o la taxonomía de puntuación equivalente: 
||**Puntuaciones de clasificación de riesgos** recomendadas (intervalo de puntuación base de CVSS v3.1)|
||&emsp;**Crítico**: 9.0 - 10.0.|
||&emsp;**High**: 7.0 - 8.9.|
||&emsp;**Medium**: 4.0 - 6.9.|
||&emsp;**Bajo**: 0,1 - 3,9.|
||&emsp;**None**: 0.0 |
|| **IMPORTANTE:** El proceso para identificar nuevas vulnerabilidades debe ser lo suficientemente sólido como para permitir la identificación y revisión de vulnerabilidades en línea con la ventana de revisión documentada que haya definido. |
|**Patching**|&#x2713; Los problemas de riesgo crítico,  alto o medio deben ser corregidos dentro de un período predefinido y documentado decidido por el ISV, que representa la ventana mínima de tiempo antes de que se resuelva el **problema.**  Aunque la ventana de revisión está definida por el ISV, la ventana debe estar dentro de un plazo razonable. Por ejemplo, tres meses para corregir una vulnerabilidad crítica no sería razonable y, por lo tanto, se rechazaría dentro de la evaluación de certificación de Microsoft 365.|
||&#x2713; directivas y procedimientos que detallan cómo  se lleva  a cabo la revisión DEBEN estar en funcionamiento y DEBEN incluir todos los sistemas operativos, aplicaciones y componentes de software aplicables que se usan en el entorno. Esto incluye todas las dependencias web usadas dentro de la aplicación o el complemento.|
||&#x2713; componentes de software y sistemas operativos que ya no son compatibles con el proveedor **NO** DEBEN usarse en el entorno. Las directivas  de soporte deben estar en su lugar para garantizar que los componentes de software no admitidos o los sistemas operativos se quitarán del entorno y debe haber un proceso para identificar cuándo los componentes de software terminan su vida útil.|
|**Análisis de vulnerabilidades**|El examen de vulnerabilidades debe incluir:|
||&#x2713; análisis trimestral de vulnerabilidades externas llevado  a cabo en la superficie pública completa del entorno en el ámbito (direcciones URL Y direcciones IP para el examen de la infraestructura y la aplicación web).|
||&#x2713; análisis de vulnerabilidad interna autenticado trimestralmente realizado en componentes del sistema en el ámbito (no para PaaS).|
||&#x2713; Debe haber una directiva de  corrección de vulnerabilidades documentada para garantizar que los componentes del sistema estén libres de vulnerabilidades conocidas, detallando la escala de tiempo para corregir vulnerabilidades en función de las puntuaciones de clasificación de riesgos recomendadas de CVSS **** definidas (vea más arriba).|
||&#x2713; Deben realizarse exámenes  en curso hasta que se solucione la vulnerabilidad clasificada por riesgo identificado dentro de la escala de tiempo necesaria, tal como se define en la directiva de corrección del ISV. Aunque la escala de tiempo de corrección está definida por el ISV, la ventana debe estar en un plazo razonable. Por ejemplo, tres meses para corregir una vulnerabilidad crítica no sería razonable y, por lo tanto, se rechazaría dentro de la evaluación de certificación de Microsoft 365.|
|**Firewalls**|Se espera que la infraestructura de soporte técnico tenga configurado un firewall (o equivalente donde se consumen los servicios en la nube) de la siguiente manera:|
||&#x2713; **debe** instalarse en todas las conexiones a Internet que expongan los entornos del ámbito.|
||&#x2713; **debe** instalarse entre todas las DMZ (zonas desmilitarizadas) y las redes de confianza.|
||&#x2713; Todo el acceso público **DEBE** finalizar en una DMZ (zona desmilitarizada). |
||&#x2713; Deben cambiarse las credenciales **administrativas** predeterminadas antes de la instalación en entornos de producción.|
||&#x2713; Todo el tráfico permitido a través de firewalls en el ámbito (en cualquier **dirección)** DEBE pasar por un proceso de aprobación y todos los protocolos, servicios y puertos deben documentarse con justificaciones empresariales.|
||&#x2713; reglas de firewall deben configurarse en línea con las reglas permitidas documentadas.|
||&#x2713; Criptografía segura, en línea con  el Apéndice **B,** DEBE estar habilitada en todas las interfaces administrativas de firewall que no sean de consola.|
||&#x2713; la autenticación multifactor (MFA) **DEBE** estar habilitada para el acceso administrativo del firewall.|
||&#x2713; las revisiones del firewall **deben** realizarse al menos cada seis meses.|
||El análisis de certificación revisará la base de reglas de firewall para la presencia de flujos de tráfico de salida a terceros potenciales para validar el uso compartido de datos de terceros externos.  |
||**Firewall de aplicaciones web (WAF).** Se dará crédito adicional si se implementa una medida DESA o equivalente para ayudar a proteger contra las amenazas y vulnerabilidades de las aplicaciones web. Si está presente, las directivas y procedimientos de soporte **deben** estar en su lugar junto con las siguientes configuraciones de WAF: |
||&#x2713; DEBLE DEBE funcionar en modo de defensa activa (bloqueo automático de ataques identificados) o en modo de supervisión (supervisión e investigación activa de alertas).|
||&#x2713; DEBLE configurado para admitir la descarga de [SSL.](#ssl)|
||&#x2713; DEBA configurarse según el conjunto de reglas principales de [OWASP](#owasp) ****   (3.0 o 3.1) para protegerse contra la mayoría de lo siguiente:|
||&emsp;&#x25fc; de protocolo y codificación.|
||&emsp;&#x25fc; inserción de encabezado, contrabando de solicitudes y división de respuesta.|
||&emsp;&#x25fc; ataques de recorrido de archivos y rutas de acceso.|
||&emsp;&#x25fc; de inclusión remota de archivos (RFI).|
||&emsp;&#x25fc; de ejecución remota de código.|
||&emsp;&#x25fc; ataques de inyección de PHP.|
||&emsp;&#x25fc; ataques de scripting entre sitios.|
||&emsp;&#x25fc; SQL de inyección.|
||&emsp;&#x25fc; de fijación de sesión.|
|**Control De cambios**|Las directivas y  procedimientos de control de cambios deben estar en marcha para garantizar que los cambios se implementan de manera que se mantenga la seguridad, la estabilidad y la integridad del entorno. Se requieren los siguientes criterios de control **de** cambios:|
||&#x2713; separación de tareas: los **entornos** de desarrollo y prueba deben ser independientes de los entornos de producción.|
||&#x2713; datos confidenciales de entornos de producción **NO DEBEN** usarse en entornos de desarrollo o prueba.|
||&#x2713; Todos los cambios DEBEN probarse en un entorno de prueba o desarrollo antes de introducirse en el entorno de producción.|
||&#x2713; solicitudes de cambio **se** genera y se autoriza **ANTES** de entrar en producción.|
||&#x2713; Como mínimo, las solicitudes de cambio **DEBEN** incluir:|
||&emsp;&#x25fc; documentación del impacto.|
||&emsp;&#x25fc; procedimientos de back-out documentados.|
||&#x2713; las solicitudes de cambio **deben** marcarse como completas, solo **después** de que se hayan llevado a cabo las pruebas de funcionalidad correctas.|
|**Desarrollo e implementación de software seguro**|La seguridad debe estar a la vanguardia de las prácticas de desarrollo de software para minimizar el riesgo de introducir vulnerabilidades de codificación en la aplicación o el complemento, manteniendo así un entorno seguro y protegiendo los datos. Las siguientes prácticas seguras de desarrollo de software **DEBEN** estar en marcha: |
||&#x2713; debe tener un proceso de desarrollo de software establecido y documentado que cubra todo el ciclo de vida de desarrollo de software.|
||&#x2713; Todos los cambios de código DEBEN pasar por un proceso de revisión y autorización por parte de otra persona que no sea el desarrollador original.|
||&#x2713; Prácticas de codificación segura **y** técnicas de revisión DEBEN abordar las 10 principales clases de vulnerabilidad de [OWASP](https://owasp.org/www-project-top-ten) o [SANS Top 25 CWE.](https://www.sans.org/top25-software-errors)|
||&#x2713; desarrolladores **deben someterse** a un aprendizaje seguro de codificación de software al menos anualmente.|
||&#x2713; repositorios de **código deben** protegerse mediante MFA.|
||&#x2713; deben haber controles **de** acceso adecuados para proteger los repositorios de código contra modificaciones de código malintencionadas.|
||**Nota:** Microsoft ha [](https://www.microsoft.com/en-us/securityengineering/sdl/) publicado el Ciclo de vida de desarrollo de seguridad (SDL) que Microsoft sigue para admitir los requisitos de seguridad y cumplimiento dentro de sus productos. SDL ayuda a los desarrolladores a crear software más seguro al reducir el número y la gravedad de las vulnerabilidades del software, al tiempo que reduce el costo de desarrollo.|
|**Administración de cuentas**| La administración de cuentas de componentes del sistema en el ámbito, así como las directivas y procedimientos de soporte técnico **DEBEN** cumplir lo siguiente: |
||&#x2713; credenciales predeterminadas (proveedor o ISV) **se** deshabilitan o quitan en todos los componentes del sistema del ámbito.|
||&#x2713; creación, modificación y eliminación de cuentas **DEBEN** pasar por un proceso de aprobación establecido.|
||&#x2713; las cuentas que no se han usado  durante más de 3 meses deben deshabilitarse o eliminarse, por lo tanto, ISV debe tener un mecanismo para lograrlo.|
||&#x2713;directivas de contraseña segura u otra mitigación adecuada **DEBEN** configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseñas debe usarse como guía:|
||&emsp;&#x25fc; longitud mínima de contraseña de ocho caracteres|
||&emsp;&#x25fc; umbral de bloqueo de cuenta de no más de 10 intentos|
||&emsp;&#x25fc; historial de contraseñas de un mínimo de cinco contraseñas|
||&emsp;&#x25fc; cumplimiento del uso de contraseñas seguras|
||&#x2713; deben emitirse cuentas de usuario únicas para cada usuario; no se van a usar cuentas compartidas.|
||&#x2713; **principios** de privilegios mínimos DEBEN aplicarse a todos los usuarios, el mecanismo usado para lograrlo debe documentarse (es decir, el uso de grupos). |
||&#x2713; se debe documentar y  llevar a cabo el endurecimiento adecuado de la cuenta de servicio, por ejemplo, el inicio de sesión interactivo deshabilitado, los inicios de sesión limitados a hosts específicos, etc. |
||&#x2713; soluciones de acceso remoto **DEBEN:** |
||&emsp;&#x25fc; mfa (autenticación multifactor)|
||&emsp;&#x25fc; un perfil de protección de tránsito que cumpla o supere el perfil de configuración de datos en tránsito, tal como se describe en el Apéndice A|
||&#x2713; Donde la administración de DNS público está fuera del entorno en el ámbito, todas las cuentas de usuario que puedan realizar modificaciones dns deben configurarse para usar MFA.|
||**Nota:** Los portales de administración en la nube también tendrán que cumplir los requisitos de administración de cuentas aplicables, consulte el Apéndice F para obtener más detalles.|
|**Detección y prevención de intrusiones (OPCIONAL)**| Se dará crédito adicional donde se usa IDPS (Sistema de detección y prevención de intrusiones) en el perímetro de los entornos de soporte técnico en el ámbito.  Los siguientes controles recomendados incluyen: |
||&#x2713; IDPS deben implementarse en el perímetro del entorno de soporte técnico |
||&#x2713; las firmas idps deben mantenerse actualizadas en el último día |
||&#x2713; IDPS deben configurarse para la inspección tls |
||&#x2713; IDPS deben configurarse para TODO el tráfico entrante y saliente |
||&#x2713; IDPS deben configurarse para alertas |
|**Registro de eventos** |La cobertura de registro **DEBE** incluir **TODOS los** componentes y aplicaciones del sistema en el ámbito, incluidos los mecanismos de protección contra malware. Se deben **registrar los siguientes** eventos:|
||&emsp;&#x25fc; Acceso de los usuarios a los componentes del sistema y la aplicación|
||&emsp;&#x25fc; Todas las acciones realizadas por un usuario con privilegios altos|
||&emsp;&#x25fc; intentos de acceso lógico no válidos|
||&emsp;&#x25fc; o modificación de cuentas con privilegios|
||&emsp;&#x25fc; de registro de eventos|
||&emsp;&#x25fc; deshabilitación de herramientas de seguridad; por ejemplo, antimalware o registro de eventos|
||&emsp;&#x25fc; registro antimalware; por ejemplo, actualizaciones, detección de malware, errores de examen|
||&emsp;&#x25fc; eventos IDPS/WAF (si están configurados)|
||Los registros **de eventos** DEBEN incluir la siguiente información:|
||&emsp;&#x25fc; de usuario |
||&emsp;&#x25fc; tipo de evento |
||&emsp;&#x25fc; fecha y hora |
||&emsp;&#x25fc; correcto/error|
||&emsp;&#x25fc; etiqueta para identificar el sistema afectado |
||La sincronización de **tiempo DEBE** usarse en todos los componentes del sistema en el ámbito para ayudar en las investigaciones forenses.|
||La sincronización de **tiempo DEBE** configurarse para usar el mismo origen de tiempo principal (y secundario si es necesario)|
||Los sistemas públicos (sistemas dentro de la DMZ) **DEBEN** escribir registros en un repositorio de registro centralizado interno. El repositorio de registro centralizado no debe estar dentro de la DMZ.|
||Los seguimientos **de auditoría** DEBEN protegerse para garantizar que un actor de amenazas no pueda modificar los datos de registro. El acceso al repositorio de registro centralizado debe limitarse únicamente al personal autorizado.|
||Los **registros DEBEN** estar disponibles inmediatamente durante 30 días. Los datos de **registro** DEBEN conservarse durante un mínimo de 90 días.|
|**Revisión** |Revisar los procesos, así como las directivas y procedimientos de soporte **técnico DEBEN** cumplir lo siguiente:|
||&#x2713; realizar revisiones diarias de registros o usar la tecnología de análisis de registro automatizado y alertas para revisar los eventos de todos los componentes del sistema en el ámbito para identificar posibles eventos de seguridad.|
||&#x2713; Debe **realizarse** un seguimiento inmediato de los posibles eventos de seguridad.|
|**Alertas** |Los procesos de alerta, así como las directivas y procedimientos de soporte técnico **DEBEN** cumplir lo siguiente: |
||&#x2713; eventos de seguridad registrados que representan un riesgo para la seguridad de sus sistemas, operaciones o datos DEBE desencadenar una alerta inmediata, por ejemplo (no una lista exhaustiva):|
||&emsp;&#x25fc;/ modificaciones de cuentas de privilegios|
||&emsp;&#x25fc; malware|
||&emsp;&#x25fc; deshabilitar herramientas de seguridad|
||&emsp;&#x25fc; de registro de eventos|
||&emsp;&#x25fc; eventos IDPS/WAF (si están configurados) |
||&#x2713; personal debe estar siempre disponible (24/7) para reaccionar ante alertas desencadenadas.|
|**Administración de riesgos**|Se debe desarrollar y llevar a cabo una metodología de evaluación de riesgos que incluya lo siguiente:|
||&#x2713; Un proceso definido formalmente.|
||&#x2713; se realiza al menos anualmente.|
||&#x2713; Incluye todos los activos dentro del entorno del ámbito.|
||&#x2713; Identifica las amenazas y vulnerabilidades de todos los activos incluidos.|
||&#x2713; incluye el uso de matrices de impacto y probabilidad definidas.|
||&#x2713; resultados en la creación de un registro de riesgos y el correspondiente plan de tratamiento de riesgos.|
|**Respuesta a incidentes**|Un plan de respuesta a **incidentes exhaustivo es** necesario y **DEBE** incluir como mínimo:|
||&#x2713;, como mínimo, la cobertura de los componentes y aplicaciones de sistemas en el ámbito.|
||&#x2713; procedimientos de respuesta a incidentes específicos para modelos de amenazas esperados.|
||&#x2713; de comunicaciones documentadas, lo que garantiza la notificación a tiempo de todas las partes interesadas clave y de todos los organismos externos relevantes, como; marcas de pago/adquirentes, organismos reguladores y autoridades de supervisión[(RGPD)](#gdpr)de acuerdo con los requisitos de informes obligatorios.|
||&#x2713; La respuesta a incidentes se actualiza en función de las lecciones aprendidas, los cambios organizativos y para incorporar los desarrollos del sector.|
||&#x2713; curso anual para los miembros del equipo de respuesta a incidentes.|

## <a name="data-handling-security-and-privacy"></a>Seguridad y privacidad de tratamiento de datos

Los datos en tránsito entre el usuario de la aplicación, los servicios intermediarios y los sistemas de ISV tendrán que protegerse mediante cifrado a través de una conexión TLS que admita un mínimo de TLS v1.1. *Vea* [**el Apéndice A**](#appendix-a).

Cuando la aplicación recupere y almacena datos M365, tendrá que implementar un esquema de cifrado de almacenamiento de datos que siga la especificación definida en el Apéndice [**B**](#appendix-a).

### <a name="test-specification"></a>Especificación de prueba

|Prueba | Controles |
| -----------------------|-------------------------------- |
|**Datos en tránsito**| La transmisión de datos confidenciales DEBE usar un mínimo de TLS 1.1 con algunas excepciones descritas en el Apéndice A.|
||La transmisión de datos **confidenciales DEBE** cifrarse adecuadamente en línea con los perfiles de cifrado descritos en el Apéndice B.|
||La compresión TLS debe deshabilitarse.|
||HSTS (HTTP Strict Transport Security) **DEBE** configurarse para >= 15552000|
|**Datos en rest**| El almacenamiento de datos **confidenciales** DEBE protegerse de acuerdo con los perfiles de cifrado descritos en el Apéndice B que cubren los requisitos mínimos de cifrado, algoritmos, tamaños de clave, hash y autenticación de mensajes.|
||Todos los tipos de datos almacenados DEBEN estar documentados.|
|**Retención y eliminación de datos**|El almacenamiento de **datos confidenciales DEBE** mantenerse al mínimo mediante la implementación de directivas, procedimientos y procesos de eliminación y retención de datos que incluyan mínimamente:|
||&#x2713; documente y limite la cantidad de almacenamiento de datos y el tiempo de retención a los requisitos legales, normativos o empresariales.|
||&#x2713; documente e implemente procesos para la eliminación segura de datos confidenciales cuando ya no sea necesario, en línea con las directivas documentadas.|
||&#x2713; documente e implemente un proceso trimestral para identificar y eliminar de forma segura los datos confidenciales almacenados que superen el período de retención definido.|
|**Administración de acceso a datos**|Limitar el acceso a los datos a las personas con una razón comercial legítima ayuda a las organizaciones a evitar el mal manejo de datos confidenciales a través de la inexperiencia o la malicia. Los datos confidenciales, recibidos por la aplicación/complemento y el acceso a claves de cifrado requieren la aprobación documentada (electrónica o por escrito) para que las partes autorizadas en todos los niveles de acceso accedan y deben incluir una lista de privilegios aprobados y comprobados que demuestren que la directiva incorpora los requisitos especificados de la siguiente manera: |
||&#x2713; Definición de necesidades de acceso y asignaciones de privilegios solo a roles que requieran específicamente dicho acceso con privilegios. |
||&#x2713; restringir el acceso a los privilegios mínimos necesarios para desempeñar responsabilidades laborales.|
||&#x2713; asegúrese de que los acuerdos de uso compartido de datos están en marcha con todos los terceros que consumen datos M365.|
|**RGPD**| Como parte del proceso de certificación de Microsoft 365, debe demostrar el cumplimiento del RGPD, ya sea mediante:|
||&#x2713; Proporcionar una revisión independiente de la conformidad del RGPD por parte de una compañía de auditoría externa con experiencia. Deberá enviar el informe para su revisión o permitir que el analista vea el informe. El informe debe proporcionar suficientes detalles para no solo validar la evaluación del auditor externo, sino también proporcionar suficiente confianza en que la revisión externa ha confirmado la conformidad con el RGPD.|
||o|
||&#x2713; enviar más pruebas para proporcionar garantía adicional de su compromiso con las leyes de privacidad de datos, de la siguiente manera:|
||&#x25fc; un proceso de solicitud de acceso de sujeto (SAR) documentado diseñado para satisfacer las solicitudes de los clientes y cumplir con los requisitos de treinta días del RGPD. Se recomienda que haya herramientas de detección de datos adecuadas para garantizar que se cumpla una RAE en estos períodos de tiempo. **Nota:** Cuando no se usan estas herramientas, deberá demostrar cómo funciona esto y demostrar cómo los procesos pueden garantizar el descubrimiento de toda la información del interesado.|
||&#x25fc;avisos de privacidad deben estar presentes en el sitio web y contener la siguiente información:
||
||Cuando no hay disponible un informe de RGPD independiente, debe haber lo siguiente para que se revise como parte de la evaluación de certificación M365: |
||&#x2713; un proceso de solicitud de acceso de sujeto (SAR) documentado diseñado para satisfacer las solicitudes de los clientes y cumplir con los requisitos de treinta días del RGPD.  Se recomienda que haya herramientas de detección de datos adecuadas para garantizar que se cumpla un SAR en estos períodos de tiempo, donde no se usan estas herramientas, deberá demostrar cómo funciona esto y demostrar cómo los procesos pueden garantizar el descubrimiento de toda la información del interesado.|
||&#x2713; avisos de privacidad deben estar presentes en el sitio web y contener la siguiente información:|
||&emsp;&emsp;&#x25a1; de contacto de organizaciones.|
||&emsp;&emsp;&#x25a1; tipo de datos personales que se están procesando.|
||&emsp;&emsp;&#x25a1; legalización del tratamiento de datos personales (*artículo 6*).|
||&emsp;&emsp;&#x25a1; detalles de los derechos del interesado:|
||&emsp;&emsp;&#x25a1; derecho a ser informado (*Artículos13 y 14*).
||&emsp;&emsp;&#x25a1; derecho de acceso del interesado (*artículo 15*).|
||&emsp;&emsp;&#x25a1; derecho de rectificación (*artículo 16*).|
||&emsp;&emsp;&#x25a1; derecho a la supresión (*artículo 17*).|
||&emsp;&emsp;&#x25a1; derecho a la restricción del procesamiento (*artículo 18*).|
||&emsp;&emsp;&#x25a1; derecho a la portabilidad de datos (*artículo 20*).|
||&emsp;&emsp;&#x25a1; right to object (*Artículo 21*).|
||&emsp;&emsp;&#x25a1; derechos en relación con el marcado automatizado de decisiones, incluida la generación de perfiles (*artículo 22*).|
||&#x2713; uso compartido de información con terceros debe tener acuerdos para garantizar que el procesamiento de los datos del interesado se alinee con las leyes de privacidad de datos.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisión de marcos de cumplimiento externo opcional

Si se han incluido marcos de seguridad externos en la Atestación de publisher, los analistas de certificación tendrán que comprobar la validez de esos marcos de cumplimiento de seguridad como parte de la evaluación de certificación de Microsoft 365.
Entre las pruebas de los siguientes marcos de cumplimiento de seguridad externos admitidos se incluyen:

* [ISMS](#isms) /  [IEC:](#iec) especificación IS0/IEC 27001</h5>
* [PCI DSS](#pci-dss)
* [SOC 2](#soc-2)

La documentación identificada en la [sección Pruebas de](#compliance-evidence) cumplimiento se usará para realizar esta revisión.

### <a name="test-specifications"></a>Especificaciones de prueba

&#x2713; El entorno de soporte técnico  de aplicaciones/complementos  Y los procesos empresariales compatibles DEBEN incluirse en el ámbito de los marcos de cumplimiento de seguridad externos admitidos y deben estar claramente indicados en la documentación proporcionada.

&#x2713; los marcos de cumplimiento de seguridad externa **admitidos** DEBEN estar actuales, es decir, en los últimos 12 meses (o en un plazo de 15 meses si la reevaluación se está llevando a cabo actualmente y se pueden proporcionar pruebas).

&#x2713; los marcos de cumplimiento de seguridad externos admitidos **deben** realizarse por una empresa independiente acreditada.

## <a name="appendix-a"></a>Apéndice A

### <a name="tls-profile-configuration-requirements"></a>Requisitos de configuración de perfil TLS

Todo el tráfico de red, ya sea dentro de una red virtual, un servicio en la nube o un centro de datos, debe protegerse con un mínimo de TLS v1.1 (se recomienda TLS v1.2+) u otro protocolo aplicable. Las excepciones a este requisito son:

* **Redireccionamiento HTTP-to-HTTPS**. La aplicación puede responder a través de HTTP para redirigir clientes a HTTPS, pero la respuesta no debe contener datos confidenciales (cookies, encabezados, contenido). No se permiten otras respuestas HTTP que no sean redirecciones a HTTPS y que respondan a sondeos de mantenimiento. Véalo a continuación.
* **Sondeos de mantenimiento**. La aplicación solo puede responder a sondeos de mantenimiento a través de **HTTP** si la entidad de comprobación no admite sondeos de mantenimiento HTTPS.
* **Acceso a certificados**. El acceso a puntos de conexión CRL, OCSP y AIA para fines de validación de certificados y comprobación de revocación se permite a través de HTTP.
* **Comunicaciones locales**. La aplicación puede usar HTTP (u otros protocolos no protegidos) para comunicaciones que no salen del sistema operativo, por ejemplo. g. conexión a un extremo de servidor web expuesto en localhost.

La compresión **TLS DEBE** estar deshabilitada.

## <a name="appendix-b"></a>Apéndice B

### <a name="encryption-profile-configuration-requirements"></a>Requisitos de configuración de perfiles de cifrado

Solo se permiten los primitivos y parámetros criptográficos de la siguiente manera:

### <a name="symmetric-cryptography"></a>Criptografía simétrica

**Cifrado**

&emsp;&#x2713; Solo se permiten AES, BitLocker, Blowfish o TDES. Cualquiera de las longitudes de clave admitidas >=128 se permiten (128, 192 y 256 bits) y se pueden usar (se recomiendan claves de 256 bits).

&emsp;&#x2713; solo se permite el modo CBC. Cada operación de cifrado debe usar un vector de inicialización (IV) generado aleatoriamente.

&emsp;&#x2713; uso de cifrados de secuencias, como RC4, **NO ESTÁ** permitido.

**Funciones hash**

&emsp;&#x2713; Todo el código nuevo debe usar SHA-256, SHA-384 o SHA-512 (denominado colectivamente SHA-2). La salida puede truncarse a no menos de 128 bits

&emsp;&#x2713; SHA-1 solo se puede usar por motivos de compatibilidad.

&emsp;&#x2713; USO DE MD5, MD4, MD2 y otras funciones hash NO ESTÁ permitido, incluso para aplicaciones no criptográficas.

**Autenticación de mensajes**

&emsp;&#x2713; Todo el código nuevo DEBE usar HMAC con una de las funciones hash aprobadas. La salida de HMAC puede truncarse a no menos de 128 bits.

&emsp;&#x2713; HMAC-SHA1 solo se puede usar por motivos de compatibilidad.

&emsp;&#x2713; clave HMAC DEBE tener al menos 128 bits. Se recomiendan claves de 256 bits.

### <a name="asymmetric-algorithms"></a>Algoritmos asimétricos

**Cifrado**

&emsp;&#x2713; RSA está permitido. La **clave DEBE** tener al menos 2048 bits y se debe usar el relleno de OAEP. El uso del relleno PKCS solo se permite por motivos de compatibilidad.

**Signatures**

&emsp;&#x2713; RSA está permitido. La **clave DEBE** tener al menos 2048 bits y debe usarse el relleno PSS. El uso del relleno PKCS solo se permite por motivos de compatibilidad.

&emsp;&#x2713;ecdsa está permitido. La **clave DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

**Key Exchange**

&emsp;&#x2713; ecdh está permitido. La **clave DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

&emsp;&#x2713; ecdh está permitido. La **clave DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

## <a name="appendix-c"></a>Apéndice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Colección Evidence: Delta para ISO 27001

Cuando ya haya alcanzado el cumplimiento de iso27001, los siguientes deltas (vacíos) no cubiertos totalmente por iso 27001 tendrán que revisarse, como mínimo, como parte de esta certificación de Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles ISO 27001 asignados no se incluyeron como parte de la evaluación ISO 27001 y también puede decidir probar los controles que se encontraron que se incluyeron para proporcionar más garantías. Los requisitos que falte en la ISO 27001 tendrán que incluirse en las actividades de evaluación de certificación de Microsoft 365.

**Protección contra malware: antivirus**

Si la protección contra malware se aplica mediante el control de aplicaciones y se atestigua en el informe ISO 27001, no es necesario realizar ninguna investigación adicional. Si no hay ningún control de aplicaciones, los analistas de certificación tendrán que identificar y evaluar la evidencia de los mecanismos de control de aplicaciones para evitar la detonación de malware en el entorno. Esto requerirá que:

* Demostrar que el software antivirus se está ejecutando en todos los componentes del sistema muestreados.

* Demostrar que el antivirus está configurado en todos los componentes del sistema muestreados para bloquear automáticamente malware, poner en cuarentena & alerta o alertar.

* El software antivirus **DEBE** configurarse para registrar todas las actividades.

**Administración de revisiones: revisión**

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Los componentes de software y los sistemas operativos que ya no son compatibles con el proveedor **no** deben usarse en el entorno. Las directivas de soporte deben estar en funcionamiento para garantizar que los componentes de software no admitidos o los sistemas operativos se quitarán del entorno y un proceso para identificar cuándo deben estar en funcionamiento los componentes de software

**Detección de vulnerabilidades**  

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que se lleva a cabo el examen trimestral de vulnerabilidades internas y externas.

* Confirme que la documentación de soporte técnico está en su lugar para la corrección de vulnerabilidades en función de la clasificación de riesgos y en línea con la especificación siguiente:
 
 &#x2713; solucionar todos los problemas de riesgo crítico y alto en línea con la clasificación de riesgos para el examen interno.
 
 &#x2713; solucionar todos los problemas de riesgo crítico, máximo y medio en línea con la clasificación de riesgos para el análisis externo.
 
 &#x2713; demostrar que la corrección se lleva a cabo en línea con la directiva de corrección de vulnerabilidad documentada.

**Firewall: firewalls (o tecnologías equivalentes)**

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que los firewalls están instalados en el límite del entorno en el ámbito.

* Demostrar que los firewalls están instalados entre la DMZ y las redes de confianza.

*   Demostrar que todo el acceso público finaliza en la DMZ.

*   Demostrar que las credenciales administrativas predeterminadas se cambian antes de la instalación en el entorno en directo.

*   Demostrar que todo el tráfico permitido a través de los firewalls pasa por un proceso de autorización que da como resultado la documentación de todo el tráfico con una justificación empresarial.

*   Demostrar que todos los firewalls están configurados para quitar tráfico no definido explícitamente.

*   Demostrar que los firewalls solo admiten criptografía segura en todas las interfaces administrativas que no son de consola.

*   Demostrar que las interfaces administrativas que no son de consola del firewall expuestas a la MFA de Soporte técnico de Internet.

*   Demostrar que las revisiones de reglas de firewall se realizan al menos cada 6 meses

**Firewall: firewalls de aplicaciones web (WAF)**  

Se proporciona crédito adicional si se implementa un ARCHIVO DESA para ayudar a proteger contra la gran cantidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando esté presente una OSC o similar, esto requerirá lo siguiente:

* Demostrar que ELSC está configurado en modo de defensa activa o supervisar más con alertas.

* Demostrar que el SISTEMABLE está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principales de OWASP (3.0 o 3.1) para protegerse contra la mayoría de los tipos de ataque siguientes:

&#x2713; de protocolo y codificación.

&#x2713; inserción de encabezado, contrabando de solicitudes y división de respuesta.

&#x2713; ataques de recorrido de archivo y ruta de acceso.

&#x2713; de inclusión remota de archivos (RFI).

&#x2713; de ejecución remota de código.

&#x2713; ataques de inyección de PHP.

&#x2713; ataques de scripting entre sitios.

&#x2713; SQL de inyección de datos.

&#x2713; de fijación de sesión.

**Control De cambios**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de solicitud de cambio, esto requerirá que:

* Demostrar que las solicitudes de cambio tienen los siguientes detalles:

&#x2713; impacto documentado.

&#x2713; detalles de qué pruebas de funcionalidad se deben llevar a cabo.

&#x2713; detalles de los procedimientos de back-out.

* Demostrar que las pruebas de funcionalidad se llevan a cabo una vez completados los cambios.

* Demostrar que las solicitudes de cambio están desactivadas después de realizar pruebas de funcionalidad.

**Administración de cuentas**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

*   Demostrar cómo &#x2713;se implementan para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).
*   Muestra cómo se deshabilitan o eliminan las cuentas que no se han usado en 3 meses.
*   &#x2713; u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como una directriz:

&#x2713; longitud mínima de contraseña de 8 caracteres.

&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.
 
&#x2713; historial de contraseñas de un mínimo de cinco contraseñas.
 
&#x2713; aplicación del uso de contraseñas seguras.
 
*   Demostrar que MFA está configurado para todas las soluciones de acceso remoto.

*   Demostrar que el cifrado seguro está configurado en todas las soluciones de acceso remoto.

*   Cuando la administración de DNS público está fuera del entorno del ámbito, todas las cuentas de usuario que puedan realizar modificaciones dns deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL)**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de los Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

*   IDPS **DEBE** implementarse en el perímetro del entorno de soporte técnico.

*   Las firmas IDPS **DEBEN** mantenerse actualizadas en el último día.

*   IDPS **DEBE** configurarse para la inspección TLS.

*   IDPS **DEBE configurarse** para TODO el tráfico entrante y saliente.

*   IDPS **DEBE** configurarse para alertar.

**Registro de eventos**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de registro de eventos de seguridad, esto requerirá que:

* Demostrar que los sistemas públicos inician sesión en una solución de registro centralizada que no está dentro de la DMZ.

* Muestra cómo un mínimo de 30 días de datos de registro están disponibles inmediatamente, con 90 días reteniendo.

**Revisión (datos de registro)**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de esta categoría, esto requerirá que:

*   Muestra cómo se realizan las revisiones diarias de registros y cómo se identifican excepciones y anomalías que muestran cómo se administran.

**Alertas**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de esta categoría, esto requerirá que:

* Muestra cómo se configuran los eventos de seguridad para desencadenar alertas para el triaje inmediato.

* Muestra cómo el personal está disponible las 24 horas del día, los 7 días de la noche, para responder a las alertas de seguridad.

**Administración de riesgos**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que se ha establecido un proceso formal de administración de riesgos.

**Respuesta a incidentes**

Como las auditorías iso 27001 no evalúan específicamente algunos elementos de las directivas y procesos de respuesta a incidentes, esto requerirá que:

*   Demostrar que el plan o procedimiento de respuesta a incidentes incluye:

&#x2713; procedimientos de respuesta específicos para los modelos de amenazas esperados.

&#x2713; capacidades de tratamiento de incidentes alineadas con NIST Cybersecurity Framework (Identificar, proteger, detectar, responder, recuperar).
 
&#x2713; La IRP cubre los sistemas en el ámbito.
 
&#x2713; curso anual para el equipo de respuesta a incidentes.

## <a name="appendix-d"></a>Apéndice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Colección evidence: deltas para PCI DSS

Cuando ya haya alcanzado el cumplimiento de PCI DSS, los siguientes deltas (vacíos) no cubiertos totalmente por PCI DSS tendrán que revisarse, como mínimo, como parte de esta certificación de Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles PCI DSS asignados no se incluyeron como parte de la evaluación de PCI DSS y también puede decidir muestrear los controles que se encontraron que se incluyeron para proporcionar más garantías. Los requisitos que falte en el PCI DSS tendrán que incluirse en las actividades de evaluación de certificación de Microsoft 365.

**Protección contra malware: control de aplicaciones**

Si la protección contra malware se ha puesto en marcha mediante el uso de antivirus y se atestigua en el informe de DSS de PCI, no es necesario realizar ninguna investigación adicional. Si no hay antivirus, los analistas de certificación tendrán que identificar y evaluar evidencias de mecanismos de control de aplicaciones para evitar la detonación de malware en el entorno. Esto requerirá que: 

*   Muestra cómo se lleva a cabo la aprobación de la aplicación y confirma que se ha completado.

*   Demostrar que existe una lista completa de aplicaciones aprobadas con justificación empresarial.

*   Proporcionar o demostrar documentación de soporte técnico está en su lugar detallando cómo se configura el software de control de aplicaciones para cumplir con mecanismos de control de aplicaciones específicos (por ejemplo, listas blancas, firma de código, etc.).

*   Demostrar que en todos los componentes del sistema muestreados, el control de aplicaciones se configura como documentado.

**Administración de revisiones: clasificación de riesgos**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar cómo se lleva a cabo la clasificación de riesgos de vulnerabilidades.

**Detección de vulnerabilidades**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que la corrección se lleva a cabo en línea con la directiva de corrección de vulnerabilidad documentada.

**Firewall: firewalls (o tecnologías equivalentes)**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que los firewalls solo admiten criptografía segura en todas las interfaces administrativas que no son de consola.

* Demostrar que las interfaces administrativas que no son de consola del firewall expuestas a la MFA de Soporte técnico de Internet.

Se proporciona crédito adicional si se implementa un Firewall de aplicaciones web (WAF) para ayudar a proteger contra la gran cantidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando esté presente una OSC o similar, esto requerirá lo siguiente:

* Demostrar que ELSC está configurado en modo de defensa activa o supervisar más con alertas.

* Demostrar que el SISTEMABLE está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principales de OWASP (3.0 o 3.1) para protegerse contra la mayoría de los tipos de ataque siguientes:

&#x2713; de protocolo y codificación.

&#x2713; inserción de encabezado, contrabando de solicitudes y división de respuesta.

&#x2713; ataques de recorrido de archivo y ruta de acceso.

&#x2713; de inclusión remota de archivos (RFI).

&#x2713; de ejecución remota de código.

&#x2713; ataques de inyección de PHP.

&#x2713; ataques de scripting entre sitios.

&#x2713; SQL de inyección de datos.

&#x2713; de fijación de sesión.

**Control De cambios**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de solicitud de cambio, esto requerirá que:

* Demostrar que las solicitudes de cambio se elevan antes de realizarse en entornos de producción.

* Demostrar que los cambios están autorizados antes de entrar en producción.

* Demostrar que las pruebas de funcionalidad se llevan a cabo una vez completados los cambios.

* Demostrar que las solicitudes de cambio están desactivadas después de realizar pruebas de funcionalidad.

**Desarrollo e implementación de software seguro**

Como las auditorías de PCI DSS no tienen acceso específicamente a algunos elementos de los procesos de implementación y desarrollo de software seguro; esto requerirá para usted:

* Los repositorios de código DEBEN estar protegidos por MFA.

*   Deben haber controles de acceso adecuados para proteger los repositorios de código contra modificaciones de código malintencionadas.

**Administración de cuentas**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

* Demostrar cómo se implementan los mecanismos de autorización para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).

* Las directivas de contraseña segura u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como una directriz: 

&#x2713; longitud mínima de contraseña de 8 caracteres.

&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.

&#x2713; historial de contraseñas de un mínimo de cinco contraseñas.

&#x2713; aplicación del uso de contraseñas seguras.

* Demostrar que el cifrado seguro está configurado en todas las soluciones de acceso remoto.

* Cuando la administración de DNS público está fuera del entorno del ámbito, todas las cuentas de usuario que puedan realizar modificaciones dns deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL)**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de los Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

* IDPS DEBE configurarse para la inspección TLS.

*   IDPS DEBE configurarse para TODO el tráfico entrante y saliente.

**Administración de riesgos**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que la evaluación de riesgos incluye matrices de impacto y de probabilidad.

**Respuesta a incidentes**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos y directivas de respuesta a incidentes, esto requerirá que el desarrollador:

* Demostrar capacidades de control de incidentes alineadas con NIST Cybersecurity Framework (Identificar, proteger, detectar, responder, recuperar).

## <a name="appendix-e"></a>Apéndice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Colección evidence: deltas para SOC 2

Cuando ya haya alcanzado el cumplimiento de SOC 2, los siguientes deltas (vacíos) no cubiertos totalmente por SOC 2 tendrán que revisarse como parte de esta certificación de Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles SOC 2 asignados no se incluyeron como parte de la evaluación de SOC 2 y también puede decidir probar los controles que se encontraron que se incluyeron para proporcionar más garantías. Los requisitos que falte en la evaluación de SOC 2 tendrán que incluirse como parte de las actividades de evaluación de certificación de Microsoft 365.

**Protección contra malware: control de aplicaciones**

Si la protección contra malware se ha puesto en marcha mediante el uso de antivirus y se atestigua en el informe de SOC 2, no es necesario realizar ninguna investigación adicional. Si no hay antivirus, los analistas de certificación tendrán que identificar y evaluar evidencias de mecanismos de control de aplicaciones para evitar la detonación de malware en el entorno. Esto requerirá que:

* Proporcionar o demostrar documentación de soporte técnico está en su lugar detallando cómo se configura el software de control de aplicaciones para cumplir con mecanismos de control de aplicaciones específicos (por ejemplo, listas blancas, firma de código, etc.).

* Muestra cómo se lleva a cabo la aprobación de la aplicación y confirma que se ha completado.

*   Demostrar que existe una lista completa de aplicaciones aprobadas con justificación empresarial.

*   Demostrar que en todos los componentes del sistema muestreados, el control de aplicaciones se configura como documentado.

**Administración de revisiones: revisión**

Como las auditorías de SOC 2 no evalúan específicamente esta categoría, esto requerirá que:

*   Cualquier problema bajo, medio, alto o crítico debe estar parcheado dentro de las ventanas de actividad de revisión normal.

*   Los componentes de software y los sistemas operativos que ya no son compatibles con el proveedor no deben usarse en el entorno. Las directivas de soporte deben estar en su lugar para garantizar que los componentes de software no admitidos o los sistemas operativos se quitarán del entorno y debe haber un proceso para identificar cuándo los componentes de software terminan su vida útil.

**Firewall: firewalls**

Como las auditorías de SOC 2 no evalúan específicamente los controles de cambio en las listas de control de acceso de firewall, esto requerirá que:

* Demostrar que todo el tráfico permitido a través de los firewalls pasa por un proceso de autorización que da como resultado la documentación de todo el tráfico con una justificación empresarial.

* Demostrar que las revisiones de reglas de firewall se realizan al menos cada seis meses.

Se proporciona crédito adicional si se implementa un Firewall de aplicaciones web (WAF) o similar para ayudar a proteger contra la gran cantidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando esté presente una OSC o similar, esto requerirá lo siguiente:

* Demostrar que ELSC está configurado en modo de defensa activa o supervisar más con alertas.

* Demostrar que el SISTEMABLE está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principales de OWASP ((3.0 o 3.1) para protegerse contra la mayoría de los tipos de ataque siguientes:

&emsp;&#x2713; de protocolo y codificación.

&emsp;&#x2713; inserción de encabezado, contrabando de solicitudes y división de respuesta.

&emsp;&#x2713; ataques de recorrido de archivos y rutas de acceso.

&emsp;&#x2713; de inclusión remota de archivos (RFI).

&emsp;&#x2713; de ejecución remota de código.

&emsp;&#x2713; ataques de inyección de PHP.

&emsp;&#x2713; ataques de scripting entre sitios.

&emsp;&#x2713; SQL de inyección.

&emsp;&#x2713; de fijación de sesión.

**Control De cambios**

Como las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de solicitud de cambio, esto requerirá que el desarrollador:

* Demostrar cómo los entornos de desarrollo y prueba son independientes del entorno de producción que obliga a la separación de tareas.

* Muestra cómo no se usan los datos en directo en los entornos de desarrollo y prueba.

* Demostrar que las pruebas de funcionalidad se llevan a cabo una vez completados los cambios.

* Demostrar que las solicitudes de cambio están desactivadas después de realizar pruebas de funcionalidad.

**Desarrollo e implementación de software seguro**

Como las auditorías de SOC 2 no tienen acceso específicamente a algunos elementos de los procesos de implementación y desarrollo de software seguro; esto requerirá para usted:

*   Debe tener un proceso de desarrollo de software establecido y documentado que cubra todo el ciclo de vida de desarrollo de software.

*   Los desarrolladores DEBEN recibir un aprendizaje seguro de codificación de software al menos anualmente.

*   Los repositorios de código DEBEN estar protegidos por MFA.

*   Deben haber controles de acceso adecuados para proteger los repositorios de código contra modificaciones de código malintencionadas.

**Administración de cuentas**

Como las auditorías de SOC2 no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

*   Demostrar cómo se implementan los mecanismos de autorización para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).

*   Muestra cómo se deshabilitan o eliminan las cuentas que no se han usado en 3 meses.

*   Las directivas de contraseña segura u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como una directriz:

&emsp;&#x2713; longitud mínima de contraseña de 8 caracteres.

&emsp;&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.

&emsp;&#x2713; historial de contraseñas de un mínimo de 5 contraseñas.

&emsp;&#x2713; cumplimiento del uso de contraseñas seguras

*   Demostrar que las cuentas de usuario únicas se emiten a todos los usuarios.

*   Cuando la administración de DNS público está fuera del entorno del ámbito, todas las cuentas de usuario que puedan realizar modificaciones dns deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL).**

Como las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de los Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

*   Las firmas IDPS DEBEN mantenerse actualizadas en el último día

*   IDPS DEBE configurarse para la inspección tls

*   IDPS DEBE configurarse para TODO el tráfico entrante y saliente

**Registro de eventos**

Como las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de registro de eventos de seguridad, esto requerirá que:

* Demostrar cómo, en todos los componentes del sistema del conjunto de ejemplo, el siguiente sistema está configurado para registrar los siguientes eventos

&emsp;&#x2713; Acceso del usuario a los componentes del sistema y las aplicaciones.

&emsp;&#x2713; Todas las acciones realizadas por un usuario con privilegios altos.

&emsp;&#x2713; intentos de acceso lógico no válidos.

Demostrar que los eventos registrados contienen; como mínimo, la siguiente información:

&emsp;&#x2713; usuario.

&emsp;&#x2713; tipo de evento.

&emsp;&#x2713; fecha y hora.

&emsp;&#x2713; correcto/error.

&emsp;&#x2713; etiqueta para identificar el sistema afectado.

*   Demostrar que todos los componentes del sistema del conjunto de ejemplo están configurados para usar la sincronización de tiempo y que son los mismos que los servidores de hora principal/secundario.

* Demostrar que los sistemas públicos inician sesión en una solución de registro centralizada que no está dentro de la DMZ.

*   Demostrar que los sistemas públicos inician sesión en una solución de registro centralizada que no está dentro de la DMZ.

* Demostrar cómo la solución de registro centralizado está protegida contra la manipulación no autorizada de los datos de registro.

* Muestra cómo un mínimo de 30 días de datos de registro están disponibles inmediatamente, con 90 días o más reteniendo.

**Administración de riesgos**

Como las auditorías de SOC2 no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que se realiza una evaluación formal de riesgos al menos anualmente.

*Respuesta a incidentes.*

Como las auditorías de SOC2 no evalúan específicamente algunos elementos de los procesos y directivas de respuesta a incidentes, esto requerirá que:

* Demostrar que el plan o procedimiento de respuesta a incidentes incluye:

&emsp;&#x2713; procedimientos de respuesta específicos para los modelos de amenazas esperados.

&emsp;&#x2713; de comunicaciones documentadas para garantizar la notificación a tiempo de las partes interesadas clave (marcas de pago/adquirentes, organismos reguladores, autoridades de supervisión, directores, clientes, etc.).

## <a name="appendix-f"></a>Apéndice F

### <a name="hosting-deployment-types"></a>Tipos de implementación de hospedaje

Microsoft reconoce que implementará aplicaciones y almacenará código de aplicación o complemento en diferentes entornos de hospedaje. Las responsabilidades generales de algunos de los controles de seguridad dentro de la certificación de Microsoft 365 dependerán del entorno de hospedaje que se esté utilizando. El Apéndice F examina los tipos de implementación comunes y los asigna a los controles de seguridad que se evalúan como parte del proceso de evaluación. Se han identificado los siguientes tipos de implementación de hospedaje:

|  |  |
|-----|------|
|**ISV hospedado**|Los tipos hospedados por ISV se pueden definir como donde eres responsable de la infraestructura usada para admitir el entorno de aplicación o complemento. Esto puede estar físicamente ubicado dentro de sus propios centros de datos o centros de datos de terceros con un servicio de ubicación local. En última instancia, tiene plena propiedad y control administrativo sobre la infraestructura auxiliar y el entorno operativo.|
|**Infraestructura como servicio (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infraestructura como servicio es un servicio que se proporciona mediante el cual el proveedor de servicios en la nube (CSP) administra y mantiene la infraestructura de soporte físico en su nombre. Normalmente, las redes, el almacenamiento, los servidores físicos y la infraestructura de virtualización son responsabilidad del CSP. El sistema operativo, middleware, tiempo de ejecución, datos y aplicaciones son las responsabilidades de usted. Las capacidades de firewall también serían administradas y mantenidas por el tercero, pero el mantenimiento de la base de reglas de firewall normalmente seguiría siendo responsabilidad de los consumidores.|
|**Plataforma como servicio/sin servidor (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Con Plataforma como servicio, se le aprovisiona con una plataforma administrada que presenta un servicio que se puede consumir. No es necesario realizar funciones sysadmin, ya que el CSP administra el sistema operativo y la infraestructura de soporte técnico. Esto suele usarse cuando las organizaciones no quieren preocuparse por presentar un servicio web y, en su lugar, pueden concentrarse en crear el código fuente de la aplicación web y publicar la aplicación web en los servicios web administrados en la nube.  Otro ejemplo puede ser un servicio de base de datos en el que se proporciona conectividad a una base de datos, pero la infraestructura y la aplicación de base de datos compatibles se abstrae del consumidor.   **Nota: Serverless y PaaS son similares, por lo que para el propósito del Tipo de implementación de hospedaje de certificación de Microsoft 365 sin servidor y PasS se consideran iguales**|
|**Hosted híbrido**|Con el tipo hospedado híbrido, puede usar varios tipos hospedados para admitir varias partes del entorno de soporte. Esto puede ser más el caso en el que las aplicaciones/complementos se usan en varias pilas M365. Aunque la certificación de Microsoft 365 admitirá dónde se desarrollan aplicaciones o complementos en varios servicios M365, es necesario evaluar todo el entorno de soporte técnico (entre aplicaciones y complementos) de acuerdo con cada una de las "asignaciones de tipos hospedados" aplicables. En ocasiones, puede usar distintos tipos hospedados para un solo complemento, donde esto se está llevando a cabo, la aplicabilidad de criterios tendrá que seguir los criterios de "Asignaciones de tipos hospedados" en los distintos tipos hospedados.|
|**Hospedaje compartido**|El hospedaje compartido es donde hospeda el entorno dentro de una plataforma que comparten varios consumidores individuales. La especificación de certificación de Microsoft 365 no se escribió para tener en cuenta esto debido a la adopción de la nube, el hospedaje compartido no es común. Si cree que se está utilizando, póngase en contacto con Microsoft, ya que es necesario crear requisitos adicionales para tener en cuenta los riesgos adicionales en este tipo de hospedaje.|


## <a name="appendix-g"></a>Apéndice G

### <a name="microsoft-365-certification-process-workflow"></a>Flujo de trabajo del proceso de certificación de Microsoft 365

![Flujo de trabajo](ProcessFlow.jpg)

## <a name="learn-more"></a>Más información

[Introducción al programa de cumplimiento de aplicaciones de Microsoft 365](~/overview.md)  
[¿Qué es Microsoft 365 App Publisher Attestation?](~/docs/attestation.md)  
[¿Qué es la certificación de Microsoft 365?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glosario

### <a name="aia"></a>AIA

*Authority Information Access es un descriptor de ubicación de servicio que se usa para buscar el certificado de la entidad de certificación emisora.

### <a name="crl"></a>CRL

*La lista de revocación de certificados proporciona un medio para que un extremo de capa de sockets seguros (SSL) compruebe que un certificado recibido de un host remoto es válido y confiable.

### <a name="cvss-score"></a>Puntuación CVSS

*Common Vulnerability Scoring System es un estándar publicado que mide la vulnerabilidad y calcula una puntuación numérica en función de su gravedad.

### <a name="cvss-patch-management-guidelines"></a>Directrices de administración de revisiones de CVSS

* Crítico (9.0 - 10.0)
* Alto (7,0 - 8,9)
* Mediano (4.0 - 6.9)
* Bajo (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zona desmilitarizada es una red intermedia física o lógica que interactúa directamente con redes externas o que no son proppropias mientras se mantiene separada y aislada la red privada interna del host.

### <a name="euii"></a>EUII

*Información de identificación del usuario final*.

### <a name="gdpr"></a>RGPD

*El Reglamento general de protección de datos es un reglamento de privacidad y protección de datos de la Unión Europea (UE) para todos los datos de los ciudadanos de la UE, independientemente de dónde se encuentra su sitio de aplicación.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security usa un encabezado de respuesta HTTP que indica al explorador web que solo tenga acceso al contenido a través de HTTPS.  Esto está diseñado para proteger contra ataques de degradación y el secuestro de cookies.

### <a name="iec"></a>IEC

*Comisión Electrotécnica Internacional.

### <a name="isms"></a>ISMS

*Sistema de administración de seguridad de la información.

### <a name="isv"></a>ISV

Los proveedores de seguridad independientes son personas y organizaciones que desarrollan, comercializan y venden software que se ejecuta en plataformas de software y hardware de terceros.

### <a name="iso-27001"></a>ISO 27001

Marco de especificación del sistema de administración de seguridad de la información para todos los controles técnicos en procesos de procedimientos y directivas de administración de riesgos de una organización.

### <a name="lfi"></a>LFI

*La inclusión de* archivos local permite que un atacante incluya archivos en un servidor a través del explorador web.

### <a name="nist"></a>NIST

El  Instituto Nacional de Estándares (NIST), una agencia no reglamentaria del Departamento de Comercio de Estados Unidos, proporciona instrucciones para que las organizaciones del sector privado en los Estados Unidos evalúen y aprueben su capacidad para prevenir, detectar y responder a los ataques cibernéticos.

### <a name="non-significant-changes"></a>Cambios no significativos

* Correcciones de errores menores.
* Mejoras de rendimiento secundarias.
* Sistemas operativos/bibliotecas/revisiones de aplicaciones cliente y servidor.

### <a name="ocsp"></a>OCSP

*El protocolo de estado de certificado* en línea se usa para comprobar el estado de revocación de los certificados digitales X.509.

### <a name="oii"></a>OII

*Información identificable de la organización*.

### <a name="owasp"></a>OWASP

*Open Web Application Security Project*.

### <a name="pci-dss"></a>PCI DSS

*Payment Card Industry Data Security Standard*, una organización que mantiene estándares para la seguridad de los datos de los titulares de tarjetas en todo el mundo.

### <a name="pen-testing"></a>Pruebas de lápiz

*Las pruebas* de penetración son un método para probar una aplicación web simulando ataques malintencionados para encontrar vulnerabilidades de seguridad que un atacante podría aprovechar.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* es un estándar abierto para intercambiar datos de autenticación y autorización entre el usuario, el proveedor de identidades y el proveedor de servicios.

### <a name="sensitive-data"></a>Datos confidenciales

* Datos de control de acceso.
* Contenido del cliente.
* Información de identidad del usuario final.
* Datos de soporte técnico.
* Datos personales públicos.
* Información seudónima del usuario final.

### <a name="significant-changes"></a>Cambios significativos

* Reubicación del entorno de hospedaje.
* Actualizaciones principales a la infraestructura de soporte técnico; por ejemplo, la implementación de un nuevo firewall, actualizaciones principales a los servicios front-facing, etc.
* Adición de funcionalidades y /o extensiones a la aplicación.
* Actualizaciones de la aplicación que capturan datos confidenciales adicionales.
* Cambios en los modelos de autorización o flujos de datos de la aplicación
* Adición de extremos de API o funciones de extremo de API.

### <a name="soc-2"></a>SOC 2

*Control de organización* de servicios 2 , un procedimiento de auditoría técnica compuesto por cinco principios de servicio de confianza para garantizar que los proveedores de servicios administren de forma segura los datos y la privacidad de los clientes de una organización.

### <a name="ssl"></a>SSL

*Capa de sockets seguros*.

### <a name="tls"></a>TLS

*Seguridad de la capa de transporte*.
