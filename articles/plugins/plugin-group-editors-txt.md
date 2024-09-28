<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group  / Display title: Groupe des éditeurs -->

## Descripción del Grupo

Los plugins de editor ayudan a los usuarios a ingresar texto con marcado o diseños para propósitos especiales, como fragmentos de HTML o código. Para usar un Editor, el desarrollador de software marca el campo de entrada de datos como tipo `Editor`. Si no hay plugins de editor habilitados, se muestra como un simple campo de área de texto. Con uno o más plugins de editor habilitados, se usa el plugin predeterminado del sitio, configurado en la Configuración Global, a menos que sea anulado por el plugin preferido del usuario, configurado en el Perfil de Usuario. Joomla tiene los tres plugins de editor principales enumerados a continuación. También pueden estar disponibles plugins de editor de terceros adicionales. Algunos editores tienen una selección muy amplia de opciones.

### Editor - CodeMirror

El editor CodeMirror es un editor de código que proporciona un entorno más adecuado para el código fuente. Tiene resaltado de sintaxis de código para muchos lenguajes de programación. Puede mostrar etiquetas no coincidentes y también ayuda a mantener sangrías de código consistentes.

![Formulario de opciones de CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Números de lista** Mostrar números de línea en el editor.
- **Plegado de código** Permitir el plegado de bloques de código.
- **Canales laterales** Marcador de código y plegado de código.
- **Resaltar línea activa** Añade un resaltado a la línea donde se encuentra el cursor.
- **Resaltar coincidencias de selección** Resaltar instancias de la palabra seleccionada en todo el documento.
- **Etiquetas coincidentes** Resaltar etiquetas coincidentes.
- **Corchetes coincidentes** Resaltar corchetes coincidentes.
- **Autocompletar etiquetas** Autocompletar etiquetas automáticamente.
- **Autocompletar corchetes** Autocompletar corchetes automáticamente.
- **Mapa de teclas** Hacer que CodeMirror funcione como otros editores populares.
- **Alternar pantalla completa** Seleccionar la tecla de función para usar para alternar el modo de pantalla completa.
- **Usar modificadores** Seleccionar cualquier tecla modificadora para usar con la tecla de alternancia de pantalla completa.

![Formulario de opciones avanzadas de CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Tema** Establece los colores para el editor.
- **Color de línea activa** El color a usar para resaltar la línea activa. Se mostrará al 50% de opacidad.
- **Color de etiqueta coincidente** El color de fondo a usar para resaltar etiquetas coincidentes. Se mostrará al 50% de opacidad.
- **Fuente** La fuente a usar en el editor. Si no está instalada, se cargará desde https://www.google.com/fonts/.
- **Tamaño de fuente (px)** El tamaño de la fuente en el editor.
- **Altura de línea (em)** La altura de una línea de texto. Esto está en ems, lo que significa que 1.0 es igual al tamaño de la fuente y 2.0 es igual a 2x el tamaño de la fuente.
- **Estilo de barra de desplazamiento** Seleccionar el estilo de barra de desplazamiento que te gustaría que CodeMirror use.
- **Vista previa** Un ejemplo de cómo se verán tus campos de editor CodeMirror con la configuración actual (guardar para actualizar).

### Editor - Ninguno

Este plugin carga un editor de texto básico. Esta opción se puede usar cuando estás pegando código HTML desde otra fuente y no deseas que el HTML sea alterado por un editor WYSIWYG. Este plugin no tiene opciones.

### Editor - TinyMCE

El editor TinyMCE es un editor WYSIWYG y es el editor predeterminado para la entrada de HTML en Joomla!.

![Formulario de opciones del plugin TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Tabulación de selección predeterminada** Selecciona *Set 2*, *Set 1* o *Set 0* funcionalidad. Con *Set 2* seleccionado, verás el editor para uso *Público*. *Set 1* seleccionado es el predeterminado para Managers y Registrados, *Set 0* seleccionado es el predeterminado para Administradores, Editores y Super Usuarios.

Cada pestaña tiene una lista larga de opciones que no se ilustran aquí. La siguiente lista es una selección.

- **Piel del sitio** Elige la piel que se aplicará al editor TinyMCE cuando se muestre en tu sitio web.
- **Piel del administrador** Elige la piel que se aplicará al editor TinyMCE cuando se muestre en tu Backend de Administrador.
- **Modo de barra de herramientas** Controla cómo se muestran los botones de la barra de herramientas que no están en la primera fila.
- **Arrastrar y soltar imágenes** Habilitar arrastrar y soltar para subir imágenes.
- **Directorio de imágenes** El directorio con los archivos de imágenes que se listarán en relación con la carpeta de imágenes predeterminada (configurada en Medios > Opciones).
- **Codificación de entidad** Controla cómo se codifican las entidades HTML. La configuración recomendada es `raw`. `named` = usar codificación de entidad con nombre (por ejemplo, `<`). `numeric` = usar codificación HTML numérica (por ejemplo, `%03c`). raw = No codificar entidades HTML. Ten en cuenta que la búsqueda de contenido puede no funcionar correctamente si la configuración no es `raw`.
- **Selección automática de idioma** Si se establece en Sí, el idioma del editor coincidirá automáticamente con el idioma de la interfaz de usuario seleccionada. Si no existe el micro-idioma, el idioma del editor será predeterminado en inglés.
- **Dirección del texto** Si el idioma se lee *De Izquierda a Derecha* o *De Derecha a Izquierda* (por ejemplo, como el árabe). El valor predeterminado es *De Izquierda a Derecha*.
- **Clases CSS de la plantilla** Si se debe cargar o no el archivo *editor.css*. Si no se encuentra dicho archivo para la plantilla predeterminada, se usa el archivo *editor.css* de la plantilla del sistema. El valor predeterminado es *Sí*.
- **Clases CSS personalizadas** Ruta URL completa opcional a un archivo CSS personalizado. Si se ingresa, esto anula la configuración de Clases CSS de la plantilla.
- **URLs** Si se deben usar URLs Relativas o Absolutas para los enlaces. El valor predeterminado es *Relativa*.
- **Nuevas líneas** Si se deben interpretar las nuevas líneas como *Elementos P* o *Elementos BR*. El valor predeterminado es *Elementos P*.
- **Usar filtro de texto de Joomla** Si está activado, se aplica el filtro de texto de la Configuración Global de Joomla para cada grupo de usuarios. Si está desactivado, se usan los filtros definidos aquí para todos los grupos de usuarios.
- **Elementos prohibidos** Los elementos que se eliminarán del texto. El valor predeterminado es *applet*, lo que eliminará los elementos de applet del texto.
- **Elementos válidos** Define qué elementos permanecerán en el texto editado cuando el editor guarde (el conjunto de reglas predeterminado para esta opción es una mezcla de las especificaciones completas de HTML5 y HTML4).
- **Elementos válidos extendidos** Lista opcional de elementos HTML válidos para agregar al conjunto de reglas existente.
- **Redimensionado** Habilitar/deshabilitar el redimensionado del área del editor (verticalmente y también horizontalmente si el *Redimensionado Horizontal* está habilitado).
- **Redimensionado Horizontal** Habilitar/deshabilitar el redimensionado horizontal.
- **Ruta del elemento** Si se establece en ON, muestra las clases configuradas para el texto marcado.
- **Recuento de palabras** Activar/desactivar el recuento de palabras.
- **Markdown** Permitir el uso de sintaxis de estilo Markdown para crear enlaces, listas y otros estilos. Esta sintaxis especial se convierte y guarda como html regular. Por ejemplo, el usuario puede escribir # texto para producir un encabezado o **texto** para poner el texto en negrita.
- **Imagen avanzada** Activar/desactivar un cuadro de diálogo de imagen más avanzado.
- **Lista avanzada** Activar/desactivar la capacidad de establecer formatos de número y tipos de viñetas en listas ordenadas y desordenadas.
- **Menú contextual** Activar/desactivar el menú contextual.
- **Plugin personalizado** Agregar plugins personalizados de TinyMCE al editor especificándolos aquí.
- **Botón personalizado** Agregar botones personalizados de TinyMCE al editor especificándolos aquí.

#### Pestaña avanzada de TinyMCE

![Formulario de opciones avanzadas de TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Número de conjuntos** Número de conjuntos que se pueden crear. Mínimo 3.
- **Altura HTML** La altura, en píxeles, de la ventana emergente del modo HTML.
- **Ancho HTML** El ancho, en píxeles, de la ventana emergente del modo HTML.

*Traducido por openai.com*

