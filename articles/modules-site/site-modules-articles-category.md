<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category  / Display title: Modules : Articles - Catégorie -->

## Descripción

El tipo de módulo *Artículos - Categoría* muestra una lista de artículos publicados de una o más categorías.

### Elementos Comunes

Algunos elementos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [El Pestaña de Módulos: Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [El Pestaña de Asignación de Menú: Módulos](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [El Pestaña Avanzada: Módulos](jdocmanual?article=help/modules/modules-advanced-tab).
* [El Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

<!-- ToDo: Un tutorial para mostrar cómo usar este módulo -->

## Cómo Acceder

- Selecciona **Sistema → Gestionar Panel → Módulos del Sitio** desde el
  menú del Administrador. Luego...
  - Para crear un nuevo módulo: selecciona el botón **Nuevo** en la Barra de Herramientas. Luego...
    - Selecciona el tipo de módulo requerido.
  - Para editar un módulo existente:
    - Encuentra el módulo en la lista de módulos instalados y selecciona el
      enlace del título en la columna **Título**.

## Captura de Pantalla

![pestaña del módulo de categoría de artículos](../../../es/images/modules-site/modules-articles-category-module-tab.png)

## Campos de Formulario

- **Título** El título del módulo. Este es también el título que se muestra para el módulo dependiendo del campo de formulario *Mostrar Título*.

### Pestaña del Módulo

#### Panel Izquierdo

- **Modo** Seleccione el modo a utilizar. Si se elige el Modo Normal, simplemente configure el módulo y mostrará una lista estática de artículos en los elementos del menú a los que asigne el módulo. Si se elige el Modo Dinámico, aún puede configurar el módulo normalmente, sin embargo, ahora la opción de Categoría ya no se utilizará. En su lugar, el módulo detectará dinámicamente si está en una vista de Categoría y mostrará la lista de artículos dentro de esa Categoría en consecuencia. Cuando se elige el Modo Dinámico, es mejor dejar el módulo configurado para mostrarse en todas las páginas, ya que decidirá si mostrar o no algo dinámicamente.
- **Mostrar en la Página del Artículo** Este ítem aparece si se selecciona el Modo *Dinámico*. Seleccione mostrar u ocultar una Lista de Artículos en las Páginas de Artículos. Esto significa que el módulo solo se mostrará dinámicamente en las Páginas de Categoría.

### Pestaña de Opciones de Filtrado

![pestaña de opciones de filtrado de categoría de artículos](../../../es/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Artículos Destacados** Mostrar, ocultar o seleccionar solo artículos destacados.
- **Conteo** El número de ítems a mostrar. El valor predeterminado de 0 mostrará todos los artículos.
- **Tipo de Filtrado de Categoría** Incluir o excluir las categorías seleccionadas.
- **Categoría** Seleccionar una o más categorías.
- **Artículos de Categoría Infantil** Incluir o excluir artículos de categorías infantiles.
- **Profundidad de Categoría** El número de niveles de categorías infantiles a devolver.
- **Tipo de Filtrado de Autor** Incluir o excluir artículos de los autores seleccionados.
- **Autores** Seleccione uno o más autores de la lista.
- **Tipo de Filtrado de Alias de Autor** Incluir o excluir los alias de autor seleccionados.
- **Alias de Autor** Seleccione uno o más alias de autor de la lista.
- **IDs de Artículos a Excluir** Ingrese cada ID de artículo a excluir en una nueva línea.
- **Filtrado de Fechas** Seleccione el tipo de filtrado de fechas.
- **Campo de Rango de Fechas** Seleccione qué campo de rango de fechas usar.
- **Rango de Fecha de Inicio** Si se selecciona el rango de fechas anteriormente, ingrese una fecha de inicio.
- **Hasta la Fecha** Si se selecciona el rango de fechas anteriormente, ingrese una fecha de finalización.
- **Fecha Relativa** Si se selecciona Fecha Relativa anteriormente, ingrese un valor numérico de días. Los resultados se recuperarán en relación con la fecha actual y el valor ingresado.

### Pestaña de Opciones de Ordenamiento

![pestaña de opciones de ordenamiento de categoría de artículos](../../../es/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Campo del Artículo para Ordenar Por** Seleccione un campo de la lista. El ordenamiento destacado solo debe usarse cuando la opción de Filtrado de Artículos Destacados esté configurada en *solo*.
- **Dirección de Ordenamiento** Seleccione la dirección de ordenamiento del artículo.

### Pestaña de Opciones de Agrupamiento

![pestaña de opciones de agrupamiento de categoría de artículos](../../../es/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Agrupamiento de Artículos** Seleccione un método de agrupamiento de artículos de la lista.
- **Dirección de Agrupamiento** Seleccione la dirección de ordenamiento.
- **Formato de Visualización de Mes y Año** Ingresar un formato de fecha válido.

### Pestaña de Opciones de Visualización

![pestaña de opciones de visualización de categoría de artículos](../../../es/images/modules-site/modules-articles-category-display-options-tab.png)

- **Títulos Vinculados** Mostrar títulos como enlaces a los artículos.
- **Fecha** Mostrar u ocultar la fecha del artículo.
- **Campo de Fecha** Seleccione el campo de fecha a mostrar.
- **Formato de Fecha** Ingresar un formato de fecha válido.
- **Categoría** Mostrar u ocultar el nombre de la categoría del artículo.
- **Visitas** Mostrar u ocultar las visitas al artículo.
- **Autor** Mostrar u ocultar el nombre del autor o alias del autor.
- **Texto Introductorio** Mostrar u ocultar el texto introductorio del artículo.
- **Límite del Texto Introductorio** El número máximo de caracteres a mostrar.
- **Mostrar "Leer Más"** Mostrar u ocultar el enlace *Leer más...* si se ha proporcionado el texto principal del artículo.
- **Mostrar Título con Leer Más** Mostrar u ocultar el título del artículo en el enlace *Leer más...*.
- **Límite de Leer Más** Limitar el número de caracteres del título del artículo a mostrar en el enlace *Leer más...*.

*Traducido por openai.com*

