<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Configuración Global -->

## Descripción

La pantalla de Configuración Global te permite configurar el sitio de Joomla con tus preferencias personales. Los ajustes realizados en esta pantalla se aplican a todo el sitio.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de Ayuda por separado:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo acceder

- Selecciona **Panel de Sistema → Configuración Global** desde el Tablero Principal. O...
- Selecciona **Sistema → Panel de Configuración → Configuración Global** desde el menú del Administrador.

## Captura de Pantalla

![Pestaña de configuración global del sitio](../../../es/images/site/global-configuration-site-tab.png)

## Campos del Formulario

### Pestaña del Sitio

#### Panel del Sitio

- **Nombre del Sitio** Introduce el nombre del sitio web. Se utilizará en varios lugares (por ejemplo, en la barra de título del navegador en el Backend y en las páginas de Sitio Offline).
- **Sitio Offline** Selecciona si el acceso al Frontend está disponible.
- **Mensaje Offline**
    - *Ocultar*
    - *Usar Mensaje Personalizado* El mensaje utiliza el valor definido en el campo *Mensaje Personalizado*.
    - *Usar Mensaje Predeterminado del Idioma del Sitio* El mensaje utiliza el valor definido en el archivo ini del idioma del sitio.
- **Imagen Offline** Selecciona una imagen para mostrar en la página de Offline. Asegúrate de que la imagen tenga menos de 400px de ancho.
- **Edición en el Frontend** Selecciona la edición para módulos y elementos de menú.
- **Editor Predeterminado** Selecciona el editor de texto predeterminado. Los usuarios registrados podrán cambiar su preferencia en sus datos personales.
- **Captcha Predeterminado** Selecciona el captcha predeterminado para tu sitio. Es posible que debas ingresar la información requerida en el plugin de captcha.
- **Nivel de Acceso Predeterminado** Selecciona el nivel de acceso predeterminado para nuevos elementos.
- **Límite de Lista Predeterminado** Establece la longitud predeterminada de las listas en el Backend para todos los usuarios.
- **Límite de Feed Predeterminado** Selecciona el número de artículos de contenido para mostrar en los feeds.
- **Correo Electrónico del Feed** Los feeds de noticias RSS y Atom incluyen la dirección de correo electrónico del autor.
  - *Correo Electrónico del Autor* Incluir el correo electrónico del autor del artículo desde el Perfil de Usuario en el feed de noticias.
  - *Correo Electrónico del Sitio* Incluir la dirección de correo *De Email* del sitio para cada artículo.

#### Panel de Metadatos

- **Descripción Meta del Sitio** Introduce una descripción general del sitio web que será utilizada por los motores de búsqueda.
- **Robots** Instrucciones para robots.
  - *index, follow* Indexa esta página y sigue los enlaces en esta página.
  - *noindex, follow* No indexar esta página, pero seguir los enlaces en la página. Por ejemplo, puedes hacer esto para una página de mapa del sitio donde deseas que se indexen los enlaces pero no deseas que esta página aparezca en los motores de búsqueda.
  - *index, nofollow* Indexa esta página, pero no sigas los enlaces en la página. Por ejemplo, puedes hacer esto para un calendario de eventos, donde deseas que la página aparezca en los motores de búsqueda pero no deseas que se indexe cada evento.
  - *noindex, nofollow* No indexar esta página ni seguir los enlaces en la página.
- **Derechos de Contenido** Describe qué derechos tienen otros para utilizar este contenido. Esto se comunica a los motores de búsqueda mediante la etiqueta meta `rights` en la cabecera HTML.
- **Metaetiqueta de Autor** Muestra la metaetiqueta del autor al ver artículos.
- **Versión de Joomla** Controla si la etiqueta meta `generator` en la cabecera del documento HTML en el Frontend y en los feeds Atom incluye la versión exacta del sitio Joomla. Se recomienda ocultarlo por razones de seguridad.

#### Panel SEO

- **URLs Amigables para Motores de Búsqueda** Selecciona si las URLs están optimizadas para los motores de búsqueda.
- **Usar Reescritura de URL**
  - *Apache y Litespeed* Renombrar `htaccess.txt` a `.htaccess`.
  - *IIS* Renombrar `web.config.txt` a `web.config`.
  - *NginX* Debes configurar tu servidor.
  - *Otro* Si no estás seguro, consulta a tu proveedor de hosting.
