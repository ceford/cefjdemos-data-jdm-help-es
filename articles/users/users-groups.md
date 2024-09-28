<!-- Filename: Help4.x:Users:_Groups  / Display title: Utilisateurs : Groupes -->

## Descripción

Los Grupos de Usuarios controlan las acciones que un usuario puede realizar en un sitio. Las acciones
incluyen cosas como ver un artículo, crear un artículo, cambiar 
opciones para un componente o iniciar sesión. El administrador del sitio asigna 
permisos para diversas acciones a cada grupo. Los permisos para las acciones pueden 
asignarse en diferentes ubicaciones en la jerarquía del componente, por ejemplo,
en la Configuración Global, opciones del componente u opciones del módulo. Si un grupo de usuarios 
no tiene permiso para una acción determinada, el usuario en ese grupo
no puede realizar dicha acción.

El control de acceso para visualización se implementa mediante el uso de **Niveles de Acceso**,
que tienen asignados uno o más grupos de usuarios. Los recursos como artículos,
elementos de menú o módulos tienen un nivel de acceso asignado. Un usuario que es miembro de 
un grupo asignado a un nivel de acceso específico puede ver cualquier recurso 
asignado a ese nivel de acceso.

Los grupos de usuarios pueden organizarse en una jerarquía en la que todos los grupos secundarios
heredan los permisos de acción y niveles de acceso de un grupo padre. Si
se usa sabiamente, esta característica puede ahorrar mucho tiempo al evitar la duplicación en
la configuración de un sistema de seguridad del sitio.

La página *Usuarios: Grupos* enumera los Grupos de Usuarios actuales en jerarquía. Se puede
utilizar para crear nuevos grupos de usuarios y eliminar grupos que ya no se necesiten.
¡No elimine ninguno de los grupos de usuarios predeterminados!

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de Listas](jdocmanual?article=help/common-elements/list-pagination).

## Cómo acceder

- Selecciona **Usuarios → Grupos** desde el menú del Administrador.

## Captura de pantalla

![grupos de usuarios](../../../es/images/users/users-groups-list.png)

## Consejos

- Selecciona el nombre de un grupo para editar las propiedades del grupo.
- Selecciona el ícono de Permisos para revisar los permisos del grupo para acceder a cada activo. Esto se usa a menudo para depurar problemas de permisos de acceso.
- Selecciona el número de Usuarios Habilitados para ver una lista de usuarios habilitados en ese grupo.
- Selecciona el número de Usuarios Bloqueados para ver una lista de usuarios bloqueados en ese grupo.

*Traducido por openai.com*

