<!-- Filename: Help6.x:Menu_Item_Blog_Layout  / Display title: Élément de Menu Disposition du Blog -->

## Descripción

Todos los elementos del menú tienen un diseño similar, pero algunos de los campos del formulario y algunas de las pestañas cambian de un tipo a otro. Esta página describe la pestaña **Diseño de Blog** utilizada para diseños de Artículos.

## Cómo Acceder

* Seleccione cualquier **Menú del Sitio** desde el menú del Administrador.
* Seleccione el botón **Nuevo** en la Barra de Herramientas.
* Seleccione cualquier tipo de elemento de menú de Componente que tenga una pestaña de *Diseño de Blog*.
* Seleccione la pestaña **Diseño de Blog**.

## Captura de pantalla

![Pestaña de diseño del blog del elemento de menú](../../../es/images/menu-items-common/articles-category-blog-blog-layout-tab.png)

## Campos del Formulario

### Pestaña de Diseño del Blog

- **\# Artículos en Destacados** Número de Artículos para mostrar utilizando todo el ancho del área principal de visualización. `0` significa que no se mostrarán Artículos cuando se utilice todo el ancho. Si un Artículo tiene una *Leer más...* ruptura, solo se mostrará la parte del texto antes de la ruptura (el texto de introducción).
- **Clase de Artículo Destacado** Puedes añadir cualquier clase de CSS para tus propias ideas de estilo. Agrega un borde en la parte superior con la clase boxed. Para posición de la imagen, usa por ejemplo image-start, image-end. Agrega image-alternate para ordenar alternadamente las imágenes de introducción.
- **\# Artículos de Introducción** Determina el número de Artículos a mostrar después del Artículo en Destacados. Estos Artículos se mostrarán en el número de columnas establecido en el parámetro Columnas a continuación. Si un Artículo tiene una *Leer más...* ruptura, solo se mostrará el texto antes de la ruptura (texto de Introducción), seguido de un enlace *Leer más...*. El orden en el que se muestran los artículos se determina por los parámetros Orden de Categoría y Orden de Artículo a continuación.
- **Clase de Artículo** Puedes agregar cualquier clase de CSS para tus propias ideas de estilo. Agrega un borde en la parte superior con la clase boxed. Para posición de la imagen usa, por ejemplo, image-start, image-end. Agrega image-alternate para ordenar alternadamente las imágenes de introducción.
- **\# Columnas** El número de columnas a utilizar en el área de Artículos de Introducción. Esto normalmente está entre 1 y 3 (dependiendo de la plantilla que estés utilizando). Si se usa 1, los Artículos de Introducción se mostrarán usando todo el ancho del área de visualización, al igual que los Artículos en Destacados.
- **Dirección de Columna Múltiple** En diseños de blog con múltiples columnas, si organizar los artículos hacia Abajo en las columnas o a lo Largo de las columnas.
  - *Abajo* Ordenar artículos bajando por la primera columna y luego subiendo a la siguiente columna.
  - *A lo Largo* Ordenar artículos a lo largo de las columnas y luego regresar a la primera columna.
- **\# Enlaces** El número de Enlaces a mostrar en el área de Enlaces de la página. Estos enlaces permiten a un Usuario vincular a Artículos adicionales, si hay más Artículos de los que caben en la primera página del Diseño del Blog.
- **Artículos Destacados**
  - *Mostrar* Mostrar artículos destacados y no destacados.
  - *Ocultar* Mostrar solo artículos no destacados.
  - *Solo* Mostrar solo artículos destacados.
- **Imagen de Introducción Vinculada** Si es Sí, un clic en la imagen de introducción muestra el artículo.
- **Incluir Subcategorías**
  - *Ninguna* Solo se mostrarán artículos de la categoría actual.
  - *Todas* Se mostrarán todos los artículos de la categoría actual y todas las subcategorías.
  - *1-5* Se mostrarán todos los artículos de la categoría actual y subcategorías hasta e incluyendo ese nivel.
- **Orden de Categoría**
  - *Sin Orden* Los artículos se ordenan solo por el Orden de Artículo, sin tener en cuenta la Categoría.
  - *Título Alfabético* Las categorías se muestran en orden alfabético (A a Z).
  - *Título Alfabético Inverso* Las categorías se muestran en orden alfabético inverso (Z a A).
  - *Orden de Categoría* Las categorías se ordenan según la columna Orden ingresada en *Artículos: Categorías*.
- **Orden de Artículo**
  - *Orden de Artículos Destacados* Los artículos se ordenan según la columna Orden ingresada en *Artículos: Destacados*.
  - *Más Recientes Primero* Los artículos se muestran comenzando con los más recientes y terminando con los más antiguos.
  - *Más Antiguos Primero* Los artículos se muestran comenzando con los más antiguos y terminando con los más recientes.
  - *Título Alfabético* Los artículos se muestran por Título en orden alfabético (A a Z).
  - *Título Alfabético Inverso* Los artículos se muestran por Título en orden alfabético inverso (Z a A).
  - *Autor Alfabético* Los artículos se muestran por Autor en orden alfabético (A a Z).
  - *Autor Alfabético Inverso* Los artículos se muestran por Autor en orden alfabético inverso (Z a A).
  - *Más Vistos* Los artículos se muestran por el número de visitas, comenzando con el que tiene más visitas y terminando con el que tiene menos visitas.
  - *Menos Vistos* Los artículos se muestran por el número de visitas, comenzando con el que tiene menos visitas y terminando con el que tiene más visitas.
  - *Orden Aleatorio* Los artículos se muestran de manera aleatoria.
  - *Orden de Artículo* Los artículos se ordenan según la columna Orden ingresada en Artículos.
  - *Orden de Artículo Inverso* Los artículos se ordenan inversamente según la columna Orden ingresada en Artículos.
- **Fecha para Ordenar** La fecha utilizada cuando los artículos se ordenan por fecha.
  - *Creado* Usar la fecha de creación del artículo.
  - *Modificado* Usar la fecha de modificación del artículo.
  - *Publicado* Usar la fecha de inicio de publicación del artículo.
  - *No Publicado* Usar la fecha de no publicación del artículo.
- **Paginación** La paginación proporciona enlaces de página en la parte inferior de la página que permiten al Usuario navegar a páginas adicionales. Estos son necesarios si los Artículos no caben en una página.
  - *Ocultar* No se muestran enlaces de paginación. *Nota* Los usuarios no podrán navegar a páginas adicionales.
  - *Mostrar* Se muestran enlaces de paginación si es necesario.
  - *Auto* Se muestran enlaces de paginación si es necesario.
- **Resumen de Paginación** Mostrar el número de página actual y el total de páginas (por ejemplo, *Página 1 de 2*) en la parte inferior de cada página.

*Traducido por openai.com*

