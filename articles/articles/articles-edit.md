<!-- Filename: Help4.x:Articles:_Edit / Display title: Artículos: Editar -->

## Descripción

Esta página se utiliza para añadir un nuevo artículo o editar un artículo existente, normalmente utilizando un editor Wysiwyg. El editor predeterminado es TinyMCE, pero si se instalan otros editores, el editor predeterminado puede configurarse para ser otro, ya sea para todo el sitio o para usuarios individuales.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de Ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [La Pestaña Publicación](jdocmanual?article=help/common-elements/edit-publishing).
* [La Pestaña Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La Pestaña Permisos](jdocmanual?article=help/common-elements/edit-permissions).
* [El popup del historial de versiones](jdocmanual?article=help/common-elements/edit-version-history).

O en artículos de usuario:

* [Añadir una Imagen a un Artículo](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Cómo Acceder

* Selecciona **Contenido → Artículos** desde el menú del Administrador. O...
* Selecciona **Artículos** desde el Tablero de Inicio. Luego...
    * Selecciona un **Título** de artículo existente en la lista para editarlo. O...
    * Selecciona el botón **Nuevo** en la Barra de Herramientas para crear un nuevo artículo.
También puedes crear un nuevo artículo seleccionando el icono **+** en el Menú o en el Tablero de Inicio.

## Captura de Pantalla

![Captura de pantalla de edición de artículos](../../../es/images/articles/articles-edit-content-tab.png)

## Campos del Formulario

- **Título** El Título de este artículo.
- **Alias** El nombre interno de este artículo. Normalmente, puedes dejar este campo en blanco y Joomla completará un valor predeterminado basado en el Título, pero en minúsculas y con guiones en lugar de espacios.

### Pestaña Contenido

#### Panel Izquierdo

- **Texto del Artículo** Aquí es donde ingresas el contenido del artículo.
    Joomla incluye 3 editores, el editor predeterminado - TinyMCE,
    se muestra arriba.

    El menú desplegable de Contenido CMS proporciona acceso para enlazar con un Artículo,
    Contacto, Campo, Imagen de Medios, Menú, Módulo, Salto de Página o un salto Leer Más.

    El símbolo de elipsis (<span class="icon-ellipsis-h"></span>) alterna la visibilidad de herramientas adicionales.
- **Alternar Editor** El botón debajo de la ventana de edición te permite alternar
    entre el editor TinyMCE y sin editor. Esto te permite ver y, a veces, corregir el código HTML.

#### Panel Derecho

- **Estado** El estado de publicación de este artículo.
  - *Publicado* El artículo es visible en el Frontend del sitio.
  - *Despublicado* El artículo no será visible para los invitados en el
    Frontend del sitio. Puede ser visible para los usuarios conectados que tienen
    permiso para editar el estado del artículo.
  - *Archivado* El artículo ya no se mostrará en los elementos de menú o en la Lista de Categorías.
  - *En la Papelera* El artículo está eliminado del sitio pero sigue en la base de datos.
- **Categoría** Selecciona la Categoría para este artículo.
- **Destacado** Selecciona Sí si el artículo se mostrará en el elemento de menú Destacado.
- **Acceso** Selecciona el nivel de acceso de visualización para este artículo. Los niveles de acceso dependen de lo que se haya configurado en Usuarios: Niveles de Acceso.
- **Idioma** Selecciona el idioma para este artículo. Mantén el valor predeterminado de 'Todos' si no estás utilizando la función multilingüe.
- **Etiquetas** Asigna etiquetas a este artículo. Puedes seleccionar una etiqueta de una
  lista predefinida o
  ingresar una nueva etiqueta escribiendo el nombre en el campo y presionando Enter.
- **Nota** Esto es normalmente para el uso del administrador (por ejemplo,
  para documentar información sobre este artículo) y no se muestra en el
  Frontend.
- **Nota de Versión** Campo opcional para identificar la versión de este
  artículo en el Historial de Versiones del artículo.

### Pestaña Imágenes y Enlaces

**Nota:** Esta pestaña puede estar oculta en *Artículo: Opciones* por un usuario con
permisos de Administrador. Permite la visualización de imágenes y enlaces en los artículos usando
diseños estandarizados.

![Editar artículos pestaña de imágenes y enlaces](../../../es/images/articles/articles-edit-images-tab.png)

#### Imagen Introductoria

- **Imagen Introductoria** Haz clic en el botón Seleccionar para elegir una imagen que se mostrará
  en una ubicación fija en el Texto de Introducción de este artículo. Esto
  abrirá una ventana que permite seleccionar una imagen de la carpeta de imágenes.
- **Descripción de la Imagen (Texto Alternativo)** Establece el atributo alt para esta
  imagen. Unas pocas palabras descriptivas para lectores de pantalla.
- **Sin Descripción** Marca esta opción en el raro caso de una imagen puramente decorativa. Ten en cuenta que si la Descripción de la Imagen está vacía y la casilla Sin Descripción no está marcada, la imagen no cumplirá con los criterios de accesibilidad. Si hay una descripción de la imagen, esta casilla no tiene efecto.
- **Clase de Imagen** Agrega cualquier clase CSS para un estilo personalizado.
  Por ejemplo, para la posición de la imagen, usa float-start o float-end.
- **Leyenda** Crea una leyenda para esta imagen.

#### Imagen Completa del Artículo

- **Imagen Completa del Artículo** Haz clic en el botón Seleccionar para elegir una imagen que se mostrará en una ubicación fija en el Texto Completo de este artículo. Esto abrirá una ventana que permite seleccionar una imagen de la carpeta de imágenes.
- **Descripción de la Imagen (Texto Alternativo)** Establece el atributo alt para esta
  imagen. Unas pocas palabras descriptivas para lectores de pantalla.
- **Sin Descripción** Marca esta opción en el raro caso de una imagen puramente decorativa. Ten en cuenta que si la Descripción de la Imagen está vacía y la casilla Sin Descripción no está marcada, la imagen no cumplirá con los criterios de accesibilidad. Si hay una descripción de la imagen, esta casilla no tiene efecto.
- **Clase de Imagen** Agrega cualquier clase CSS para un estilo personalizado.
  Por ejemplo, para la posición de la imagen, usa float-start o float-end.
- **Leyenda** Ingresa una leyenda opcional para esta imagen.

#### Enlace A

- **Enlace A** La URL del primer enlace que se mostrará en una ubicación fija en el texto del artículo. Esta debe ser una URL completa, no relativa. Por ejemplo, normalmente comenzaría con `https:`.
- **Texto del Enlace A** El texto utilizado para el Enlace A. Si está en blanco, se mostrará la URL.
- **Ventana de Destino de la URL** Establece el valor predeterminado para el destino del primer Enlace en este artículo. Las opciones son:
  - *Abrir en la ventana principal* Abre en la ventana principal del navegador, reemplazando el artículo actual de Joomla.
  - *Abrir en una nueva ventana* Abre el enlace en una nueva ventana del navegador.
  - *Abrir en ventana emergente* Abre el enlace en una ventana emergente del navegador (sin controles completos de navegación).
  - *Modal* Abre el enlace en una ventana emergente modal.

#### Enlace B, Enlace C

- Mismas opciones que el Enlace A.

### Pestaña Opciones

**Nota**: Esta pestaña puede estar oculta por un usuario con permisos de Administrador en las
Opciones del Artículo. Es un conjunto de opciones que se utilizan para controlar cómo se
mostrará este artículo en el Frontend.

![Pestaña Opciones](../../../es/images/articles/articles-edit-options-tab.png)

#### Diseño

- **Diseño** Usa un diseño de la vista de artículo proporcionada o anula en las plantillas.
- **Título** Mostrar el Título del Artículo.
- **Títulos Enlazados** Mostrar el título como un enlace al artículo.
- **Etiquetas** Ingresa etiquetas para este artículo. Selecciona etiquetas existentes ingresando las primeras letras o crea nuevas etiquetas ingresándolas aquí.
- **Texto de Introducción**
  - *Mostrar* El Texto de Introducción del artículo se mostrará en una página que muestra el
    artículo completo.
  - *Ocultar* Solo la parte del artículo después del salto Leer Más
    se mostrará en una página que muestra el artículo completo.
- **Posición de la Información del Artículo**
  - *Arriba* Coloca el bloque de información del artículo encima del texto.
  - *Abajo* Coloca el bloque de información del artículo debajo del texto.
  - *Dividido* Divide el bloque de información del artículo en 2 bloques separados.
    Un bloque está arriba y el otro está abajo del texto.
- **Título de la Información del Artículo** Muestra 'Detalles' en la parte superior del bloque de información del artículo.

#### Categoría

- **Categoría** Mostrar el Título de la Categoría del Artículo.
- **Enlace a la Categoría** Mostrar el título como un enlace a esa Categoría.
- **Categoría Padre** Mostrar el Título de la Categoría Padre del Artículo.
- **Enlace a la Categoría Padre** Mostrar el título como un enlace a esa Categoría.

#### Asociaciones

- **Asociaciones** Mostrar las banderas asociadas o el Código de Idioma.
  Solo multilingüe.

#### Autor

- **Autor** Mostrar el autor del Artículo.
- **Enlace a la Página de Contacto del Autor** Mostrarlo como un enlace a un diseño de Contacto para ese autor. Nota: El autor debe estar configurado como un Contacto.

#### Fecha

- **Fecha de Creación** Mostrar la fecha de creación del Artículo.
- **Fecha de Modificación** Mostrar la fecha de modificación del Artículo.
- **Fecha de Publicación** Mostrar la fecha de inicio de la publicación del Artículo.

#### Opciones

- **Navegación** Mostrar los enlaces de navegación, *Anterior* y/o *Siguiente*, cuando
  se muestra una página que contiene el artículo completo.
- **Visitas** Mostrar el número de veces que el artículo ha sido mostrado por un usuario.
- **Enlaces No Autorizados** Si se selecciona Sí, se mostrará el Texto de Introducción de los artículos restringidos. Al hacer clic en el enlace Leer más, los usuarios deberán iniciar sesión
  para ver el contenido completo del artículo.
- **Posición de los Enlaces**
  - *Arriba* Los enlaces se muestran encima del contenido.
  - *Abajo* Los enlaces se muestran debajo del contenido.
- **Texto de Leer Más** Personaliza el texto que se muestra en lugar de la redacción predeterminada 'Leer más'.
- **Título de la Página del Navegador** Texto para el título de la página del navegador que se utilizará
  cuando el artículo se vea con un elemento de menú no relacionado con artículos. Si está en blanco, se utilizará el título del artículo.

### Pestaña Campos

Esta sección muestra los campos personalizados que están definidos para este artículo. Estos
son campos que no están asignados a un Grupo de Campos. Cada Grupo de Campos, si está definido,
aparecerá como una pestaña separada.

![Pestaña de Campos](../../../es/images/articles/articles-edit-fields-tab.png)


### Pestaña Configurar Pantalla de Edición

**Nota:** Esto puede estar oculto por un usuario con permisos de Administrador en las
Opciones del Artículo.

![Pestaña Configurar pantalla de edición](../../../es/images/articles/articles-edit-editor-tab.png)

- **Opciones de Publicación** Si se selecciona Ocultar, la pestaña de Opciones de Publicación
  no se mostrará en el Backend. Esto significa que los usuarios del Backend no
  podrán editar los campos en esta pestaña. Estos campos siempre estarán
  configurados con sus valores predeterminados.
- **Opciones del Artículo** Si se selecciona Ocultar, la pestaña de Opciones del Artículo
  no se mostrará en el Backend. Esto significa que los usuarios del Backend no
  podrán editar los campos en esta pestaña. Estos campos siempre estarán configurados
  con sus valores predeterminados.
- **Imágenes y Enlaces del Administrador** Si se selecciona Sí, se mostrará la pestaña de Imágenes y Enlaces.
- **Imágenes y Enlaces del Frontend** Si se selecciona Sí, la pestaña de Imágenes y Enlaces se mostrará en la pantalla del editor de artículos del Frontend.

## Consejos

- Hay 2 métodos para insertar una imagen en un artículo utilizando el editor TinyMCE.
  1. La lista desplegable *Contenido CMS* proporciona acceso a la pantalla de Medios.
  2. La lista desplegable *Insertar* es un formulario simple que requiere la URL de la imagen.
    Se utiliza para imágenes externas.
- Un inserto *Leer Más* ahorra espacio en cualquier página de diseño de Destacados o Blog mostrando solo la primera parte de un Artículo. Los insertos de *Salto de Página* proporcionan navegación multipágina para artículos largos. Ambos pueden usarse en un solo artículo si se desea. Por ejemplo, un salto *Leer Más* podría colocarse después del primer párrafo y los saltos de *Salto de Página* podrían colocarse después de otros grupos de párrafos para crear un artículo de varias páginas. No se mostraría ninguna navegación en la página de Destacados o Blog hasta que el Usuario seleccione el enlace Leer más. En ese momento, se mostraría el índice del artículo mostrando enlaces a cada página.
