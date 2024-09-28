<!-- Filename: Help4.x:Permissions_for_Group  / Display title: Permissions pour le Groupe -->

## Descripción

La página de *Permisos de Grupo* muestra un informe de permisos que muestra los permisos exactos para cualquier grupo de usuarios en todos los recursos del sitio. Es útil para depurar problemas de acceso de usuarios.

### Elementos Comunes

Algunos elementos de esta página se tratan en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Encabezados de Columnas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginación de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Cómo acceder

- Selecciona **Usuarios → Grupos** desde el menú de Administrador. Luego...
  - Selecciona el icono de **Permisos** para un grupo específico de la lista de
    grupos de usuarios.

## Captura de Pantalla

![permisos de usuarios para grupo](../../../es/images/users/users-permissions-for-group.png)

Sobre la tabla de Permisos se muestran elementos seleccionados que indican permisos de acceso
usando íconos para *Permitido*, *No Permitido* y *Prohibido*. La clave de íconos está debajo
de la tabla.

- **Inicio de Sesión en el Sitio** Pueden los usuarios del grupo iniciar sesión en el Frontend del sitio.
- **Inicio de Sesión del Administrador** Pueden los usuarios del grupo iniciar sesión en el Backend del sitio.
- **Inicio de Sesión en Servicios Web** Pueden los usuarios del grupo acceder a la API de Servicios Web de Joomla
  mediante un Token de API de Super Usuario.
- **Acceso Desconectado** Pueden los usuarios del grupo acceder al Frontend del sitio cuando está desconectado.
- **Super Usuario** Pueden los usuarios del grupo realizar cualquier acción sobre
  todo el sitio independientemente de cualquier otra configuración de permisos.

### Encabezados de Columna

En la tabla que contiene los activos del sitio se muestran permisos para el grupo seleccionado.

- **Título del Activo** El nombre del activo en lenguaje llano.
- **Nombre del Activo** El nombre interno del activo.
- **Configurar Opciones** Pueden los usuarios del grupo editar las
  opciones (excepto permisos) de este activo.
- **Acceso a la Interfaz de Administración** Pueden los usuarios del grupo acceder a la 
  interfaz de administración del activo.
- **Crear** Pueden los usuarios del grupo crear contenido en el activo.
- **Eliminar** Pueden los usuarios del grupo eliminar contenido en el activo.
- **Editar** Pueden los usuarios del grupo editar contenido en el activo.
- **Editar Estado** Pueden los usuarios del grupo editar el estado del activo.
- **Editar Propio** Pueden los usuarios del grupo editar cualquier contenido que posean en el activo.
- **Editar Valor de Campo Personalizado** Pueden los usuarios del grupo editar cualquier
  valor de campo personalizado en el activo.
- **LFT** Los valores de izquierda y derecha en la jerarquía de anidamiento. Esto se
  usa para el anidamiento y ordenamiento del activo.
- **ID** Este es un número de identificación único para este ítem asignado
  automáticamente por Joomla. Se usa para identificar el ítem internamente,
  y no puede ser cambiado.

*Traducido por openai.com*


