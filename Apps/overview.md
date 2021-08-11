---
title: Cumplimiento de Aplicaciones de Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introducción al programa y descripción general
keywords: microsoft 365 m365 app editor certificación atestación
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: 17d5c8cdba50666e2c38912e42fc60dd36d00d091531294bf865d6c0f92a31f4
ms.sourcegitcommit: 717ca5bc90981def8914c4cd1fad992f67be4d5b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/06/2021
ms.locfileid: "54803662"
---
# <a name="microsoft-365-app-compliance-program"></a>Cumplimiento de Aplicaciones de Microsoft 365

El programa de Cumplimiento de aplicaciones de Microsoft 365 es una estrategia de tres niveles enfocada a la seguridad y al cumplimiento de las aplicaciones. Cada nivel se basa en el anterior y ofrece un programa escalonado para dar a los usuarios la confianza que necesitan al usar aplicaciones del ecosistema de Microsoft 365. Actualmente, todos los niveles del programa son voluntarios y los desarrolladores de aplicaciones deciden si completarlos o no a su total discreción. 

Nuestra misión es que los clientes de Microsoft tengan plena confianza en las aplicaciones que ejecutan sus organizaciones.

  ![Estrategia de 3 niveles para el cumplimiento de las aplicaciones](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Verificación del editor

[La verificación de editor](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) ayuda a los administradores y usuarios a comprender la autenticidad de la integración de los desarrolladores de aplicaciones con la Plataforma de identidad de Microsoft. Cuando se marca en una aplicación el "editor verificado", significa que el editor ha verificado su identidad con una cuenta de Microsoft Partner Network que ha completado el proceso de verificación y que ha asociado esta cuenta de MPN al registro de la aplicación.
La verificación de editor se usa con las aplicaciones que cumplan las condiciones siguientes:  
- Usar OAuth 2.0 y OpenID Connect para iniciar las sesiones de los usuarios y solicitar acceso a los datos con una API del servicio, como Microsoft Graph. 
- Registrarse en Azure AD como multiempresa.  

> [!IMPORTANT]
> La verificación de editor no impide que un desarrollador de aplicaciones inicie o complete la Certificación de editor o la Atestación de Microsoft 365. Si no se aplica a la comprobación de la aplicación, puede omitirse e iniciarse la atestación.

## <a name="publisher-attestation"></a>Atestación del editor

En la [atestación de editor](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide), los desarrolladores comparten información general, de control de datos, de seguridad y de cumplimiento sobre el servicio de su aplicación. Esto reduce la necesidad de que los administradores de TI trabajen directamente con los editores de aplicaciones. Se reúne en un solo lugar y con un solo formato toda la información necesaria para tomar una decisión informada sobre cada una de las aplicaciones que hayan completado la atestación del editor. El objetivo es facilitar y acelerar el proceso de adopción de aplicaciones, mientras se asegura a los clientes que las aplicaciones que usan en sus espacios empresariales cumplen con los estándares de la organización.

La Atestación del editor se aplica a WebApps y a todas las aplicaciones que se integran con los siguientes productos de Microsoft:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft no valida la información proporcionada. Es exclusivamente el desarrollador quien da fe de la veracidad, exactitud e integridad de la documentación de atestación y los correspondientes datos de rendimiento de la aplicación. 

## <a name="microsoft-365-certification"></a>Certificación Microsoft 365
La [Certificación de Microsoft 365](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) ofrece a las organizaciones la garantía y confianza de que sus datos y privacidad están protegidos adecuadamente cuando usen aplicaciones de Microsoft Teams. La certificación confirma que una solución de aplicación es compatible con las tecnologías de Microsoft, cumple con los procedimientos recomendados de seguridad de aplicaciones en la nube y es compatible con Microsoft.Durante este proceso, los desarrolladores de aplicaciones trabajan con un evaluador de terceros para validar los estándares de seguridad y cumplimiento de la organización. La Certificación de Microsoft 365 se aplica a las mismas aplicaciones que cumplen los requisitos para la atestación del publicador. 


