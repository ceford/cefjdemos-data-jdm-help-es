<!-- Filename: Help4.x:Information:_Database  / Display title: Maintenance : Base de données -->

## Descripción

Esta página verifica que la estructura de la tabla de la base de datos esté actualizada y trata de solucionar cualquier problema que se encuentre. En una actualización normal de la versión de Joomla, los cambios en la estructura de la tabla de la base de datos (también llamada `esquema`) se ejecutan automáticamente para mantener sincronizada la versión de la base de datos con la versión de Joomla. Si una actualización se realiza manualmente, o si alguna parte de una actualización automática falla, es posible que el esquema de la base de datos no se actualice para coincidir con la versión de los archivos del programa Joomla. En este caso, la página enumerará cualquier problema de la base de datos que se haya descubierto. A menudo es posible solucionar cualquier problema seleccionando el botón *Actualizar Estructura*.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de Ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo Acceder

- Seleccione **Sistema → Panel de Mantenimiento → Base de Datos** del menú del Administrador.

## Captura de pantalla

![Base de datos de mantenimiento](../../../es/images/maintenance/maintenance-database.png)

## Encabezados de Columna

- **Problemas** Aquí se mencionarán cualquier problema. Un Tooltip al pasar el ratón proporciona más información.
- **Versión de la Base de Datos** El número de versión de la Base de Datos.
- **Versión del Manifiesto** El número de versión de Joomla o de la Extensión.
- **Carpeta** Si la extensión es un complemento, el subdirectorio del directorio de plugins de la instalación de Joomla! donde se encuentra la extensión.

## Consejos

- Si ocurren problemas durante una actualización, usa esta verificación de la base de datos para ver si la base de datos se actualizó correctamente.
- Se recomienda encarecidamente que se use el componente de actualización de Joomla para actualizar el sitio, de modo que los cambios en la base de datos se ejecuten automáticamente.

*Traducido por openai.com*

