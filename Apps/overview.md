---
title: Cumplimiento de Aplicaciones de Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introducción al programa y descripción general
keywords: microsoft 365 m365 app editor certificación atestación
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: e36bee4289de320d264a8a5e55c7bc20a4ea803b
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545777"
---
# <a name="microsoft-365-app-compliance-program"></a>Cumplimiento de Aplicaciones de Microsoft 365

El programa de cumplimiento de aplicaciones de Microsoft 365 es un enfoque de dos pasos para la seguridad y el cumplimiento de aplicaciones e incluye la verificación de Publisher y la certificación de Microsoft 365. Cada nivel se basa en el anterior y ofrece un programa escalonado para dar a los usuarios la confianza que necesitan al usar aplicaciones del ecosistema de Microsoft 365.  

Nuestra misión: proporcionar a los clientes de Microsoft una forma de confiar completamente en las aplicaciones que ejecutan sus organizaciones.

![Estrategia de 2 niveles para el cumplimiento de las aplicaciones](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>Verificación del editor

[La verificación de editor](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) ayuda a los administradores y usuarios a comprender la autenticidad de la integración de los desarrolladores de aplicaciones con la Plataforma de identidad de Microsoft. Cuando se marca en una aplicación el "editor verificado", significa que el editor ha verificado su identidad con una cuenta de Microsoft Partner Network que ha completado el proceso de verificación y que ha asociado esta cuenta de MPN al registro de la aplicación.
La verificación de editor se usa con las aplicaciones que cumplan las condiciones siguientes:  
- Usar OAuth 2.0 y OpenID Connect para iniciar las sesiones de los usuarios y solicitar acceso a los datos con una API del servicio, como Microsoft Graph. 
- Registrarse en Azure AD como multiempresa.  

> [!IMPORTANT]
> La verificación de editor no impide que un desarrollador de aplicaciones inicie o complete la Certificación de editor o la Atestación de Microsoft 365. Si no se aplica a la comprobación de la aplicación, puede omitirse e iniciarse la atestación.

## <a name="microsoft-365-certification"></a>Certificación Microsoft 365
El proceso de certificación de Microsoft 365 tiene dos fases: la **atestación** y la **certificación.**
1.  La **atestación** implica completar un cuestionario sobre los atributos de seguridad, control de datos y cumplimiento de una aplicación de vital importancia para los clientes. A continuación, toda la información se publica en un solo lugar y en un formato coherente y fácil de leer. El objetivo es acelerar el proceso de adopción de aplicaciones, mientras se asegura a los clientes que las aplicaciones que usan en sus espacios empresariales cumplen con los estándares de la organización.
1.  La **certificación** implica una auditoría exhaustiva de una aplicación contra un conjunto de controles derivados de marcos estándar líderes de la industria. Se pedirá a los ISV que proporcionen pruebas para demostrar que cumplen con cada control antes de obtener una certificación. El objetivo es dar a los clientes la seguridad de que pueden confiar en la aplicación porque las aplicaciones que han recibido una certificación de Microsoft 365 mostraron prácticas de seguridad y cumplimiento sólidas para proteger la seguridad de los datos y la privacidad.


La certificación de Microsoft 365 se aplica a WebApps y a todas las aplicaciones que se integran con los siguientes productos de Microsoft:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

### <a name="get-started"></a>Introducción
- [Cómo completar la verificación de Publisher](https://docs.microsoft.com/en-us/azure/active-directory/develop/mark-app-as-publisher-verified)
- [Cómo completar la certificación de Microsoft 365](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification)

