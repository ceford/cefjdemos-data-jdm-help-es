<!-- Filename: Help4.x:Banners:_Edit  / Display title: Bannières : Modifier -->

## Descripción

Se utiliza para agregar o editar banners que se pueden mostrar en tu sitio web de Joomla! Recuerda crear al menos un Cliente de Banner y una Categoría de Banner antes de crear cualquier Banner.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña de Publicación](jdocmanual?article=help/common-elements/edit-publishing).
* [El Popup de Historial de Versiones](jdocmanual?article=help/common-elements/edit-version-history).

## Cómo Acceder

Desde el menú de Administrador:
- Seleccione **Componentes → Banners** para ir a la página de lista de Banners.
- Seleccione el botón **Nuevo** en la Barra de herramientas para crear un nuevo Banner.
- Seleccione un **nombre** de Banner de la columna *Nombre* para editar un Banner existente.

## Captura de pantalla

Un banner puede ser una imagen clicable o algún código personalizado. El tipo de imagen se muestra en la captura de pantalla a continuación. El tipo personalizado tiene el cuadro de selección de imagen reemplazado por un área de texto de código.

![Pestaña de edición de detalles de banners](../../../es/images/banners/banners-edit-details-tab.png)

## Campos del Formulario

- **Nombre** El nombre del Banner. Este es el nombre que se mostrará
  en la columna *Nombre* de la lista de Banners.
- **Alias** El nombre interno del elemento. Normalmente, puedes dejar
  esto en blanco y Joomla rellenará un valor predeterminado derivado del Nombre pero
  en minúsculas y con guiones en lugar de espacios.

## Pestaña de Detalles

### Panel Izquierdo

- **Tipo** El tipo de banner a mostrar. Las opciones son un archivo de imagen o
  código HTML personalizado.
  - **Imagen** Archivo de imagen a mostrar para el banner. Haz clic en el botón 
    *Seleccionar* para buscar y seleccionar el archivo de imagen a usar. Utiliza 
    la página de Medios para cargar archivos de imagen de Banner en tu sitio. Las 
    imágenes para Banners deben estar en el directorio /images/banners/.
    - **Ancho** El ancho fijo para redimensionar la imagen del banner. Deja
      esto en blanco si deseas usar el ancho real del archivo de imagen del banner.
    - **Altura** La altura fija para redimensionar la imagen del banner. Deja
      esto en blanco si deseas usar la altura real del archivo de imagen del banner.
    - **Texto Alternativo** Texto a mostrar en lugar de la imagen del banner
      en el caso de que la imagen no pueda ser mostrada.
    - **Texto Alternativo** Texto alternativo para la imagen del Banner.
  - **Personalizado** Selecciona Personalizado si deseas ingresar un código
    personalizado para tu banner.
    - **Código Personalizado** Usa {CLICKURL} y {NAME} para fusionar los valores 
      'URL de clic' y 'Nombre' respectivamente en tu código personalizado. Por ejemplo:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`ingresa la URL de la imagen" alt="{NAME}" title="{NAME}"></a>`.
      Otra opción es ingresar un código HTML personalizado. Por ejemplo:<br>
      `<div class="tuclase"><a href=`&#34;`https://tudominio.com"><img src=`&#34;`ruta de tu imagen"></a></div>`
- **URL de Clic** La URL a la que navegar cuando el Usuario haga clic en el
  Banner.
- **Descripción** Ingresa una descripción para el Banner.

### Panel Derecho

- **Estado** El estado publicado del elemento.
- **Fijado** Si el Banner está *fijado* o no. Si uno o más Banners en una 
  Categoría son designados como *pegajosos*, tendrán prioridad sobre los Banner 
  que no sean pegajosos.
    - Por ejemplo, si dos Banners en una Categoría están fijados y un tercer Banner 
    no está fijado, el tercer Banner no se mostrará si la configuración del módulo 
    de visualización de Banners es *Fijado, Aleatorizar* o *Fijado, Ordenar*. Solo 
    se mostrarán los dos Banners fijados. Si los banners fijados tienen un número fijo 
    de impresiones, una vez que se usen esas impresiones, los banners fijados dejarán 
    de mostrarse, y los banners no fijados comenzarán a mostrarse automáticamente.
- **Idioma** Idioma del elemento.
- **Nota de Versión** Campo opcional para identificar esta versión del elemento
  en la ventana de Historial de Versiones del elemento.

### Pestaña de Detalles del Banner

![Pestaña de edición de detalles del banner](../../../es/images/banners/banners-edit-banner-details-tab.png)

- **Máx. Impresiones** El número de impresiones compradas para este
  Banner. Las impresiones son el número de veces que un Banner se mostrará
  en una página. Marca la casilla 'Ilimitado' si se permite un número ilimitado de
  impresiones.
- **Total de Impresiones** El número de veces que este Banner ha sido
  mostrado en una página web a un usuario. No se permite entrada. Puedes restablecer
  este número a 0 presionando el botón 'Restablecer impresiones'.
- **Total de Clics** El número de veces que se ha hecho clic en este Banner. No
  se permite entrada. Puedes restablecer este número a 0 presionando el
  botón *Restablecer clics*.
- **Cliente** El Cliente para este Banner. Selecciona uno de la lista desplegable
  de Clientes existentes.
- **Tipo de Compra:** El tipo de compra del banner. Esto se utiliza para
  indicar cómo el cliente del banner compró el tiempo de visualización del
  banner.
- **Rastrear Impresiones** Si se debe o no rastrear el número de veces que el
  banner se muestra a los visitantes del sitio web.
- **Rastrear Clics** Si se debe o no rastrear el número de veces que se hace clic
  en el banner por los visitantes del sitio web.

## Consejos

- Los banners se colocan en páginas específicas añadiendo Módulos de tipo *Banners* utilizando la lista de Módulos.
- Si tienes una serie de Banners que te gustaría mostrar en una o más páginas en orden aleatorio:
  1. Crea los Banners que deseas incluir, asegurándote de que tienen el mismo Cliente y Categoría.
  2. Crea un Módulo de Banner para este Cliente y Categoría, y en la Asignación de Menú elige las Selecciones de Menú para que el módulo se muestre.
  3. En el Módulo de Banner, establece el valor de *Aleatorizar* en *Fijado, Aleatorizar*.

  Con estos ajustes, los diferentes Banners para ese Cliente y Categoría se mostrarán en las páginas seleccionadas en orden aleatorio.

*Traducido por openai.com*

