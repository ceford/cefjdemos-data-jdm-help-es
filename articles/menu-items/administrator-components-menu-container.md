<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container  / Display title: Élément de Menu : Conteneur du Menu des Composants -->

## Descripción

El Contenedor del Menú de Componentes se utiliza para mostrar un contenedor de componentes en la interfaz del Administrador. Un caso de uso podría ser el siguiente:

Supongamos que solo deseas mostrar ciertos enlaces de componentes a un subconjunto de usuarios en tu sitio. Los Super Usuarios verán enlaces a todo, por supuesto. Puedes hacer esto de la siguiente manera:

- Crea un nuevo Grupo de Usuarios llamado, por ejemplo, Sucursal, con Público como padre.
- Establece los Permisos Globales para este grupo para Permitir Inicio de Sesión de Administrador.
- Crea un nuevo menú llamado, por ejemplo, Menú de Sucursal sin presets importados.
- Crea un Módulo vinculado llamado, por ejemplo, Menú de Sucursal con el menú para mostrar como Menú de Sucursal. Establece Comprobar Menú en No y Acceso en Público.
- Crea un elemento de menú Contenedor del Menú de Componentes para el Menú de Sucursal llamado, por ejemplo, Componentes de Sucursal.
  - Oculta cualquier componente que no desees que los usuarios de Sucursal vean.
  - Muestra aquellos a los que deberían tener acceso.
- Establece los Permisos del Componente para el Grupo Sucursal en permitido para todos, excepto Configurar ACL y Configurar Opciones.

Para un Super Usuario, el menú de Administrador tendrá una obvia duplicación de enlaces. Sin embargo, un usuario de Sucursal solo verá el menú de Componentes de Sucursal y el Tablero de Inicio. ¡También necesitarás ajustar los permisos de Acceso de los módulos de Ícono Rápido allí! Y realmente necesitas crear un módulo de Tablero para cualquier componente al que los usuarios de Sucursal tengan acceso.

Para los usuarios que necesitan acceso a Artículos, puedes agregar más elementos de menú al Menú de Sucursal. De esta manera, puedes construir un menú personalizado completo para los usuarios de Sucursal.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de Ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Cómo Acceder

Para crear un nuevo elemento de menú Contenedor de Componente:

- Crea un nuevo Menú desde **Menús → Gestionar** en el menú del Administrador.
  - Selecciona **Administrador** en el selector desplegable *Sitio/Administrador*.
  - Selecciona el botón **Nuevo** en la Barra de Herramientas. Rellena el formulario:
    - **Título** Menú de Ramas
    - **Nombre Único** menu_de_ramas
    - **Descripción** Menú personalizado para Ramas.
    - **Importar Preestablecido** Ninguno
    - **Guardar**
    - **Permisos** Selecciona el grupo *Rama* y establece todos en *Permitir*.
    - **Guardar & Cerrar**
    - Selecciona el botón **Crear un Módulo** y completa el formulario de diálogo:
    - **Título** Componentes de Ramas
    - **Revisar Menú** No (de lo contrario, aparecerá un mensaje que te invitará 
      a *activar el modo de recuperación del menú*.)
    - **Acceso** Especial
    - **Posición** Menú
- Selecciona **Menús → \[nombre del menú\]** desde el menú del Administrador.
- Selecciona el botón **Nuevo** en la Barra de Herramientas para crear un nuevo elemento de menú.
- Selecciona el botón de Tipo de Elemento de Menú **Seleccionar**.
- Selecciona el enlace **Lista de Contenedor de Componente** desde **Enlaces del Sistema** en
  el cuadro de diálogo modal Tipo de Elemento de Menú.

Para editar un existente Elemento de Menú Contenedor de Componente, selecciona su Título en
la lista de Elementos de Menú.


## Captura de pantalla

![Menú de Componentes del Administrador](../../../en/images/menu-items/administrator-components-menu-container.png)

## Campos del Formulario

- **Nombre** El nombre del elemento del menú, por ejemplo *Menú de Sucursal*. Aparecerá
  en la parte inferior del menú del Administrador.
- **Alias** El nombre interno del elemento. Normalmente, puedes dejar
  esto en blanco y Joomla completará un valor predeterminado con el Título en minúsculas y
  con guiones en lugar de espacios.

### Pestaña de Detalles

#### Panel Izquierdo

- **Tipo de Elemento de Menú** En este caso *Contenedor de Menú de Componentes*.
- **Mostrar u Ocultar Elementos del Menú** Lista de elementos del menú con botones para establecer
  el estado de visibilidad. Si un elemento padre está configurado para *Ocultar*, todos los elementos hijos
  también se ocultan, incluso si están configurados para *Mostrar*.

#### Panel Derecho

- **Menú** Muestra en qué menú aparecerá el enlace.
- **Padre** El elemento (categoría, elemento del menú, etc.) que es
  el padre del elemento que se está editando.
- **Orden** Indica el orden de este Elemento de Menú en el Menú. El
  Orden predeterminado es añadir el Elemento de Menú al final del Menú. Este
  Elemento de Menú se moverá a la posición de orden justo después del Elemento de Menú
  seleccionado en la lista desplegable. Ten en cuenta que el Orden de los Elementos de Menú
  también puede cambiarse en el Administrador de Elementos de Menú.
- **Estado** El estado de publicación del elemento.
- **Nota** Esto normalmente es para el uso del administrador del sitio (por
  ejemplo, para documentar información sobre este elemento) y no se muestra en
  la interfaz del sitio.

## Consejos

- El elemento **Componentes de Sucursal** aparece en la parte inferior del menú de Administrador. El acceso al menú principal del Administrador y a esta sección se puede personalizar para el grupo de Sucursal.

*Traducido por openai.com*

