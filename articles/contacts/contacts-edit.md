<!-- Filename: Help4.x:Contacts:_New_or_Edit  / Display title: Contacts : Modifier  -->

## Descripción

El *Formulario de Edición de Contactos* se utiliza para añadir un nuevo Contacto o editar un Contacto existente.

**Ten en cuenta:** Si un contacto tiene un elemento de menú, entonces la Configuración del Menú de Contacto
anula algunas configuraciones disponibles aquí. ¡Cuidado con no
divulgar información personal por error!

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda por separado:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [La pestaña Publicación](jdocmanual?article=help/common-elements/edit-publishing).
* [La pestaña Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La ventana emergente de Historial de Versiones](jdocmanual?article=help/common-elements/edit-version-history).

## Cómo Acceder

- Seleccione **Componentes → Contactos → Contactos** en el menú del Administrador.
- Para **Agregar** un nuevo Contacto:
  - Seleccione el botón **Nuevo** en la Barra de Herramientas.
- Para **Editar** un Contacto existente:
  - Seleccione un título de contacto en la columna **Título**.

## Captura de pantalla

![Tab de edición de contactos](../../../es/images/contacts/contacts-edit-contact-tab.png)

## Campos del Formulario

En esta sección, puedes ingresar información sobre el contacto, como
nombre, dirección, correo electrónico, etc. Las opciones te permiten controlar
configuraciones como qué información se muestra para cada contacto.

- **Nombre** El nombre completo del contacto.
- **Alias** El nombre interno del elemento. Normalmente, puedes dejar esto
  en blanco y Joomla llenará un valor predeterminado con el título en minúsculas y
  con guiones en lugar de espacios.

### Pestaña Editar Contacto

Aquí ingresas la información básica sobre el contacto.

- **Usuario Vinculado** Si este contacto está vinculado a un usuario, selecciona el icono *Seleccionar Usuario*
  para revelar un formulario emergente desde el cual seleccionar uno de los usuarios registrados.
  Un usuario vinculado puede ser eliminado con el botón *- Ningún Usuario -* en el 
  formulario emergente de Seleccionar Usuario.
- **Imagen** La imagen a mostrar para este contacto. Selecciona un archivo de imagen
  de la lista desplegable. Esto muestra imágenes en la carpeta 'images/stories'.
  Las imágenes pueden ser subidas usando el componente de Medios.
- **Posición** La posición actual del contacto.
- **Correo Electrónico** La dirección de correo electrónico del contacto. Ten en cuenta que las direcciones de correo electrónico
  en Joomla! pueden ser protegidas de "spambots" habilitando el Plugin "Cloaking de Correo Electrónico de Contenido".
  Esto está habilitado por defecto.
- **Dirección** La dirección del contacto.
- **Ciudad o Suburbio** La ciudad o suburbio del contacto.
- **Estado o Provincia** El estado o provincia del contacto.
- **Código Postal / ZIP** El código postal del contacto.
- **País** El país del contacto.
- **Teléfono** El número de teléfono del contacto.
- **Móvil** El número de teléfono móvil del contacto.
- **Fax** El número de fax del contacto.
- **Sitio Web** La dirección del sitio web del contacto.
- **Campos de Ordenar** Para habilitar campos de ordenar en listas de Categoría, ve a la
  pantalla **Contactos → Opciones** y ajusta **Diseños de Lista → Ordenar Por** 
  a **Ordenar Nombre**. Luego necesitas usar palabras reales para la ordenación.
  Por ejemplo, establece el Primer Campo de Ordenar en **Doe**, el segundo campo en **John**
  para el primer contacto; luego el Primer Campo de Ordenar en **Doe**, el segundo campo
  en **Jane** para el segundo contacto. El tercer campo no se usa en
  este caso. Los campos de ordenación son campos de caracteres, así que si quieres ordenar
  por edad necesitas ingresar 0x para edades menores de 10, por ejemplo, 08.
  - **Primer Campo de Ordenar** El nombre a usar como el primer campo de ordenar.
  - **Segundo Campo de Ordenar** El nombre a usar como el segundo campo de ordenar.
  - **Tercer Campo de Ordenar** El nombre a usar como el tercer campo de ordenar.
- **Estado**: El estado publicado del elemento. Los valores posibles son:
  - *Publicado*: El elemento está publicado. Este es el único estado que permitirá
    a los usuarios regulares del sitio web ver este elemento.
  - *No Publicado*: El elemento no está publicado.
  - *Archivado*: El elemento ha sido archivado.
  - *En Papelera*: El elemento ha sido enviado a la Papelera.