- **Agregar Sufijo a la URL** Si seleccionas sí, el sistema agregará un sufijo a la URL según el tipo de documento.
- **Aliases Unicode** Elige entre transliteración y aliases Unicode. La transliteración es el valor predeterminado.
- **Nombre del Sitio en los Títulos de Página** Comienza o termina todos los Títulos de Página con el nombre del sitio (por ejemplo, *Mi Nombre de Sitio - Mi Nombre de Artículo*).

#### Panel de Cookies

- **Dominio de la Cookie** Dominio a usar al establecer cookies de sesión. Precede el dominio con '.' si la cookie debe ser válida para todos los subdominios.
- **Ruta de la Cookie** Ruta para la cual la cookie debe ser válida.

### Pestaña Sistema

![Pestaña del sistema de configuración global](../../../es/images/site/global-configuration-system-tab.png)

#### Panel de Depuración

- **Depurar Sistema** Si está activado, se mostrará información de diagnóstico, traducción de idiomas y errores SQL (si los hay). La información se mostrará en el pie de cada página que veas en el Backend y Frontend de Joomla. No es recomendable dejar el modo de depuración activado en un sitio web en producción.
- **Depurar Idioma** Habilita para ver los indicadores de depuración `**...**` o `??...??` en la salida de página donde los archivos de idiomas de Joomla se utilizan para traducir claves de cadenas a sus valores traducidos. El primer formato indica que la cadena se ha traducido correctamente. El segundo indica que el texto se ha ingresado en lenguaje común y no se puede traducir.
  - **Mostrar Idioma** Selecciona si debes mostrar la constante del idioma o el valor del idioma cuando depures las cadenas de idioma.

#### Panel de Caché

- **Caché del Sistema** Habilita el caché y establece el nivel de caché.
  - *Nivel Conservador* Caché del sistema más pequeño.
  - *Nivel Progresivo* Caché del sistema más rápido y grande, incluye caché de renderizadores de módulos. No es apropiado para sitios extremadamente grandes.
  - **Manejador de Caché**
    - *Archivo* El mecanismo de caché nativo es basado en archivos. Asegúrate de que las carpetas de caché sean escribibles.
  - **Caché Específico de la Plataforma** Habilita cuando la salida HTML en dispositivos móviles difiere de otros dispositivos.
  - **Tiempo de Caché (minutos)** La duración máxima en minutos para que se almacene un archivo de caché antes de que se actualice.
  - **Ruta a la Carpeta de Caché** Especifica una carpeta escribible para almacenar archivos de caché si no deseas usar la carpeta predeterminada.

#### Panel de Sesiones

- **Manejador de Sesiones** El mecanismo mediante el cual Joomla identifica a un Usuario una vez que se conecta al sitio web utilizando cookies no persistentes.
  - *Base de Datos* El manejador de sesión de base de datos es el manejador predeterminado porque es el único que Joomla puede configurar y controlar completamente por su cuenta.
  - *Sistema de Archivos* El manejador de sistema de archivos será ligeramente más eficiente que el manejador de base de datos, pero requiere que PHP esté configurado correctamente, de lo contrario, se bloqueará y Joomla será totalmente inutilizable.
    - *Ruta de Guardado de Sesiones* Introduce una ruta de sistema de archivos completa. Asegúrate de que la ruta tenga permisos adecuados para que PHP pueda leer y escribir archivos, y si `la recolección de basura de sesiones` está habilitada, para eliminar archivos de ella. Si esta ruta no está establecida, Joomla dependerá de la configuración `session.save_path INI` de PHP o recurrirá al directorio temporal del sistema (según lo definido por la función PHP sys_get_temp_dir()). Si ninguna de esas rutas está configurada o los permisos son incorrectos, se acabó el juego. Para recuperarte, edita el archivo configuration.php y establece `$session_handler = 'database'`.
  - *Otros Manejadores* APCu, Memcached, Redis y WinCache dependen de extensiones opcionales de PHP y pueden estar disponibles si tu sistema las soporta. APCu o WinCache pueden no ser mejores que la opción de *sistema de archivos* simple. Los manejadores de Memcached y Redis son excesivos para Joomla en un entorno típico de hosting compartido. Esos tipos de manejadores tienen éxito si estás implementando Joomla en un entorno balanceado donde intervienen múltiples servidores y necesitas que los datos de sesión de la aplicación estén disponibles en todos los servidores.
