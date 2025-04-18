<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Tareas programadas -->

## Descripción

Las Tareas Programadas se utilizan para ejecutar tareas de mantenimiento rutinario del sitio como una alternativa a los trabajos cron del servidor. Las tareas se definen en los complementos del grupo de tareas. Se suministran varios complementos de tareas que pueden utilizarse como ejemplos para crear otras tareas especializadas.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de columnas de lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo acceder

A partir del menú del Administrador:

- Seleccione **Sistema → Administrar panel → Tareas programadas**

La lista inicial de Tareas Programadas tiene tres elementos.

## Captura de pantalla

![scheduled tasks list](../../../es/images/maintenance/scheduled-tasks-list.png)

## Encabezados de columna

Columnas únicas para tareas programadas:

- **Tipo de Tarea** Las tareas se crean a partir de una lista disponible de tipos.
- **Fecha de Última Ejecución** La fecha y hora de la última ejecución de la tarea.
- **Fecha de Próxima Ejecución** La fecha y hora de la próxima ejecución de la tarea.
- **Probar Tarea** Un botón para ejecutar la tarea manualmente.
- **Prioridad de la Tarea** La prioridad puede ser Baja, Normal o Alta. Las tareas de mayor prioridad pueden potencialmente bloquear tareas de menor prioridad.

## Historial de Ejecución

Seleccione el botón en la barra de herramientas para ver una lista de ejecuciones de tareas individuales.

![task execution history list](../../../es/images/maintenance/scheduled-tasks-logs.png)

## Tareas Disponibles

La siguiente captura de pantalla muestra una lista de tareas disponibles. Algunas son demostraciones, otras son útiles.

![Scheduled Tasks Available](../../../es/images/maintenance/scheduled-tasks-types.png)

Cada tarea tiene sus propios parámetros relacionados que deberían ser autoexplicativos. Por ejemplo, la tarea **Sitio Fuera de Línea** solo tiene sentido si la **Editar Tarea → Campos Básicos → Regla de Ejecución** está configurada en **Ejecución Manual**.

## Opciones de tareas programadas

Seleccione el botón de Opciones en la Barra de herramientas para configurar tareas programadas.

### Configurar pestaña de Tareas

![task timeout setting](../../../es/images/maintenance/scheduled-tasks-options-configure-tasks.png)

- **Tiempo de Tarea Excedido** El valor predeterminado es de 300 segundos.

### Pestaña de Programador Perezoso

![lazy schedule setting](../../../es/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- Las tareas **habilitadas** son activadas por los visitantes del sitio.
- Las tareas **deshabilitadas** deben ser activadas por un trabajo de cron externo.
- **Intervalo de solicitud** El valor predeterminado es 300 segundos.

### Pestaña de Cron web

![web cron setting](../../../es/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Web Cron** Desactivado es el valor predeterminado. Activado requiere un hash para activar la tarea. Antes del primer guardado, hay un mensaje de que se necesita una clave. Después de guardar, hay un campo que contiene una URL de enlace de Webcron para copiar.

*Traducido por openai.com*

