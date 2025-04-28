<!-- Filename: Help4.x:Tags:_New_or_Edit  / Display title: Tags: Nouvelle ou Édition -->

## Descripción

La página de *Etiquetas: Nueva o Editar* se utiliza para agregar o editar etiquetas que pueden ser utilizadas para mostrar contenido del sitio por nombre de etiqueta.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo Acceder

- Selecciona **Componentes → Etiquetas** en el menú del Administrador. Luego
  - Selecciona el botón '**Nuevo**' en la Barra de herramientas para crear una nueva Etiqueta.
  - Selecciona el Título de una Etiqueta en la columna de **Título** de la lista para editar
    una etiqueta existente.

## Captura de pantalla

![editar etiquetas detalles de la etiqueta pestaña](../../../es/images/tags/tags-edit-tag-details-tab.png)

## Campos del Formulario

- **Título** El nombre de este elemento. Este campo es obligatorio.
- **Alias** El nombre interno del elemento. Normalmente, puedes dejar esto
  en blanco y Joomla llenará un valor predeterminado del Título en minúsculas y
  con guiones en lugar de espacios.

### Pestaña Detalles de la Etiqueta

#### Panel Izquierdo

- **Descripción** Indica el propósito de esta etiqueta.

#### Panel Derecho

- **Padre** El ítem (categoría, elemento del menú, etc.) que es el
  padre del elemento que se está editando.
- **Estado** El estado de publicación del ítem.
- **Acceso** El nivel de acceso de visualización para este ítem.
- **Idioma** Idioma del ítem.
- **Nota** Esto es normalmente para el uso del administrador del sitio (por
  ejemplo, para documentar información sobre este ítem) y no se muestra en
  el Frontend del sitio.
- **Nota de la Versión** Campo opcional para identificar esta versión del ítem
  en la ventana del Historial de Versiones del ítem.

### Pestaña Opciones

![tags edit tag options tab](../../../es/images/tags/tags-edit-options-tab.png)

#### Panel de Opciones

- **Diseño** Usa un diseño de la vista del componente proporcionado o
  sobrescrituras en las plantillas.
- **Clase CSS para el enlace de la etiqueta** Agrega clases CSS específicas para el enlace de la etiqueta.
  Si está vacío, *label label-info* se agregará por defecto en el diseño de la etiqueta.

#### Paneles de Imágenes

- **Imagen de Avance** La imagen que se mostrará como parte de la lista.
- **Flotante** Atributo flotante para la imagen.
- **Alt** Texto alternativo para la imagen.
- **Leyenda** La leyenda para la imagen.
- **Imagen Completa** Una imagen que se mostrará en la vista de la etiqueta única.

### Pestaña de Publicación

![tags edit tag publishing tab](../../../es/images/tags/tags-edit-publishing-tab.png)

#### Panel de Publicación

- **Fecha de Creación** Fecha en que se creó el ítem (Artículo, Categoría, etc.).
- **Creado Por** Nombre del Usuario de Joomla que creó este ítem. Este
  se predeterminará al usuario actualmente conectado. Si deseas cambiar
  esto a un usuario diferente, haz clic en el botón Seleccionar Usuario para seleccionar un
  usuario diferente.
- **Creado por Alias** Este campo opcional te permite ingresar un alias
  para este Autor para este Artículo. Esto te permite mostrar un nombre de Autor diferente para este Artículo.
- **Fecha de Modificación** Fecha de la última modificación.
- **Modificado Por** Nombre de usuario que realizó la última modificación.
- **Revisión** ...
- **Hits** El número de veces que se ha visto un ítem.
- **ID** Este es un número de identificación único para este ítem asignado
  automáticamente por Joomla. Se utiliza para identificar internamente el ítem,
  y no puedes cambiar este número. Al crear un nuevo ítem, este campo muestra "0" 
  hasta que guardes la nueva entrada, momento en el cual se le asigna un nuevo ID.

#### Panel de Metadata

- **Meta Descripción** Un párrafo opcional para ser utilizado como la
  descripción de la página en el resultado HTML. Generalmente se mostrará
  en los resultados de los motores de búsqueda. Si se ingresa, esto crea un
  elemento meta HTML con un atributo de nombre `<description>` y un atributo de contenido igual al texto ingresado.
- **Palabras Clave** Entrada opcional para palabras clave. Deben ingresarse separadas
  por comas (por ejemplo: gatos, perros, mascotas) y pueden ingresarse en
  mayúsculas o minúsculas. (Por ejemplo: *GATOS* coincidirá con *gatos* o
  *Gatos*). Las palabras clave pueden usarse de varias maneras:
  1.  Para ayudar a los motores de búsqueda y otros sistemas a clasificar el contenido del
      Artículo.
  2.  En combinación con las etiquetas de Banners, para mostrar Banners específicos basados
      en el contenido del Artículo. Por ejemplo, supongamos que tienes un Banner con
      un anuncio de productos para perros y otro Banner para productos para gatos. 
      Puedes hacer que tu Banner de perros se muestre cuando un Usuario esté viendo un 
      Artículo relacionado con perros y tu Banner de gatos se muestre para un Artículo relacionado con gatos. Para hacer esto, deberías:
      - Agregar las palabras clave "perro" y "gato" a los Artículos apropiados.
      - Agregar las Etiquetas "perro" y "gato" a los Banners apropiados en
        Banners: Editar.
      - Configurar el parámetro del módulo Banner 'Buscar por Etiquetas' en "Sí" en el
        lista de módulos del sitio: Banners.
  3.  Solo para artículos, en combinación con el módulo Artículos - Relacionados,
      para mostrar Artículos que compartan al menos una palabra clave en común. Por
      ejemplo, si el Artículo actual mostrado tiene las palabras clave "gatos,
      perros, monos", cualquier otro Artículo con al menos una de estas
      palabras clave se mostrará en el módulo 'Artículos - Relacionados'.
- **Autor** Entrada opcional para un nombre de Autor dentro de los metadatos. Si
  se ingresa, esto crea un elemento meta HTML con el atributo de nombre
  'author' y el atributo content con lo ingresado aquí.
- **Robots** Las instrucciones para los 'robots' web que navegan por esta
  página.
  - *index, follow* Indexar esta página y seguir los enlaces en esta página.
  - *noindex, follow* No indexar esta página, pero seguir los
    enlaces en la página. Por ejemplo, podrías hacer esto para una página de mapa del sitio
    donde deseas que los enlaces se indexen pero no quieres que esta
    página aparezca en los motores de búsqueda.
  - *index, nofollow* Indexar esta página, pero no seguir ningún enlace en
    la página. Por ejemplo, podrías hacer esto para un calendario de eventos,
    donde deseas que la página aparezca en motores de búsqueda pero no 
    deseas indexar cada evento.
  - *noindex, nofollow* No indexar esta página ni seguir ningún enlace en
    la página.
  - *Usar Global* Configurar en Configuración Global: Configuración de Metadata.

*Traducido por openai.com*

