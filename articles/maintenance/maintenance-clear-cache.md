<!-- Filename: Help4.x:Maintenance:_Clear_Cache / Display title: Mantenimiento: Limpiar la caché -->

## Descripción

Los archivos de caché son archivos temporales que se crean para mejorar el rendimiento del sitio cuando está habilitado en la configuración global del sitio. Los archivos de caché pueden quedar desactualizados y causar problemas de renderización, los cuales se pueden corregir eliminando *todos* los archivos de caché. Después de la eliminación, el sitio web puede ser un poco más lento hasta que los archivos de caché se vuelvan a crear con el uso.

### Elementos Comunes

Algunos aspectos de esta página se cubren en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de columna de lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo Acceder

- Selecciona **Sistema → Panel de Mantenimiento → Limpiar Caché** desde el menú del Administrador.

## Captura de Pantalla

![Mantenimiento Limpiar Caché](../../../es/images/maintenance/maintenance-clear-cache.png)

## Encabezados de Columna

- **Grupo de Caché** El tipo de elemento que se está almacenando en caché en este archivo. Este también es el nombre del subdirectorio donde se almacenan este tipo de archivos de caché. Los archivos de caché se almacenan en el directorio `\<ruta-a-Joomla!\>/cache/\<Nombre del Grupo de Caché\>`.
- **Número de Archivos** La cantidad de archivos actualmente en este grupo de caché.
- **Tamaño** El tamaño total de los archivos de caché en este grupo.

## Consejos

- Normalmente, deseas eliminar todos los archivos de caché. Para hacer esto, haz clic en la casilla de verificación en el encabezado de la columna para seleccionar todos los archivos y luego haz clic en el icono Eliminar en la barra de herramientas.
