<!-- Filename: Help4.x:Editors / Display title: Editor -->

## TinyMCE

TinyMCE es el editor predeterminado para los usuarios del Frontend y del Backend.
El editor ofrece a los usuarios una interfaz familiar de procesamiento de texto al editar contenido.

TinyMCE se puede configurar con 3 conjuntos diferentes de botones en la barra de herramientas.
Esto se establece en el plugin **Editor - TinyMCE**.

### Barras de herramientas

#### Configuración simple

El conjunto de barra de herramientas 2 proporciona una fila de botones como se muestra a continuación.

Este conjunto está asignado por defecto al grupo de usuarios **Público**.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/600px-Help-4x-editor-tinymce-simple-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/900px-Help-4x-editor-tinymce-simple-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/1200px-Help-4x-editor-tinymce-simple-en.png 2x"
data-file-width="1451" data-file-height="80" width="600" height="33"
alt="editor tinymce simple" />

- Los botones permiten aplicar al texto: **negrita**, **subrayado** o **tachado**.
- **Deshacer** y **Rehacer**.
- Lista **no ordenada**, lista **ordenada**.
- **Pegar como texto**: A menudo, al copiar y pegar texto desde otras fuentes, como archivos PDF, documentos de texto o páginas web, el texto seleccionado
  contiene información de formato que no se necesita o no se desea. Usar
  la opción **"Pegar como texto"** eliminará todo el formato del texto.

#### Configuración media

El conjunto de barra de herramientas 1 proporciona dos filas de botones como se muestra a continuación.

Este conjunto está asignado por defecto a los grupos de usuarios **Manager** y **Registered**.

<img
src="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/800px-Help-4x-editor-tinymce-advanced-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1200px-Help-4x-editor-tinymce-advanced-en.png 1.5x, https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1600px-Help-4x-editor-tinymce-advanced-en.png 2x"
data-file-width="1977" data-file-height="236" width="800" height="95"
alt="editor tinymce advanced" />

Esta opción proporciona todos los mismos botones documentados en la
**Barra de herramientas del Conjunto 2** mencionada anteriormente.
Además, se encuentran disponibles las siguientes opciones.

#### Fila superior

* **Contenido del CMS**: La lista desplegable proporciona acceso para enlazar a un
  **Artículo**, **Contacto**, **Campo**, **Medios**, **Menú** o **Módulo**.

**Artículo**: El ejemplo muestra cómo crear fácilmente un enlace a cualquier artículo
del sitio actual.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/600px-Help-4x-article-quick-link-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/900px-Help-4x-article-quick-link-button-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/1200px-Help-4x-article-quick-link-button-en.png 2x"
data-file-width="2304" data-file-height="1321" width="600" height="344"
alt="article quick link button" />

Para crear un enlace al artículo deseado:

* Coloca el cursor en el punto del artículo donde quieres que se inserte
  el título del artículo enlazado.
* Haz clic en el botón **Artículo** para abrir la ventana.
* Haz clic en el título para seleccionar el artículo deseado en la ventana.
  Puedes usar la búsqueda y los filtros para ayudarte a encontrar el artículo que buscas.
* Se insertará un enlace con el título del artículo en la ubicación actual del cursor.
* Si es necesario, puedes editar el texto del enlace.

Del mismo modo, puedes enlazar otros elementos como **Medios**, **Módulos**, etc.

**Salto de página**: Este botón permite insertar un salto de página dentro de un artículo.
Un salto de página permite la navegación por páginas cuando el artículo se muestra
en un diseño. Esto es útil para artículos largos.
Cuando se presiona este botón, se muestra una ventana como la que se muestra a continuación:

<img
src="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/600px-Help-4x-editor-pagebreak-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/900px-Help-4x-editor-pagebreak-button-en.png 1.5x, https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/1200px-Help-4x-editor-pagebreak-button-en.png 2x"
data-file-width="1542" data-file-height="862" width="600" height="335"
alt="editor pagebreak button" />