- **Duración de la Sesión (minutos)** Cierra sesión automáticamente a un Usuario después de que ha estado inactivo durante el número de minutos ingresado. No lo establezcas demasiado alto.
- **Sesiones Compartidas** Cuando está habilitado, la sesión de un usuario se comparte entre las secciones Frontend y Backend del sitio. Ten en cuenta que cambiar este valor invalidará todas las sesiones existentes en el sitio. Esto no está disponible cuando la opción *Forzar HTTPS* está configurada como *Solo Administrador*.
- **Rastrear Metadatos de Sesión**
  - *Sí* Se registrará información adicional sobre la sesión de un usuario (incluyendo su nombre de usuario, ID de usuario y en qué aplicación están conectados) en la tabla de base de datos de sesiones.
  - *No* Las funciones dependientes de estos datos no estarán disponibles.

### Pestaña del Servidor

![Pestaña del servidor de configuración global](../../../es/images/site/global-configuration-server-tab.png)

#### Panel del Servidor

- **Ruta a la Carpeta Temporal** Por favor, especifica una carpeta escribible para almacenar archivos temporales.
- **Compresión de Página Gzip**
  - *Sí* Comprime automáticamente las páginas HTML generadas con Gzip, haciéndolas más pequeñas y aumentando la puntuación de velocidad de tu sitio.
  - *No* Si tu servidor ya lo está haciendo por ti o si entra en conflicto con extensiones de terceros.
- **Informes de Errores** Este parámetro establece el nivel de informes de errores que utilizará PHP en el sitio de Joomla.
  - *Predeterminado del Sistema* Deja el nivel de informes de errores al configurado en el servidor.
  - *Ninguno* Desactiva el informe de errores.
  - *Simple* Anula la configuración del servidor para dar un nivel básico de informes.
  - *Máximo* Anula la configuración del servidor para permitir el informe de todos los errores. Si tu sitio de Joomla falla hasta el punto en que no es posible utilizar la página de administrador para activar el informe de errores, puedes activar el informe completo editando el archivo `configuration.php`. Establecer `$error_reporting = 'maximum'` es equivalente a establecer *Informe de Errores* en *Máximo*.
