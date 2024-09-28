<!-- Filename: Help4.x:Extensions:_Discover  / Display title: Extensions : Découvrir -->

## Descripción

Esta página te permite descubrir extensiones que no han pasado por el
proceso de instalación normal. Por ejemplo, algunas extensiones son demasiado grandes
en tamaño de archivo para cargarlas usando la interfaz web debido a las limitaciones del entorno de
alojamiento web. Usando esta característica, puedes cargar archivos de extensión directamente
en tu servidor web usando otros medios como FTP o SFTP y colocar esos
archivos de extensión en el directorio apropiado. Luego puedes usar la
función de descubrir para encontrar la extensión recién cargada y activarla en
tu instalación de Joomla!. Usando la operación de descubrir, también puedes
descubrir e instalar varias extensiones al mismo tiempo. Una extensión
puede ser instalada con la función de descubrir y los siguientes pasos:

1. Sube los archivos de extensión descomprimidos al directorio apropiado
   en tu instalación de Joomla!. Por ejemplo, si deseas subir una
   extensión de plantilla de sitio a tu instalación de Joomla! deberías
   crear un directorio para la extensión de la plantilla en el subdirectorio /templates
   de tu instalación de Joomla!. Luego, deberías subir
   los archivos de la extensión de la plantilla a ese directorio.
2. Después de subir los archivos de extensión, regresa a la
   página de Descubrir del Administrador de Extensiones y selecciona el botón **Descubrir** 
   en la barra de herramientas. Esto iniciará la función de búsqueda que 
   buscará en los directorios de extensiones de Joomla! buscando extensiones no instaladas.
3. Si la extensión que subiste es compatible con la versión de Joomla! y
   no está ya instalada, aparecerá en la lista de
   extensiones descubiertas en esta página.
4. Marca la casilla de verificación a la izquierda de la extensión descubierta y luego
   selecciona el botón **Instalar** en la barra de herramientas. Esto instalará la
   extensión en tu instalación de Joomla!.

### Elementos Comunes

Algunos elementos de esta página están cubiertos en artículos de
Ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de columna de lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Orden de ítems de lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo Acceder

- Selecciona **Sistema → Panel de Instalación → Descubrir** desde el menú del Administrador.

## Captura de pantalla

![Lista de descubrimiento de extensiones](../../../es/images/extensions/discover-list.png)

## Encabezados de Columna

- **Nombre** El nombre de la extensión.
- **Ubicación** Indica si es una extensión del sitio o del administrador.
- **Tipo** El tipo de extensión – Módulo, Plugin, Plantilla, Idioma.
- **Versión** El número de versión de la extensión.
- **Fecha** La fecha de lanzamiento de la extensión.
- **Autor** El autor de la extensión.
- **Directorio** Si la extensión es un plugin, esto muestra el subdirectorio dentro del directorio /plugins de la instalación de Joomla! donde se encuentra la extensión. Por defecto, Joomla! tiene los siguientes subdirectorios en el directorio de Plugins, cada uno representando diferentes tipos de plugins definidos: autenticación, contenido, editores, editores-xtd, extensión, búsqueda, sistema, usuario.
- **ID** El número de identificación. Un número de identificación asignado de forma única para esta entrada. Es asignado automáticamente por Joomla! y se utiliza para la identificación interna de la entrada. El número no se puede cambiar.

## Consejos

- Si tienes muchas extensiones que deseas instalar, puedes subirlas
  todas en los directorios apropiados de tu instalación de Joomla!
  y luego usar esta pantalla para descubrirlas todas en una sola operación. 
  Puedes entonces instalar todas las extensiones en un solo paso seleccionándolas
  todas y luego seleccionando el botón **Instalar** en la barra de herramientas.

*Traducido por openai.com*

