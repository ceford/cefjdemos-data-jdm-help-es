<!-- Filename: Help4.x:Templates:_Edit_Style  / Display title: Modèles : Modifier le style -->

## Descripción

La página *Plantillas: Editar Estilo* se utiliza para editar los estilos de las plantillas. Cuando se instala una plantilla por primera vez, se crea un estilo predeterminado para ella. El estilo predeterminado de la plantilla tendrá el mismo nombre que la plantilla con un sufijo *- Default*. Para hacer una variación diferente del estilo predeterminado de la plantilla, marque la casilla de verificación del estilo predeterminado y presione el ícono *Duplicar* en la barra de herramientas. Luego edite el duplicado.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo Acceder

- Selecciona **Sistema → Panel de Plantillas → Estilos de Plantillas de Sitio** 
  desde el menú del Administrador. O...
- Selecciona **Sistema → Panel de Plantillas → Estilos de Plantillas del Administrador** 
  desde el menú del Administrador. Luego...
  - Selecciona el nombre del Estilo de Plantilla para editar en la columna de Estilos.

## Captura de pantalla

![editar estilo de la pestaña del editor de plantillas de Cassiopeia](../../../es/images/templates/templates-site-edit-style-details-tab.png)

## Campos de Formulario

- **Nombre del Estilo** El nombre del estilo. Este es el nombre que se
  mostrará en la columna Estilo de la pantalla *Plantilla: Estilos*.

### Pestaña Detalles

- **Información** El nombre de la plantilla, indicador de Sitio o Administrador
  y una breve descripción.

### Pestaña Avanzado

![templates cassiopeia edit style editor tab](../../../es/images/templates/templates-site-edit-style-advanced-tab.png)

Esta sección puede no estar presente para todos los estilos. Si una plantilla de la cual
se deriva un estilo tiene opciones configurables, estarán presentes aquí. Son estas opciones configurables adicionales las que permiten tener múltiples estilos diferentes de plantillas con variaciones de estas opciones. Las opciones disponibles variarán según las opciones que el desarrollador de la plantilla haya puesto a disposición.

### Configuraciones de Color de Atum

La plantilla predeterminada del Administrador te permite experimentar con variaciones de color. ¡Guarda y observa!

### Configuraciones de Imagen de Atum

Puedes seleccionar una imagen para reemplazar el **Logo de Inicio de Sesión** en el formulario de acceso del Administrador y el **Logo de Marca** en la Barra de Título del Administrador en modo expandido y en modo compacto. Los valores predeterminados son los logos de la Marca Joomla. En la Barra de Título, la palabra Joomla! está presente en la versión **Marca Grande** y omitida en la versión **Marca Pequeña**. Selecciona **Alternar Menú** para ver el cambio.

Si proporcionas tu propia Marca Pequeña, también necesitas proporcionar una anulación de estilo de ancho. Para hacerlo, crea un archivo user.css en la raíz de la plantilla e inserta lo siguiente, pero reemplaza 3rem con un ancho adecuado para tu imagen:

       .header .logo.small {
           width: 3rem;
       }

### Pestaña Asignación de Menú

![templates cassiopeia edit style editor tab](../../../es/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Esta sección contiene todos los ítems de menú configurados en tu sitio web Joomla!. Para aplicar el estilo actual a la página web correspondiente de un ítem de menú, marca la casilla junto al ítem del menú. Puedes presionar el botón *Alternar Selección* para invertir las selecciones de los ítems de menú.

**Nota** Si una casilla está atenuada y no se puede marcar, podría ser porque el ítem de menú está siendo usado por otro usuario. Puedes ver si este es el caso yendo a la pantalla del administrador de menús para el menú en cuestión. Si hay un símbolo de candado junto al ítem del menú, entonces está siendo usado actualmente por otro usuario.

*Traducido por openai.com*

