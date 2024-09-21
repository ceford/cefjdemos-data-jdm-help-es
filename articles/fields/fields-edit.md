<!-- Filename: Help4.x:Fields:_Edit / Display title: Campos: Editar -->

## Descripción

La página *Componente: Editar Campo* es similar para todos los componentes que implementan campos, pero el título de la página cambia dependiendo del contexto: *Artículos: Editar Campo*, *Contactos: Editar Campo* o *Usuarios: Editar Campo*.

La pestaña **General** cambia para reflejar el tipo de campo que se está editando, y una vez que un campo ha sido guardado, su tipo de campo no puede ser cambiado. Sin embargo, es fácil eliminar campos y crear nuevos.

### Elementos Comunes

Algunos aspectos de esta página se cubren en artículos de Ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña de Publicación](jdocmanual?article=help/common-elements/edit-publishing).
* [La pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo Acceder

* Selecciona **Contenido → Campos** desde el menú del Administrador. O...
* Selecciona **Contactos → Campos** desde el menú del Administrador. O...
* Selecciona **Usuarios → Campos** desde el menú del Administrador. Luego...
  * Selecciona el botón **Nuevo** en la barra de herramientas para crear un nuevo campo. O...
  * Selecciona un **Título** de la lista para editar un campo existente.

**Nota:** Hay una lista desplegable que permite la creación de Campos para una Categoría y Correo en el componente de Contacto. Requieren algo de experiencia en codificación para preparar sobrescrituras de plantillas adecuadas.

## Captura de Pantalla

![Artículos editar campo](../../../es/images/fields/articles-edit-field.png)

## Campos del Formulario

- **Título** El título de este campo.

### Pestaña General

#### Panel Izquierdo

Parámetros para todos los campos:

- **Tipo** Si creas un campo, puedes elegir uno de los 16 tipos de campo. Cuando guardas el campo, este tipo es permanente.
- **Nombre** El nombre se usará para identificar el campo. Si lo dejas en blanco, Joomla completará un valor predeterminado a partir del título.
- **Etiqueta** Usa un texto descriptivo del campo para la etiqueta del campo. Este texto no es traducible. Si no introduces texto para una etiqueta, el texto del título también se usará como etiqueta.
- **Descripción** La descripción del campo. Un texto que se mostrará como una ayuda emergente cuando el usuario pase el ratón sobre el cuadro de texto mientras lo utiliza en el Backend al crear un artículo o un contacto o un componente de terceros que admita campos. Este texto no es traducible. No verás esta descripción en el Frontend.
- **Obligatorio** ¿Es este un campo obligatorio? En este caso, el campo debe completarse antes de enviar un artículo, un contacto o un componente de terceros que admita campos.

#### Panel Derecho

- **Estado** El estado de publicación de este campo.
  - *Publicado* El campo es visible al editar un artículo o un contacto. Y es visible en el Frontend.
  - *No Publicado* El campo no será visible para los usuarios al editar un artículo o un contacto.
  - *Archivado* El campo ya no se mostrará al editar un artículo o un contacto. Puedes abrirlo en Campos cuando configures el filtro para archivados.
  - *En la Papelera* El campo está eliminado, pero sigue en la base de datos. Se puede eliminar permanentemente de la base de datos en Campos con la función Vaciar Papelera.
- **Grupo de Campos** Puedes asignar un campo a un grupo de campos.
- **Categoría** Puedes asignar un campo a una o más categorías. Ten en cuenta que el valor predeterminado *Todo* no incluye artículos *Sin Categoría*.
- **Acceso** Selecciona el nivel de acceso para este campo. Los niveles de acceso dependen de lo que se haya configurado en *Usuarios: Niveles de Acceso*.
- **Idioma** Selecciona el idioma para este campo. Si no estás utilizando la función multilingüe de Joomla, mantén el valor predeterminado *Todo*.
- **Nota** Un campo opcional para hacer notas personales sobre el campo.

### Pestaña Opciones

![Artículos editar pestaña de opciones de campo](../../../es/images/fields/articles-edit-field-options-tab.png)

#### Opciones del Formulario

- **Texto de Ayuda** Un texto de ayuda que aparecerá dentro del campo como una pista para la entrada. El texto de ayuda está activo en el Backend al crear un artículo o un contacto o un componente de terceros que admita campos. No lo verás en el Frontend.
- **Clase de Campo** Los atributos de clase del campo cuando el campo se renderiza. Si se necesitan clases diferentes, enuméralas con espacios.
- **Clase de Etiqueta (Formulario)** Clase CSS para aplicar a la etiqueta del campo cuando está en modo de edición (ingresando datos en un campo).
- **Editable En** ¿En qué parte del sitio debe mostrarse el campo? ¿En el Backend, en el Frontend o en ambos?
- **Atributo Mostrar en** Mostrar u ocultar el campo según el valor de otros campos. La sintaxis para usar aquí es, por ejemplo: `lista-de-elementos:valor1[OR]lista-de-elementos:valor2`
  - lista-de-elementos: El *nombre* de un campo ya creado del cual este campo dependerá para ser mostrado.
  - valor1: El valor necesario para que se muestre el campo del que depende.
  - `[OR]`: Para crear una opción entre varios campos. En el ejemplo, este campo se mostrará cuando el campo *lista-de-elementos* tenga el valor: *valor1* O *valor2*.
  - `[AND]`: Para combinar varios campos. Este campo se mostrará solo cuando el campo *lista-de-elementos* tenga el valor: *valor1* Y *valor2*.
  - También puedes usar el valor *no es igual a* como en *lista-de-elementos!:valor1*. La sintaxis mostrará este campo solo cuando *lista-de-elementos* no sea igual a *valor1*.
  - Para mostrar este campo cuando el campo *lista-de-elementos* ha sido seleccionado y no tiene un valor vacío, usa la sintaxis *lista-de-elementos!:* (sin un valor especificado).

**Nota:** Los campos de subformulario manejan el identificador *nombre* de *lista-de-elementos* de manera diferente. Si creas un campo personalizado de subformulario y agregas este campo condicional allí, debes usar *field\[ID\]* en lugar de *lista-de-elementos*, donde ID es el id del campo *lista-de-elementos*. Por lo tanto, el atributo *mostrar en* para este campo condicional que estás creando debe ser: `field36:valor1[OR]field36:valor2` donde 36 es el ID del campo 'Lista de elementos'.

#### Opciones de Visualización

- **Clase de Visualización** La clase del contenedor del campo en la salida.
- **Clase de Valor** La clase del valor del campo en la salida.
- **Etiqueta** Mostrar la etiqueta cuando el campo se renderiza.
- **Clase de Etiqueta (Salida)** Clase CSS para aplicar a la etiqueta del campo cuando se muestra (mostrando la salida de un campo).
- **Visualización Automática** Joomla ofrece algunos eventos de contenido que se activan durante el proceso de creación de contenido. Este es el lugar para definir cómo los campos deben integrarse en el contenido. Puedes elegir
  - Después del Título
  - Antes del Contenido Mostrado
  - Después del Contenido Mostrado
  - No mostrar automáticamente
- **Prefijo** Texto fijo para mostrar antes de un campo, por ejemplo, £.
- **Sufijo** Texto fijo para mostrar después de un campo, por ejemplo, €.
- **Diseño** Si hay un diseño personalizado, se seleccionaría aquí.
- **Mostrar Cuando Es Solo Lectura** Si el campo es solo de lectura (quizás el usuario no tiene el nivel de acceso), ¿debería mostrarse o esconderse el campo?

#### Búsqueda Inteligente

- **Índice de Búsqueda** Advertencia: Cuando se selecciona *Hacer Buscable*, el contenido del campo se indexa con los permisos de visualización del elemento de contenido. Esto podría llevar a una divulgación inesperada de información.
