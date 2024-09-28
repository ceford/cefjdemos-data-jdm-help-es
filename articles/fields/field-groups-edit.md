<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group  / Display title: Composant : Modifier le groupe de champs -->

## Descripción

Los Grupos de Campos se utilizan para recopilar campos relacionados bajo una pestaña nombrada en un formulario de entrada de datos. El Componente: Editar Grupo de Campos es similar para todos los componentes que implementan campos, pero el título de la página cambia dependiendo del contexto: Artículos: Editar Grupo de Campos, Contactos: Editar Grupo de Campos o Usuarios: Editar Grupo de Campos.

### Elementos Comunes

Algunos aspectos de esta página se cubren en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Publicación](jdocmanual?article=help/common-elements/edit-publishing).
* [La Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo Acceder

* Selecciona **Contenido → Grupos de Campos** desde el menú del Administrador. O...
* Selecciona **Contacto → Grupos de Campos** desde el menú del Administrador. O...
* Selecciona **Usuarios → Grupos de Campos** desde el menú del Administrador. Luego...
  * selecciona el botón **Nuevo** en la Barra de Herramientas para crear un nuevo campo. O...
  * Selecciona un **Título** de la lista para editar un campo existente.

**Nota:** Hay un menú desplegable que permite la creación de Campos para una
Categoría, y Correo en el componente de Contacto. Requieren cierta experiencia en codificación para preparar las sobrescrituras de plantillas adecuadas.

## Captura de pantalla

Este ejemplo es una página de *Artículos: Editar Grupo de Campos*. *Contactos: Editar Grupo de Campos* y *Usuarios: Editar Grupo de Campos* son similares.

![artículos editar grupo de campos](../../../es/images/fields/articles-edit-field-group.png)

## Campos del Formulario

- **Título** El Título para este grupo de campos.

### General

#### Panel Izquierdo

- **Descripción** Texto que se mostrará como una nota informativa al pasar el ratón 
  sobre el cuadro de texto mientras se crea un artículo, un contacto o un 
  componente de terceros que soporte campos personalizados. Este texto no es 
  traducible. No verás esta descripción en el Frontend.

#### Panel Derecho

- **Estado** El estado publicado de este grupo de campos.
  - *Publicado* El grupo de campos es visible mientras se edita un artículo o un 
    contacto. Y es visible en el Frontend.
  - *No publicado* El grupo de campos no será visible para los usuarios mientras 
    editan un artículo o un contacto.
  - *Archivado* El grupo de campos ya no se mostrará al editar un artículo o un 
    contacto. Puedes abrirlo en Grupos de Campos configurando el filtro en archivado.
  - *En la papelera* El grupo de campos está eliminado pero aún en la base de datos. 
    Puede ser eliminado permanentemente de la base de datos en Grupos de Campos con 
    la función Vaciar Papelera.
- **Acceso** Selecciona el nivel de acceso de visualización para este grupo de campos. Los 
  niveles de acceso dependen de lo que se haya configurado en Usuarios: Niveles de Acceso.
- **Idioma** Selecciona el idioma para este grupo de campos. Si no estás usando la 
  función de multilenguaje de Joomla, deja el valor predeterminado de *Todo*.
- **Nota** Un campo opcional para tomar notas personales sobre el grupo de campos.

### Opciones

- **Mostrar cuando solo lectura** Si el grupo de campos es solo de lectura (tal vez 
  el usuario no tiene el nivel de acceso) ¿debería mostrarse o ocultarse el grupo de campos?

*Traducido por openai.com*

