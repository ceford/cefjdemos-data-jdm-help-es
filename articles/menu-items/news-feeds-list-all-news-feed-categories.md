<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories  / Display title: Lister toutes les catégories du flux d'actualités -->

## Descripción

El tipo de elemento de menú **Listar Todas las Categorías en un Árbol de Categorías de Noticias** se utiliza para mostrar una lista de todas las Categorías de RSS News Feed. Las categorías se muestran en una lista jerárquica. Dependiendo de las opciones seleccionadas para este diseño, se puede seleccionar un Título de categoría para mostrar los News Feeds en esa categoría.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña Detalles](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Pestaña Categoría](jdocmanual?article=help/menu-items-common/menu-item-category).
* [La Pestaña Diseños de Listas](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [La Pestaña Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Pestaña Mostrar Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Pestaña Metadatos](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Pestaña Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La Pestaña Asignación de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Cómo Acceder

Para crear un nuevo Listar Todas las Categorías en un elemento de menú del Árbol de Categorías del Feed de Noticias:

- Selecciona **Menús → \[nombre del menú\]** desde el menú del Administrador
  (por ejemplo, **Menús → Menú Principal**). Luego...
  - Selecciona el botón Nuevo en la Barra de Herramientas. Luego...
  - Selecciona el botón de Selección del Tipo de Elemento de Menú.
  - En el cuadro de diálogo modal, selecciona el elemento Feeds de Noticias para abrir una lista y
    luego selecciona el elemento **Listar Todas las Categorías del Feed de Noticias**.

Para editar un elemento de menú existente de Listar Todas las Categorías del Feed de Noticias:

- Selecciona su Título en la lista de Elementos de Menús.

## Captura de pantalla

![Lista de todos los ítems de Menú en la pestaña de detalles de Categorías de Noticias](../../../es/images/menu-items/news-feeds-list-all-categories-details-tab.png)

## Campos del Formulario

### Pestaña de Categorías

![Lista de Elementos del Menú todas las Categorías del Feed de Noticias pestaña de categorías](../../../es/images/menu-items/news-feeds-list-all-categories-tree-categories-tab.png)

- **Descripción de la Categoría de Nivel Superior** Mostrar u ocultar la descripción de la categoría de nivel superior. Tenga en cuenta que esta descripción puede ser reemplazada para este esquema ingresando una *Descripción Alternativa*.
- **Descripción Alternativa** Si escribe un texto en este campo, reemplazará la descripción de la categoría de nivel superior, si tiene una. Si la opción de Descripción de Nivel Superior está configurada en *Mostrar*, esta descripción se mostrará en lugar de la descripción normal de la categoría.
- **Niveles de Subcategoría** El número de niveles de subcategorías para mostrar en el esquema. Seleccione *Todo* para mostrar todos los niveles en la jerarquía de subcategorías.
- **Categorías Vacías** Mostrar u ocultar las categorías que no contienen elementos de contenido ni subcategorías.
- **Descripciones de Subcategorías** Mostrar u ocultar la descripción de la categoría de las subcategorías.
- **\# Feeds en la Categoría** Mostrar u ocultar el número de Feeds de Noticias en una Categoría.

### Pestaña de Opciones de Visualización de Feeds

![Lista de Elementos del Menú todas las Categorías del Feed de Noticias pestaña de opciones de visualización de feeds](../../../es/images/menu-items/news-feeds-list-all-categories-tree-feed-display-options-tab.png)

- **Imagen del Feed** Mostrar u ocultar la imagen de los Feeds de Noticias.
- **Descripción del Feed** Mostrar u ocultar las descripciones de los Feeds de Noticias.
- **Contenido del Feed** Mostrar u ocultar el contenido de los Feeds de Noticias.
- **Recuento de Caracteres** Número de caracteres a mostrar si el Contenido del Feed de los Feeds de Noticias está configurado para mostrarse.

## Consejos

- Las categorías pueden ser *anidadas* en niveles, similar a las carpetas en un disco duro. En teoría, no hay un límite absoluto en el número de niveles que puedes tener. Sin embargo, como cuestión práctica se recomienda mantener los niveles al mínimo. El diseño Mostrar Todas las Categorías puede no funcionar correctamente si el número de niveles mostrados es mayor de cinco.
- Si configuras los títulos de las categorías como enlazables, el usuario puede navegar a la categoría. Si existe un elemento de menú preexistente para esta categoría (por ejemplo, un elemento de menú Lista de Categorías), entonces las opciones de ese elemento de menú controlarán la visualización de esa página. De lo contrario, las opciones configuradas para el elemento de menú actual Mostrar Todas las Categorías controlarán la visualización de la página.
- Puedes configurar la opción para enlazar a una lista en dos lugares.
  - En *News Feed: Opciones* puedes establecer el valor predeterminado para todas las categorías.
  - En *Categoría: Editar* para una Categoría de Fuentes de Noticias, puedes establecer un valor para una categoría específica. Si esto se configura, sobrescribirá el valor predeterminado.

*Traducido por openai.com*

