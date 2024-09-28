<!-- Filename: Help4.x:Site_System_Information  / Display title: Informations Système -->

## Descripción

La página de *Información del Sistema* proporciona información sobre el entorno del servidor anfitrión. Hay cinco paneles de pestañas diferentes: Información del Sistema, Configuración de PHP, Archivo de Configuración, Permisos de Carpetas e Información de PHP. Cada panel ofrece información detallada sobre ese aspecto del sitio. Es útil para solucionar problemas de configuración.

- Tenga en cuenta que ninguna de estas configuraciones se puede cambiar desde estos paneles. Esto debe realizarse en diferentes ubicaciones a lo largo de la instalación de Joomla!, dependiendo de la configuración específica.
- Algunas configuraciones se pueden cambiar desde la página de Configuración Global. Otras dependen de la configuración del servidor anfitrión y no se pueden cambiar desde dentro de Joomla!.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de ayuda por separado:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

- Seleccione **Sistema → Panel de Información → Información del Sistema** 
  desde el menú del Administrador.

## Captura de pantalla

![tablero de inicio](../../../es/images/site/system-information-tab.png)

## Pestañas de Formulario

### Pestaña de Información del Sistema

- **PHP Built on** Proporciona detalles del sistema operativo principal
  en el que se está ejecutando el servidor web que ejecuta Joomla.
- **Database Type** Proporciona el tipo de base de datos que se está utilizando
  en la instalación de Joomla.
- **Database Version** Proporciona la versión actual de la base de datos MySQL
  que se está utilizando en la instalación de Joomla.
- **Database Collation** Cómo está estructurada la base de datos MySQL
  para la información utilizada por Joomla!
- **Database Connection Collation** El conjunto de caracteres y la colación de
  la base de datos.
- **PHP Version** Proporciona la versión actual del script del servidor PHP
  que se está utilizando para esta instalación de Joomla.
- **Web Server** Proporciona el tipo y la versión actual del servidor web
  en el que se está ejecutando la instalación de Joomla!
- **Web Server to PHP Interface** El script que permite la interacción
  entre el servidor web (en la mayoría de los casos, Apache) y el lenguaje de scripting PHP.
- **Joomla! Version** Proporciona la versión actual de Joomla!. Se
  recomienda que siempre esté actualizada y usando la versión estable
  más reciente.
- **User Agent** El resumen del sistema operativo y la información del navegador
  de la máquina local del usuario actual, que se utiliza para crear un
  ID de sesión único para el acceso y la funcionalidad dentro del sitio web de Joomla!

### Pestaña de Configuración de PHP

![tablero de inicio](../../../es/images/site/php-settings-tab.png)

Esta pantalla muestra información sobre la Configuración de PHP. Si algo
de esto se destaca como incorrecto, debería corregirse.

- **Safe Mode** Configuración recomendada: OFF
- **Open basedir** Configuración recomendada: Depende del sitio
- **Display Errors** Configuración recomendada: OFF
- **Short Open Tags** Configuración recomendada: ON
- **File Uploads** Configuración recomendada: ON
- **Magic Quotes** Configuración recomendada: OFF
- **Register Globals** Configuración recomendada: OFF
- **Output Buffering** Configuración recomendada: OFF
- **Session Save Path** Configuración recomendada: Depende del sitio
- **Session Auto Start** Configuración recomendada: 0
- **XML Enabled** Configuración recomendada: YES
- **Zlib Enabled** Configuración recomendada: YES
- **Native ZIP Enabled** Configuración recomendada: YES
- **Disabled Functions** Configuración recomendada: Depende del sitio
- **Multibyte String (mbstring) Enabled** Configuración recomendada: YES
- **Iconv Available** Configuración recomendada: YES
- **Maximum Input Variables** Configuración recomendada: 2500

### Pestaña de Archivo de Configuración

![tablero de inicio](../../../es/images/site/configuration-file-tab.png)

Esta pestaña muestra el contenido del archivo *configuration.php* actual de Joomla!
que se almacena en el directorio `path-to-joomla-root`. Este archivo se crea automáticamente
cuando instalas Joomla! por primera vez y es donde se registran la mayoría de los cambios
en la sección de Configuración Global de Joomla. Ten en cuenta
que ninguna de las configuraciones puede cambiarse desde esta página. Usa la
Configuración Global para ver más información sobre estos ajustes y realizar cambios.

### Pestaña de Permisos de Carpetas

![tablero de inicio](../../../es/images/site/folder-permissions-tab.png)

Esta pestaña muestra una lista de los directorios a los que el servidor web debería
tener acceso de escritura. Ten en cuenta que todos los directorios listados en esta
página deben decir **Writable**. Si no, puede que necesites cambiar los
permisos para poder instalar y usar Joomla! con éxito. El
archivo configuration.php está incluido y se muestra como **Unwritable**.

### Pestaña de Información de PHP

![tablero de inicio](../../../es/images/site/php-information-tab.png)

Esta pestaña muestra la configuración del lenguaje de scripting del servidor PHP
que utiliza Joomla!, junto con toda la información
del sistema asociada que contribuye a la creación del servidor web. Es la salida de un script php.info integrado en
Joomla!.

PHP está instalado y se ejecuta en el servidor (de ahí lo de servidor del lado del servidor arriba),
y por lo tanto todas las configuraciones se hacen en el servidor. El visitante
del sitio web no necesita tener nada especial ejecutándose en su
máquina local para ver o usar cualquiera de las funcionalidades adicionales
que PHP aporta al sitio web.

Todas las configuraciones que probablemente alguna vez
se necesiten se muestran aquí. Cualquier cambio necesario se realizaría dentro de los archivos de configuración como *php.ini* en
el servidor web.

La cantidad de control que un propietario de un sitio web tiene sobre esta información depende de
si poseen el servidor o si el anfitrión del servidor es flexible en su
enfoque hacia el cliente.

Es una buena práctica conocer las limitaciones de una instalación de servidor
en particular. La salida de esta pantalla se utiliza para encontrar información detallada
sobre cómo se implementa PHP en el servidor.

Para obtener detalles completos sobre la información contenida en la pestaña Información de PHP,
visita: [http://php.net/phpinfo](http://php.net/phpinfo).

## Consejos

- Si tiene problemas para instalar extensiones, subir archivos o
  cambiar opciones de configuración, revise la pestaña de Permisos de Directorio
  para asegurarse de que tiene permiso para escribir en los archivos de su servidor web.
  El *Estado* de los directorios debe ser *Escribible*. Si no es así, es posible que
  no pueda subir o editar archivos en estos directorios.
- Cuando busque ayuda con problemas de configuración, por ejemplo, en un
  foro web de Joomla!, es muy útil publicar información específica
  sobre su instalación de Joomla!. Esta página es una forma fácil de encontrar
  toda esta información en un solo lugar. Aún mejor, utilice el 
  **Asistente de Publicaciones del Foro** documentado en la parte superior de las páginas individuales
  del Foro de Joomla, como el foro de 
  [Preguntas Generales](https://forum.joomla.org/viewforum.php?f=834).

*Traducido por openai.com*