- **Título**. Escribe el título de la nueva página (por ejemplo, 'Página
  2').
- **Tabla de contenido del alias**. Campo opcional para mostrar en la
  tabla de contenidos de esta página. En un artículo multipáginas,
  Joomla! muestra una especie de 'tabla de contenidos' de forma tal que
  el usuario pueda navegar por las distintas páginas del artículo. Si se
  deja en blanco este campo, se usará el título de la página. Si deseas
  un título distinto para la tabla de contenidos, escríbelo aquí.
- **Insertar un salto de página**. Haz clic en este botón para insertar
  el salto de página, este se mostrará como una linea punteada gris a lo
  ancho del artículo. Ten en cuenta que un salto de página no puede ser
  editado, si necesitas modificar algo del salto de página, deberás
  borrarlo ubicando el cursor después de este y presionando la tecla
  Retroceso (Backspace) hasta cuando este se borre, a continuación
  podrás insertar un nuevo salto de página con la información deseada.
- La configuración se establece en el plugin **Contenido - Salto de página**.

**Leer más**: Este botón inserta una marca de **Leer más** en el artículo.
Esto se muestra como una línea de puntos roja a lo largo del artículo.

* Si un artículo tiene una marca de **Leer más**, solo se mostrará inicialmente el texto anterior a la marca,
  llamado **Texto de introducción**, junto con un enlace de **Leer más**.
  Si el usuario hace clic en este enlace, se mostrará el artículo completo o solo la parte después del salto,
  dependiendo de la configuración de los parámetros de **Texto de introducción** del artículo.
* La marca de **Leer más** te permite ahorrar espacio en las páginas mostrando solo el **Texto de introducción**.
* Si deseas insertar saltos para un artículo que se muestra en un diseño de artículo, utiliza el botón **Salto de página**.

Los botones en la lista desplegable de contenido CMS pueden deshabilitarse en
**Plugins - editors-xtd**.

* Los botones en la parte superior izquierda permiten aplicar al texto: **cursiva**.
  A continuación, hay botones para **alinear a la izquierda**, **derecha**, **centrar** y **justificar**.
* **Formatos**: Selecciona formatos predefinidos para **Encabezados**, **Inline**, **Bloques**, etc.
* **Disminuir sangría** (mover a la izquierda) y **Aumentar sangría** (mover a la derecha).
* **3 puntos**: Muestra la segunda fila de la barra de herramientas.

#### Configuración media: Segunda fila

* **Insertar/editar enlace**: Para insertar o editar un enlace, selecciona el texto enlazado y presiona este botón.
  Se mostrará un cuadro emergente donde puedes ingresar los detalles del enlace.
* **Eliminar enlace**: Para eliminar un enlace, selecciona el texto enlazado y presiona este botón.
* **Ancla**: Una ancla es un marcador dentro de un artículo que te permite enlazar directamente a ese punto del artículo.
* **Código fuente**: Se muestra una ventana emergente con el código fuente HTML, lo que permite editar directamente el código.
* **Insertar una línea horizontal**: Para insertar una línea horizontal, coloca el cursor en la ubicación deseada
  dentro del artículo y haz clic en este botón.
* **Tabla**: Insertar nueva tabla, propiedades de la fila, propiedades de la celda,
  insertar fila antes, insertar fila después, eliminar fila, insertar columna antes, insertar columna después,
  eliminar columna, dividir celdas combinadas, combinar celdas.
* **Subíndice**, **Superíndice**, **Carácter especial**.
* **Vista previa del texto en una ventana emergente**.

#### Configuración avanzada

El conjunto de barra de herramientas 0 proporciona las opciones de edición más completas, como se muestra a continuación.
Este conjunto está asignado por defecto a los grupos de usuarios **Administrador**, **Editor** y **Super Usuarios**.

<img
src="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/800px-Help-4x-editor-tinymce-extended-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1200px-Help-4x-editor-tinymce-extended-en.png 1.5x, https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1600px-Help-4x-editor-tinymce-extended-en.png 2x"
data-file-width="1977" data-file-height="393" width="800" height="159"
alt="editor tinymce extended" />

Esta opción proporciona todos los mismos botones documentados en la
**Barra de herramientas del Conjunto 1** mencionada anteriormente.
Además, se encuentran disponibles las siguientes opciones.

#### Fila superior

* **Bloques**: Párrafo, Encabezados, Preformateado.
* **Fuentes**: Selecciona la fuente deseada.
* **Tamaño de fuente**: Selecciona el tamaño de fuente deseado.
* **Buscar y reemplazar**.
* **Insertar/editar imagen**: Para insertar una imagen, coloca el cursor en la ubicación deseada y presiona este botón.
  Se mostrará un cuadro emergente que te permitirá ingresar la fuente, ancho, alto y otra información sobre la imagen.

#### Segunda fila

* Seleccionar **color del texto** o **color de fondo**.
* **Pantalla completa**.
* **Emoticones**.
* **Insertar medios**: Para insertar medios, coloca el cursor en la ubicación deseada y presiona este botón.
  Se mostrará un cuadro emergente que te permitirá ingresar el tipo, archivo o URL, y otra información sobre el medio.
* **Dirección de izquierda a derecha** o **de derecha a izquierda**: Estos botones permiten ingresar o cambiar
  la dirección del texto, por ejemplo para idiomas que se leen de derecha a izquierda.
* **Cortar**, **Copiar**, **Pegar**.
* **Mostrar caracteres invisibles** (como finales de párrafo).
* **Mostrar bloques**.
* **Espacio no separable**.
* **Cita en bloque**.
* **Insertar plantilla**.

#### Tercera fila

* **Imprimir** el texto del artículo.
* **Insertar/editar fragmento de código**.
* **Insertar fecha/hora**.
* **Borrar formato**.

### Accesibilidad

TinyMCE es compatible con lectores de pantalla como <a href="https://www.freedomscientific.com/products/software/jaws/"  
rel="nofollow noreferrer noopener">JAWS</a> y <a href="https://www.nvaccess.org/"  
rel="nofollow noreferrer noopener">NVDA</a>.
Puedes usarlo de manera efectiva incluso si no usas el ratón.

#### Atajos de teclado

|                                           | PC                         | macOS                      |
| ----------------------------------------- | -------------------------- | -------------------------- |
| **Tarea**                                 | **PC**                     | **macOS**                  |
| Enfocar/saltar a la barra de menú         | Alt+F9                     | ⌥+F9                       |
| Enfocar/saltar a la barra de herramientas | Alt+F10                    | ⌥+F10                      |
| Enfocar/saltar a la ruta del elemento     | Alt+F11                    | ⌥+F11                      |
| Cerrar menú/submenú/diálogo               | Esc                        | esc                        |
| Volver al área de contenido del editor    | Esc                        | esc                        |
| Navegar izquierda/derecha por menú/barra  | Tab y las teclas de flecha | Tab y las teclas de flecha |

Consulta más información en:

* <a href="https://www.tiny.cloud/docs/advanced/accessibility/"  
  class="external text" target="_blank"  
  rel="nofollow noreferrer noopener">TinyMCE - Accesibilidad</a>
* Una lista de <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"  
  class="external text" target="_blank"  
  rel="nofollow noreferrer noopener">atajos de teclado</a> disponibles (PC, Mac)
  dentro del área de edición.

## CodeMirror

El plugin **Editor - CodeMirror** está diseñado para facilitar la entrada de código HTML
en un artículo o descripción. **CodeMirror** admite **resaltado de sintaxis**
y **autocompletado**, como se muestra en esta captura de pantalla.

<img
src="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/800px-Help-4x-screenshot-editor-codemirror-example-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1200px-Help-4x-screenshot-editor-codemirror-example-en.png 1.5x, https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1600px-Help-4x-screenshot-editor-codemirror-example-en.png 2x"
data-file-width="1977" data-file-height="905" width="800" height="366"
alt="screenshot editor codemirror example" />

* Los botones que se muestran debajo de la ventana de edición permiten acceder para enlazar a cualquier
  elemento del sitio.
* **CodeMirror** ofrece algunas de las mismas ventajas que usar **Editor - Ninguno**,
  pero facilita un poco más el trabajo con código HTML sin procesar.
* La configuración se establece en el plugin **Editor - CodeMirror**.

## Ninguno

Si se selecciona **Editor - Ninguno** para un usuario, se mostrará un editor de texto simple.
Esto te permite ingresar código HTML sin formato. Puedes usar el botón de la barra de herramientas
**Vista previa** para ver cómo se mostrará el HTML.

Ten en cuenta que la opción **Ninguno** puede ser útil si estás ingresando contenido
predefinido (**boilerplate**) o HTML personalizado, por ejemplo, para crear un enlace de PayPal.
**TinyMCE** reformatea automáticamente y elimina parte del HTML cuando se guarda un archivo.
Esto puede hacer que el HTML complejo no funcione correctamente.

Si esto sucede, puedes cambiar temporalmente el editor a **Ninguno** y crear el contenido deseado.
Ten en cuenta que si deseas editar este contenido en el futuro, deberías asegurarte de cambiar tu editor a **Ninguno**.
De lo contrario, si abres y guardas el contenido con **TinyMCE**, podrías perder tu HTML personalizado.

El plugin **Editor - Ninguno** no tiene configuración.
