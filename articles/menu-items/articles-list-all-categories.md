<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Listar Todas las Categorías -->

## Descripción

El tipo de elemento de menú *Listar Todas las Categorías en un Árbol de Categorías de Artículos* se utiliza
para mostrar las categorías en una lista jerárquica. Dependiendo de las opciones seleccionadas
para este diseño, puedes hacer clic en el título de una categoría para mostrar los artículos en
esa categoría.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Detalles](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Pestaña de Categoría](jdocmanual?article=help/menu-items-common/menu-item-category).
* [La Pestaña de Diseño de Blog](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [La Pestaña de Diseños de Lista](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [La Pestaña de Opciones](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [La Pestaña de Integración](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [La Pestaña de Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Pestaña de Visualización de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Pestaña de Metadatos](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Pestaña de Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La Pestaña de Asignación de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Cómo Acceder

Selecciona **Menús → \[nombre del menú\]** desde el menú del Administrador.

Para añadir un Elemento de Menú:

1.  Selecciona el botón **Nuevo** en la Barra de Herramientas.
2.  Selecciona el botón **Seleccionar** del Tipo de Elemento de Menú.
3.  Selecciona el ítem **Artículos**.
4.  Selecciona el ítem **Listar Todas las Categorías en un Árbol de Categorías de Artículos**.

Para editar un Elemento de Menú:

- selecciona un **Título** de la lista.

## Captura de Pantalla

![Pestaña de detalles del elemento de menú Artículos Listar Todas las Categorías](../../../es/images/menu-items/articles-list-all-categories-details-tab.png)

## Campos del Formulario

- **Título** El título que se mostrará para este elemento de menú.
- **Alias** El nombre interno del elemento de menú. Normalmente, puedes dejar
  esto en blanco y Joomla llenará un valor por defecto basado en el título en minúsculas
  y con guiones en lugar de espacios.

### Pestaña de Detalles

#### Panel Izquierdo

- **Tipo de Elemento de Menú** El tipo de elemento de menú seleccionado cuando este elemento de menú
  fue creado. Puede ser uno de los tipos de elementos de menú principales o un tipo de elemento de menú
  proporcionado por una extensión instalada.
- **Seleccionar la Categoría de Nivel Superior**
  - *Raíz* Incluir todas las categorías de artículos.
  - De lo contrario, selecciona la categoría de nivel superior deseada. Todas las categorías
    secundarias de la categoría seleccionada se mostrarán en el elemento de menú.
- **Enlace** El enlace generado por el sistema para este elemento de menú. Este campo
  no se puede cambiar y es solo informativo.
- **Ventana de Destino** Selecciona de la lista desplegable.
- **Estilo de Plantilla** Selecciona de la lista desplegable.

#### Panel Derecho

- **Menú** Muestra en qué menú aparecerá el enlace.

### Pestaña de Categorías

![Pestaña de categorías del elemento de menú Artículos Listar Todas las Categorías](../../../es/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Descripción de la Categoría de Nivel Superior** Muestra la descripción de la
  categoría de nivel superior.
- **Descripción Alternativa** Introduce una descripción para reemplazar la
  descripción de la categoría en el elemento de menú.
- **Niveles de Subcategorías** Controla cuántos niveles de subcategorías
  mostrar.
- **Categorías Vacías** Muestra categorías que no contienen ningún artículo
  o subcategorías.
- **Descripciones de Subcategorías** Muestra la descripción de
  las subcategorías.
- **\# Artículos en la Categoría** Muestra un conteo del número total de
  artículos en cada categoría.

### Pestaña de Diseño de Blog

Las Opciones de Diseño de Blog controlan la apariencia del desglose de categorías si
esto resulta en un diseño de blog.

El formulario de diseño de blog tiene un diseño diferente al de los Elementos Comunes
mencionados anteriormente, pero los campos son similares.

### Pestaña Compartida

Las Opciones Compartidas se aplican para Opciones Compartidas en Lista, Blog y Destacado,
a menos que sean cambiadas por la configuración del menú.

![Pestaña compartida del elemento de menú Artículos Listar Todas las Categorías](../../../es/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Paginación** La paginación proporciona enlaces de página en la parte inferior de la
  página que permiten al Usuario navegar a páginas adicionales. Esto es necesario si los
  artículos no caben en una sola página.
  - *Ocultar* Los enlaces de paginación no se muestran. *Nota* Los usuarios no podrán
    navegar a páginas adicionales.
  - *Mostrar* Se muestran los enlaces de paginación si es necesario.
  - *Auto* Se muestran los enlaces de paginación si es necesario.
- **Resumen de Paginación** Muestra el número de página actual y el total de páginas
  (por ejemplo, *Página 1 de 2*) en la parte inferior de cada página.

## Consejos

- Las categorías pueden estar *anidadas* en niveles, similar a carpetas en un disco
  duro. En teoría, no hay un límite absoluto en la cantidad de niveles
  que puedes tener. Sin embargo, como cuestión práctica, se recomienda mantener
  los niveles al mínimo. El diseño Mostrar Todas las Categorías puede no funcionar
  correctamente si el número de niveles mostrados es mayor a 5.
- Si configuras los títulos de las categorías como enlazables, el usuario puede profundizar
  en la categoría. Cuando lo hacen, normalmente verán un elemento de menú de Lista de Categorías
  o Blog de Categorías, dependiendo de la opción seleccionada. Si existe un elemento de menú
  preexistente para esta categoría (por ejemplo, un elemento de menú de Blog de Categorías),
  entonces ese elemento de menú se mostrará en la profundización y las opciones configuradas
  para ese elemento de menú controlarán la visualización de la página. De lo contrario, las opciones
  configuradas para el actual elemento de menú Mostrar Todas las Categorías controlarán
  la visualización de la página.
- Puedes configurar la opción de profundizar a una lista o blog en 2 lugares.
  - En *Artículos: Opciones* puedes configurar el valor predeterminado para todas las categorías.
  - En *Categoría: Editar* puedes configurar un valor para una categoría específica. Si esto
    se configura, sobrescribe el valor predeterminado.
- Para personalizar un *Formato de Fecha* puedes usar `D M Y` para día mes año o `d-m-y`
  para una versión corta, por ejemplo 17-08-05. Si se deja en blanco, se utiliza la
  traducción de la clave DATE_FORMAT_LC1 del archivo de idioma.
