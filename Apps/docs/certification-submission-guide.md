---
ms.author: oromalle
title: Guía de envío de certificación de Microsoft 365
author: orionomalley
manager: tonybal
description: Microsoft 365 detalles de la guía de envío de certificación
keywords: equipos de certificación de aplicaciones Microsoft 365 cumplimiento de seguridad m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 5081e187615400b038795215ad0d5dcc934e1a87
ms.sourcegitcommit: ffdee67a99a6f03cc93fe4d99f00e484b9a8a0e5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/10/2022
ms.locfileid: "64751829"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guía de envío de certificación de Microsoft 365

**En este artículo:**
- [Introducción](#introduction)
- [Requisitos previos](#prerequisites) 
- [actualizaciones de la especificación de certificación de Microsoft 365](#microsoft-365-certification-specification-updates)
- [Ámbito de certificación](#certification-scope)
- [Proceso de certificación](#certification-process)
- [Envío inicial de documentos](#initial-document-submission) 
- [Actividades de recopilación y evaluación de evidencias](#evidence-collection-and-assessment-activities)
- [Criterios de certificación](#app-certification-criteria)
- [Application Security](#application-security)
- [Seguridad operativa](#operational-security) 
- [Control de datos Seguridad y privacidad](#data-handling-security-and-privacy)
- [Revisión opcional de marcos de cumplimiento externo](#optional-external-compliance-frameworks-review)
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

Como parte del programa Microsoft 365 App Compliance, la certificación de Microsoft 365 ofrece garantía y confianza a las organizaciones empresariales de que los datos y la privacidad están protegidos y protegidos adecuadamente al integrar aplicaciones o complementos para desarrolladores de terceros en la plataforma de Microsoft 365. Las aplicaciones y los complementos que pasan la validación se designarán **Microsoft 365 Certificado** en todo el ecosistema de Microsoft 365. 

Al participar en el programa de certificación Microsoft 365, acepta estos términos complementarios y cumple con cualquier documentación complementaria que se aplique a su participación en el programa de certificación de Microsoft 365 con Microsoft Corporation ("Microsoft", "nosotros", "nosotros" o "nuestro"). Usted nos declara y garantiza que tiene la autoridad para aceptar estos términos complementarios de certificación Microsoft 365 en nombre de usted mismo, una empresa y/u otra entidad, según corresponda. Podemos cambiar, modificar o cancelar estos términos complementarios en cualquier momento. Su participación continua en el programa de certificación de Microsoft 365 después de cualquier cambio o modificación significa que acepta los nuevos términos complementarios. Si no acepta los nuevos términos complementarios o si terminamos estos términos complementarios, debe dejar de participar en el programa de certificación de Microsoft 365.

Este documento está dirigido a isv (proveedores de software independientes) para proporcionar información sobre el proceso de certificación de Microsoft 365, requisitos previos para iniciar el proceso y detalles de controles de seguridad específicos que los ISV deben tener en vigor.  Puede encontrar información general del programa de cumplimiento de aplicaciones Microsoft 365 en la [página](../overview.md) Microsoft 365 programa de cumplimiento de aplicaciones. 

> [!IMPORTANT]
> Actualmente, Microsoft 365 Certificación es aplicable a todos:
>* Microsoft Teams aplicaciones (pestañas, bots, etc.).
>* Aplicaciones o complementos de Sharepoint
>* complementos de Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Requisitos previos

### <a name="publisher-attestation"></a>Atestación del editor

Antes de obtener el Microsoft 365 proceso de certificación, debe haber completado Publisher atestación. Sin embargo, puede iniciar el proceso de certificación de Microsoft 365 antes de completar Publisher atestación.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lea la especificación de certificación de Microsoft 365

Microsoft recomienda que todos los ISV (proveedor de software independiente) lean esta Microsoft 365 Especificación de certificación en su totalidad para asegurarse de que el entorno dentro del ámbito y la aplicación o el complemento cumplen todos los controles aplicables. Esto ayudará a garantizar un proceso de evaluación sin problemas.

## <a name="microsoft-365-certification-specification-updates"></a>actualizaciones de la especificación de certificación de Microsoft 365 

Las actualizaciones de la especificación de certificación Microsoft 365 se prevén aproximadamente cada seis o doce meses. Estas actualizaciones pueden introducir nuevos dominios de seguridad de destino o controles de seguridad. Las actualizaciones se basarán en los comentarios de los desarrolladores, los cambios en el panorama de amenazas y para aumentar la línea base de seguridad del programa a medida que madure. 

Los ISV que ya han iniciado la evaluación de certificación de Microsoft 365 pueden continuar la evaluación con la versión de la especificación de certificación de Microsoft 365 que era válida cuando se inició la evaluación. Todos los nuevos envíos, incluida la recertificación anual, deberán evaluarse con respecto a la versión publicada.

> [!NOTE]
> No es necesario cumplir con todos los controles de esta Microsoft 365 Especificación de certificación para obtener una certificación. Sin embargo, se han establecido umbrales de paso (que no se divulgarán) para cada uno de los dominios de seguridad descritos en esta Microsoft 365 Especificación de certificación. Algunos controles se clasifiquen como "**Error difícil**", lo que significa que la falta de estos controles de seguridad dará lugar a una evaluación errónea. 

## <a name="certification-scope"></a>Ámbito de certificación

El **entorno en el ámbito** es el entorno que admite la entrega del código de aplicación o complemento y admite cualquier sistema back-end con el que la aplicación o el complemento puedan comunicarse. Los entornos conectados adicionales también se incluirán en el ámbito a menos que haya una segmentación adecuada y los entornos conectados no puedan afectar a la seguridad del entorno dentro del ámbito. Los entornos de recuperación ante desastres también tendrán que incluirse en el ámbito de la evaluación, ya que estos entornos serían necesarios para cumplir el servicio en caso de que suceda algo en el entorno principal.  Los componentes   **del sistema de ámbito de** **términoreferencian todos los** dispositivos y sistemas que se usan en el entorno dentro del ámbito. Entre los componentes dentro del ámbito se incluyen, entre otros:
* Las aplicaciones web.
* Servidores.
* Firewalls (o equivalentes).
* Interruptores.
* Equilibradores de carga.
* Infraestructura virtual.
* Portales de administración web del proveedor de nube 

> [!IMPORTANT]
> El entorno en el ámbito debe tener una red perimetral y el entorno de soporte de la aplicación o complemento debe segmentarse desde los sistemas empresariales internos y los entornos corporativos, limitando así el ámbito de las actividades de evaluación solo a los sistemas dentro del ámbito. Los analistas de certificación validarán las técnicas de segmentación durante la evaluación, junto con la revisión de los informes de pruebas de penetración que deberían haber incluido pruebas para validar la eficacia de las técnicas de segmentación en uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infraestructura como servicio (IaaS), Plataforma como servicio (PaaS) y Software como servicio (SaaS) 
Cuando IaaS o PaaS se usan para admitir la infraestructura de la aplicación o la entrega de código de complemento que se está revisando, el proveedor de la plataforma en la nube será responsable de algunos de los controles de seguridad evaluados a lo largo del proceso de certificación. Por lo tanto, el proveedor de la plataforma en la nube deberá proporcionar a los analistas de certificación una verificación externa independiente de los procedimientos recomendados de seguridad a través de informes de cumplimiento externos, como pci DSS atestación de cumplimiento (AOC), ISO27001 o informes soc 2 de tipo II. 


El apéndice F proporciona detalles sobre qué controles de seguridad probablemente serán aplicables en función de los siguientes tipos de implementación y en función de si la aplicación o el complemento filtran o no los datos de M365: 
* ISV hospedado 
* IaaS Hosted 
* Hospedado sin servidor o PaaS 
* Hospedado híbrido 
* Hospedado compartido 

Cuando se implemente IaaS o PaaS, deberá proporcionar pruebas del entorno que se hospeda dentro de estos tipos de implementación.

### <a name="sampling"></a>Muestreo

Las solicitudes de pruebas en apoyo de la evaluación de certificación deben basarse en una muestra de los componentes del sistema en el ámbito en consideración de los diferentes sistemas operativos, la función principal del dispositivo y los distintos tipos de dispositivo. Se seleccionará un ejemplo adecuado al principio del proceso de certificación. La tabla siguiente debe usarse como guía sobre cuál puede ser el tamaño de la muestra:

|Tamaño de población              | Muestra                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4|

> [!NOTE]
>Si se identifican discrepancias entre los dispositivos incluidos en el ejemplo inicial, el tamaño de la muestra puede aumentarse durante la evaluación. 

## <a name="certification-process"></a>Proceso de certificación

Antes de iniciar el proceso de certificación, tendrá que haber completado correctamente la atestación de Publisher. Una vez completado, el proceso de certificación de Microsoft 365 continuará de la siguiente manera:

### <a name="preparation"></a>Preparación
1. Vaya al centro de partners y revise la documentación de [atestación Publisher](../docs/attestation.md) completada. Si es necesario, puede editar y actualizar las respuestas; sin embargo, si lo hace, tendrá que volver a enviar la documentación de atestación para su aprobación. Si el envío tiene más de tres meses, es necesario que vuelva a enviar Publisher atestación para su revisión y validación. 
1. Lea detenidamente la [Guía de envío de certificación de Microsoft 365](../docs/certification-submission-guide.md) para comprender lo que se le pedirá. Asegúrese de que podrá cumplir los [requisitos de control](../docs/certification-submission-guide.md#app-certification-criteria) especificados en Microsoft 365 Guía de envío de certificación.
1. En el centro de partners, haga clic en "Iniciar certificación". Esto le llevará al portal de envío de documentos inicial. Envíe su [envío de documento inicial](../docs/certification-submission-guide.md#initial-document-submission). Esto nos ayudará a determinar qué está en el ámbito de la evaluación en función de cómo se diseña la aplicación y controla los datos de los clientes. Compruebe esta página con frecuencia para ver si se ha aceptado el envío.

>[!NOTE]
>Para todas las aplicaciones de Office, puede hacer referencia a nuestra [guía de usuario de aplicaciones de Office](../docs/userguide.md). Para todas las aplicaciones web, puede hacer referencia a nuestra [Guía del usuario de la aplicación SaaS](../docs/saasuserguide.md).

### <a name="assessment"></a>Evaluación
1. Una vez que se haya aceptado el envío de documentos inicial, el conjunto de controles de seguridad necesarios para la aplicación se mostrará automáticamente en el portal. A continuación, se le pedirá que envíe pruebas para cada control que demuestre que el control está en su lugar. Tenga en cuenta que se le dará **60 días** para enviar todas las pruebas. Un analista revisará las pruebas y aprobará el control o solicitará pruebas nuevas o adicionales. Consulte esta página con frecuencia para ver si se han aceptado las pruebas.
### <a name="certification"></a>Certificación
1. Una vez que el envío ha sido validado por un analista, se le notificará de la decisión de certificación. Las aplicaciones que reciban una certificación recibirán un distintivo en su aplicación dentro **de AppSource** y en **las páginas de documentos de Microsoft** . Puede leer las ventajas completas de la certificación [aquí](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Revisar y volver a certificar
En caso de que la aplicación se someta a [cambios significativos](../docs/certification-submission-guide.md#significant-changes) en cualquier momento, deberá notificarnos.

También se le pedirá que pase por la recertificación anualmente. Esto requerirá la revalidación de los controles en el ámbito en el entorno actual. Este proceso puede comenzar hasta 90 días antes de la expiración de la certificación. La certificación existente no expirará durante el período de recertificado. La recertición en todos los programas expira en el aniversario de un año de la certificación de Microsoft 365.

Si la certificación no se renueva antes de la fecha de expiración, se revocará el estado de certificación de las aplicaciones. Todas las etiquetas, iconos y marcas de certificación asociadas se quitarán de la aplicación y se le prohibirá anunciar la aplicación como Microsoft 365 certificado.


> [!IMPORTANT]
> **Período de tiempo de envío:** Se prevé que, en promedio, el proceso de evaluación debe tardar 30 días, siempre que pueda comprobar el estado de envío con frecuencia y responder a comentarios y solicitudes de pruebas complementarias de manera oportuna. Al iniciar el proceso de certificación, se permite un máximo de 60 días para completar la evaluación. Si todos los envíos no se han completado dentro del período de tiempo de 60 días, el envío se emitirá un error y el proceso debe iniciarse de nuevo. Estos resultados no se harán públicos.


## <a name="initial-document-submission"></a>Envío inicial de documentos


El envío inicial del documento ayudará a los analistas de certificación a realizar el ámbito y determinar lo que estará en el ámbito de la evaluación. Después de lo cual se le pedirá que envíe documentación complementaria y pruebas utilizadas para llevar a cabo la evaluación. El envío inicial debe incluir la información especificada a continuación. Para obtener más información, consulte la [Guía de submisión de documentos initital](../docs/initialdocumentsubguide.md).

| **DocumentationOverview&nbsp;**     |   **Detalles de la documentación**  |
| -------------------------| -----------------------------|
|**Descripción de aplicación o complemento** | Descripción del propósito y la funcionalidad de la aplicación o complemento. Esto debe proporcionar al analista de certificación una buena comprensión de cómo funciona la aplicación o el complemento y cuál es su uso previsto
|**Informe de pruebas de penetración** |Un informe de pruebas de penetración completado en los últimos 12 meses. Este informe debe incluir el entorno que admite la implementación de la aplicación o agregar junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o el complemento. **Nota:** Si no realiza pruebas de penetración anuales, puede optar por que se realicen a través del proceso de certificación.|
|**Diagramas de arquitectura**|Diagrama de arquitectura lógica que representa una introducción de alto nivel de la infraestructura auxiliar de la aplicación o del complemento. Esto debe incluir **todos los** entornos de hospedaje y la infraestructura compatible con la aplicación o el complemento. Este diagrama DEBE representar todos los distintos componentes del sistema auxiliares dentro del entorno para ayudar a los analistas de certificación a comprender los sistemas en el ámbito y ayudar a determinar el muestreo. Indique también qué tipo de entorno de hospedaje se usa; Hospedado por ISV, IaaS, PaaS o híbrido. **Nota:** Cuando se use SaaS, indique los diversos servicios SaaS que se usan para proporcionar los servicios auxiliares dentro del entorno.|
|**Huella pública** | Detalles de **todas las** direcciones IP públicas y direcciones URL usadas por la infraestructura auxiliar. Esto debe incluir el intervalo IP enrutable completo asignado al entorno a menos que se haya implementado una segmentación adecuada para dividir el intervalo en uso (se necesitarán pruebas adecuadas de segmentación)|
|**Diagramas de flujo de datos** |Flow diagramas que detallan lo siguiente:
||&#x2713; flujos de datos M365 hacia y desde la aplicación o complemento ( [incluidos EUII](#euii) y [OII](#oii) ).|
||&#x2713; flujos de datos M365 dentro de la infraestructura auxiliar (si procede)|
||&#x2713; Diagramas que resaltan dónde y qué datos se almacenan, cómo se pasan datos a terceros externos (incluidos los detalles de qué terceros) y cómo se protegen los datos en tránsito a través de redes abiertas o públicas y en reposo.|
|**Detalles del punto de conexión de API**| Una lista completa de todos los puntos de conexión de API usados por la aplicación. Para ayudar a comprender el ámbito del entorno, proporcione ubicaciones de punto de conexión de API dentro del entorno.                                
|**Permisos de API de Microsoft**| Proporcione documentación en la que se detallan **TODAS** las API de Microsoft que se usan junto con los permisos que se solicitan para que la aplicación o el complemento funcionen junto con una justificación para los permisos solicitados.|
|**Tipos de almacenamiento de datos** |Almacenamiento y control de datos de documentos que describen lo siguiente:|
||&#x2713; ¿En qué medida se reciben y almacenan los datos de los clientes M365 [EUII](#euii) y [OII](#oii) ?|
||&#x2713; El período de retención de datos.|
||&#x2713; Por qué se capturan los datos M365 del cliente.|
||&#x2713; Dónde se almacenan los datos M365 del cliente (deben incluirse en los diagramas de flujo de datos proporcionados anteriormente).|
|**Confirmación de cumplimiento**|Documentación de soporte técnico para marcos de seguridad externos incluidos en el envío de atestación de Publisher o que se debe tener en cuenta al revisar Microsoft 365 controles de certificación. Actualmente, se admiten los tres siguientes:|
||&#x2713; certificación de cumplimiento de [PCI DSS](#pci-dss) (AOC).|
||&#x2713; informes [SOC 2](#soc-2) de tipo I/Tipo II.|
||&#x2713; [ISMSIEC](#isms) / - Declaración de aplicabilidad (SoA) y certificación 1S0/IEC 27001.[](#iec)|
|**Dependencias web**|Documentación que enumera todas las dependencias usadas por la aplicación o el complemento con las versiones en ejecución actuales.|
|**Inventario de software**|Un inventario de software actualizado que incluye todo el software usado en el entorno dentro del ámbito junto con las versiones.|
|**Inventario de hardware**| Un inventario de hardware actualizado que usa la infraestructura auxiliar. Esto se usará para ayudar con el muestreo al realizar la fase de evaluación. Si el entorno incluye PaaS, proporcione detalles de los servicios consumidos.|

## <a name="evidence-collection-and-assessment-activities"></a>Actividades de recopilación y evaluación de evidencias

Los analistas de certificación tendrán que revisar las pruebas en todos los componentes del sistema dentro del conjunto de ejemplo definido. Entre los tipos de pruebas necesarias para respaldar el proceso de evaluación se incluyen las siguientes:

**Colección de evidencias**

* Documentación inicial, resaltada en la sección [Envío de documentación inicial](#initial-document-submission) anterior 
* Documentos de directiva 
* Procesar documentos 
* Configuración del sistema 
* Cambiar vales 
* Cambiar registros de control 
* Informes del sistema

Se usarán varios métodos para recopilar las pruebas necesarias para completar el proceso de evaluación.  Esta colección de evidencias puede tener la forma de: 
* Documentos 
* Capturas de pantalla 
* Entrevistas 
* Screensharing 

Las técnicas de recopilación de pruebas utilizadas se determinarán durante el proceso de evaluación. Para obtener ejemplos concretos del tipo de evidencia requerida en su envío, consulte la [Guía de evidencia de ejemplo](../docs/certification-sample-evidence-guide.md).

**Actividades de evaluación**

Los analistas de certificación revisarán las pruebas que proporcione para determinar si ha cumplido adecuadamente los controles de esta especificación de certificación de Microsoft 365. 

Siempre que sea posible y para reducir el tiempo necesario para completar la evaluación, cualquier o toda la documentación detallada en los  [envíos](#initial-document-submission)  de documentación inicial debe proporcionarse con antelación.

Los analistas de certificación revisarán primero las pruebas proporcionadas a partir del envío de documentación inicial y la Publisher información de atestación para identificar las líneas de investigación adecuadas, el tamaño del muestreo y la necesidad de obtener más pruebas, tal como se ha detallado anteriormente.  Los analistas de certificación analizarán toda la información recopilada para extraer conclusiones sobre cómo y si cumple los controles de esta Microsoft 365 Especificación de certificación. 

## <a name="app-certification-criteria"></a>Criterios de certificación de aplicaciones

La aplicación, la infraestructura auxiliar y la documentación auxiliar se evaluarán en los siguientes dominios de seguridad:

1. [**Application Security**](#application-security)
1. [**Seguridad operativa/Implementación segura**](#operational-security)
1. [**Control de datos Seguridad y privacidad**](#data-handling-security-and-privacy)

Cada uno de estos dominios de seguridad incluye controles clave específicos que abarcan uno o más requisitos específicos que se evaluarán como parte del proceso de evaluación. Para asegurarse de que Microsoft 365 Certificación incluya a los desarrolladores de todos los tamaños, cada uno de los dominios de seguridad se evalúa mediante un sistema de puntuación para determinar una puntuación general de cada uno de los dominios. Las puntuaciones de cada uno de los controles de certificación de Microsoft 365 se asignan entre 1 (bajo) y 3 (alto) en función del riesgo percibido de que no se cumpla ese control. Cada uno de los dominios de seguridad tendrá un porcentaje mínimo que se considerará un pase. Algunos elementos de esta especificación incluyen algunos criterios de error automático:

- Los permisos de API no siguen el principio de privilegios mínimos (PoLP).  
- No se requiere ningún informe de pruebas de penetración.
- No hay defensas antimalware
- No se usa Multi-Factor Authentication para proteger el acceso administrativo.  
- Sin procesos de aplicación de revisiones.  
- No hay un aviso de privacidad [de RGPD](#gdpr) adecuado.  

## <a name="application-security"></a>Application Security

El dominio de seguridad de la aplicación se centra en las tres áreas siguientes: 
* Validación de permisos de GraphAPI 
* Comprobaciones de conectividad externa
* Pruebas de seguridad de aplicaciones 

### <a name="graphapi-permission-validation"></a>Validación de permisos de GraphAPI

La validación de permisos de GraphAPI se lleva a cabo para validar que la aplicación o el complemento no solicita permisos excesivamente permisivos. Esto se lleva a cabo comprobando manualmente qué permisos se solicitan. Los analistas de certificación harán referencia cruzada a estas comprobaciones con el envío de atestación Publisher y evaluarán el nivel de acceso que se solicita para asegurarse de que se cumplen las prácticas de "privilegios mínimos". Cuando los analistas de certificación creen que no se cumplen estas prácticas de "privilegios mínimos", los analistas de certificación tendrán una discusión abierta con usted para validar la justificación empresarial de los permisos que se solicitan. Las discrepancias con el envío de atestación de Publisher encontradas durante esta revisión también recibirán comentarios para que su Publisher atestación se pueda actualizar. 

### <a name="external-connectivity-checks"></a>Comprobaciones de conectividad externa

Como parte de la evaluación, un analista realizará un ligero recorrido por la funcionalidad de las aplicaciones para identificar las conexiones fuera de M365.  Las conexiones que no se identifican como microsoft o conexiones directas a su servicio se marcarán y tratarán durante la evaluación.

### <a name="application-security-testing"></a>Pruebas de seguridad de aplicaciones

Una revisión adecuada de los riesgos asociados con la aplicación o el complemento y el entorno auxiliar es esencial para proporcionar a los clientes garantías en la seguridad de la aplicación o el complemento. Las pruebas de seguridad de aplicaciones en forma de pruebas de penetración deben realizarse si la aplicación tiene conectividad con cualquier servicio no publicado por Microsoft. Si la aplicación funciona de forma independiente sin conectividad a ningún servicio o back-end que no sea de Microsoft, no se requieren pruebas de penetración.


**Ámbito de pruebas de penetración**

Las actividades de prueba de penetración **deben** realizarse en el entorno de producción en directo que admita la implementación de la aplicación o complemento (por ejemplo, donde se hospeda el código de aplicación o complemento, que normalmente será el recurso dentro del archivo de manifiesto) junto con cualquier entorno adicional que admita el funcionamiento de la aplicación o complemento (por ejemplo, si la aplicación o el complemento se comunica con otras aplicaciones web fuera de Microsoft 365).  Al definir el ámbito, es necesario tener cuidado para asegurarse de que todos los sistemas o entornos "conectados" que puedan afectar a la seguridad del entorno dentro del ámbito también se incluyan dentro de todas las actividades de pruebas de penetración. 

Cuando se usan técnicas para segmentar los entornos dentro del ámbito de otros entornos, las actividades de pruebas de penetración DEBEN validar la eficacia de dichas técnicas de segmentación. Esto debe detallarse en el informe de pruebas de penetración. 

Los informes de pruebas de penetración se revisarán para asegurarse de que no haya vulnerabilidades que cumplan los siguientes  **criterios de error automático** descritos en los controles siguientes.
 
**Requisitos de pruebas de penetración**


|**Tipo de criterios**|**Controles de pruebas de penetración**|
| -------------------------|-----------------------------|
|**Criterios generales**| **Controls**|
|| Las pruebas de penetración de aplicaciones e infraestructura **deben** realizarse anualmente (cada 12 meses) y ser realizadas por una empresa independiente de buena reputación. |
|| La corrección de las vulnerabilidades críticas y de alto riesgo identificadas **debe** completarse en el plazo de un mes a partir de la conclusión de las pruebas de penetración, o antes, en función del proceso de revisión documentado. |
|| Superficie externa completa (direcciones IP, direcciones URL, puntos de conexión de API, etc.) Debe incluirse en el ámbito de las pruebas de penetración y debe documentarse en el informe de pruebas de penetración. |
|| Las pruebas de penetración de aplicaciones web DEBEN incluir todas las clases de vulnerabilidad; por ejemplo, la versión más reciente de OWASP Top 10 o SANS Top 25 CWE. |
|| No es necesario volver a probar las vulnerabilidades identificadas por la empresa de pruebas de penetración; sin embargo, la corrección y la autoexavaluación son suficientes, pero **se deben** proporcionar pruebas adecuadas para demostrar una corrección suficiente durante la evaluación.|
|**Criterios de error automático:**|**Controls**|
|| Presencia de un sistema operativo no compatible. |
|| Presencia de cuentas administrativas predeterminadas, enumerables o adivinables.|
|| Presencia de riesgos de inyección de SQL.|
|| Presencia de scripting entre sitios.|
|| Presencia de vulnerabilidades de recorrido del directorio (ruta de acceso de archivo).|
|| Presencia de vulnerabilidades HTTP, por ejemplo, división de respuesta de encabezado, contrabando de solicitudes y ataques desincronización.|
|| Presencia de divulgación de código fuente ( [incluidoLFI](#lfi)).|
|| Cualquier puntuación crítica o alta tal como se define en las directrices de administración de revisiones de CVSS.|
|| Cualquier vulnerabilidad técnica significativa que se pueda aprovechar fácilmente para poner en peligro una gran cantidad de EUII o OUI.|






> [!IMPORTANT]
>Los informes deben ser capaces de proporcionar la garantía suficiente de que se puede demostrar todo lo detallado en la sección Especificación de pruebas de seguridad de aplicaciones.


**Requisitos y reglas de pruebas de penetración gratuitas**

- En el caso de los ISV que actualmente no participan en pruebas de penetración, las pruebas de penetración se pueden realizar de forma gratuita en la certificación Microsoft 365. Microsoft organizará y cubrirá el costo de una prueba de penetración durante un máximo de 12 días de pruebas manuales. Los costos de pruebas de penetración se calculan en función del número de días necesarios para probar el entorno. Cualquier gasto que supere los 12 días de prueba será responsabilidad del ISV. 
- Los ISV deberán presentar pruebas y recibir la aprobación del 50 % de los controles en el ámbito antes de que se realice la prueba de penetración. Para empezar, basta con rellenar el envío inicial del documento y elegir que se incluyan pruebas de penetración como parte de la evaluación. Se le pondrá en contacto con el ámbito y programará la prueba de penetración cuando haya completado el 50 % de los controles.
- El informe emitido una vez completado el pentest se proporcionará al ISV una vez que haya completado la certificación. Este informe junto con la certificación de Microsoft 365 se puede usar para mostrar a los clientes potenciales que su entorno es seguro.
- Los ISV también serán responsables de demostrar que las vulnerabilidades identificadas en la prueba de penetración se han corregido antes de que se otorgue una certificación, pero no es necesario generar un informe limpio.

Una vez organizada una prueba de penetración, el ISV es responsable de las tarifas asociadas a la reprogramación y cancelaciones de la siguiente manera:

| **Reprogramación de la escala temporal de tarifas** | **Proporción por pagar** |
|------------------|------------------------|
| Volver a programar la solicitud recibida más de 30 días antes de la fecha de inicio programada. | 0% por pagar |
| Vuelva a programar la solicitud recibida entre 8 y 30 días antes de la fecha de inicio programada. | 25% a pagar |
| Vuelva a programar la solicitud recibida en un plazo de 2 a 7 días antes de la fecha de inicio programada con una fecha de re-reserva firme.| 50% a pagar |
| Vuelva a programar la solicitud recibida menos de 2 días antes de la fecha de inicio. | 100% por pagar |

| **Escala temporal de la cuota de cancelación** | **Proporción por pagar** |
|------------------|------------------------|
| Solicitud de cancelación recibida más de 30 días antes de la fecha de inicio programada. | 25% a pagar |
| Solicitud de cancelación recibida de 8 a 30 días antes de la fecha de inicio programada. | 50% a pagar |
| Solicitud de cancelación recibida dentro de los 7 días anteriores a la fecha de inicio programada. | 90% a pagar |

## <a name="operational-security"></a>Seguridad operativa

Este dominio mide la alineación de los procesos de infraestructura e implementación compatibles de la aplicación con los procedimientos recomendados de seguridad.

### <a name="controls"></a>Controles

|**Familia de control**| **Controls**|
| ------------------------|------------------------------ |
| **Protección contra malware: antivirus**|Proporcione documentación de directivas que rigen los procedimientos y las prácticas antivirus.|
||Proporcione pruebas demostrables de que el software antivirus se ejecuta en todos los componentes del sistema muestreados.|
||Proporcione pruebas demostrables de que las firmas antivirus están actualizadas en todos los entornos (en un plazo de 1 día).|
||Proporcione pruebas demostrables de que el antivirus está configurado para realizar exámenes en el acceso o exámenes periódicos en todos los componentes del sistema muestreados. Nota: Si el examen en el acceso no está habilitado, debe habilitarse un mínimo de análisis diario y alertas.|
||Proporcione pruebas demostrables de que el antivirus está configurado para bloquear automáticamente el malware o la cuarentena y las alertas en todos los componentes del sistema muestreados.|
|**Controles de aplicación**: SOLO se requiere si no se usa el antimalware tradicional|Proporcione pruebas demostrables de que las aplicaciones se aprueban antes de implementarse.|
||Proporcione pruebas demostrables de que existe una lista completa de aplicaciones aprobadas con justificación empresarial y se mantiene.|
||Proporcione documentación complementaria en la que se detalla que el software de control de aplicaciones está configurado para cumplir mecanismos de control de aplicaciones específicos. (Ejemplo: Lista permitida: sample1, sample3, firma de código)|
||Proporcione pruebas demostrables de que el control de aplicaciones está configurado como se documenta a partir de todos los componentes del sistema muestreados.|
|**Administración de revisiones: clasificación de riesgos**| Proporcione documentación de directivas que rigen cómo se identifican y asignan nuevas vulnerabilidades de seguridad a una puntuación de riesgo.|
||Proporcione pruebas de cómo se identifican las nuevas vulnerabilidades de seguridad.|
||Proporcione pruebas que demuestren que a todas las vulnerabilidades se les asigna una clasificación de riesgos una vez identificadas.|
|**Patch Managmeent - Patching**|Proporcione documentación de directivas para la aplicación de revisiones de componentes del sistema en el ámbito que incluyan un período de tiempo de aplicación de revisiones mínimo adecuado para vulnerabilidades críticas, de riesgo alto y medio; y retirada de cualquier software y sistemas operativos no admitidos.|
||Proporcione pruebas demostrables de que se están aplicando revisiones a todos los componentes del sistema muestreados.|
||Proporcione pruebas demostrables de que los sistemas operativos no admitidos y los componentes de software no se usan en el entorno.|
|**Examen de vulnerabilidades**|Proporcione los informes trimestrales de examen de vulnerabilidades de la infraestructura y las aplicaciones web. El examen debe realizarse en toda la superficie pública (direcciones IP y direcciones URL) e intervalos IP internos.|
||Proporcione pruebas demostrables de que la corrección de las vulnerabilidades identificadas durante el examen de vulnerabilidades se aplica en consonancia con el período de tiempo de aplicación de revisiones documentado.|
|**Cortafuegos**|Proporcione documentación de directivas que rigen los procedimientos y las prácticas de administración del firewall.|
||Proporcione pruebas demostrables de que las credenciales administrativas predeterminadas se cambian antes de la instalación en entornos de producción.|
||Proporcione pruebas demostrables de que los firewalls están instalados en el límite del entorno dentro del ámbito e instalados entre la red perimetral (también conocida como RED perimetral, zona desmilitarizada y subred filtrada) y redes internas de confianza.|
||Proporcione pruebas demostrables de que todo el acceso público finaliza en la zona desmilitarizada (DMZ).|
||Proporcione pruebas demostrables de que todo el tráfico permitido a través del firewall pasa por un proceso de aprobación.|
||Proporcione pruebas demostrables de que la base de reglas de firewall está configurada para quitar el tráfico no definido explícitamente.|
||Proporcione pruebas demostrables de que el firewall solo admite criptografía segura en todas las interfaces administrativas que no son de consola.|
||Proporcione pruebas demostrables de que está realizando revisiones de reglas de firewall al menos cada 6 meses.|
|**Web Application Firewall (WAF) (OPCIONAL):** se recompensará el crédito adicional por satisfacer los siguientes controles.|Proporcione pruebas demostrables de que el Web Application Firewall (WAF) está configurado para supervisar, alertar y bloquear el tráfico malintencionado de forma activa.|
||Proporcione pruebas demostrables de que waf admite la descarga ssl.|
||Proporcionar pruebas demostrables de que el WAF se protege frente a algunas o todas las siguientes clases de vulnerabilidades según el conjunto de reglas principal de OWASP (3.0 o 3.1) |
|**Cambiar control**|Proporcione la documentación de directiva que rige los procesos de control de cambios.|
||Proporcione pruebas demostrables de que los entornos de desarrollo y pruebas aplican la separación de las tareas del entorno de producción.|
||Proporcione pruebas demostrables de que los datos de producción confidenciales no se usan en los entornos de desarrollo o pruebas.|
||Proporcione pruebas demostrables de que las solicitudes de cambio documentadas contienen el impacto del cambio, detalles de los procedimientos de retroceso y de las pruebas que se llevarán a cabo.|
||Proporcione pruebas demostrables de que las solicitudes de cambio se someten a un proceso de autorización y firma.|
|**Protección del desarrollo o la implementación de software**| Proporcione directivas y procedimientos que admitan el desarrollo y la implementación de software seguros, incluida la guía de procedimientos recomendados de codificación segura contra clases de vulnerabilidad comunes como OWASP Top 10 o SANS Top 25 CWE.|
|| Proporcione pruebas demostrables de que un segundo revisor somete los cambios de código a un proceso de revisión y autorización.|
|| Proporcione pruebas demostrables de que los desarrolladores se someten a un entrenamiento de desarrollo de software seguro anualmente.|
|| Proporcione pruebas demostrables de que los repositorios de código están protegidos con la autenticación multifactor (MFA).|
|| Proporcione pruebas demostrables de que los controles de acceso están en su lugar para proteger los repositorios de código.
|**Administración de cuentas**| Proporcione documentación de directivas que rigen los procedimientos y procedimientos de administración de cuentas.
||Proporcione pruebas demostrables de que las credenciales predeterminadas se deshabilitan, quitan o cambian en los componentes del sistema muestreados.|
||Proporcione pruebas demostrables de que la creación, modificación y eliminación de cuentas pasa por un proceso de aprobación establecido.|
||Proporcione pruebas demostrables de que se ha implementado un proceso para deshabilitar o eliminar cuentas que no se usan en un plazo de 3 meses.|
||Proporcione pruebas demostrables de que hay una directiva de contraseña segura u otras mitigaciones adecuadas para proteger las credenciales de usuario.  Lo siguiente debe usarse como una guía mínima: longitud mínima de contraseña de 8 caracteres, umbral de bloqueo de cuenta de no más de 10 intentos, historial de contraseñas de un mínimo de 5 contraseñas, cumplimiento del uso de contraseña segura|
||Proporcione pruebas demostrables de que se emiten cuentas de usuario únicas a todos los usuarios.|
||Proporcione pruebas demostrables de que se siguen los principios de privilegios mínimos dentro del entorno.|
||Proporcione pruebas demostrables de que se ha implementado un proceso para proteger o proteger las cuentas de servicio y que se está siguiendo el proceso.|
||Proporcione pruebas demostrables de que MFA está configurado para todas las conexiones de acceso remoto y todas las interfaces administrativas que no son de consola.|
||Proporcione pruebas demostrables de que el cifrado seguro está configurado para todas las conexiones de acceso remoto y todas las interfaces administrativas que no son de consola, incluido el acceso a los repositorios de código y las interfaces de administración en la nube.|
||Proporcione pruebas demostrables de que MFA se usa para proteger el portal de administración que se usa para administrar y mantener todos los registros del servicio de nombres de dominio (DNS) públicos.|
|**Detección y prevención de intrusiones (OPCIONAL):** Se recompensará el crédito adicional por cumplir los siguientes controles.|Proporcione pruebas demostrables de que los sistemas de detección y prevención de intrusiones (IDPS) se implementan en el perímetro de los entornos dentro del ámbito.|
||Proporcione pruebas demostrables de que las firmas IDPS se mantienen actualizadas (en un plazo de 24 horas).|
||Proporcione pruebas demostrables de que IDPS está configurado para admitir la inspección tls de todo el tráfico web entrante.|
||Proporcione pruebas demostrables de que IDPS está configurado para supervisar todos los flujos de tráfico entrantes.|
||Proporcione pruebas demostrables de que IDPS está configurado para supervisar todos los flujos de tráfico salientes.|
|**Registro de eventos de seguridad** |Proporcione documentación de directiva para procedimientos recomendados y procedimientos que rigen el registro de eventos de seguridad.|
|| Proporcione pruebas demostrables que muestren que el registro de eventos de seguridad está configurado en todos los componentes del sistema muestreados para registrar los siguientes eventos: Acceso de usuario a los componentes del sistema y la aplicación, Todas las acciones realizadas por un usuario con privilegios elevados, Acceso lógico no válido intenta crear o modificar la cuenta con privilegios, Alteración del registro de eventos, Deshabilitación de herramientas de seguridad (como antimalware o registro de eventos),  Registro de antimalware (como actualizaciones, detección de malware y errores de examen)., eventos IDPS y WAF, si están configurados|
||Proporcione pruebas demostrables de que los eventos de seguridad registrados contienen la siguiente información mínima: Usuario, Tipo de evento, Fecha y hora, Indicadores de éxito o error, Etiqueta que identifica el sistema afectado|
||Proporcione pruebas demostrables de que todos los componentes del sistema muestreados están sincronizados en el tiempo con los mismos servidores primarios y secundarios.|
||Proporcione pruebas demostrables cuando los sistemas accesibles al público estén en uso de que los registros de eventos de seguridad se envían a una solución de registro centralizada que no se encuentra dentro de la red perimetral.|
||Proporcione pruebas demostrables para mostrar que la solución de registro centralizado está protegida contra la alteración no autorizada de los datos de registro.|
||Proporcione pruebas demostrables de que un mínimo de 30 días de datos de registro de eventos de seguridad están disponibles inmediatamente, con 90 días de registros de eventos de seguridad retenidos.|
|**Revisión (datos de registro)** |Proporcione la documentación de directiva que rige los procedimientos y las prácticas de revisión de registros.|
||Proporcione pruebas demostrables de que los registros son revisados diariamente por herramientas humanas o automatizadas para identificar posibles eventos de seguridad.|
||Proporcione pruebas demostrables de que se investigan y corrigen posibles eventos de seguridad y anomalías.|
|**Alertas** | Proporcione documentación de directivas que rigen procedimientos y procedimientos de alertas de eventos de seguridad.|
|| Proporcionar pruebas demostrables de que las alertas se desencadenan para la evaluación inmediata de los siguientes tipos de eventos de seguridad: creación o modificación de cuentas con privilegios, eventos de virus o malware, manipulación del registro de eventos, IDPS o eventos WAF|
||Proporcione pruebas demostrables que muestren que el personal siempre está disponible, todo el día, todos los días, para responder a las alertas de seguridad.|
|**Administración de riesgos**|Proporcione pruebas demostrables de que se ha establecido un proceso formal de administración de riesgos de seguridad de la información.|
||Proporcione pruebas demostrables de que una evaluación formal del riesgo se realiza anualmente, como mínimo.|
||Proporcione pruebas demostrables de que la evaluación del riesgo de seguridad de la información incluye amenazas, vulnerabilidades o equivalentes.|
||Proporcione pruebas demostrables de que la evaluación de riesgos de seguridad de la información incluye el impacto, la matriz de riesgo de probabilidad o el equivalente.|
||Proporcione pruebas demostrables de que la evaluación de riesgos de seguridad de la información incluye un registro de riesgos y un plan de tratamiento.|
|**Respuesta a incidentes**|Proporcione el plan de respuesta a incidentes de seguridad (IRP).|
||Proporcionar pruebas demostrables de que el IRP de seguridad incluye un proceso de comunicación documentado para garantizar una notificación oportuna a las partes interesadas clave, como las marcas de pago y los adquirentes, los organismos reguladores, las autoridades de supervisión, los directores y los clientes.|
||Proporcione pruebas demostrables de que todos los miembros del equipo de respuesta a incidentes han completado el entrenamiento anual o un ejercicio de tabla superior.|
||Proporcione pruebas demostrables para mostrar que el IRP de seguridad se actualiza en función de las lecciones aprendidas o de los cambios de la organización.|

## <a name="data-handling-security-and-privacy"></a>Control de datos Seguridad y privacidad

Los datos en tránsito entre el usuario de la aplicación, los servicios intermedios y los sistemas de ISV deberán protegerse mediante cifrado a través de una conexión TLS que admita un mínimo de TLS v1.1. *Consulte* [**el Apéndice A**](#appendix-a).

Cuando la aplicación recupere y almacene datos M365, deberá implementar un esquema de cifrado de almacenamiento de datos que siga la especificación definida en [**el Apéndice B**](#appendix-a).

### <a name="controls"></a>Controles

|**Familia de control**| **Controls** |
| -----------------------|-------------------------------- |
|**Datos en tránsito**| Proporcionar pruebas demostrables de que la configuración de TLS cumple o supera los requisitos de cifrado dentro de los [requisitos de configuración del perfil TLS](../docs/certification-submission-guide.md#appendix-a)|
||Proporcione pruebas demostrables de que la compresión TLS está deshabilitada en todos los servicios accesibles desde el público que controlan las solicitudes web.|
||Proporcione pruebas demostrables de que la seguridad de transporte estricta HTTP de TLS está habilitada y configurada para >= 15552000 en todos los sitios.|
|**Datos en reposo**| Proporcione pruebas demostrables de que los datos en reposo se cifran en línea con los requisitos de perfil de cifrado, mediante algoritmos de cifrado como AES, Blowfish, TDES y tamaños de clave de cifrado de 128 bits y 256 bits.|
||Proporcione pruebas demostrables de que la función hash o la autenticación de mensajes (HMAC-SHA1) solo se usan para proteger los datos en reposo en línea con los requisitos de perfil de cifrado.|
||Proporcione un inventario que muestre todos los datos almacenados, incluida la ubicación de almacenamiento y el cifrado utilizados para proteger los datos.|
|**Retención y eliminación de datos**|Proporcione pruebas demostrables de que se ha establecido formalmente un período de retención de datos aprobado y documentado.|
||Proporcione pruebas demostrables de que los datos retenidos coinciden con el período de retención definido.|
||Proporcione pruebas demostrables de que los procesos están en vigor para eliminar datos de forma segura después de su período de retención.|
|**Administración del acceso a datos**|Proporcione una lista de todas las personas con acceso a datos o claves de cifrado, incluida la justificación empresarial.|
||Proporcione pruebas demostrables de que las personas muestreadas que tienen acceso a datos o claves de cifrado se aprobaron formalmente, detallando los privilegios necesarios para su función de trabajo.|
||Proporcione pruebas demostrables de que las personas muestreadas que tienen acceso a datos o claves de cifrado solo tienen los privilegios incluidos en la aprobación.|
||Proporcione una lista de todos los terceros con los que se comparten los datos del cliente.|
||Proporcione pruebas demostrables de que todos los terceros que consumen datos de clientes tienen acuerdos de uso compartido en vigor.|
|**RGPD** (si procede)| Proporcione un proceso de solicitud de acceso de sujeto documentado (SAR) y proporcione pruebas que demuestren que los interesados pueden generar SAR.|
||Proporcione pruebas demostrables de que puede identificar todas las ubicaciones de los datos de los interesados al responder a un SAR.|
||Mantiene un aviso de privacidad que debe contener los detalles de las empresas (nombre, dirección, etc.).|
||Mantiene un aviso de privacidad que debe explicar los tipos de datos personales que se están procesando.|
||Usted mantiene un aviso de privacidad que debe explicar la licitud del procesamiento de datos personales|
||Usted mantiene un aviso de privacidad que explica en detalle los derechos del interesado: Derecho a ser informado, Derecho de acceso por parte del interesado, Derecho a la eliminación, Derecho a la restricción del procesamiento, Derecho a la portabilidad de datos, Derecho a oponerse, Derechos en relación con la toma de decisiones automatizadas, incluida la generación de perfiles.|
|| Mantiene un aviso de privacidad que debe explicar durante cuánto tiempo se conservarán los datos personales.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisión opcional de marcos de cumplimiento externo

Aunque no es necesario, si actualmente cumple con la norma ISO 27001, PCI DSS o SOC2, puede optar por usar estas certificaciones para satisfacer algunos de los controles de certificación de Microsoft 365. Los analistas de certificación intentarán alinear los marcos de seguridad externos existentes con la especificación de certificación Microsoft 365. Sin embargo, si la documentación auxiliar no puede proporcionar garantías de que Microsoft 365 controles de certificación se evaluaron como parte de la auditoría o evaluación de marcos de seguridad externos, deberá proporcionar pruebas adicionales de que dichos controles están en vigor.

La documentación debe demostrar adecuadamente que el entorno de ámbito para la certificación de Microsoft 365 se incluyó en el ámbito de estos marcos de seguridad externos. La validación de estos marcos de seguridad se cumplirá aceptando pruebas de certificaciones válidas realizadas por empresas externas de confianza. Estas empresas de confianza deben ser miembros de organismos internacionales de acreditación para los programas de cumplimiento pertinentes. Consulte Iso Certification and Conformity Standards for ISO 27001 and Qualified Security Assessors (QSA) for PCI DSS(Estándares de certificación y conformidad iso 27001 y evaluadores de seguridad calificados (QSA) para PCI DSS.

En la tabla siguiente se resaltan los marcos externos y la documentación que requieren los analistas de certificación como parte de este proceso de validación:

| **Standard** | **Requisitos**  |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Se necesitará una versión pública de la **Declaración de aplicabilidad** (SOA) y una copia del certificado ISO 27001 emitido.  El SOA resume su posición en cada uno de los 114 controles de seguridad de la información y se usará para identificar si existe alguna exclusión de controles que no se detallan satisfactoriamente en el certificado ISO 27001. Si esto no se puede determinar mediante la revisión de la versión orientada al público del SOA, el analista podría necesitar acceso al SOA completo si se usará ISO 27001 para validar algunos de los controles Microsoft 365 Certification Specification.  Además de validar el ámbito de las actividades de evaluación ISO 27001, los analistas también confirmarán la validez de la empresa de auditoría como se ha descrito anteriormente.|
|**[PCI DSS](#pci-dss)**| Se debe proporcionar un documento de **atestación de cumplimiento** (AOC) de nivel 1 válido que identifique claramente los componentes del sistema y la aplicación en el ámbito.  No se **aceptará** una AOC de autoevaluación como prueba de los procedimientos recomendados de seguridad para reuniones. El AOC se usará para determinar cuál de los Microsoft 365 controles de especificación de certificación se han evaluado y confirmado como parte de la evaluación de PCI DSS.|
|**[SOC 2](#soc-2)**|El informe **SOC 2 (tipo I o tipo II)** debe estar actualizado (emitido en los últimos 15 meses y el período de tiempo declarado iniciado en los últimos 27 meses) para ser utilizado como prueba de conformidad con cualquiera de los controles de evaluación dentro de esta Microsoft 365 Especificación de certificación.|

Si se han incluido marcos de seguridad externos en la atestación de Publisher, los analistas de certificación deberán comprobar la validez de esos marcos de cumplimiento de seguridad como parte de la evaluación de certificación de Microsoft 365.

|**Marco** | **Consideraciones adicionales** |
|-------------- | --------------------|
|ISO 27001| [**Apéndice C**](#appendix-c): Colección de evidencias : Deltas para ISO 27001.|
|PCI DSS | [**Apéndice D**](#appendix-d): Colección de evidencias: deltas para PCI DSS.|
|SOC 2| [**Apéndice E**](#appendix-e): Colección de evidencias: Deltas para SOC 2.|

> [!NOTE]
> Aunque los marcos o estándares de seguridad externos mencionados anteriormente se pueden enviar como pruebas para cumplir algunos de los controles de certificación de Microsoft 365, pasar la certificación de Microsoft 365 no significa que se aprobará correctamente una auditoría en esos estándares o marcos. La especificación de certificación de Microsoft 365 es solo un pequeño subconjunto de esos estándares o marcos de seguridad que permite a Microsoft obtener un nivel de garantía en referencia a su posición de seguridad.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Requisitos para usar marcos de cumplimiento externos

&#x2713; el entorno compatible con la aplicación o complemento **y** los procesos empresariales auxiliares **deben** incluirse dentro del ámbito de los marcos de cumplimiento de seguridad externos compatibles y deben indicarse claramente en la documentación proporcionada.

&#x2713; Los marcos de cumplimiento de seguridad externos admitidos **deben** estar actualizados, es decir, en los últimos 12 meses (o en un plazo de 15 meses si la reevaluación se está realizando actualmente y se pueden proporcionar pruebas).

&#x2713; Los marcos de cumplimiento de seguridad externos admitidos **deben** ser llevados a cabo por una empresa acreditada independiente.

## <a name="appendix-a"></a>Apéndice A

### <a name="tls-profile-configuration-requirements"></a>Requisitos de configuración del perfil TLS

Todo el tráfico de red, ya sea dentro de una red virtual, un servicio en la nube o un centro de datos, debe protegerse con un mínimo de TLS v1.1 (se recomienda TLS v1.2+) u otro protocolo aplicable. Las excepciones a este requisito son:

* **Redirección de HTTP a HTTPS**. La aplicación puede responder a través de HTTP para redirigir los clientes a HTTPS, pero la respuesta no debe contener datos confidenciales (cookies, encabezados, contenido). No se permiten otras respuestas HTTP que no sean redireccionamientos a HTTPS y que respondan a sondeos de estado. Véalo a continuación.
* **Sondeos de estado**. La aplicación solo puede responder a sondeos de estado a través de HTTP **si** la entidad de comprobación no admite sondeos de estado HTTPS.
* **Acceso al certificado**. El acceso a los puntos de conexión CRL, OCSP y AIA con fines de validación y revocación de certificados se permite a través de HTTP.
* **Comunicaciones locales**. La aplicación puede usar HTTP (u otros protocolos no protegidos) para las comunicaciones que no salen del sistema operativo, e. g. conectarse a un punto de conexión de servidor web expuesto en localhost.

La compresión TLS **debe** estar deshabilitada.

## <a name="appendix-b"></a>Apéndice B

### <a name="encryption-profile-configuration-requirements"></a>Requisitos de configuración del perfil de cifrado

Solo se permiten primitivos y parámetros criptográficos como se indica a continuación:

### <a name="symmetric-cryptography"></a>Criptografía simétrica

**Cifrado**

&emsp;&#x2713; solo se permiten AES, BitLocker, Blowfish o TDES. Se permite cualquiera de las longitudes de clave admitidas >=128 (128, 192 y 256 bits) y se pueden usar (se recomiendan claves de 256 bits).

&emsp;&#x2713; solo se permite el modo CBC. Cada operación de cifrado debe usar un vector de inicialización (IV) nuevo y generado aleatoriamente.

&emsp;&#x2713; No **se** permite el uso de cifrados de secuencias, como RC4.

**Funciones hash**

&emsp;&#x2713; Todo el nuevo código debe usar SHA-256, SHA-384 o SHA-512 (denominado colectivamente SHA-2). La salida se puede truncar a no menos de 128 bits

&emsp;&#x2713; SHA-1 solo se puede usar por motivos de compatibilidad.

&emsp;&#x2713; No se permite el uso de MD5, MD4, MD2 y otras funciones hash, ni siquiera para aplicaciones no criptográficas.

**Autenticación de mensajes**

&emsp;&#x2713; Todo el código nuevo DEBE usar HMAC con una de las funciones hash aprobadas. La salida de HMAC se puede truncar a no menos de 128 bits.

&emsp;&#x2713; HMAC-SHA1 solo se puede usar por motivos de compatibilidad.

&emsp;&#x2713; clave HMAC debe tener al menos 128 bits. Se recomiendan claves de 256 bits.

### <a name="asymmetric-algorithms"></a>Algoritmos asimétricos

**Cifrado**

&emsp;&#x2713; se permite RSA. La clave **debe** tener al menos 2048 bits y se debe usar el relleno de OAEP. El uso del relleno PKCS solo se permite por motivos de compatibilidad.

**Firmas**

&emsp;&#x2713; se permite RSA. La clave **DEBE** tener al menos 2048 bits y se debe usar el relleno PSS. El uso del relleno PKCS solo se permite por motivos de compatibilidad.

&emsp; se permite&#x2713;ECDSA. La clave **DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

**Exchange clave**

&emsp;&#x2713; ECDH está permitido. La clave **DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

&emsp;&#x2713; ECDH está permitido. La clave **DEBE** tener al menos 256 bits. Se debe usar la curva NIST P-256, P-384 o P-521.

## <a name="appendix-c"></a>Apéndice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Colección de evidencias: Delta para ISO 27001

Cuando ya haya alcanzado el cumplimiento iso27001, las siguientes diferencias (brechas) no cubiertas totalmente por ISO 27001 tendrán que revisarse como mínimo como parte de esta certificación Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles ISO 27001 asignados no se incluyó como parte de la evaluación ISO 27001 y también puede decidir que se incluyan controles de ejemplo para proporcionar mayor garantía. Cualquier requisito que falte de la norma ISO 27001 deberá incluirse dentro de las actividades de evaluación de certificación de Microsoft 365.

**Protección contra malware: antivirus**

Si la protección contra malware está en vigor mediante el control de aplicaciones y se atestigua en el informe ISO 27001, no es necesario realizar ninguna investigación adicional. Si no hay ningún control de aplicación, los analistas de certificación tendrán que identificar y evaluar las pruebas de los mecanismos de control de aplicaciones para evitar la detonación de malware dentro del entorno. Esto requerirá que:

* Demostrar que el software antivirus se está ejecutando en todos los componentes del sistema muestreados.

* Demostrar que el antivirus está configurado en todos los componentes del sistema muestreados para bloquear automáticamente el malware, poner en cuarentena & alerta o alertar.

* El software antivirus **debe** configurarse para registrar todas las actividades.

**Administración de revisiones: aplicación de revisiones**

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Los componentes de software y los sistemas operativos que ya no son compatibles con el proveedor no **deben** usarse dentro del entorno. Las directivas auxiliares deben estar implementadas para asegurarse de que los componentes de software o sistemas operativos no admitidos se quitarán del entorno y un proceso para identificar cuándo los componentes de software van al final de la vida útil deben estar en su lugar.

**Detección de vulnerabilidades**  

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que se realiza un examen trimestral de vulnerabilidades internas y externas.

* Confirme que la documentación auxiliar está en su lugar para la corrección de vulnerabilidades en función de la clasificación de riesgos y en consonancia con la especificación de la siguiente manera:
 
 &#x2713; Corregir todos los problemas de riesgo crítico y alto en línea con la clasificación de riesgos para el examen interno.
 
 &#x2713; Corregir todos los problemas de riesgo crítico, alto y medio en línea con la clasificación de riesgos para el análisis externo.
 
 &#x2713; Demostrar que la corrección se realiza en línea con la directiva de corrección de vulnerabilidades documentada.

**Firewall: firewalls (o tecnologías equivalentes)**

Como las auditorías ISO 27001 no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que los firewalls están instalados en el límite del entorno dentro del ámbito.

* Demostrar que los firewalls están instalados entre la red perimetral y las redes de confianza.

*   Demostrar que todo el acceso público finaliza en la red perimetral.

*   Demostrar que las credenciales administrativas predeterminadas se cambian antes de la instalación en el entorno activo.

*   Demostrar que todo el tráfico permitido a través de los firewalls pasa por un proceso de autorización que da como resultado la documentación de todo el tráfico con una justificación empresarial.

*   Demostrar que todos los firewalls están configurados para quitar el tráfico no definido explícitamente.

*   Demostrar que los firewalls solo admiten criptografía segura en todas las interfaces administrativas que no son de consola.

*   Demostrar que las interfaces administrativas que no son de consola del firewall expuestas a Internet admiten MFA.

*   Demostrar que las revisiones de reglas de firewall se realizan al menos cada 6 meses

**Firewall: firewalls de aplicaciones web (WAF)**  

Se proporcionará crédito adicional si se implementa un WAF para ayudar a protegerse frente a la infinidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando haya un WAF o similar, esto requerirá que:

* Demostrar que WAF está configurado en modo de defensa activo o supervisando más con las alertas.

* Demostrar que WAF está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principal de OWASP (3.0 o 3.1) para protegerse frente a la mayoría de los siguientes tipos de ataque:

&#x2713; problemas de protocolo y codificación.

&#x2713; inyección de encabezados, contrabando de solicitudes y división de respuestas.

&#x2713; ataques de recorrido de archivos y rutas de acceso.

&#x2713; ataques de inclusión remota de archivos (RFI).

&#x2713; ataques de ejecución remota de código.

&#x2713; ataques por inyección de PHP.

&#x2713; ataques de scripting entre sitios.

ataques por inyección de &#x2713; SQL.

&#x2713; ataques de fijación de sesión.

**Cambiar control**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de solicitud de cambios, esto requerirá que:

* Demostrar que las solicitudes de cambio tienen los siguientes detalles:

&#x2713; impacto documentado.

&#x2713; Detalles de qué pruebas de funcionalidad se realizarán.

&#x2713; Detalles de los procedimientos de retroceso.

* Demostrar que las pruebas de funcionalidad se realizan una vez completados los cambios.

* Demostrar que las solicitudes de cambio se cierran después de realizar pruebas de funcionalidad.

**Administración de cuentas**

Dado que las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

*   Demostrar cómo se implementan los &#x2713;para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).
*   Muestra cómo se deshabilitan o eliminan las cuentas que no se han usado en 3 meses.
*   &#x2713; u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como guía:

&#x2713; longitud mínima de contraseña de 8 caracteres.

&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.
 
&#x2713; historial de contraseñas de un mínimo de cinco contraseñas.
 
&#x2713; Aplicación del uso de contraseñas seguras.
 
*   Demostrar que MFA está configurado para todas las soluciones de acceso remoto.

*   Demostrar que el cifrado seguro está configurado en todas las soluciones de acceso remoto.

*   Cuando la administración de DNS público está fuera del entorno dentro del ámbito, todas las cuentas de usuario que puedan realizar modificaciones de DNS deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL)**

Dado que las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

*   IDPS **DEBE** implementarse en el perímetro del entorno auxiliar.

*   Las firmas IDPS **DEBEN** mantenerse actualizadas en el último día.

*   EL IDPS **DEBE** configurarse para la inspección de TLS.

*   IDPS **DEBE** configurarse para TODO el tráfico entrante y saliente.

*   IDPS **DEBE** configurarse para las alertas.

**Registro de eventos**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de registro de eventos de seguridad, esto requerirá que:

* Demostrar que los sistemas accesibles públicamente están registrando en una solución de registro centralizada que no está dentro de la red perimetral.

* Demostrar cómo un mínimo de 30 días de datos de registro está disponible inmediatamente, con 90 días retenidos.

**Revisión (registro de datos)**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de esta categoría, esto requerirá que:

*   Demostrar cómo se realizan las revisiones de registros diarias y cómo se identifican las excepciones y anomalías, lo que muestra cómo se controlan.

**Alertas**

Como las auditorías ISO 27001 no evalúan específicamente algunos elementos de esta categoría, esto requerirá que:

* Demostrar cómo se configuran los eventos de seguridad para desencadenar alertas para la evaluación de prioridades inmediata.

* Demostrar cómo el personal está disponible 24/7 para responder a las alertas de seguridad.

**Administración de riesgos**

Dado que las auditorías ISO 27001 no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que se establece un proceso formal de administración de riesgos.

**Respuesta a incidentes**

Dado que las auditorías ISO 27001 no evalúan específicamente algunos elementos de las directivas y procesos de respuesta a incidentes, esto requerirá que:

*   Demostrar que el plan o procedimiento de respuesta a incidentes incluye:

&#x2713; Procedimientos de respuesta específicos para los modelos de amenazas esperados.

&#x2713; capacidades de control de incidentes que se alinean con NIST Cybersecurity Framework (Identificar, Proteger, Detectar, Responder, Recuperar).
 
&#x2713; El IRP cubre los sistemas en el ámbito.
 
&#x2713; entrenamiento anual para el equipo de respuesta a incidentes.

## <a name="appendix-d"></a>Apéndice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Colección de evidencias: deltas para PCI DSS

Cuando ya haya alcanzado el cumplimiento de PCI DSS, las siguientes diferencias (brechas) no cubiertas totalmente por PCI DSS tendrán que revisarse, como mínimo, como parte de esta certificación Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles PCI DSS asignados no se incluyó como parte de la evaluación de PCI DSS y también puede decidir incluir los controles de ejemplo que se han encontrado para proporcionar mayor garantía. Los requisitos que falten en pci DSS deberán incluirse en las actividades de evaluación de certificación de Microsoft 365.

**Protección contra malware: control de aplicaciones**

Si la protección contra malware está en vigor mediante el uso de antivirus y se atestigua en el informe de PCI DSS, no es necesario realizar ninguna investigación adicional. Si no existe ningún antivirus, los analistas de certificación deberán identificar y evaluar las pruebas de los mecanismos de control de aplicaciones para evitar la detonación de malware dentro del entorno. Esto requerirá que: 

*   Muestre cómo se lleva a cabo la aprobación de la aplicación y confirme que se ha completado.

*   Demostrar que existe una lista completa de aplicaciones aprobadas con justificación empresarial.

*   Proporcione o muestre documentación complementaria en la que se detalla cómo se configura el software de control de aplicaciones para cumplir los mecanismos de control de aplicaciones específicos (es decir, la lista de permitidos, la firma de código, etc.).

*   Demostrar que en todos los componentes del sistema muestreados, el control de la aplicación se configura como se documenta.

**Administración de revisiones: clasificación de riesgos**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar cómo se realiza la clasificación de riesgos de vulnerabilidades.

**Detección de vulnerabilidades**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que la corrección se realiza en línea con la directiva de corrección de vulnerabilidades documentada.

**Firewall: firewalls (o tecnologías equivalentes)**

Como las auditorías de PCI DSS no evalúan específicamente esta categoría, esto requerirá que:

* Demostrar que los firewalls solo admiten criptografía segura en todas las interfaces administrativas que no son de consola.

* Demostrar que las interfaces administrativas que no son de consola del firewall expuestas a Internet admiten MFA.

Se proporcionará crédito adicional si se implementa un Web Application Firewall (WAF) para ayudar a protegerse frente a la infinidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando haya un WAF o similar, esto requerirá que:

* Demostrar que WAF está configurado en modo de defensa activo o supervisando más con las alertas.

* Demostrar que WAF está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principal de OWASP (3.0 o 3.1) para protegerse frente a la mayoría de los siguientes tipos de ataque:

&#x2713; problemas de protocolo y codificación.

&#x2713; inyección de encabezados, contrabando de solicitudes y división de respuestas.

&#x2713; ataques de recorrido de archivos y rutas de acceso.

&#x2713; ataques de inclusión remota de archivos (RFI).

&#x2713; ataques de ejecución remota de código.

&#x2713; ataques por inyección de PHP.

&#x2713; ataques de scripting entre sitios.

ataques por inyección de &#x2713; SQL.

&#x2713; ataques de fijación de sesión.

**Cambiar control**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de solicitud de cambios, esto requerirá que:

* Demostrar que las solicitudes de cambio se generan antes de realizarse en entornos de producción.

* Demostrar que los cambios están autorizados antes de entrar en producción.

* Demostrar que las pruebas de funcionalidad se realizan una vez completados los cambios.

* Demostrar que las solicitudes de cambio se cierran después de realizar pruebas de funcionalidad.

**Protección del desarrollo o la implementación de software**

Como las auditorías de PCI DSS no acceden específicamente a algunos elementos de procesos de implementación y desarrollo de software seguros; esto le requerirá lo siguiente:

* Los repositorios de código deben protegerse mediante MFA.

*   Deben existir controles de acceso adecuados para proteger los repositorios de código frente a modificaciones de código malintencionadas.

**Administración de cuentas**

Dado que las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

* Demostrar cómo se implementan los mecanismos de autorización para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).

* Las directivas de contraseña segura u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como guía: 

&#x2713; longitud mínima de contraseña de 8 caracteres.

&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.

&#x2713; historial de contraseñas de un mínimo de cinco contraseñas.

&#x2713; Aplicación del uso de contraseñas seguras.

* Demostrar que el cifrado seguro está configurado en todas las soluciones de acceso remoto.

* Cuando la administración de DNS público está fuera del entorno dentro del ámbito, todas las cuentas de usuario que puedan realizar modificaciones de DNS deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL)**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

* EL IDPS DEBE configurarse para la inspección de TLS.

*   IDPS DEBE configurarse para TODO el tráfico entrante y saliente.

**Administración de riesgos**

Dado que las auditorías de PCI DSS no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que la evaluación de riesgos incluye matrices de impacto y probabilidad.

**Respuesta a incidentes**

Como las auditorías de PCI DSS no evalúan específicamente algunos elementos de las directivas y procesos de respuesta a incidentes, esto requerirá que el desarrollador:

* Demostrar que las funcionalidades de control de incidentes se alinean con NIST Cybersecurity Framework (Identificar, Proteger, Detectar, Responder, Recuperar).

## <a name="appendix-e"></a>Apéndice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Colección de evidencias: deltas para SOC 2

Cuando ya haya alcanzado el cumplimiento de SOC 2, las siguientes diferencias (brechas) no cubiertas totalmente por SOC 2 tendrán que revisarse como parte de esta certificación de Microsoft 365.

> [!NOTE]
> Como parte de la evaluación de certificación de Microsoft 365, el analista de certificación determinará si alguno de los controles de SOC 2 asignados no se incluyó como parte de la evaluación de SOC 2 y también puede decidir tomar muestras de los controles que se han detectado que se han incluido para proporcionar una mayor garantía. Los requisitos que falten en la evaluación de SOC 2 deberán incluirse como parte de las actividades de evaluación de certificación Microsoft 365.

**Protección contra malware: control de aplicaciones**

Si la protección contra malware está en vigor mediante el uso de antivirus y se atestigua en su informe soc 2 no es necesaria ninguna investigación adicional. Si no existe ningún antivirus, los analistas de certificación deberán identificar y evaluar las pruebas de los mecanismos de control de aplicaciones para evitar la detonación de malware dentro del entorno. Esto requerirá que:

* Proporcione o muestre documentación complementaria en la que se detalla cómo se configura el software de control de aplicaciones para cumplir los mecanismos de control de aplicaciones específicos (es decir, la lista de permitidos, la firma de código, etc.).

* Muestre cómo se lleva a cabo la aprobación de la aplicación y confirme que se ha completado.

*   Demostrar que existe una lista completa de aplicaciones aprobadas con justificación empresarial.

*   Demostrar que en todos los componentes del sistema muestreados, el control de la aplicación se configura como se documenta.

**Administración de revisiones: aplicación de revisiones**

Como las auditorías de SOC 2 no evalúan específicamente esta categoría, esto requerirá que:

*   Cualquier problema bajo, medio, alto o crítico debe revisarse dentro de las ventanas de actividad de aplicación de revisiones normales.

*   Los componentes de software y los sistemas operativos que ya no son compatibles con el proveedor no deben usarse dentro del entorno. Las directivas auxiliares deben estar implementadas para garantizar que los componentes de software o los sistemas operativos no admitidos se quitarán del entorno y un proceso para identificar cuándo los componentes de software terminan su vida útil.

**Firewall: firewalls**

Dado que las auditorías de SOC 2 no evalúan específicamente los controles de cambio en las listas de control de acceso del firewall, esto requerirá que:

* Demostrar que todo el tráfico permitido a través de los firewalls pasa por un proceso de autorización que da como resultado la documentación de todo el tráfico con una justificación empresarial.

* Demostrar que las revisiones de reglas de firewall se realizan al menos cada seis meses.

Se proporcionará crédito adicional si se implementa un Web Application Firewall (WAF) o similar para ayudar a protegerse frente a la infinidad de amenazas y vulnerabilidades de aplicaciones web a las que se puede exponer la aplicación. Cuando haya un WAF o similar, esto requerirá que:

* Demostrar que WAF está configurado en modo de defensa activo o supervisando más con las alertas.

* Demostrar que WAF está configurado para admitir la descarga de SSL.

* Se configura según el conjunto de reglas principal de OWASP ((3.0 o 3.1) para protegerse frente a la mayoría de los siguientes tipos de ataque:

&emsp;&#x2713; problemas de protocolo y codificación.

&emsp;&#x2713; inserción de encabezados, contrabando de solicitudes y división de respuestas.

&emsp;&#x2713; ataques de recorrido de archivos y rutas de acceso.

&emsp;&#x2713; ataques de inclusión remota de archivos (RFI).

&emsp;&#x2713; ataques de ejecución remota de código.

&emsp;&#x2713; ataques por inyección de PHP.

&emsp;&#x2713; ataques de scripting entre sitios.

&emsp;ataques por inyección de&#x2713; SQL.

&emsp;&#x2713; ataques de fijación de sesión.

**Cambiar control**

Como las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de solicitud de cambios, esto requerirá que el desarrollador:

* Demostrar cómo los entornos de desarrollo y pruebas son independientes del entorno de producción que exige la separación de tareas.

* Demostrar cómo no se usan los datos activos en los entornos de desarrollo y pruebas.

* Demostrar que las pruebas de funcionalidad se realizan una vez completados los cambios.

* Demostrar que las solicitudes de cambio se cierran después de realizar pruebas de funcionalidad.

**Protección del desarrollo o la implementación de software**

Como las auditorías de SOC 2 no acceden específicamente a algunos elementos de procesos de implementación y desarrollo de software seguros; esto le requerirá lo siguiente:

*   Debe tener un proceso de desarrollo de software establecido y documentado que cubra todo el ciclo de vida de desarrollo de software.

*   Los desarrolladores deben someterse a un entrenamiento de codificación de software seguro al menos anualmente.

*   Los repositorios de código deben protegerse mediante MFA.

*   Deben existir controles de acceso adecuados para proteger los repositorios de código frente a modificaciones de código malintencionadas.

**Administración de cuentas**

Como las auditorías de SOC2 no evalúan específicamente algunos elementos de los procesos de administración de cuentas, esto requerirá que:

*   Demostrar cómo se implementan los mecanismos de autorización para mitigar los ataques de reproducción (por ejemplo, MFA, Kerberos).

*   Muestra cómo se deshabilitan o eliminan las cuentas que no se han usado en 3 meses.

*   Las directivas de contraseña segura u otras mitigaciones adecuadas deben configurarse para proteger las credenciales de usuario. La siguiente directiva de contraseña mínima debe usarse como guía:

&emsp;&#x2713; longitud mínima de contraseña de 8 caracteres.

&emsp;&#x2713; umbral de bloqueo de cuenta de no más de 10 intentos.

&emsp;&#x2713; historial de contraseñas de un mínimo de 5 contraseñas.

&emsp;&#x2713; Aplicación del uso de contraseñas seguras

*   Demostrar que las cuentas de usuario únicas se emiten a todos los usuarios.

*   Cuando la administración de DNS público está fuera del entorno dentro del ámbito, todas las cuentas de usuario que puedan realizar modificaciones de DNS deben configurarse para usar MFA.

**Detección y prevención de intrusiones (OPCIONAL).**

Dado que las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de Servicios de detección y prevención de intrusiones (IDPS), esto requerirá que:

*   Las firmas IDPS DEBEN mantenerse actualizadas, en el último día

*   IDPS DEBE configurarse para la inspección de TLS

*   IDPS DEBE configurarse para TODO el tráfico entrante y saliente.

**Registro de eventos**

Como las auditorías de SOC 2 no evalúan específicamente algunos elementos de los procesos de registro de eventos de seguridad, esto requerirá que:

* Demostrar cómo, en todos los componentes del sistema del conjunto de ejemplo, se configuran los siguientes sistemas para registrar los siguientes eventos.

&emsp;&#x2713; Acceso de usuario a los componentes del sistema y a las aplicaciones.

&emsp;&#x2713; Todas las acciones realizadas por un usuario con privilegios elevados.

&emsp;&#x2713; intentos de acceso lógico no válidos.

Demostrar que los eventos registrados contienen; como mínimo, la siguiente información:

&emsp;&#x2713; usuario.

&emsp;&#x2713; tipo de evento.

&emsp;&#x2713; fecha y hora.

&emsp;&#x2713; indicador de éxito/error.

&emsp;&#x2713; Etiqueta para identificar el sistema afectado.

*   Demostrar que todos los componentes del sistema del conjunto de ejemplo están configurados para usar la sincronización de tiempo y que son los mismos que los servidores de hora principal y secundario.

* Demostrar que los sistemas accesibles públicamente están registrando en una solución de registro centralizada que no está dentro de la red perimetral.

*   Demostrar que los sistemas accesibles públicamente están registrando en una solución de registro centralizada que no está dentro de la red perimetral.

* Demostrar cómo la solución de registro centralizado está protegida frente a alteraciones no autorizadas de los datos de registro.

* Demostrar cómo un mínimo de 30 días de datos de registro está disponible inmediatamente, con 90 días o más retenidos.

**Administración de riesgos**

Dado que las auditorías de SOC2 no evalúan específicamente algunos elementos de los procesos de evaluación de riesgos, esto requerirá que:

* Demostrar que se realiza una evaluación formal del riesgo al menos anualmente.

*Respuesta a incidentes.*

Dado que las auditorías de SOC2 no evalúan específicamente algunos elementos de las directivas y procesos de respuesta a incidentes, esto requerirá que:

* Demostrar que el plan o procedimiento de respuesta a incidentes incluye:

&emsp;&#x2713; Procedimientos de respuesta específicos para los modelos de amenazas esperados.

&emsp;&#x2713; proceso de comunicaciones documentadas para garantizar la notificación oportuna de las partes interesadas clave (marcas de pago/adquirentes, organismos reguladores, autoridades de supervisión, directores, clientes, etc.

## <a name="appendix-f"></a>Apéndice F

### <a name="hosting-deployment-types"></a>Hospedaje de tipos de implementación

Microsoft confirma que implementará aplicaciones y almacenará código de aplicación o complemento en diferentes entornos de hospedaje. Las responsabilidades generales de algunos de los controles de seguridad dentro de la certificación Microsoft 365 dependerán del entorno de hospedaje que se use. En el apéndice F se examinan los tipos de implementación comunes y se asignan a los controles de seguridad que se evalúan como parte del proceso de evaluación. Se han identificado los siguientes tipos de implementación de hospedaje:

|Tipos de hospedaje  |Descripción  |
|-----|------|
|**ISV hospedado**|Los tipos hospedados de ISV se pueden definir como donde es responsable de la infraestructura que se usa para admitir el entorno de aplicación o complemento. Esto puede encontrarse físicamente dentro de sus propios centros de datos o centros de datos de terceros con un servicio de ubicación conjunta. En última instancia, tiene plena propiedad y control administrativo sobre la infraestructura auxiliar y el entorno operativo.|
|**Infraestructura como servicio (IaaS)** (https://azure.microsoft.com/overview/what-is-iaas/)|La infraestructura como servicio es un servicio que se proporciona mediante el cual el proveedor de servicios en la nube (CSP) administra y mantiene la infraestructura de soporte físico en su nombre. Normalmente, las redes, el almacenamiento, los servidores físicos y la infraestructura de virtualización son responsabilidad del CSP. El sistema operativo, middleware, tiempo de ejecución, datos y aplicaciones son las responsabilidades de usted. Las funcionalidades de firewall también serían administradas y mantenidas por el tercero, sin embargo, el mantenimiento de la base de reglas de firewall normalmente seguiría siendo la responsabilidad de los consumidores.|
|**Plataforma como servicio/sin servidor (PaaS)** (https://azure.microsoft.com/overview/what-is-paas/)| Con Plataforma como servicio, se aprovisiona con una plataforma administrada que presenta un servicio que se puede consumir. No es necesario realizar funciones sysadmin, ya que el CSP administra el sistema operativo y la infraestructura auxiliar. Esto normalmente se usaría cuando las organizaciones no quieran preocuparse por presentar un servicio web y, en su lugar, pueden concentrarse en crear el código fuente de la aplicación web y publicar la aplicación web en los servicios web administrados en la nube.  Otro ejemplo puede ser un servicio de base de datos en el que se proporciona conectividad a una base de datos, pero la infraestructura auxiliar y la aplicación de base de datos se abstrae del consumidor.   **Nota: Sin servidor y PaaS son similares, por lo que para el propósito de la Microsoft 365 tipo de implementación de hospedaje de certificación sin servidor y PasS se consideran iguales**|
|**Hospedado híbrido**|Con el tipo hospedado híbrido, puede usar varios tipos hospedados para admitir varias partes del entorno auxiliar. Este puede ser más el caso en el que las aplicaciones o complementos se usan en varias pilas M365. Aunque la certificación de Microsoft 365 admitirá dónde se desarrollan aplicaciones o complementos en varios servicios M365, una evaluación de todo el entorno compatible (entre aplicaciones o complementos) tendría que evaluarse de acuerdo con cada una de las "asignaciones de tipos hospedados" aplicables. En ocasiones, puede usar diferentes tipos hospedados para un único complemento, donde esto se está llevando a cabo, la aplicabilidad de los criterios tendrá que seguir los criterios "Asignaciones de tipos hospedados" en los distintos tipos hospedados.|
|**Hospedaje compartido**|El hospedaje compartido es donde hospeda el entorno dentro de una plataforma que comparten varios consumidores individuales. La especificación de certificación de Microsoft 365 no se escribió para tener en cuenta esto debido a la adopción de la nube, el hospedaje compartido no es común. Si cree que se está usando, póngase en contacto con Microsoft, ya que será necesario crear requisitos adicionales para tener en cuenta los riesgos adicionales en este tipo de hospedaje.|


## <a name="appendix-g"></a>Apéndice G

## <a name="learn-more"></a>Más información

[Introducción al programa de cumplimiento de aplicaciones de Microsoft 365](~/overview.md)  
[¿Qué es Microsoft 365 Attestation Publisher App?](~/docs/attestation.md)  
[¿Qué es la certificación Microsoft 365?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glosario

### <a name="aia"></a>AIA

*Authority Information Access es un descriptor de ubicación de servicio que se usa para buscar el certificado de la entidad de certificación emisora.

### <a name="crl"></a>CRL

*La lista de revocación de certificados proporciona un medio para que un punto de conexión de capa de sockets seguros (SSL) compruebe que un certificado recibido de un host remoto es válido y confiable.

### <a name="cvss-score"></a>Puntuación de CVSS

*Common Vulnerability Scoring System es un estándar publicado que mide la vulnerabilidad y calcula una puntuación numérica en función de su gravedad.

### <a name="cvss-patch-management-guidelines"></a>Directrices de administración de revisiones de CVSS

* Crítico (9.0 - 10.0)
* Alto (7.0 - 8.9)
* Medio (4.0 - 6.9)
* Bajo (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zona desmilitarizada es una red intermedia física o lógica que interactúa directamente con redes externas o no de propiedad, al tiempo que mantiene la red interna, privada y aislada del host.

### <a name="euii"></a>EUII

*Información de identificación del usuario final*.

### <a name="gdpr"></a>RGPD

*El Reglamento General de Protección de Datos es un reglamento de privacidad y protección de datos de la Unión Europea (UE) para todos los datos de los ciudadanos de la UE, independientemente de dónde se encuentre su sitio de aplicación.

### <a name="hsts"></a>HSTS

*Http Strict Transport Security utiliza un encabezado de respuesta HTTP que indica al explorador web que solo acceda al contenido a través de HTTPS.  Esto está diseñado para protegerse frente a ataques de degradación y secuestro de cookies.

### <a name="iec"></a>IEC

*Comisión Electrotécnica Internacional.

### <a name="isms"></a>SGSI

*Sistema de administración de seguridad de la información.

### <a name="isv"></a>ISV

Los proveedores de seguridad independientes son personas y organizaciones que desarrollan, comercializan y venden software que se ejecuta en plataformas de hardware y software de terceros.

### <a name="iso-27001"></a>ISO 27001

Marco de especificación del sistema de administración de la seguridad de la información para todos los controles técnicos de los procesos y directivas de administración de riesgos de una organización.

### <a name="lfi"></a>LFI

*La inclusión de archivos local* permite a un atacante incluir archivos en un servidor a través del explorador web.

### <a name="nist"></a>NIST

El *Instituto Nacional de Estándares* (NIST), una agencia no reguladora del Departamento de Comercio de ee. UU. proporciona orientación a las organizaciones del sector privado en los Estados Unidos para evaluar y aprobar su capacidad de prevenir, detectar y responder a ciberataques.

### <a name="non-significant-changes"></a>Cambios no significativos

* Correcciones de errores menores.
* Mejoras de rendimiento menores.
* Sistemas operativos, bibliotecas o revisiones de aplicaciones cliente y servidor.

### <a name="ocsp"></a>OCSP

*El protocolo de estado de certificado en línea* se usa para comprobar el estado de revocación de los certificados digitales X.509.

### <a name="oii"></a>OII

*Información de identificación de la organización*.

### <a name="owasp"></a>OWASP

*Abra Project seguridad de aplicaciones web*.

### <a name="pci-dss"></a>PCI DSS

*Estándar de seguridad de datos del sector de tarjetas de pago*, una organización que mantiene estándares para la seguridad de los datos de los titulares de tarjetas en todo el mundo.

### <a name="pen-testing"></a>Pruebas de lápiz

*Las pruebas de penetración* son un método para probar una aplicación web mediante la simulación de ataques malintencionados para encontrar vulnerabilidades de seguridad que un atacante podría aprovechar.

### <a name="saml"></a>SAML

*El lenguaje de marcado de aserción de seguridad* es un estándar abierto para intercambiar datos de autenticación y autorización entre el usuario, el proveedor de identidades y el proveedor de servicios.

### <a name="sensitive-data"></a>Datos confidenciales

* Datos de control de acceso.
* Contenido del cliente.
* Información de identidad del usuario final.
* Datos de soporte técnico.
* Datos personales públicos.
* Información seudónima del usuario final.

### <a name="significant-changes"></a>Cambios significativos

* Reubicación del entorno de hospedaje.
* Principales actualizaciones de la infraestructura auxiliar; por ejemplo, la implementación de un nuevo firewall, las actualizaciones principales de los servicios frontales, etc.
* Adición de funcionalidades y /o extensiones a la aplicación.
* Actualizaciones de la aplicación que capturan datos confidenciales adicionales.
* Cambios en los flujos de datos o modelos de autorización de la aplicación
* Adición de puntos de conexión de API o funciones de punto de conexión de API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, un procedimiento de auditoría técnica compuesto por cinco principios de servicio de confianza para garantizar que los proveedores de servicios administren de forma segura los datos y la privacidad de los clientes de una organización.

### <a name="ssl"></a>SSL

*Capa de sockets seguros*.

### <a name="tls"></a>TLS

*Seguridad de la capa de transporte*.
