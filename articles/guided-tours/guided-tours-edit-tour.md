<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour  / Display title: Visites Guidées : Modifier la Visite -->

## Descripción

Esta página se utiliza para agregar un nuevo Tour o editar un Tour existente. Un tour debe 
incluir al menos un paso. Una vez que se ha creado un nuevo tour, vaya a la lista de Tours 
y seleccione el botón con la etiqueta *0* de la columna de Pasos. El primer paso del tour se 
crea automáticamente a partir del título y la descripción del tour.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Publicación](jdocmanual?article=help/common-elements/edit-publishing).

## Cómo Acceder

- Selecciona **Sistema -> Administrar -> Recorridos Guiados** desde el menú del Administrador.
- Selecciona el botón de la barra de herramientas **Nuevo** para agregar un recorrido.
- Selecciona un **Título** de la lista para editar un recorrido.

## Captura de Pantalla

![Edición de Tours Guiados](../../../es/images/guided-tours/guided-tours-edit-tour.png)

## Campos del Formulario

- **Título** El Título de este tour. Si el título es una clave de idioma, se muestra un campo adicional, representando la traducción de esa clave para la configuración regional del usuario.
- **Identificador del Tour** Un identificador único para el tour. Al *Guardar* o *Guardar como Copia*, se proporciona un valor por defecto. Un formato sugerido sería *nombreautor-nombretour*, *nombrecompañia-nombretour* o *dominio-nombretour*. Este identificador tiene múltiples propósitos: iniciar un tour desde cualquier lugar (no solo desde el módulo de Tours Guiados), diferenciar tours que provienen de diferentes orígenes y, en sitios multilingües, dicta la estructura de nombres de archivos de idioma.

### Pestaña Editar Tour

#### Panel Izquierdo

- **URL Relativa** La ruta relativa obligatoria desde donde comienza el tour. Por ejemplo, para iniciar un tour desde la página del tour, ingrese `administrator/index.php?option=com_guidedtours&view=tours`.
- **Descripción** Aquí es donde se ingresa la descripción del tour. La descripción del tour puede ser una clave de idioma. Cuando este es el caso, un campo secundario presenta la descripción traducida de esa clave para la configuración regional del usuario.

#### Panel Derecho

- **Selector de Componente** El tour será visible prioritariamente en las páginas de las extensiones seleccionadas. Use *Todo* para mostrar el tour en todas las páginas. Cuando se establece en *Todo*, el tour se coloca al final de la lista de tours contextuales en el menú desplegable del módulo. Este es un campo obligatorio.
- **Inicio Automático** Permite que el tour comience automáticamente cuando un usuario alcanza el contexto en el cual se debe mostrar el tour.

## Consejos

- Hay 2 métodos para insertar una imagen en la descripción del tour usando el editor TinyMCE.
  1. La lista desplegable **Contenido CMS** proporciona acceso a la pantalla **Media** que te permite buscar archivos de imágenes y subir imágenes.
  2. La lista desplegable *Insertar* es un formulario simple para el cual necesitas saber la URL de la imagen. Se usa para imágenes externas.
- Hay 2 formas en las que se pueden crear tours para entornos multilingües:
  1. Crear un tour para cada idioma soportado.
  2. Crear un solo tour para todos los idiomas y usar claves de idioma para el título y la descripción.
- Usa **GUIDEDTOUR** en las claves de idioma como una convención donde se usen claves de idioma (para el título y la descripción).

*Traducido por openai.com*

