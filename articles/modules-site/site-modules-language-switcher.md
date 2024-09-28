<!-- Filename: Help4.x:Site_Modules:_Language_Switcher  / Display title: Modules : Commutateur de Langue -->

## Descripción

El tipo de módulo *Language Switcher* te permite cambiar entre los idiomas de contenido disponibles. Seleccionar un idioma te llevará a la página correspondiente para ese idioma.

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Los Módulos: Pestaña Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [Los Módulos: Pestaña de Asignación de Menú](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Los Módulos: Pestaña Avanzada](jdocmanual?article=help/modules/modules-advanced-tab).
* [La Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo Acceder

- Selecciona **Sistema → Administrar Panel → Módulos del Sitio** desde el
  menú del Administrador. Luego...
  - Para crear un nuevo módulo: selecciona el botón **Nuevo** en la Barra de Herramientas. Luego...
    - Selecciona el tipo de módulo requerido.
  - Para editar un módulo existente:
    - Encuentra el módulo en la lista de módulos instalados y selecciona el
      enlace del título en la columna **Título**.

## Captura de Pantalla

![pestaña del módulo del conmutador de idiomas](../../../es/images/modules-site/modules-language-switcher-module-tab.png)

## Campos del Formulario

- **Título** El título del módulo. Este título también se muestra
  para el módulo dependiendo del campo de formulario *Mostrar Título*

### Pestaña del Módulo

#### Panel Izquierdo

- **Pre-texto** Este es el texto o HTML que se muestra encima del
  selector de idioma.
- **Post-texto** Este es el texto o HTML que se muestra debajo del
  selector de idioma.
- **Usar Desplegable** Los tres siguientes elementos cambian para *Sí* y *No*
  - **No**
    - **Usar Banderas de Imágenes** Si se establece en *Sí*, muestra la elección de idioma como
    banderas de imágenes. De lo contrario, usa los nombres nativos del idioma del contenido. Si se establece en
    *No*, aparece un campo adicional: **Nombres Completos de Idiomas**, que muestra
    un código de idioma de dos caracteres en mayúsculas para cada idioma.
    - **Idioma Activo** Muestra o no el idioma activo.
    Si se muestra, se añadirá la clase `lang-active` al elemento.
    - **Visualización Horizontal** El valor por defecto está establecido en *Sí*, es decir, para crear una
    visualización en lista horizontal. Establecer en *No* para una lista vertical.
  - **Sí** El elemento *Idioma Activo* se muestra seleccionado.
    - **Usar Banderas en el Desplegable** Si se establece en *Sí* la bandera del idioma se coloca
      antes del nombre del idioma en la lista desplegable.
    - **Nombres Completos de Idiomas** Si se establece en *No*, muestra un código de
      idioma de dos caracteres en mayúsculas para cada idioma.
    - **Idioma Activo** Sin efecto en la lista desplegable.

*Traducido por openai.com*

