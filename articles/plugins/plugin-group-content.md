<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group  / Display title: Groupe de Contenu -->

## Descripción del Grupo

### Contenido - Confirmar Consentimiento

![Plugin de consentimiento de contenido](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Política de Privacidad Corta** Aviso breve del texto que se mostrará encima del Checkbox de Consentimiento de Privacidad.
- **Artículo de Privacidad** Si es necesario, selecciona/crea tu Artículo de Privacidad para enlazar a tu formulario.

Para más información, consulta Configuración del Plugin de Consentimiento de Privacidad.

### Contenido - Contacto

![Plugin de contacto de contenido](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirección** Puedes enlazar el nombre del autor a:
  - Página de contacto asociada.
  - Página web especificada en el perfil de contacto asociado.
  - Correo electrónico especificado en el perfil de contacto asociado.
- **Aplicar enlace también al alias** Enlace a los datos reales del usuario incluso si se ha establecido un alias de autor en las opciones del artículo.

### Contenido - Ofuscación de Correo Electrónico

Este plugin ofusca todos los correos electrónicos en el contenido utilizando JavaScript para frustrar a los spambots. Esto ayuda a prevenir que los correos electrónicos contenidos en los artículos sean agregados a listas de spam. Puedes desactivar la Ofuscación de Correo Electrónico dentro de un artículo insertando {emailcloak=off} en cualquier parte del texto del artículo. En este caso, ningún correo electrónico en el artículo será ofuscado por este plugin.

![Plugin de ofuscación de correo electrónico de contenido](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Modo** Cómo se mostrarán los correos electrónicos. Las opciones son *Como dirección de correo enlazable* o como *Texto no enlazable*.

### Contenido - Campos

Este plugin te permite mostrar un campo personalizado que se ha insertado con el plugin *Button - Fields* o utilizando la Sintaxis: `{field #}` directamente en el área del editor. Sintaxis:

- **`{field 1}`** mostrará el campo con el ID 1.
- **`{field 1,foo}`** mostrará el campo seleccionado usando el diseño alternativo `foo`.
- **`{fieldgroup 2}`** mostrará todos los campos dentro del grupo de campos con el ID 2.

### Contenido - Joomla

![Plugin Joomla de contenido](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Verificar Eliminación de Categoría** Verifica que las categorías estén completamente vacías antes de ser eliminadas.
- **Correo Electrónico en Artículo Nuevo del Sitio** Envía un correo electrónico a los usuarios si *Enviar correo* está *Activado* cuando se envía un nuevo artículo a través del Frontend.

### Contenido - Cargar Módulos

Este plugin te permite colocar un Módulo dentro de un Artículo con la sintaxis: `{loadposition xx}`, donde `xx` es un código de posición definido por el usuario. Por ejemplo, si creas un Módulo con el valor de Posición de `mi posición1`, entonces escribir el texto `{loadposition miposición1}` dentro de un Artículo hará que ese Módulo se muestre en ese punto del Artículo.

![Plugin de cargar módulos de contenido](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Estilo** El estilo para el Módulo cargado.

### Contenido - Salto de Página

Este plugin agrega funcionalidad de tabla de contenidos a un Artículo paginado. Esto se realiza automáticamente a través del uso del botón Pagebreak añadido a la parte inferior del panel de texto en un Artículo. El código HTML se incluye aquí como referencia de lo que está disponible. El Pagebreak se mostrará en la ventana de texto como una simple línea horizontal.

![Plugin de salto de página de contenido](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Mostrar Título del Sitio** Si se añadirá o no el título y los atributos de encabezado del plugin a la etiqueta de Título del Sitio.
- **Encabezado del Índice del Artículo** Mostrar u ocultar el Encabezado del Índice del Artículo. El Encabezado se muestra en la parte superior de la Tabla de Contenido.
- **Encabezado Personalizado del Índice del Artículo** Introduce un texto personalizado para el Encabezado del Índice del Artículo. Si está vacío, se usará el estándar.
- **Tabla de Contenidos** Ocultar o Mostrar una tabla de contenidos para Artículos de varias páginas.
- **Mostrar todo** Si se dará o no a los Usuarios la opción de mostrar todas las páginas de un Artículo.
- **Estilo de Presentación** Mostrar el artículo con páginas separadas, pestañas o deslizadores.

![Descripción del salto de página de contenido](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Contenido - Navegación de Página

Este plugin te permite agregar enlaces de navegación Siguiente y Anterior a los Artículos, por ejemplo cuando se utiliza un diseño de blog o lista. Esta característica se puede controlar con los siguientes parámetros de Joomla!:

- **Mostrar Navegación** en el Artículo - Pantalla de Configuración Global
- **Mostrar Navegación** en los Parámetros - Sección Componente de la Pantalla de Nuevo/Editar Ítem del Menú - Parámetros - Componente para diseños de Artículo.

Ten en cuenta que, si el plugin de Navegación de Página está deshabilitado en esta pantalla, no se mostrará ninguna Navegación de Página y la configuración de los parámetros anteriores no tendrá efecto.

![Plugin de salto de página](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Posición** Posición del enlace de navegación. Las opciones son *Encima* del Artículo o *Debajo* del Artículo.
- **Relacionado a** Asigna la ubicación relativa para los parámetros de Posición. Texto lo colocará directamente encima o debajo del contenido del artículo. Artículo Completo lo colocará encima o debajo de la pantalla completa, incluyendo el título y leer más.
- **Texto del Enlace** Elige lo que se mostrará como el texto del enlace.

### Contenido - Búsqueda Inteligente

Los cambios en el contenido no actualizarán el índice de Búsqueda Inteligente si no habilitas este plugin.

### Contenido - Votación

![Plugin de votación de contenido](../../../en/images/plugins/plugin-group-content-vote.png)

- **Posición** Posición de la votación.

*Traducido por openai.com*

