<!-- Filename: Help4.x:Help_screens_styleguide  / Display title: Guide de Style des Écrans d'Aide -->

<div class="alert alert-warning">
Ce guide de style est destiné à l'installation de Joomla MediaWiki (docs.joomla.org).
</div>

Ceci est un travail en cours et doit être utilisé comme un guide pour
créer des écrans d'aide pour **Joomla 3.x**. Les écrans d'aide présents
sur le Joomla! Docs Wiki sont accessibles par chaque installation Joomla!
en utilisant le système d'aide par défaut. En suivant ce guide de style,
le projet Joomla! peut offrir une cohérence à travers les
écrans d'aide afin de faciliter la navigation.

Si vous avez une question, veuillez la poster sur la page de discussion
associée à l'écran d'aide en cliquant sur l'onglet ***Discussion*** en haut de la
page de l'écran d'aide.

## Diseño de la Página de Ayuda

### Descripción

Cada pantalla de ayuda debe tener una sección de "**Descripción**". Esta sección proporciona más detalles sobre lo que hace la pantalla y se utiliza en las tablas de pantallas de ayuda a lo largo de este wiki. <a href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens" class="mw-redirect" title="Menu Management">Aquí hay un ejemplo de uso</a>.

No hay un formato específico para esta sección porque la descripción debe estar en correlación directa con el propósito y la funcionalidad de la pantalla. Puede haber subsecciones en la descripción que describen detalles más específicos. Trata de mantener la descripción breve y concisa. Si la descripción es larga, considera usar viñetas para resumirla.

## Cómo Acceder

Cada pantalla de ayuda debería tener una sección **Cómo Acceder** 
que proporcione los pasos necesarios para llegar a la pantalla que se está 
describiendo. Esto podría ser redundante porque un usuario debe estar en la 
pantalla de administrador para haber accedido a la pantalla de ayuda. 
Recuerda, las pantallas de ayuda pueden ser obtenidas de diferentes maneras. 
Por ejemplo, alguien que use un motor de búsqueda para averiguar cómo hacer 
algo podría encontrar una pantalla de ayuda en el wiki sin haber accedido
al sistema de ayuda.

#### Notas:

- Si la manera de llegar a la pantalla es desde otra pantalla, el nombre de
  esa pantalla debería ser un enlace a su pantalla de ayuda.
- Se "hace clic" en los botones, incluyendo los botones de la barra de herramientas, 
  pero se "seleccionan" los elementos del menú. El uso consistente de esta terminología 
  debería ayudar a los usuarios.
- Para facilitar la representación, use la flecha derecha ( → ), 
  **Esto apuntando → a eso**.

### Captura de Pantalla

Captura de pantalla que muestra el aspecto general de la pantalla.

#### Notas:

- Las imágenes de la captura de pantalla pueden tener cualquier ancho, pero las imágenes 
  más grandes deberían tener \|800px añadido en el origen.
- El nombre del archivo debe seguir nuestras
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC:Image naming convention">convenciones de 
  nombramiento estándar</a> para pantallas de ayuda.
  **Help-3x-***\<ruta-del-sistema-de-menú-en-minúsculas-separadas-por-guiones\>***-screen-en.png**.
  Por ejemplo, una captura de pantalla de la pantalla del Gestor de Artículos sería
  **\[\[File:Help-3x--content-article-manager-screen-en.png\]\]**.
- El nombre del archivo siempre debe incluir un código de idioma al final del nombre, 
  para el inglés se añade -en.
- Puedes usar archivos .png o .jpg.

## Campos del Formulario (por Pestaña)

### Pestaña de Detalles

Esta sección solo debe incluirse en las pantallas de ayuda que describen
pantallas que incluyen un formulario. Esto incluye todas las pantallas de añadir/editar,
pero también incluye pantallas como Configuración Global del Sitio
y ventanas emergentes modales como <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Help4.x:Components
Article Manager Options</a>.

### Otros Tipos de Pestañas

Si los campos se agrupan en conjuntos de campos o pestañas, agrupe los campos bajo
subtítulos.

