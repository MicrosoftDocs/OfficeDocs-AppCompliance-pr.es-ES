---
title: Automatización de la certificación de Microsoft 365 con App Compliance Automation Tool para Microsoft 365
description: Uso de app compliance automation tool for Microsoft 365 (ACAT) para automatizar la certificación de Microsoft 365.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: b708f68ed5717d08b321f02f3ba09989a77fdf17
ms.sourcegitcommit: e639149031755df8cd50c03341b6507146cc48b0
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/01/2022
ms.locfileid: "65793035"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Automatización de la certificación de Microsoft 365 con App Compliance Automation Tool para Microsoft 365

App Compliance Automation Tool for Microsoft 365 (ACAT) colabora con el programa de cumplimiento de aplicaciones Microsoft 365 para cumplir algunos de los controles necesarios para la certificación Microsoft 365. Este artículo le ayudará a empezar a trabajar con ACAT y a usar las evaluaciones de cumplimiento con la certificación Microsoft 365.

> [!IMPORTANT]
> ACAT está en versión preliminar privada en este momento. Si desea unirse al programa de versión preliminar privada, regístrese [aquí](https://aka.ms/acat/private/signup).

> [!NOTE]
> Si desea proporcionar comentarios a la versión preliminar privada de ACAT, puede empezar desde este [formulario](https://aka.ms/acat/feedback). El equipo de producto de ACAT le realizará un seguimiento lo antes posible una vez que recibamos sus mensajes. 

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>Creación del primer informe de cumplimiento para incorporar ACAT

ACAT le permite centrarse en el cumplimiento de la aplicación o el entorno específico de una aplicación (por ejemplo, producción, almacenamiento provisional, etc.). Permite crear un **informe de cumplimiento** en el que puede definir el límite de cumplimiento en función de la infraestructura en la nube de la aplicación o del entorno específico de una aplicación.

> [!IMPORTANT]
> Dado que ACAT está en versión preliminar privada, no se puede buscar en Azure Portal directamente. Regístrese en el [programa de versión preliminar privada de ACAT](https://aka.ms/acat/private/signup) y obtenga acceso desde el equipo de soporte técnico.

- Busque e inicie ***App Compliance Automation Tool para Microsoft 365*** en Azure Portal.
- Vaya a ***Informes*** desde la izquierda.

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="Creación de un informe de cumplimiento":::
   Vaya a Informes para crear un nuevo informe de cumplimiento :::image-end:::

- Seleccione ***Crear nuevo informe*** para empezar a crear el primer informe de cumplimiento con la configuración adecuada. 
    - **Conceptos básicos**
        - **Nombre del informe**: el nombre del informe de cumplimiento es obligatorio y no se puede duplicar dentro del inquilino. Podría ser la combinación de números, alfabetos y caracteres de subrayado. Se recomienda usar un nombre significativo con el informe de cumplimiento, por ejemplo, que indique la aplicación o el entorno específicos.
        - **Tiempo de activación**: ACAT generará diariamente las evaluaciones de cumplimiento del informe de cumplimiento. Esta configuración se usa para especificar cuándo se debe desencadenar la generación. 
        - **Seleccionar suscripción**: en versión preliminar privada, ACAT le permite definir el ámbito del informe de cumplimiento eligiendo los recursos de Azure en una suscripción específica. Puede elegir la suscripción adecuada en función de la infraestructura en la nube. Si la suscripción de la aplicación no está en la lista, debe solicitar permiso al administrador. 
        - **Seleccionar recursos**: una vez especificada la suscripción, seleccione los recursos adecuados en función de la infraestructura en la nube. De forma predeterminada, todos los recursos se seleccionarán automáticamente. También puede buscar los recursos por filtros (por ejemplo, grupo de recursos, etiqueta, etc.) y, a continuación, seleccionar los recursos. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="Configuración básica":::
       Configuración básica para el informe de cumplimiento :::image-end:::

    - **Microsoft 365 certificación**: la configuración de certificación de Microsoft 365 es opcional durante la creación.  Se puede configurar más adelante una vez que empiece a publicar la aplicación.
        - **GUID de la oferta**: el GUID de la oferta es el identificador único de la oferta de Marketplace en [Microsoft Partner Network](https://partner.microsoft.com/dashboard). Seleccione *más información* para obtener instrucciones paso a paso sobre cómo obtener el identificador único.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365 configuración de certificación":::
       Configuración sobre la certificación de Microsoft 365:::image-end:::

Una vez que confirme la configuración y cree el informe de cumplimiento, ACAT recopilará automáticamente los datos relacionados con el cumplimiento de los orígenes siguientes. 

- Habilite el [Microsoft Defender for Cloud](https://azure.microsoft.com/services/defender-for-cloud/) (nivel gratis) para su suscripción. 
- Habilite algunas directivas personalizadas para su suscripción. 

> [!NOTE]
> Si la creación es correcta, ACAT comenzará a recopilar y generar las evaluaciones de cumplimiento del informe de cumplimiento a partir del día siguiente. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>Auditoría de las evaluaciones de cumplimiento con el informe de cumplimiento

Con ACAT, podría conocer el estado en tiempo de ejecución del informe de cumplimiento y auditar las evaluaciones de cumplimiento fácilmente. 

- Vaya a ***Informes*** desde la izquierda. Puede obtener un breve resumen de los informes de cumplimiento existentes.
    - **Estado en tiempo de ejecución**: el estado en tiempo de ejecución indica si ACAT sigue administrando el informe de cumplimiento correctamente en la última generación. Hay tres estados para el estado en tiempo de ejecución. 
        - **Activo**: el informe de cumplimiento se ejecuta de forma continua y correcta. 
        - **Error**: ACAT no ha podido generar las evaluaciones de cumplimiento para este informe de cumplimiento de la última generación. Este estado podría ocurrir por varias razones, por ejemplo, hay una configuración incorrecta en la suscripción para bloquear los datos de cumplimiento enrutados a ACAT, se produjo un error del sistema o una interrupción con ACAT, etc. 
        - **Deshabilitado**: este informe de cumplimiento está deshabilitado (en pausa) manualmente. Esta característica no está habilitada en versión preliminar privada. 
    - **Hora del último desencadenador** y **Hora del siguiente desencadenador**: ACAT generará diariamente las evaluaciones de cumplimiento para el informe de cumplimiento. *La hora del último desencadenador* indica cuándo se desencadenó la última generación y la *hora del desencadenador siguiente* indica la hora del desencadenador para la próxima generación. 
    - **Microsoft 365 certificación**: comprenda el estado del informe de cumplimiento de los controles de certificación de Microsoft 365. Los tres estados para el estado de cumplimiento de certificación Microsoft 365 incluyen:
        - **Pasado**: no hay errores en los controles de certificación de Microsoft 365 totalmente automatizados.
        - **Error**: se han detectado responsabilidades de clientes erróneas para los controles de certificación de Microsoft 365 totalmente automatizados.
        - **Manual**: este estado incluye dos tipos de controles: el *control manual parcial automatizado* , que está parcialmente automatizado por ACAT y todavía necesita algún esfuerzo manual para recopilar pruebas de cumplimiento, y el *control manual* que requiere un esfuerzo manual completo para recopilar pruebas de cumplimiento. ACAT automatiza partes de las responsabilidades del cliente para el control parcialmente automatizado. Puede usar el estado de cumplimiento de él como referencia, pero no puede usarlo para Microsoft 365 auditoría de certificación directamente.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="Lista de informes de cumplimiento":::
       Lista del informe de cumplimiento existente.
    :::image-end:::

Además de conocer el resumen de alto nivel de los informes de cumplimiento existentes, también puede auditar los detalles de la evaluación de cumplimiento con su equipo en ACAT. Para obtener los detalles de la evaluación de cumplimiento del informe de cumplimiento específico, haga clic en el nombre del informe. ACAT mostrará los detalles como se muestra a continuación.

- **Configuración**: puede cambiar la configuración del informe de cumplimiento con *Configuración*. En la versión preliminar privada, puede cambiar la configuración relacionada con la certificación de Microsoft 365. 
- **Descargar informe**: ACAT le permite descargar las evaluaciones del informe de cumplimiento como archivos csv en un formato que se puede compartir con los asociados para la colaboración.
    - **Inventario de infraestructura** en la nube: este archivo contiene los detalles de recursos de este informe de cumplimiento. Se podría usar para describir el inventario en la nube de la aplicación. 
    - **Microsoft 365 evaluación de cumplimiento de certificación**: este archivo incluye las evaluaciones de cumplimiento del informe de cumplimiento desde la vista del control de certificación de Microsoft 365. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="Barra de herramientas del informe de cumplimiento":::
    Barra de herramientas para el informe de cumplimiento.
:::image-end:::

- **Aspectos básicos**: esta sección indica el estado y la configuración del informe de cumplimiento. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="Aspectos básicos del informe de cumplimiento":::
    Aspectos básicos para el informe de cumplimiento.
:::image-end:::

- **Resultados de la evaluación**
    - El estado de cumplimiento del control de certificación Microsoft 365 se clasifica en cinco categorías. 
        - **Pasado**: no hay errores en los controles de certificación de Microsoft 365 totalmente automatizados.
        - **Error**: se han detectado responsabilidades de clientes erróneas para los controles de certificación de Microsoft 365 totalmente automatizados.
        - **Pasado: se necesitan pruebas adicionales**: no hay errores en los controles de certificación de Microsoft 365 parcialmente automatizados. Todavía debe recopilar pruebas adicionales para los controles manualmente.
        - **Error: se necesitan pruebas adicionales**: se han detectado responsabilidades erróneas del cliente para los controles de certificación de Microsoft 365 parcialmente automatizados.
        - **Control manual**: ACAT no automatiza ninguna responsabilidad del cliente por los controles de certificación de Microsoft 365. 
    - Las evaluaciones de cumplimiento están organizadas por Microsoft 365 familia y control de control de certificación. 
        - Para obtener más información sobre los detalles del control de cumplimiento y cómo recopilar pruebas de cumplimiento para el control manual, haga clic en el nombre del control. 
        - Al expandir el control totalmente automatizado y el control parcialmente automatizado, puede obtener más detalles de cumplimiento de la responsabilidad del cliente de ese control. 
        - Para cada responsabilidad del cliente, también podría detectar el estado de cumplimiento de los recursos relacionados y los pasos de corrección del recurso con errores haciendo clic en el botón de acción. 
            - **Recursos incorrectos**: debe seguir los pasos de corrección para corregir los recursos incorrectos. 
            - **Recursos no aplicables**: debe realizar un seguimiento del motivo de N/A para configurar los recursos y, a continuación, ACAT podría recopilar las evaluaciones de cumplimiento de los recursos.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="Evaluaciones de informes de cumplimiento":::
    Evaluaciones de cumplimiento para el informe de cumplimiento.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Uso del primer informe de cumplimiento con la auditoría de certificación de Microsoft r365

Antes de usar el informe de cumplimiento con Microsoft 365 certificación, debe configurar el GUID de la oferta para asociar el informe de cumplimiento a la oferta de Marketplace. Hay dos opciones: 

- Durante el proceso de creación del informe de cumplimiento, configure el GUID de la oferta en *Microsoft 365 pestaña de certificación*. 
- Si ya se ha creado el informe de cumplimiento, vaya a la *Configuración* de este informe de cumplimiento para configurar el GUID de la oferta.

Una vez configurado el GUID de la oferta, vaya a [Microsoft Partner Network](https://partner.microsoft.com/dashboard) para iniciar el cumplimiento de la aplicación. La *documentación inicial* es la primera fase de Microsoft 365 certificación. En esta fase, si elige *Sí* para la pregunta de si usa ACAT, puede elegir el informe de cumplimiento adecuado para esta auditoría. La certificación Microsoft 365 enviará automáticamente al auditor las evaluaciones de cumplimiento de los controles totalmente automatizados, lo que ahorrará tiempo y esfuerzo. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>Obtener información general de alto nivel de los informes de cumplimiento 

***La información general*** le proporciona una mejor comprensión del estado de alto nivel de los informes de cumplimiento. 

- **Estado en tiempo de ejecución del informe de** cumplimiento: esta información general le proporcionará la estadística del estado en tiempo de ejecución de los informes de cumplimiento.
    - **Activo**: el informe de cumplimiento se ejecuta de forma continua y correcta. 
    - **Error**: ACAT no ha podido generar las evaluaciones de cumplimiento de este informe de cumplimiento en la última generación. Este estado podría producirse por varias razones, por ejemplo, hay una configuración incorrecta en la suscripción para bloquear los datos de cumplimiento enrutados a ACAT, se produjo un error del sistema o una interrupción con ACAT, etc. 
    - **Deshabilitado**: este informe de cumplimiento está deshabilitado (en pausa) manualmente. Esta característica no está habilitada en versión preliminar privada. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="Introducción al estado en tiempo de ejecución":::
    Información general sobre el estado en tiempo de ejecución del informe de cumplimiento.
:::image-end:::

- **Informes de cumplimiento normativo activo**: esta información general le proporcionará la estadística de los resultados de cumplimiento de cada informe de cumplimiento *activo* .
    - **Pasado**: no hay errores en los controles de certificación de Microsoft 365 totalmente automatizados.
    - **Error**: se han detectado responsabilidades de clientes erróneas para los controles de certificación de Microsoft 365 totalmente automatizados.
    - **Manual**: este estado incluye dos tipos de controles: el *control manual parcial automatizado* , que está parcialmente automatizado por ACAT y todavía necesita algún esfuerzo manual para recopilar pruebas de cumplimiento, y el *control manual* que requiere un esfuerzo manual completo para recopilar pruebas de cumplimiento. ACAT automatiza partes de las responsabilidades del cliente para el control parcialmente automatizado. Puede usar el estado de cumplimiento de él como referencia, pero no puede usarlo para Microsoft 365 auditoría de certificación directamente.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="Introducción al estado de cumplimiento":::
    Información general sobre el estado de cumplimiento de los informes de cumplimiento activos.
:::image-end:::

## <a name="troubleshooting"></a>Solución de problemas 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>¿Por qué se ha producido un error en el informe de cumplimiento creado debido a un error de autorización? 

Al crear un informe de cumplimiento, ACAT configurará el entorno con su suscripción para recopilar los datos de cumplimiento automáticamente y esta acción requiere un permiso específico de la suscripción. Puede comprobar el permiso de suscripción como se indica a continuación. 

- Busque e inicie **las suscripciones** en [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
- Vaya a la suscripción que desea usar para crear el informe de cumplimiento. 
- Vaya al **control de acceso (IAM)** de la izquierda. 
- Seleccione **Ver mi acceso** para comprobar su permiso.
    - Si su organización usa [roles integrados de Azure](/azure/role-based-access-control/built-in-roles), las asignaciones de roles deben incluir al menos uno de los siguientes roles:
        - [Colaborador de la directiva de recursos](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) y [Administración de seguridad](/azure/role-based-access-control/built-in-roles#security-admin)
        - Otra asignación de roles que tiene permisos superiores (por ejemplo, [Propietario](/azure/role-based-access-control/built-in-roles#owner), etc.)

### <a name="how-to-report-an-acat-issue-or-warning"></a>¿Cómo notificar un problema o una advertencia de ACAT? 

Cuando se produce un problema en ACAT y desea ponerse en contacto con el [programa de versión preliminar privada de ACAT](mailto:acatprivatepreview@microsoft.com) para obtener ayuda, necesitamos su ayuda para recopilar las pruebas para comprender mejor su escenario.

- Obtener los detalles del error o advertencia de ACAT
    - Vaya a **Notificaciones** encima de [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Seleccione **Más eventos en el registro de actividad**. 
    
    
    
    - Cambiar a la **actividad de directorio** 
    - Cambie el **intervalo de tiempo** correctamente y establezca el **proveedor de recursos de inquilino** como *Microsoft.AppComplianceAutomation* para filtrar el error o la advertencia de ACAT en el registro de actividad. 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-log-settings.png" alt-text="Registro de actividad":::
        Busque registros de ACAT en registro de actividad.
    :::image-end:::

    - Descubra el error o advertencia de ACAT, seleccione esta opción para obtener los detalles y guardar los detalles como un archivo.
    
- Compruebe si ACAT ha configurado correctamente la suscripción. 
    - Busque e inicie **las suscripciones** en [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Vaya a la suscripción que desea usar para crear el informe de cumplimiento. 
    - Seleccione **Proveedor de recursos** para comprobar si el estado de estos proveedores es *Registrado*.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Volver a [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) e inicie **Resource Graph Explorador**.
    - Seleccione **Nueva consulta.**
    - Ejecute esta consulta para comprobar la asignación de directiva y descargar el resultado como CSV. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - Ejecute esta consulta para comprobar la automatización y descargar el resultado como CSV.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - Ejecute esta consulta para comprobar la evaluación y descargar el resultado como CSV. Debe reemplazar el marcador de posición ***your-subscriptionId*** por la suscripción específica que desea consultar.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```