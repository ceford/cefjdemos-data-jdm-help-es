<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Crear Artículo -->

## Descripción

El ítem de menú *Crear Artículo* permite a los usuarios enviar un artículo a través de la interfaz del sitio. Normalmente, esto está disponible solo para usuarios que han iniciado sesión en el Frontend del sitio. Los usuarios deben tener permisos para crear artículos.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña Detalles](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La pestaña Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La pestaña Visualización de la Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La pestaña Metadatos](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La pestaña Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La pestaña Asignación de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Cómo Acceder

Selecciona **Menús → \[nombre del menú\]** desde el menú de Administrador.

Para agregar un ítem de menú:

1.  Selecciona el botón **Nuevo** en la barra de herramientas.
2.  Selecciona el botón **Seleccionar** en *Tipo de Ítem de Menú*.
3.  Selecciona el ítem **Artículos** en el cuadro de diálogo emergente.
4.  Selecciona el ítem **Crear Artículo**.

Para editar un ítem de menú:

- Selecciona un **Título** de la lista.

## Captura de Pantalla

![Ítem de Menú Crear Artículo](../../../es/images/menu-items/articles-create-article-details-tab.png)

## Campos del Formulario

- **Título** El título que se mostrará para este ítem de menú.
- **Alias** El nombre interno del ítem de menú. Normalmente, puedes dejar
  este campo en blanco y Joomla llenará un valor predeterminado con el Título en minúsculas y con guiones en lugar de espacios.

### Detalles

#### Panel Izquierdo

- **Tipo de Ítem de Menú** El tipo de ítem de menú seleccionado cuando se creó este ítem de menú. Puede ser uno de los tipos de ítems de menú principales o un tipo de ítem de menú proporcionado por una extensión instalada.
- **Enlace** El enlace generado por el sistema para este ítem de menú. Este campo no se puede cambiar y es solo para información.
- **Ventana de Destino** Selecciona del menú desplegable.
- **Estilo de Plantilla** Selecciona del menú desplegable.

#### Panel Derecho

- **Menú** Muestra en qué menú aparecerá el enlace.

### Opciones

![Ítem de Menú Crear Artículo opciones](../../../es/images/menu-items/articles-create-article-options-tab.png)

- **Categoría Específica**
  - *Sí* Los artículos se asignarán a la categoría especificada. El usuario no podrá seleccionar una categoría.
  - *No* El usuario podrá seleccionar la categoría desde el cuadro de lista. Solo se mostrarán las categorías para las cuales el usuario tenga permiso de *Crear*.
- **Redirección al Enviar/Cancelar** Selecciona la página a la que el usuario será redirigido después de enviar un artículo exitosamente.
- **Redirección Personalizada al Cancelar**
  - *Sí* Establece una página a la que se redirigirá cuando el usuario cancele el envío del artículo.
  - *No* Cuando el usuario cancele el envío del artículo, será redirigido a la página de *Redirección al Enviar/Cancelar*.

## Ejemplo de Captura de Pantalla del Frontend

Esta captura de pantalla muestra la plantilla Frontend de Joomla **Cassiopeia** con todas las opciones de diseño de edición configuradas en 'Ocultar'.

[articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Consejos

Un usuario no autorizado normalmente recibirá un error al seleccionar un ítem de menú *Crear Artículo*. Por esta razón, es una práctica común dar al ítem de menú un Nivel de Acceso de visualización que solo pueda ser visto por usuarios autorizados para agregar artículos.