### Encabezados de Columna

Esta sección solo debe incluirse en las pantallas de ayuda que describen
pantallas de administración del backend; es decir, donde se muestra una lista de elementos.
Esta sección debe describir cada una de las columnas de la lista.

### Filtros de la Lista

Esta sección solo debe incluirse en las pantallas de ayuda que describen
pantallas de administración del backend; es decir, donde se muestra una lista de elementos.
Esta sección debe describir cómo usar los filtros de la lista para
filtrar el contenido de la pantalla. Ver
<a href="https://docs.joomla.org/Screen.content.15#List_Filters"
title="Screen.content.15">Screen.content.15#List_Filters</a> como ejemplo
de la versión 1.5.

### Opciones

Esta sección solo debe incluirse en las pantallas de ayuda donde la pantalla
tiene un botón de la barra de herramientas llamado Opciones que abre una sub-pantalla modal de opciones. Si
hay muchas opciones y la pantalla de ayuda se volvería excesivamente larga
si se describieran aquí, entonces enlace a una pantalla de ayuda separada
con un sufijo "\_Options". Por ejemplo, ver <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Components Article
Manager Options</a>.

Dado que la pantalla modal de Opciones suele estar tabulada, debe agregar una
sub-sección en esta sección para cada pestaña. Por ejemplo, si hay una
pestaña etiquetada como "Diseño de Edición", debe agregar un encabezado de tercer nivel
con ese nombre y dentro de esa sub-sección debe describir cada uno de los
campos disponibles. Debe comenzar cada sub-sección con una captura de pantalla del
panel de Opciones adecuado.

### Barra de Herramientas

Obviamente, esta sección solo debe incluirse en las pantallas de ayuda donde una
barra de herramientas está presente.

Describa los botones disponibles y sus funciones asociadas. Use
**fragmentos** aquí porque muchos serán iguales para diferentes pantallas.
Es mejor proporcionar una imagen de la barra de herramientas.

La primera palabra siempre debe ser un verbo y, a menos que sea un verbo irregular, 
también debe terminar en la letra "s". Esto significa que debe estructurar la descripción como si 
estuviera usando la palabra "esto" como el sujeto, pero deje fuera el sujeto de la oración. 
Esto hará que la oración sea un fragmento de oración. Por ejemplo:

- En lugar de "Para encontrar tesoros enterrados, haga clic en este botón."
  - Diga, "Encuentra tesoros enterrados."
- En lugar de "Puede hacer clic en este botón para insertar una imagen de John
  Stamos en el documento actual."
  - Diga, "Inserta una imagen de John Stamos."
- En lugar de "Infórmese de que una imagen de John Stamos es lo mismo
  que un tesoro enterrado."
  - Diga, "Le informa que una imagen de John Stamos es lo mismo que
    un tesoro enterrado."

Dado que muchas barras de herramientas son iguales en múltiples pantallas, la convención de 
nomenclatura de archivos de imágenes de barras de herramientas está diseñada para facilitar la 
reutilización de imágenes de barras de herramientas siempre que sea posible. Las imágenes de barras de 
herramientas deben seguir esta convención de nomenclatura: Help\<versión\>-Toolbar-\<iconslist\>.png donde
\<iconslist\> es una lista separada por '-' de las leyendas de la barra de herramientas. Cada palabra
debe estar en mayúsculas, sin espacios ni '&'. Por ejemplo:
Help30-Toolbar-New-Edit-Delete-Options-Help.png

### Proceso por Lotes

Esta sección solo debe incluirse en las pantallas de ayuda donde la pantalla
tiene una función de proceso por lotes. Por ejemplo, ver
<a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories"
title="Help4.x:Components Banners Categories">Help4.x:Components Banners
Categories</a>.

### Consejos

Como sugiere el nombre, esta sección debe incluir consejos, sugerencias,
sugerencias que pueden ayudar a un usuario a realizar tareas relacionadas con la
pantalla.

*Traducido por openai.com*

