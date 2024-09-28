<!-- Filename: Help4.x:Smart_Search:_Content_Maps  / Display title: Recherche Intelligente : Cartes de Contenu -->

## Descripción

La página de *Búsqueda Inteligente: Mapas de Contenido* muestra los mapas de contenido que se encuentran actualmente en el índice de Búsqueda Inteligente. Los mapas de contenido te permiten hacer referencias cruzadas de tu contenido indexado (artículos, etc.) con información meta relacionada, como la categoría en la que se encuentra. Cada ítem de contenido que es indexado por Búsqueda Inteligente se añade a uno o más mapas de contenido que pueden usarse como filtros al buscar en el índice.

Los mapas de contenido se dividen en dos partes:

- Grupo de Mapas: Estos son super-contenedores para un tipo particular de información. Por ejemplo, un Grupo de Mapas podría ser *Tipo*, *Categoría*, *Evento*, *Idioma* o *Autor*.
- Mapa de Contenido: Los mapas de contenido son los valores reales de la información meta en un Grupo de Mapas particular. Los Mapas de Contenido son, por ejemplo, los nombres de las categorías o autores.

Estos Grupos de Mapas y Mapas de Contenido son lo que conforma el panel de búsqueda avanzada disponible en el front-end. Para cada Grupo de Mapas puede haber una lista desplegable y los Mapas de Contenido se añaden como valores a la lista respectiva. Los desarrolladores de sitios más avanzados pueden sobrescribir los diseños predeterminados y usar listas multi-selección o casillas de verificación en su lugar.

Es importante tener en cuenta que los Grupos de Mapas y los Mapas de Contenido de diferentes tipos de contenido se combinan en una sola lista. Un artículo de Joomla en una categoría llamada *Noticias* y un feed de noticias o contacto en una categoría con el mismo nombre están mapeados al mismo Mapa de Contenido en el mismo Grupo de Mapas. Esto es un poco como etiquetar diferentes tipos de contenido con la misma etiqueta. El efecto es que el visitante de tu sitio no necesita saber cómo está clasificado tu contenido para establecer los filtros correctos para encontrarlo.

La pantalla de mapas de contenido muestra todos los Grupos de Mapas dentro del índice de Búsqueda Inteligente junto con un número que indica la cantidad de Mapas de Contenido dentro de ese Grupo de Mapas y los ítems dentro de un Mapa de Contenido. Al hacer clic en el número de un Grupo de Mapas, puedes ver el Mapa de Contenido dentro de ese Grupo de Mapas junto con la cantidad de ítems de contenido que pertenecen a ese Mapa de Contenido. Un ítem de contenido puede pertenecer a múltiples Mapas de Contenido dentro de un Grupo de Mapas, así como a múltiples Grupos de Mapas.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columna de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenación de Ítems de Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Si eres nuevo en Búsqueda Inteligente, deberías leer la [guía rápida de Búsqueda Inteligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Cómo acceder

- Seleccione **Componentes → Búsqueda Inteligente → Mapas de Contenido** desde el
  menú del Administrador.

## Captura de pantalla

![contenido de mapas de búsqueda inteligente](../../../es/images/smart-search/smart-search-content-maps.png)

## Encabezados de Columna

- **Estado** El estado del elemento de contenido dentro de la Búsqueda Inteligente. Cambiar el estado solo afecta si el elemento de contenido está disponible en los resultados de búsqueda y no afecta al elemento de contenido en sí.
- **Título** El título del Grupo de Mapas o Mapa de Contenidos.
- **Mapas** El número de mapas dentro del Grupo de Mapas. Al seleccionar el número, se mostrarán los mapas dentro del Grupo de Mapas.
- **Contenido Publicado Indexado** El número de elementos de contenido publicados en el Grupo de Mapas. Al seleccionar el número, se mostrarán los elementos de contenido publicados dentro del Grupo de Mapas.
- **Contenido No Publicado Indexado** El número de elementos de contenido no publicados en el Grupo de Mapas. Al seleccionar el número, se mostrarán los elementos de contenido no publicados dentro del Grupo de Mapas.

## Barra de herramientas

- **Acciones** Muestra una lista de acciones para los ítems seleccionados. Marca
  una o más casillas de verificación de ítems para activar la lista.
  - **Publicar**. Hace que los Grupos de Mapas o Mapas de Contenido seleccionados
    estén disponibles para los visitantes de tu sitio web.
  - **Despublicar.** Hace que los Grupos de Mapas o Mapas de Contenido seleccionados
    no estén disponibles para los visitantes de tu sitio web. Un Grupo de Mapas
    despublicado no se mostrará como una lista de selección en el front-end. Un Mapa de
    Contenido despublicado no aparecerá en la lista de selección para el Grupo de Mapas
    en el que se encuentra. Volver a indexar no cambia el estado de publicación de
    los Grupos de Mapas o los Mapas de Contenido.
- **Eliminar** Elimina los Grupos de Mapas o Mapas de Contenido seleccionados. Funciona
  con uno o múltiples Grupos de Mapas o Mapas de Contenido seleccionados. Puedes
  recuperar Grupos de Mapas o Mapas de Contenido eliminados ejecutando nuevamente el
  indexador de Smart Search.
- **Estadísticas** Muestra algunas estadísticas básicas sobre Smart Search.

*Traducido por openai.com*

