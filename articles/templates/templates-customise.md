<!-- Filename: Help4.x:Templates:_Customise / Display title: Plantillas: Personalizar -->

## Descripción

La página de *Plantillas: Personalizar* se utiliza para editar el código fuente de una plantilla. Puedes crear sobreescrituras para archivos PHP y crear archivos user.css y user.js para añadir a las versiones del sistema. También puedes crear plantillas secundarias para permitir la edición de los archivos maestros de la plantilla sobreescrita.

## Cómo Acceder

- Selecciona **Sistema → Panel de Plantillas → Plantillas del Sitio** desde el menú del Administrador. O...
- Selecciona **Sistema → Panel de Plantillas → Plantillas del Administrador** desde el menú del Administrador. Luego...
  - Selecciona un nombre de plantilla de la columna **Plantilla**.

## Captura de Pantalla

Las pantallas de Plantillas del Administrador y del Sitio utilizan el mismo diseño. La pantalla de Plantilla del Sitio se ilustra aquí.

![personalizar plantillas cassiopeia pestaña del editor](../../../es/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Campos del Formulario

### Pestaña del Editor

- Selecciona un archivo para editar. El área de edición muestra texto con resaltado de sintaxis para la mayoría de los tipos de archivo.

### Pestaña de Crear Sobreescrituras

![personalizar plantillas cassiopeia pestaña de crear sobreescrituras](../../../es/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Selecciona un elemento para sobreescribir. Los elementos marcados con un ícono de archivo sólido se abren para revelar una lista de elementos. Los elementos marcados con íconos de página abierta y rellena superpuestos crean una sobreescritura inmediatamente sin pedir confirmación. La sobreescritura se coloca en la ubicación apropiada. Hay un mensaje de confirmación, por ejemplo:
  *Sobreescritura creada en /templates/cassiopeia/html/mod_whosonline*.

### Pestaña de Archivos Actualizados

![personalizar plantillas cassiopeia pestaña de actualizados](../../../es/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Si no ha habido actualizaciones en la plantilla desde que se crearon las sobreescrituras, esta pestaña contendrá un mensaje simple:

<div class="alert alert-success">
Los archivos sobreescritos están actualizados. No se han realizado cambios
en la última extensión o actualización de Joomla.
</div>

Si ha habido actualizaciones, una tabla mostrará una lista de sobreescrituras que necesitan ser revisadas.

### Pestaña de Descripción de Plantilla

![personalizar plantillas cassiopeia pestaña de descripción de plantilla](../../../es/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Miniatura y Descripción** Información sobre esta plantilla.

## Barra de Herramientas

Ten en cuenta que los botones de la Barra de Herramientas cambian cuando se selecciona un archivo para editar.

### Sin archivo seleccionado

En la parte superior de la página verás la barra de herramientas mostrada en la captura de pantalla anterior. Las funciones son:

- **Crear Plantilla Secundaria** Selecciona para crear una nueva plantilla secundaria completa. Se te pedirá un nuevo nombre para la plantilla secundaria. También hay una oportunidad para cerrar sin crear una nueva plantilla secundaria. Para eliminar la nueva plantilla secundaria: selecciona el botón **Cerrar**, selecciona el botón de Estilos en la Barra de Herramientas de la lista de Plantillas, marca la casilla de la plantilla secundaria nueva y selecciona Eliminar en la barra de herramientas.
- **Vista Previa de Plantilla** Selecciona para abrir la vista predeterminada del Sitio utilizando esta plantilla.
- **Administrar Carpetas** Selecciona para crear una nueva carpeta dentro de la jerarquía de plantillas. Aparece una ventana emergente. **Importante:** selecciona la carpeta en la que debe aparecer la nueva carpeta antes de crearla.
- **Nuevo Archivo** Selecciona para crear un nuevo archivo o para cargar un archivo desde tu computadora a la jerarquía de plantillas de Joomla. Aparece una ventana emergente. **Importante:** selecciona la carpeta en la que debe aparecer el nuevo archivo antes de crear el nuevo archivo.
- **Verificar Sobreescrituras** Activada cuando se selecciona una Sobreescritura en la pestaña *Sobreescrituras*. Las opciones son:
  - Marcar Como Comprobado
  - Marcar Como No Comprobado
  - Eliminar Registro
- **Cerrar** Cierra la pantalla actual y vuelve a la pantalla anterior sin guardar las modificaciones que hayas realizado. Este ícono de la barra de herramientas no se muestra si estás creando un nuevo elemento.
- **Ayuda** Abre esta pantalla de ayuda.

### Archivo seleccionado

- **Guardar** Guarda el elemento y permanece en la pantalla actual.
- **Guardar y Cerrar** Guarda el elemento y cierra la pantalla actual.
- **Renombrar Archivo** Selecciona un archivo para editar. Selecciona el botón Renombrar para solicitar un nuevo nombre.
- **Eliminar Archivo** Se te pedirá que Confirmes o Canceles.
- **Verificar Sobreescrituras** Activada cuando se selecciona una Sobreescritura en la pestaña *Sobreescrituras*.
- **Cerrar Archivo** Cierra el archivo abierto y vuelve a la Pestaña del Editor.
- **Ayuda** Abre esta pantalla de ayuda.

## Consejos

- Antes de editar el archivo HTML y el archivo CSS de la plantilla, es una buena idea hacer una copia de seguridad del archivo que estás editando. Además, puedes editar estos archivos fuera de Joomla utilizando el editor HTML o CSS de tu elección.
