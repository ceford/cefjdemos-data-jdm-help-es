<!-- Filename: Help4.x:Component:_Fields  / Display title: Composant : Champs -->

## Descripción

Los campos se utilizan para mostrar atributos adicionales de Artículos, Contactos o Usuarios.
Los datos se ingresan en un formulario de edición del Administrador y se muestran en el Sitio.
Un ejemplo:

Supongamos que escribes artículos sobre aspectos de la naturaleza, a veces Flores, a veces
Animales. Un campo que podrías querer registrar y mostrar para ambos es el 
Nombre Latín, que requiere un campo de texto. Otro podría ser Hábitat: Bosque, Estanque,
Pradera, etc., que requiere una lista desplegable. Para las flores, podrías desear 
registrar la Temporada de Floración usando 4 casillas de verificación, una para cada estación, o 12 
casillas de verificación, una para cada mes.

Los campos vacíos en el formulario de entrada no se muestran en la salida del Sitio, por lo que 
podrías mantener todos los campos en una lista larga. Sin embargo, usualmente es mejor usar 
categorías para tus Artículos, por ejemplo, Flores y Animales. Los campos se pueden asignar 
a más de una Categoría. Por lo tanto, los campos de Nombre Latín y Hábitat se asignarían 
a ambos, pero el campo de Temporada de Floración solo se asignaría a la categoría de Flores.

Si un campo no está asignado a un grupo, aparecerá en el formulario de edición en una 
pestaña de Campos. Si un campo está asignado a un grupo, aparecerá en una pestaña con 
ese nombre. Así que para el grupo de Flores parece apropiado crear un grupo 
nombrado Datos de Flores (o simplemente Flores, aunque usar el mismo nombre para diferentes 
cosas puede resultar confuso). Y para los otros campos comunes podrías usar un grupo 
llamado Naturaleza.

### Elementos Comunes

Algunos elementos de esta página se abordan en artículos de ayuda por separado:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenación de Ítems de Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Proceso por Lote de Lista](jdocmanual?article=help/common-elements/list-batch-process).

### Artículo Relacionado

* Hay un ejemplo más extenso sobre el uso de [Campos y Grupos de Campos](jdocmanual?article=user/fields/fields-and-field-groups)
* Hay un artículo en la Revista Comunitaria que incluye el uso de campos personalizados 
en una categoría para [Crear un banner desde la descripción de la categoría de Joomla](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## Cómo Acceder

* Selecciona **Contenido → Campos** desde el menú del Administrador.
* Selecciona **Artículos** de la lista desplegable *Artículos/Categoría*.
  * Selecciona el botón **Nuevo** en la *Barra de herramientas* para añadir un nuevo campo.
  * Selecciona un **Título** de la lista para editar un campo existente.

**Nota:** Hay una lista desplegable que permite la creación de Campos para una
Categoría y Correo en el componente de Contacto. Requieren algo de experiencia en codificación para preparar sobrescrituras de plantillas adecuadas.

## Captura de pantalla

![Lista de campos de artículos](../../../es/images/fields/articles-fields-list.png)

Hay 16 tipos de campos disponibles, cada uno implementado como un complemento. Es probable que haya más disponibles en el futuro.


*Traducido por openai.com*

