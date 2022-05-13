---
title: Guía de clonación de envíos de certificación
author: oromalle
ms.author: oromalle
manager: tonybal
description: Guía para clonar el envío de certificación de Microsoft 365
keywords: Clonación de certificación de Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 49335e04752f8c1263e270d2eb3472e00978ccbb
ms.sourcegitcommit: e7d5b928692a072b066cdd957aeabad64cfee931
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/13/2022
ms.locfileid: "65385480"
---
# <a name="certification-submission-cloning-user-guide"></a>Guía del usuario de clonación de envíos de certificación
Esta guía solo es aplicable si va a pasar por la certificación Microsoft 365 y:
- Tiene varias integraciones de la misma aplicación exacta (es decir, la misma aplicación tiene integraciones de teams, outlook, office y sharepoint).
- Tiene dos aplicaciones que comparten exactamente el mismo back-end y la infraestructura auxiliar. 

En estos dos escenarios, la aplicación tendrá la misma evidencia en el ámbito de la certificación y puede aprovechar esta característica de clonación para acelerar la certificación de varias aplicaciones. 

>[!IMPORTANT]
>Actualmente, esta característica solo funciona entre diferentes aplicaciones M365 (aplicaciones de SharePoint, aplicaciones Teams y complementos de Office), O entre aplicaciones web (SaaS). No se puede clonar entre una aplicación web y una aplicación M365.

>[!NOTE]
>Solo puede clonar desde aplicaciones que tengan una certificación completa. No se puede clonar desde aplicaciones que están actualmente en curso para la certificación.

**Paso 1. Iniciar certificación**

Para iniciar la certificación, active la casilla de consentimiento y haga clic en Enviar.
![Inicio de la certificación](../media/CertStartConsent.png)


**Paso 2. Seleccione la aplicación desde la que desea clonar.**

En el cuadro desplegable, seleccione la aplicación que desea usar para clonar el envío.
![Certificación Seleccionar aplicación](../media/CertSelectApp.png)


**Paso 3. Puede elegir lo que quiere clonar.**

Puede elegir COPIAR SOLO el envío inicial del documento. Si desea hacerlo, simplemente haga clic en Copiar.
![Clonación de certificación sin pruebas](../media/CertCloneNoEvidence.png)

También puede elegir copiar todas las pruebas del envío desde el que se ha enviado la clonación. Si desea hacerlo, seleccione el cuadro que indica "Solicitar copiar pruebas para todos los controles del envío seleccionado" y, a continuación, haga clic en Copiar.
![Clonación de certificación con pruebas](../media/CertCloneWithEvidence.png)


**Paso 4. Enviar el envío inicial de documentos y esperar a su aprobación**

Si solicitó copiar pruebas de su envío, el analista deberá aprobar la solicitud de clonación de pruebas.
![Id. de certificación enviado](../media/IDSSubmitted.png)


**Paso 5. Copia del envío de pruebas**

Una vez aprobada la solicitud inicial de clonación de pruebas y envío de documentos, recibirá una lista de todos los controles en el ámbito de su submisión. Tendrá que hacer clic en Copiar para clonar todas las pruebas de su otro envío.
![Clonación de certificación con evidenciaCertificación](../media/CertCloneApproved.png)
![ de clonación con evidencia](../media/CertCloneApprovedCopied.png)


**Paso 6. Envío del envío de certificación**

En este momento, ha copiado correctamente todas las pruebas de su otro envío y puede enviar la evaluación de certificación para su aprobación.
![Clonación de certificación con pruebas](../media/CertCloneApprovedCopiedSubmit.png)