- **Categoría** La categoría a la que pertenece este elemento.
- **Destacado** Si el elemento se mostrará o no en la vista destacada.
- **Acceso** El nivel de acceso de visualización para este elemento.
- **Idioma** El idioma del elemento.
- **Etiquetas** Ingresa una o más etiquetas opcionales para este elemento. Puedes
  seleccionar etiquetas existentes ingresando las primeras letras. También
  puedes crear nuevas etiquetas ingresándolas aquí. Las etiquetas te permiten ver
  listas de elementos relacionados a través de tipos de contenido (por ejemplo, artículos,
  contactos y categorías).
- **Nota de Versión** Campo opcional para identificar esta versión del elemento
  en la ventana de Historial de Versiones del elemento.

### Pestaña Información Miscelánea

![Pestaña de editar contacto de Contactos](../../../es/images/contacts/contacts-edit-miscellaneous-tab.png)

Otra información sobre este contacto puede ser ingresada usando el editor.

### Pestaña Mostrar

![Pestaña de editar contacto de Contactos](../../../es/images/contacts/contacts-edit-display-tab.png)

- **Mostrar Categoría** Mostrar u ocultar la categoría del contacto.
- **Mostrar Lista de Contactos** Mostrar u ocultar la lista de contactos.
- **Formato de Visualización** Determina el estilo usado para mostrar secciones del formulario de contacto.
- **Etiquetas** Mostrar u ocultar cualquier etiqueta de este elemento.
- **Información del Contacto** Mostrar u ocultar la información del contacto.
- **Información Miscelánea** Mostrar u ocultar la información miscelánea.
- **vCard** Mostrar u ocultar el enlace vCard para este contacto.
- **Mostrar Artículos del Usuario** Si este contacto está mapeado a un usuario, y si
  esto está configurado en Mostrar, entonces se mostrará una lista de artículos creados por este usuario.
- **\# Artículos para Listar** Número de artículos para listar.
- **Perfil de Usuario** Si este contacto está mapeado a un usuario, y si esto
  está configurado en Mostrar, entonces se mostrará el perfil de este usuario.
- **Mostrar Grupos de Campos Personalizados del Usuario** Mostrar campos personalizados del usuario que
  pertenecen a todos o solo a grupos de campos seleccionados.
- **Enlaces de Contacto** Mostrar u ocultar los enlaces de contacto.
- **Etiqueta del Enlace A** Etiqueta para un enlace adicional para este contacto.
- **URL del Enlace A** La URL del enlace adicional para este contacto.
- **Etiqueta del Enlace B** Etiqueta para un enlace adicional para este contacto.
- **URL del Enlace B** La URL del enlace adicional para este contacto.
- **Etiqueta del Enlace C** Etiqueta para un enlace adicional para este contacto.
- **URL del Enlace C** La URL del enlace adicional para este contacto.
- **Etiqueta del Enlace D** Etiqueta para un enlace adicional para este contacto.
- **URL del Enlace D** La URL del enlace adicional para este contacto.
- **Etiqueta del Enlace E** Etiqueta para un enlace adicional para este contacto.
- **URL del Enlace E** La URL del enlace adicional para este contacto.
- **Diseño** Usar un diseño diferente del componente suministrado o
  sobrescrituras en las plantillas.

### Pestaña Formulario

![Pestaña de editar contacto de Contactos](../../../es/images/contacts/contacts-edit-form-tab.png)

- **Formulario de Contacto** Mostrar u ocultar el formulario de correo electrónico. Si se selecciona Mostrar, se
  muestra un formulario que permite al usuario enviar un correo electrónico al
  contacto desde el sitio web.
- **Enviar Copia al Remitente** Mostrar u ocultar la casilla de verificación: 
  *Enviar una copia de este mensaje a tu propia dirección.*
- **Verificación de Sesión** Verificar la existencia de la cookie de sesión. Esto
  significa que los usuarios sin cookies habilitadas no podrán enviar
  correos electrónicos.
- **Respuesta Personalizada** Desactiva la respuesta automatizada, permitiendo que los Plugins
  manejen la integración con otros sistemas.
- **Redirección de Contacto** Ingresa una URL alternativa, donde el usuario será
  redirigido después de que el correo electrónico se envíe.

*Traducido por openai.com*

