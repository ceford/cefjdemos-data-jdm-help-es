<!-- Filename: Help6.x:List_Ordering  / Display title: Ordre des listes -->

## Donde el Orden Importa

El orden de los elementos en una lista comienza a ser importante cuando se ve desde el
frontend del sitio. Por ejemplo, supongamos que tienes una serie de artículos destacados que
presentas en un diseño de Artículo Destacado. El formulario de entrada de datos del menú para ese
diseño ofrece varias alternativas de *Orden de Artículos*, una de las cuales es
**Orden de Artículos Destacados**. El orden predeterminado es el orden en el que
se añaden los artículos. Pero, ¿qué pasa si quieres que un artículo en particular sea el primero
en la lista? Si tienes un Comité con artículos sobre cada miembro, es posible que desees
que el Presidente esté en la primera posición en el diseño de la página principal.

El mismo principio se aplica a los diseños de Blogs de Categoría. Puedes tener varios
Comités, cada uno en una Categoría diferente. En ese caso, filtras la lista de artículos
por Categoría y colocas el artículo sobre el Presidente primero en la lista.

## La Columna de Orden

En una vista de lista de componentes, la columna de Orden generalmente es la segunda desde la izquierda (en idiomas de izquierda a derecha) justo al lado de la columna de Casilla de Verificación. Si la lista no está ordenada por la columna de Orden, estará vacía. En ese caso, necesita seleccionar el ícono de la columna de Orden, un doble cheurón (<span class="ms-1 icon-sort"></span>). Cada vez que se selecciona el ícono, el orden cambia de ascendente a descendente. Necesita un orden ascendente (<span class="ms-1 icon-caret-up"></span>) para arrastrar un ítem hacia arriba, hacia la parte superior de la lista. Esto se indica en el campo de orden de clasificación de la barra de búsqueda.

## Arrastrar y Soltar

Con la columna de ordenación configurada para su uso, cada elemento contendrá un ícono de elipsis vertical (<span class="icon-ellipsis-v"></span>). Este ícono se puede arrastrar hacia arriba o hacia abajo para cambiar el orden de la lista. El nuevo orden de la lista se establece en la base de datos con una llamada de JavaScript. No hay recarga de página.

¡Es complicado! Necesitas practicar. Y esta es una de las ocasiones en las que quizá desees configurar el límite de la lista a *Todo*.

*Traducido por openai.com*

