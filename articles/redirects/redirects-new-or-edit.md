<!-- Filename: Help4.x:Redirects:_New_or_Edit  / Display title: Redirections : Nouveau ou Modifier -->

## Descripción

La página *Redirecciones: Nueva o Editar* se utiliza para añadir una nueva redirección o editar
una existente. La URL desde la que desea redirigir no debe ser una URL funcional en
su sitio web que realmente cargue una página web. Puede ser la URL de una página web
que haya deshabilitado en la interfaz de administrador de Joomla!. La
URL de origen que especifique cuando cree la redirección debe ser la URL completa
tal como la escribiría en su navegador web. La URL de destino que
especifique cuando cree una redirección también debe ser la URL completa.

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

- Selecciona **Sistema → Redirecciones** desde el menú del Administrador. Luego...
  - Para crear un nuevo redireccionamiento, haz clic en el botón **Nuevo** en la Barra de herramientas. O...
  - Para editar un redireccionamiento existente, haz clic en su enlace en la columna **URL Expirada**.

## Captura de pantalla

![Redirige enlaces](../../../es/images/redirects/redirects-edit.png)

## Campos de Formulario

### Pestaña Editar/Nuevo Enlace \#1

- **URL Expirada** La URL a la que se redirigirá.
- **Nueva URL** La URL a la que redirigir.
- **Estado** Estado publicado del elemento. Los valores posibles son:
  - *Habilitado* El elemento está habilitado. Este es el único estado que 
    permitirá a los usuarios regulares del sitio web ver este elemento.
  - *Deshabilitado* El elemento está deshabilitado.
  - *Archivado* El elemento ha sido archivado.
  - *En la papelera* El elemento ha sido enviado a la papelera.
- **Comentario** Un comentario que solo puede ver un administrador. Está 
  destinado principalmente para referencia del administrador.
- **ID** Este es un número de identificación único para este elemento asignado 
  automáticamente por Joomla. Se usa para identificar el elemento internamente 
  y no puedes cambiar este número. Al crear un nuevo elemento, este campo 
  muestra "0" hasta que guardes la nueva entrada, momento en el cual se le 
  asignará un nuevo ID.
- **Fecha de Creación** Fecha en que se creó el elemento (Artículo, Categoría, etcétera).
- **Fecha de Última Actualización** Muestra la última fecha en que se modificó el elemento.

## Cómo Crear una Redirección

1. Primero, asegúrate de haber habilitado la opción *Usar Reescritura de URL* en las opciones de Configuración Global de tu instalación de Joomla!. Ten en cuenta que solo habilitar la opción *Usar Reescritura de URL* no es suficiente. También debes realizar el paso adicional de renombrar el archivo `htaccess.txt` en el directorio del servidor web donde instalaste Joomla! a `.htaccess` o al nombre de archivo que requiera tu servidor web Apache para directivas de configuración adicionales. En el archivo de configuración de Apache, esta configuración se llama `AccessFileName` y, por defecto, está configurada como `.htaccess`.
2. A continuación, abre la página *Redirección: Enlaces* y selecciona el botón de la barra de herramientas *Nuevo*.
3. En la página *Redirecciones: Nuevo*, ingresa la información de la redirección. Al ingresar URLs en los campos *URL Caducada* y *Nueva URL*, ingresa la URL completa tal como la escribirías en tu navegador web para verla. La *URL Caducada* debe ser una URL que no resuelva a ninguna página web válida en tu sitio web. Puedes especificar una URL de origen para una página web de Joomla! que hayas puesto en un estado deshabilitado en el backend del administrador. Asegúrate de que la opción *Estado* esté configurada como **Habilitado**.
4. Selecciona el botón de la barra de herramientas **Guardar & Cerrar** para guardar tu nueva redirección y ponerla en efecto.

## Consejos

- Al ingresar URLs en los campos *URL Expirada/Fuente* y *URL Nueva/Destino*, introduce la URL completa tal como la escribirías en tu navegador web para ver la página web.

*Traducido por openai.com*

