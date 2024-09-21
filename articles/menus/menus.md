<!-- Filename: Help4.x:Menus / Display title: Menús -->

## Descripción

Los menús permiten a un usuario navegar por el sitio. Un menú es un objeto
que contiene uno o más elementos de menú. Cada elemento de menú apunta a una
página lógica en el sitio. Se requiere un módulo de menú para colocar el menú en
la página. Un menú puede tener más de un módulo. Por ejemplo, un
módulo puede mostrar solo los elementos del menú de primer nivel y un segundo módulo
puede mostrar los elementos del menú de nivel 2.

La página *Menús* ofrece una visión general de los menús disponibles en un sitio Joomla.
Esto incluye los detalles del número de elementos de menú publicados, no publicados
y en la papelera de cada menú individual, así como los nombres de los módulos
vinculados.

El proceso para agregar un menú al sitio normalmente es el siguiente:

1.  Crear un nuevo menú (utilizando esta página).
2.  Crear uno o más nuevos elementos de menú para el menú. Cada elemento de menú
    tendrá un tipo específico de elemento de menú.
3.  Crear uno o más módulos de menú para mostrar el menú en el sitio.
    - Seleccione los elementos del menú (páginas) que mostrarán el módulo.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de columnas de lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenación de elementos de lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginación de lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo Acceder

- Seleccione **Menús → Administrar** desde el menú del Administrador.

## Captura de Pantalla

![lista de menús](../../../es/images/menus/menus-list.png)

## Encabezados de Columnas

- **Título** El nombre del menú.
- **Elementos del Menú** Un enlace a los elementos de menú de ese menú.
- **\# Publicados** Número de elementos de menú publicados en este menú.
- **\# No Publicados** Número de elementos de menú no publicados en este menú.
- **\# En la Papelera** Número de elementos de menú en la papelera en este menú.
- **Módulos Vinculados** Un menú desplegable muestra el nombre, el nivel de acceso y la posición
  de la plantilla de cualquier módulo de menú asociado con el menú.

## Consejos

- Los botones numerados llevan a una lista filtrada de los elementos de menú de ese menú.
- Un menú debe tener un título descriptivo corto adecuado para su uso en listas y
  listas desplegables.
- La *Descripción* es un recordatorio útil del propósito para el cual fue creado el menú.
- Si un menú no tiene módulos asociados, el botón de la columna *Módulos Vinculados* es
  un enlace a un diálogo modal de *Agregar un módulo para este menú*.
- Si elimina un menú existente, no olvide que todos los elementos de menú
  del respectivo menú también serán eliminados. Aparece un mensaje de advertencia:

  **¿Está seguro de que desea eliminar estos menús? Al confirmar, se eliminarán los
  tipos de menú seleccionados, todos sus elementos de menú y los módulos de menú asociados.**
- El Menú Principal tiene el elemento de menú predeterminado del sitio. ¡No debe ser
  eliminado! El elemento de menú predeterminado define la página que se muestra cuando
  se visita la URL del dominio del sitio, como `www.ejemplo.com`. El sitio no funcionará
  si se elimina. Normalmente es el elemento de menú *Inicio*, pero se puede configurar
  en cualquier elemento de menú, incluido un elemento de menú en un menú oculto. Si se cambia
  el elemento de menú predeterminado, asegúrese de que ese elemento de menú tampoco se elimine.
