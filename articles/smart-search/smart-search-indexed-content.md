<!-- Filename: Help4.x:Smart_Search:_Indexed_Content  / Display title: Recherche intelligente : Contenu indexé -->

## Descripción

La página *Búsqueda Inteligente: Contenido Indexado* muestra una lista de todos los elementos de contenido que han sido indexados en Búsqueda Inteligente.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de Ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de columnas de la lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenación de elementos de la lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de la lista](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Si eres nuevo en Búsqueda Inteligente, deberías leer la 
  [Guía rápida de Búsqueda Inteligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Cómo acceder

- Selecciona **Componentes → Búsqueda Inteligente → Índice** desde el menú del Administrador.

## Captura de Pantalla

![búsqueda inteligente de contenido indexado](../../../es/images/smart-search/smart-search-indexed-content.png)

## Crear un Índice

Seleccione el botón **Índice** en la barra de herramientas. Esto abrirá una ventana para mostrar el progreso de la operación de indexación. La operación de indexación puede tomar algún tiempo dependiendo del número de elementos de contenido del sitio y el número de palabras y frases de búsqueda contenidas en cada elemento de contenido. Una barra de progreso indicará cuánto de la operación de indexación se ha completado hasta el momento. No cierre esta ventana hasta que la indexación se haya completado. En sitios con una gran cantidad de contenido, esto puede llevar mucho tiempo (decenas de minutos).

Debe ejecutar el indexador después de que se haya introducido nuevo contenido en el sitio web del cual la función de Búsqueda Inteligente no es automáticamente consciente. Por ejemplo, al importar en lote nuevo contenido donde el importador no activa automáticamente la Búsqueda Inteligente para indexar cada nuevo elemento de contenido. NOTA: El indexador de Búsqueda Inteligente también se puede ejecutar desde la interfaz de línea de comandos (CLI) si es necesario. Vea Configuración de la indexación automática de Búsqueda Inteligente.

## Barra de Herramientas

- **Índice** Ejecuta el indexador de Búsqueda Inteligente. Aparecerá una pequeña ventana emergente con una barra de progreso que avanza a medida que el proceso de indexación trabaja a través del contenido del sitio.
- **Acciones** Seleccione un cuadro de verificación para activar la lista desplegable.
  - **Publicar** Hace que los elementos seleccionados estén disponibles para los visitantes del sitio web.
  - **Despublicar** Hace que los elementos seleccionados no estén disponibles para los visitantes del sitio web.
- **Eliminar** Elimina los elementos de contenido seleccionados. Funciona con uno o varios elementos de contenido seleccionados. Eliminar un elemento de contenido de Búsqueda Inteligente solo lo elimina del índice y no afecta el contenido en sí.
- **Mantenimiento**
  - **Optimizar**
  - **Limpiar Índice** Purgar el índice de Búsqueda Inteligente vaciando todas las tablas de índice. Para seguir usando Búsqueda Inteligente, seleccione el botón Índice en la Barra de Herramientas después de purgar. ADVERTENCIA: Purgar el índice también vacía los filtros de contenido. Deben ser reingresados manualmente después de un ciclo de Purgar-Índice.
- **Estadísticas** Muestra algunas estadísticas básicas sobre Búsqueda Inteligente.

## Consejos

- Si ejecutas el indexador y obtienes un error de *nulo indefinido*, entonces verifica
  los permisos en el directorio `/logs` de Joomla. El servidor web necesita
  tener permisos de escritura en ese directorio para que el indexador funcione.
- Si la lista está vacía, asegúrate de que el complemento Smart Search
  esté habilitado.

*Traducido por openai.com*

