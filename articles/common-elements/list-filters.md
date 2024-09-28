<!-- Filename: Help6.x:List_Filters  / Display title: Filtres de Liste -->

## Propósito¶

La mayoría de los componentes tienen vistas de lista que muestran elementos de la base de datos. Puede haber cientos de elementos, miles quizás, o incluso millones. Por lo tanto, se utilizan los Filtros de Lista para reducir la lista mostrada a aquellos que probablemente contengan el que necesitas trabajar.

Por ejemplo, los elementos eliminados no se muestran generalmente por defecto. Si deseas ver tus elementos eliminados, necesitas configurar el filtro **- Seleccionar Estado -** a **En la Papelera**. La siguiente captura de pantalla muestra los filtros para la página de Artículos.

## Opciones de Filtrado de la Lista de Artículos¶

![Lista de artículos](../../../es/images/common-elements/articles-list-filter-options.png)

Para **mostrar** u **ocultar** las Opciones, selecciona el botón de **Opciones de Filtrado**. Ten en cuenta
que las Opciones siempre se muestran al regresar a cualquier página en la que se haya seleccionado una Opción.

El número de Opciones mostradas varía con el componente. Incluso el componente de Contenido,
que muestra la lista de Artículos, puede tener filtros adicionales. Por ejemplo, se muestra un filtro de **- Seleccionar Etapa -** si el componente de Contenido tiene los **Workflows** habilitados.

## La Barra de Búsqueda

### Búsqueda por Texto

*Pasa el cursor* o *Selecciona* el campo de *Búsqueda* para ver una *Descripción emergente* o escuchar un equivalente *Audio* que indica qué campos se buscarán. El comportamiento predeterminado es buscar el texto ingresado dentro del texto del título.

El componente de contenido permite un prefijo para buscar dentro del ID, Autor o Contenido. Cada uno de esos términos necesita un punto seguido (dos puntos) pero puede estar en cualquier *Mayúscula/Minúscula*. Por ejemplo, *ID:19* o *Autor:Juan* o *contenido:lorem ipsum*.

Para realizar una búsqueda, ingrese parte del término de búsqueda y seleccione el icono **Buscar** (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Opciones de Filtro y Limpiar

El botón **Opciones de Filtro** se utiliza para alternar la vista de los diversos filtros. Si no hay Filtros para un componente, este botón estará ausente.

El botón **Limpiar** se utiliza para eliminar todos los filtros y restaurar la lista a su estado sin filtrar. Si no hay filtros para un componente, este botón estará ausente.

### Orden de Resultados

El orden en el que se presentan los resultados es seleccionable por el usuario. Para artículos, el orden predeterminado es *ID Descendente*, lo que coloca los artículos más recientes en la parte superior de la lista. Pero puede que desee buscar artículos por más visitas, *Visitas descendentes*, o artículos que pronto desaparecerán, *Finalización de Publicación ascendente*.

El orden de resultados puede cambiarse seleccionando un icono de orden en los encabezados de las columnas de la lista. El icono predeterminado *ID Descendente* está representado por un caret hacia abajo (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>). Cambia a un caret hacia arriba si el orden de clasificación se invierte, *ID Ascendente*.

### Número de Resultados

El número de resultados en una lista se establece en la página de Configuración Global, pestaña Sitio, campo Límite de Lista Predeterminado. El valor predeterminado para una nueva instalación es 20.

Hay ocasiones en las que esto no es conveniente. Usted podría desear ver *50* o *100*. Tenga cuidado si elige *Todos*. Puede tomar mucho tiempo recuperar los resultados y renderizar la página. El servidor puede quedarse sin memoria o tiempo y provocar un error fatal. Y su navegador puede tardar mucho en mostrar la página.

El valor predeterminado para este conjunto de documentación se ha establecido en 5 porque es suficiente para capturas de pantalla ilustrativas.

## Cómo Usar Filtros

El propósito de cada filtro debería ser evidente por sí mismo a partir de su etiqueta de selector sin filtrar. Por ejemplo, el filtro de Artículos **- Seleccionar Estado -** ofrece cinco opciones: *Eliminado*, *No Publicado*, *Publicado*, *Archivado* y *Todos*. La última opción es funcionalmente equivalente a sin filtrar (*- Seleccionar Estado -*).

Cuando se cambia una opción de filtro, la página se recarga automáticamente con los nuevos resultados filtrados por la nueva opción de filtro.

## Ocultar Columnas

Algunas listas de componentes tienen muchas columnas y pueden ser demasiado anchas para tu pantalla. Esto es especialmente cierto en algunas traducciones del texto de los encabezados de columnas. El resultado más molesto es que los Títulos pueden ajustarse y ser difíciles de leer.

Para hacer más espacio para el Título, puedes abrir la lista desplegable de Columnas y seleccionar las columnas menos importantes para ocultar. Luego cierra nuevamente la lista de Columnas. El efecto es inmediato ya que usa JavaScript para ocultar las columnas seleccionadas en el diseño. Aún están presentes en la página.

Tus ajustes son guardados por tu navegador, por lo que se usarán hasta que los cambies nuevamente, incluso si cierras sesión y vuelves a iniciar sesión.

*Traducido por openai.com*

