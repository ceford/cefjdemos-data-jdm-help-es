<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensiones: Instalar -->

## Descripción

Las Extensiones se utilizan para agregar capacidades a Joomla! que no existen en la instalación estándar. Hay cientos de extensiones disponibles para Joomla!, y continuamente se desarrollan más.

Las extensiones se categorizan en cinco tipos, como sigue:

- Un *Componente* es una mini-aplicación que renderiza el cuerpo principal de la página. Ejemplos de Componentes son Contactos, la Página Principal y las Fuentes de Noticias.
- Un *Módulo* es una Extensión más pequeña, típicamente utilizada para renderizar un pequeño elemento que se muestra en múltiples páginas. Ejemplos de Módulos incluyen Menús y Elementos Relacionados.
- Un *Plugin* es una sección de código que se ejecuta cuando ocurre un evento predefinido dentro de Joomla!. Por ejemplo, los editores son Plugins que se ejecutan cuando se abre una sesión de edición.
- La Extensión de *Idioma* permite que el Front-end y Back-end de Joomla! se presenten en cualquier idioma para el cual exista una extensión de idioma. De esta manera, Joomla! puede lanzarse en un nuevo idioma sin cambios en el programa principal.
- Un *Template* controla la forma en que se muestra el contenido de un sitio web, incluyendo la ubicación y disposición de los elementos, colores, fuentes, etc. Los Templates permiten que la apariencia del sitio web se separe de su contenido.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de Ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

- Selecciona **Sistema → Panel de Instalación → Extensiones** desde el menú del Administrador.

Hay cuatro métodos de instalación disponibles. Si **Instalar desde Web** ha sido seleccionado primero en la lista o fue el último método seleccionado, habrá un breve retraso mientras Joomla descarga una selección inicial de datos de Extensiones desde el Directorio de Extensiones de Joomla.

El orden normal de las pestañas para los métodos de instalación es el siguiente:

* Subir archivo de paquete
* Instalar desde carpeta
* Instalar desde URL
* Instalar desde Web

Solo se necesita un método para instalar una Extensión. El procedimiento normal para instalar una Extensión de Joomla! es el siguiente:

1.  Descarga uno o más archivos comprimidos (normalmente en formato ".zip" o "tar.gz") desde el sitio web del proveedor de la Extensión a un directorio local en tu computadora. Nota que algunas Extensiones se instalan como un solo archivo (por ejemplo, un Componente o Módulo) mientras que otras pueden tener dos o más archivos (por ejemplo, un Componente y un Módulo). Si hay dos o más partes, cada una puede tener su propio archivo comprimido, o las partes pueden estar combinadas en un archivo de paquete.
2.  Elige uno de los métodos descritos para instalar la extensión.
3.  Cuando haya finalizado, la pantalla mostrará un mensaje de **Éxito** o **Error**.
4.  Dependiendo de la Extensión, puede ser necesario habilitarla (por ejemplo, en las listas de Módulos o Plugins).

## Pestaña Subir archivo de paquete

![Pestaña de instalación de extensión subir archivo de paquete](../../../es/images/extensions/install-upload-package-file.png)

- Arrastra y suelta o navega hasta la ubicación donde descargaste el archivo comprimido de la Extensión.

La subida comienza automáticamente. Nota el **Tamaño máximo de subida: 32.00MB** definido para tu instalación. Si no puedes aumentar este valor, puedes usar *Instalar desde carpeta*.

## Pestaña Instalar desde carpeta

![Pestaña de instalación de extensión desde carpeta](../../../es/images/extensions/install-from-folder.png)

1.  Crea un directorio temporal en tu disco duro local y descomprime el archivo comprimido de la Extensión en este directorio temporal.
2.  Utilizando FTP, sube el contenido de este directorio (incluyendo archivos y subdirectorios) a un directorio en tu servidor.
3.  En el campo *Directorio de Instalación*, especifica el directorio del servidor donde subiste los archivos y subdirectorios del paquete.
4.  Haz clic en el botón *Verificar e Instalar* y Joomla! instalará el contenido del directorio dado.

Ten en cuenta que es una práctica común colocar la carpeta que contiene tu extensión descomprimida en la carpeta tmp de tu sitio Joomla.

## Pestaña Instalar desde URL

![Pestaña de instalación de extensión desde URL](../../../es/images/extensions/install-from-url.png)

En lugar de descargar el archivo comprimido en tu computadora local, solo especifica la URL del archivo comprimido objetivo. Luego haz clic en el botón "Verificar e Instalar" y Joomla! lo instalará automáticamente directamente desde esta URL. *Ten en cuenta que, con este método, no tendrás una copia del archivo comprimido en tu computadora local.*

## Pestaña Instalar desde Web

Para instalar una extensión directamente desde el Directorio de Extensiones de Joomla (JED). Puedes seleccionar extensiones para listar por Categoría o buscar por nombre parcial.

![Pestaña de instalación de extensión desde web](../../../es/images/extensions/install-from-web.png)

## Consejos

- Cuatro métodos alternativos de instalación están disponibles, como se indicó anteriormente. El más común es el método "Subir archivo de paquete".
- Si deseas instalar un Módulo o Plugin de terceros que pertenece a un Componente, generalmente necesitarás instalar el Componente así como el Módulo o Plugin para poder usar el Módulo o Plugin. Esto normalmente está documentado en las instrucciones de instalación de la Extensión en el sitio web del autor.
- De manera similar, si desinstalas un Componente de terceros que también tiene sus propios Módulos o Plugins, estos Módulos y Plugins ya no podrán ser utilizados. Por lo tanto, normalmente se recomienda desinstalar también estos Módulos y Plugins dependientes.
- Algunos Componentes desarrollados por desarrolladores de terceros pueden incluir sus propios Módulos o Plugins en el instalador. En este caso, asegúrate de que los directorios del Módulo o Plugin sean escribibles. De lo contrario, la Extensión no funcionará correctamente.
- **ADVERTENCIA DE SEGURIDAD:** Se recomienda que uses solo aquellas Extensiones de terceros que realmente necesites en tu sitio. No uses tu sitio en vivo para pruebas, ya que podría comprometer tu sitio y servidor. Prueba nuevas extensiones en un sitio de prueba local antes de implementarlas en tu sitio en vivo.
- No instales Extensiones de Joomla! descargadas de sitios de [Warez](https://es.wikipedia.org/wiki/Warez) porque pueden estar infectadas con un virus o malware que puede causar daños en el servidor y contaminar la computadora de tus visitantes.
- Instalar desde URL remota puede ser peligroso. Por esta razón, generalmente se recomienda usar las opciones "Instalar desde Web", "Subir archivo de paquete" o "Instalar desde carpeta" cuando instales nuevas Extensiones.
