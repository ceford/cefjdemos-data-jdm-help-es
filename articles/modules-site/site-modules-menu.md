<!-- Filename: Help4.x:Site_Modules:_Menu / Display title: Módulos: Menú -->

## Descripción

Este tipo de módulo *Menú* te permite colocar un Menú en la posición deseada y en las páginas web deseadas. Un sitio web puede tener más de un menú en una sola página y diferentes menús en diferentes páginas web.

### Elementos Comunes

Algunos elementos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Módulos: Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [La Pestaña de Módulos: Asignación de Menú](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [La Pestaña de Módulos: Avanzado](jdocmanual?article=help/modules/modules-advanced-tab).
* [La Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo Acceder

- Selecciona **Sistema → Panel de Administración → Módulos del Sitio** desde el menú del Administrador. Luego...
  - Para crear un nuevo módulo: selecciona el botón **Nuevo** en la Barra de Herramientas. Luego...
    - Selecciona el tipo de módulo requerido.
  - Para editar un módulo existente:
    - Busca el módulo en la lista de módulos instalados y selecciona el enlace en la columna **Título**.

## Captura de Pantalla

![pestaña del módulo menú](../../../es/images/modules-site/modules-menu-module-tab.png)

## Campos del Formulario

- **Título** El título del módulo. Este también es el título que se mostrará para el módulo, dependiendo del campo de formulario *Mostrar Título*.

### Pestaña del Módulo

#### Panel Izquierdo

- **Seleccionar Menú** Selecciona un menú de la lista de menús disponibles.
- **Elemento Base** Selecciona un ítem del menú que siempre se usará como base para la visualización del menú. Debes configurar el Nivel de Inicio al mismo nivel o superior al del elemento base. Esto hará que el módulo se muestre en todas las páginas asignadas. Si seleccionas *Actual*, se usará el ítem activo en ese momento como base. Esto hará que el módulo solo se muestre cuando el elemento padre del menú esté activo.
- **Nivel de Inicio** Nivel en el que comenzará la representación del menú. Configurar los niveles de inicio y fin en el mismo número y establecer *Mostrar Elementos del Submenú* en *Mostrar* solo mostrará ese nivel específico.
- **Nivel Final** Nivel en el que se detendrá la representación del menú. Si eliges *Todos*, se mostrarán todos los niveles dependiendo de la configuración de *Mostrar Elementos del Submenú*.
- **Elementos del Submenú** Mostrar u ocultar los elementos del submenú.