- **Forzar HTTPS** Forzar el acceso al sitio en las áreas seleccionadas para que ocurra solo con HTTPS (conexiones HTTP encriptadas con el prefijo de protocolo https://) y también forzar el uso de cookies seguras. Ten en cuenta que debes tener HTTPS habilitado en tu servidor para utilizar esta opción.

#### Panel de Ubicación

- **Zona Horaria del Sitio Web** Elige una ciudad en la lista para configurar la fecha y hora para su visualización.

#### Panel de Servicios Web

- **Habilitar CORS** El Compartir Recursos de Origen Cruzado o [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) permite que los scripts que se ejecutan en un navegador interactúen con recursos de un origen diferente.
  - **Access-Control-Allow-Origin** Especifica el origen permitido para acceder a los servicios web en este sitio, enviado en respuesta a una solicitud preliminar. Predeterminado: `*` (=todos).
  - **Access-Control-Allow-Headers** Especifica el(los) encabezado(s) enviados en respuesta a una solicitud preliminar. Predeterminado: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Especifica el(los) método(s) del servicio web permitidos para acceder a este sitio, enviado en respuesta a una solicitud preliminar. Predeterminado: todos los métodos disponibles para la ruta solicitada.

#### Panel de Proxy

- **Detrás de un Balanceador de Carga** Si tu sitio está detrás de un balanceador de carga o un proxy inverso, habilita esta configuración para que las direcciones IP y otras configuraciones dentro de Joomla lo tengan en cuenta automáticamente.
- **Habilitar Proxy Saliente** Algunos hosts no permiten ningún acceso de red desde tu sitio al exterior por defecto y requieren que configures manualmente un proxy saliente.
  - **Host de Proxy Saliente** Nombre de dominio o dirección IP.
  - **Puerto de Proxy Saliente**
  - **Nombre de Usuario de Proxy Saliente** Deja en blanco si tu proxy saliente no requiere autenticación.
  - **Contraseña de Proxy Saliente**

#### Panel de Base de Datos

- **Tipo de Base de Datos** El tipo de base de datos en uso, seleccionado durante el proceso de instalación. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Host** El nombre de host para tu base de datos ingresado durante el proceso de instalación. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Nombre de Usuario de la Base de Datos** El nombre de usuario para acceder a tu base de datos ingresado durante el proceso de instalación. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Contraseña de la Base de Datos** La contraseña a utilizar para acceder a la base de datos. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Nombre de la Base de Datos** El nombre de tu base de datos ingresado durante el proceso de instalación. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Prefijo de Tablas de la Base de Datos** El prefijo utilizado para tus tablas de base de datos, creado durante el proceso de instalación. No edites este campo a menos que sea absolutamente necesario (por ejemplo, la transferencia de la base de datos a un nuevo proveedor de hosting).
- **Cifrado de Conexión**
  - Predeterminado (controlado por el servidor)
  - Autenticación unidireccional
    - **Verificar Certificado del Servidor**
      - **Ruta al Archivo CA** Ruta del sistema de archivos.
  - Autenticación bidireccional
    - **Ruta al Archivo de Clave Privada** Ubicación del sistema de archivos.
    - **Ruta al Archivo de Certificado** Ubicación del sistema de archivos.
    - **Verificar Certificado del Servidor**
      - **Ruta al Archivo CA** Ruta del sistema de archivos.
    - **Suite de Cifrado Soportada (opcional)** No se requiere entrada (solo recomendada para usuarios experimentados). Para más detalles, consulta la documentación de tu base de datos.

#### Panel de Correo

- **Enviar Correo**
  - *Sí* Activa el envío de correos.
  - *No* Desactiva el envío de correos. Se recomienda poner el sitio offline al desactivar la función de correo.
- **Deshabilitar Correo Masivo**
  - *Sí* Desactiva la función de Correo Masivo a Usuarios.
  - *No* Activa la función de Correo Masivo a Usuarios.
- **Correo Electrónico de Origen** La dirección de correo electrónico que se utilizará para enviar correos del sitio.
- **Nombre de Origen** Texto mostrado en el campo de encabezado *De:* al enviar un correo del sitio. Usualmente el nombre del sitio.
- **Correo Electrónico de Respuesta** La dirección de correo electrónico que se utilizará para recibir respuestas de los usuarios finales.
- **Nombre de Respuesta** Texto mostrado en el

 campo de encabezado *Para:* cuando los usuarios finales respondan al correo recibido.
- **Mailer** Selecciona qué mailer usar para la entrega del correo del sitio.

### Pestaña de Registro

![Pestaña de registro de configuración global](../../../es/images/site/global-configuration-logging-tab.png)

#### Panel de Registro

- **Ruta a la Carpeta de Registro** Joomla puede opcionalmente mantener un archivo de registro de sus propias operaciones y las de extensiones de terceros. Proporciona la ruta absoluta a una carpeta que sea escribible por PHP; si falta o no es escribible, Joomla no se cargará en absoluto. Por razones de seguridad, no debes usar una carpeta con acceso a nivel del sistema, como `/tmp`.
- **Registrar Casi Todo** Registra todo, excepto APIs obsoletas.
- **Registrar API Obsoleta** Registra APIs obsoletas.

#### Panel de Registro Personalizado

- **Prioridades de Registro** Se puede usar para gestionar el registro personalizado. Selecciona los eventos que deseas ver en el archivo de registro. El predeterminado es *Todos*. Los elementos pueden seleccionarse o deseleccionarse haciendo clic en la lista desplegable.
- **Categorías de Registro** Una lista separada por comas de categorías de registro para incluir o excluir. Las categorías de registro comunes incluyen, pero no se limitan a: `database`, `databasequery`, `database-error`, `deprecated` y `jerror`. Si está vacía, el registro personalizado está deshabilitado.
- **Modo de Categoría de Registro** Establece el modo para la lista de categorías de registro anterior.

### Pestaña de Filtros de Texto

![Pestaña de filtros de texto de configuración global](../../../es/images/site/global-configuration-text-filters-tab.png)

Estos ajustes de filtros de texto se aplicarán a todos los campos de editor de texto presentados por los usuarios en los grupos seleccionados.

Estas opciones de filtrado dan más control sobre el HTML que tus proveedores de contenido envían. Puedes ser tan estricto o tan liberal como necesites para satisfacer las necesidades de tu sitio. El filtrado es opcional y la configuración predeterminada proporciona buena protección contra el marcado comúnmente asociado con ataques a sitios web.

## Consejos

- La mayoría de estas configuraciones pueden establecerse una vez y luego dejarse solas.
- Si se necesitan hacer modificaciones importantes, considera poner el sitio offline para probarlo y asegurarte de que todo esté en orden.
- Las configuraciones se guardan en el archivo `configuration.php` en la raíz del sitio. Los permisos de este archivo se establecen como de solo lectura (444) después de realizar cambios a través de la página de Configuración Global y deben otorgarse permisos de escritura al propietario (644) antes de editarlo con un editor de texto.
