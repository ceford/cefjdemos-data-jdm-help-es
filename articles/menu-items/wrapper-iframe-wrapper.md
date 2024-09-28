<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper  / Display title: Conteneur Iframe -->

## Descripción

El tipo de elemento de menú *Iframe Wrapper* se utiliza para crear una página con contenido incrustado utilizando un IFrame con control del tamaño, ancho y alto del iframe.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Detalles](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Pestaña de Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Pestaña de Visualización de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Pestaña de Metadatos](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Pestaña de Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La Pestaña de Asignación de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Cómo Acceder

Para crear un nuevo Elemento de Menú con Contenedor IFrame:

- Seleccione **Menús → \[nombre del menú\]** desde el menú del Administrador
  (por ejemplo, **Menús → Menú Principal**). Luego...
  - Seleccione el botón **Nuevo** en la Barra de Herramientas. Luego...
  - Seleccione el botón para seleccionar el Tipo de Elemento de Menú.
  - En el cuadro de diálogo modal, seleccione el elemento Usuarios para abrir una lista y luego
    seleccione el elemento de menú **Contenedor IFrame**.

Para editar un elemento de menú existente *Contenedor IFrame*:

- Seleccione su Título en la lista de *Menú: Elementos*.

## Captura de pantalla

![Pestaña de detalles del envoltorio del iframe](../../../es/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Campos del Formulario

### Pestaña de Parámetros de Barras de Desplazamiento

![Pestaña de parámetros de barras de desplazamiento del envoltorio de IFrame](../../../es/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Ancho** Ancho de la ventana IFrame. Introduce un número de píxeles o
  un porcentaje. Por ejemplo, *550* significa 550 píxeles; *75%* significa el 75%
  del ancho del contenedor `<main>`. Un número absoluto de píxeles podría ser
  más ancho que el contenedor y causar problemas de diseño. Si tienes dudas, prueba con el 100%.
- **Altura** Altura de la ventana IFrame. Introduce un número de píxeles. Por ejemplo,
  *550* significa 550 píxeles.

### Pestaña Avanzada

![Pestaña avanzada del envoltorio de IFrame](../../../es/images/menu-items/wrapper-advanced-tab.png)

- **Altura automática** Ajusta automáticamente la altura a la altura de la página externa.
  *Nota* - esto solo funcionará si la página externa está en el **mismo
  dominio**. Por ejemplo, `http://www.ejemplo.com` el HTML externo debe
  estar en la estructura de archivos raíz de `ejemplo.com`. Los subdominios no
  funcionarán, ya que un subdominio se considera un dominio separado.
- **Añadir automáticamente** Prefija automáticamente la dirección web con http://. Esta
  función detectará automáticamente y no prefijará una URL con http:// o
  https:// si ya se están utilizando en la URL.
- **Carga diferida (Lazy Loading)** ...

*Traducido por openai.com*

