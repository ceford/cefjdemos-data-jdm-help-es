<!-- Filename: Help4.x:Edit_Permissions  / Display title: Modifier les Autorisations -->

## Propósito

Muchas extensiones tienen pantallas de edición con una pestaña de Permisos que se utiliza para cambiar los permisos asignados a los Grupos de Usuarios. El número de Grupos de Usuarios puede variar ya que se pueden agregar Grupos de Usuarios personalizados para usos especiales. El número de Acciones que se pueden alterar también varía según la extensión. Este artículo es una breve descripción de las pantallas de permisos para dichos propósitos especiales.

Imagina que hay un usuario que se ocupa de los Medios (imágenes y archivos) pero no se le permiten otras responsabilidades. Se ha creado un grupo llamado Oddjob y se ha asignado al nivel de acceso Especial. También se ha creado un usuario llamado Oddjob y se ha asignado al grupo Oddjob.

Para obtener información más detallada sobre los Grupos de Usuarios, Niveles de Acceso y Permisos, hay un tutorial por separado sobre [Control de Acceso](jdocmanual?article=user/users/access-control).

## Permisos de Configuración Global

En este ejemplo, los usuarios del grupo Oddjob han recibido el permiso global para iniciar sesión en la interfaz de administrador, pero nada más.

![Captura de Pantalla de Permisos](../../../es/images/common-elements/global-configuration-permissions-tab.png)

## Permisos de Configuración del Componente

Para acceder a un componente específico se deben configurar los permisos en las opciones del componente.
En este ejemplo, las opciones del componente Media.

![Captura de Pantalla de Media](../../../es/images/common-elements/media-options-permissions-tab.png)

Notarás que este componente tiene menos Acciones disponibles y al grupo Oddjob se le otorgan suficientes permisos para realizar el trabajo.

Para cambiar los permisos de este componente:

* Selecciona el Grupo haciendo clic en su título ubicado a la izquierda.<br>
    Encuentra la Acción deseada.
    * Eliminar. Los usuarios pueden eliminar este artículo.
    * Editar. Los usuarios pueden editar este artículo.
    * Editar Estado. Los usuarios pueden cambiar el estado publicado y la información relacionada con este artículo.
* Selecciona el permiso deseado para la acción que deseas cambiar.
    * Heredado. Heredado para usuarios de este Grupo desde la Configuración Global, Opciones de Artículos, o Categoría de Artículos.
    * Permitido. Permitido para usuarios de este Grupo. Nota: Si esta acción está Denegada en uno de los niveles superiores, el permiso Permitido aquí no tendrá efecto. Una configuración de Denegado no puede ser anulada.
    * Denegado. Denegado para usuarios de este Grupo.
* Haz clic en Guardar en la barra de herramientas en la parte superior. Cuando la pantalla se actualice, la columna de Configuración Calculada mostrará el permiso efectivo para este Grupo y Acción.

## La Experiencia del Usuario

Después de iniciar sesión, un usuario en el grupo Oddjob verá los módulos del Tablero de Inicio que tengan acceso **Especial** establecido y un enlace en el menú al componente Media.

![Tablero de Inicio para Oddjob](../../../es/images/common-elements/home-dashboard-for-oddjob.png)

Y la pantalla Media para el usuario Oddjob es como se esperaba:

![Pantalla Media para Oddjob](../../../es/images/common-elements/media-screen-for-oddjob.png)

*Traducido por openai.com*

