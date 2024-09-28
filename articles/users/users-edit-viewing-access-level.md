<!-- Filename: Help4.x:Users:_Edit_Viewing_Access_Level  / Display title: Utilisateurs : Modifier le niveau d'accès en lecture -->

## Descripción

Los niveles de acceso controlan qué usuarios pueden ver qué recursos en un sitio.
Los recursos incluyen elementos de menú, módulos, categorías y elementos de componentes
(artículos, contactos, etc.). Cada recurso en el sitio está asignado a
un nivel de acceso. Los grupos de usuarios también están asignados a cada nivel de acceso.

Si un usuario es miembro de un grupo que, a su vez, tiene permiso para un
nivel de acceso, entonces ese usuario puede ver todos los recursos asignados a ese
nivel de acceso. Es importante entender que los grupos de usuarios se pueden
organizar en una jerarquía de padres e hijos. Si es así, entonces un grupo hijo tiene
acceso a todos los niveles de acceso a los que tiene acceso el grupo padre. Por lo tanto,
no necesitas asignar a un grupo hijo acceso a niveles a los que el grupo padre ya tiene acceso.

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

- Selecciona **Usuarios → Niveles de Acceso** desde el menú de Administrador.
  Luego...
  - Selecciona un enlace de la columna **Nombre del Nivel** para editar un nivel existente. O...
  - Selecciona el botón Nuevo para crear un nuevo nivel de acceso.

## Captura de pantalla

![usuarios viendo niveles de acceso](../../../es/images/users/users-edit-viewing-access-level-details-tab.png)

### Pestaña Detalles del Nivel

- **Título del Nivel** Ingrese un título para este nivel de acceso.
- **Grupos de Usuarios con Acceso de Visualización** Marque cualquier grupo para tener este
  nivel de acceso.

### Pestaña Grupos de Usuarios con Acceso de Visualización

![usuarios viendo niveles de acceso](../../../es/images/users/users-edit-viewing-access-level-ugwva-tab.png)

Seleccione una casilla para agregar un grupo de usuarios a un nivel de visualización. En el
ejemplo mostrado, todos los grupos son hijos de Público, por lo que no es necesario
marcar ninguno de los grupos hijos. Heredan los permisos de acceso público. ¡Esta función solo debe usarse para grupos personalizados!

## Consejos

- Si añades un nuevo grupo, es posible que necesites editar cualquier nivel de acceso al que este grupo deba tener acceso.

*Traducido por openai.com*

