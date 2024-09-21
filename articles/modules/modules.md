<!-- Filename: Help6.x:Modules / Display title: Módulos -->

## Descripción

Los módulos son extensiones ligeras y flexibles utilizadas para mostrar fragmentos de información en cajas organizadas alrededor de un componente en una página. Un ejemplo bien conocido es el módulo *Login* (Inicio de Sesión). Los módulos se asignan por elemento de menú, por lo que puedes decidir mostrar u ocultar un módulo dependiendo de la página que el usuario esté viendo.

Algunos módulos están vinculados a componentes. Por ejemplo, el módulo *Últimas Noticias* está vinculado al componente de contenido para mostrar enlaces a los artículos más recientes. Los módulos no necesitan estar vinculados a componentes. Ni siquiera necesitan estar vinculados a algo, ya que pueden ser simplemente HTML o texto estático.

Puede haber múltiples instancias del mismo módulo. Por ejemplo, puedes usar una instancia del módulo *Imagen Aleatoria* en algunas páginas y otra instancia en otras, cada una utilizando una carpeta de imágenes diferente para seleccionar imágenes.

Las listas de *Módulos (Sitio)* y *Módulos (Administrador)* muestran los módulos instalados actualmente en cada interfaz y permiten agregar nuevos módulos o editar módulos existentes.

### Elementos Comunes

Algunos elementos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Orden de Elementos en la Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Proceso por Lotes en la Lista](jdocmanual?article=help/common-elements/list-batch-process).

Para ver listas de módulos instalados y disponibles, selecciona uno de los siguientes:

* [Módulos del Sitio](jdocmanual?article=help/modules-site/site-modules-site)
* [Módulos del Administrador](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Cómo acceder

- Selecciona **Contenido → Módulos del Sitio** desde el menú del Administrador. O...
- Selecciona **Contenido → Módulos del Administrador** desde el menú del Administrador.

## Filtros de Lista

* **Sitio o Administrador** Selecciona entre módulos del Sitio o del Administrador.

## Encabezados de Columna

Esta es una lista breve de los encabezados únicos para las listas de módulos.

- **Posición** La posición en la página donde se muestra este módulo.
- **Tipo** El nombre del sistema del Módulo.
- **Páginas** Los elementos de menú en los que se mostrará este Módulo. Este elemento no está presente en las listas de módulos del Administrador.
  - *Todos* Se muestra en todas las páginas.
  - *Ninguno* No se muestra en ninguna página.
  - *Seleccionado* Se muestra solo en las páginas seleccionadas.
  - *Todos excepto los seleccionados* Se muestra en todas las páginas excepto en las seleccionadas.
- **Acceso** El nivel de acceso de visualización para este módulo.
- **Idioma** El idioma del módulo, por defecto es *Todos*. Este elemento no está presente en las listas de módulos del Administrador.

### Posiciones de los Módulos

Para ver las posiciones de los módulos en un sitio en vivo, ve a **Sistema → Plantillas** y selecciona el botón **Opciones** en la barra de herramientas. Configura *Vista Previa de las Posiciones de los Módulos* en habilitado y guarda. Esta configuración es válida tanto para las plantillas del sitio como para las del administrador. Luego añade `?tp=1` al final de una URL que no contenga ya una cadena de consulta, o `&tp=1` al final de una URL que ya contenga una cadena de consulta. La página mostrará todas las posiciones de módulos disponibles, incluso aquellas a las que no se han asignado módulos. Las posiciones también se muestran en el formulario de edición del Módulo.

## Consejos

- Los sitios web de Joomla requieren al menos un módulo de Menú.
- Otros Tipos de Módulos (por ejemplo, Banners) son opcionales.
- Algunos Módulos están vinculados a componentes. Por ejemplo, cada Módulo de Menú
  está relacionado con un Menú.
- Otros Módulos (por ejemplo, Breadcrumbs) no dependen de ningún otro contenido.
- Se permiten y son comunes múltiples instancias de un Módulo.
