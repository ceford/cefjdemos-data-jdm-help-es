<!-- Filename: Help4.x:Redirects:_Links  / Display title: Redirections : Liens -->

## Descripción

La página *Redirecciones: Enlaces* muestra una lista de redirecciones actuales del sitio web.

El componente de redirección se utiliza para redirigir URLs de páginas web que ya no existen en su sitio web hacia páginas web que sí están funcionando. La URL desde la que desea redirigir no debe estar funcionando ni cargando una página web. Puede ser la URL de una página web que haya desactivado.

La *URL Caducada* que especifique cuando cree la redirección debe ser la URL completa tal y como la escribiría en su navegador web. El componente solo mostrará la última parte de la URL fuente en la lista de redirección.

La *Nueva URL* que especifique al crear una redirección debe ser también la URL completa. Debe tener habilitada la opción *Usar Reescritura de URL* en las opciones de *Configuración Global* de su instalación de Joomla! para que las redirecciones que cree funcionen.

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de Ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo acceder

- Seleccione **Sistema → Administrar panel → Redirecciones** en el menú del Administrador.

## Captura de pantalla

![Redirige enlaces](../../../es/images/redirects/redirects-links.png)

## Encabezados de Columna

- **URL Expirada** La URL que se está redirigiendo en tu sitio web.
  Solo se muestra la parte de la página web de la URL en este listado.
- **URL Nueva** La URL de destino para la redirección.
- **Página de Referencia** La página web de referencia para la redirección.
- **Fecha de Creación** Fecha en que se creó el ítem (Artículo, Categoría, etcétera).
- **Hits 404** Número de Hits 404 que ha habido en esta URL.
- **Código de Estado** El Código de Estado de la página.

## Consejos

- Para que tus redirecciones funcionen, debes habilitar la opción 
  **Usar Reescritura de URL** en las opciones de **Configuración Global** de tu
  instalación de Joomla!. Ten en cuenta también que solo habilitar la opción *Usar Reescritura
  de URL* no es suficiente. Debes tomar el paso adicional de renombrar el archivo `htaccess.txt` en el directorio del sitio web donde instalaste Joomla! a `.htaccess` o al nombre de archivo que tu servidor web Apache requiera para directivas de configuración adicionales. En el archivo de configuración de Apache esta configuración se llama `AccessFileName` y por defecto está configurada como `.htaccess`.

*Translated by openai.com*

