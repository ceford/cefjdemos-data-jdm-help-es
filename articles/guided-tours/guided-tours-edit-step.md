<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step  / Display title: Visites Guidées : Modifier l'Étape -->

## Descripción

Esta página se utiliza para agregar un nuevo Paso o editar un Paso existente de un recorrido.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña de publicación](jdocmanual?article=help/common-elements/edit-publishing).

## Cómo Acceder

- Selecciona **Sistema -> Administrar -> Recorridos Guiados** desde el menú del Administrador.
- Selecciona el botón **Pasos** numerado para un recorrido para abrir la página de pasos del recorrido.
- Selecciona el botón de la barra de herramientas **Nuevo** para agregar un paso.
- Selecciona un **Título** de la lista para editar un paso.

## Captura de pantalla

![Edición de paso en recorridos guiados](../../../es/images/guided-tours/guided-tours-edit-step.png)

## Campos de Formulario

- **Título** El Título para este paso. Usualmente es una llamada a la acción, por ejemplo, `Ingrese un título` si el paso requiere interacción del usuario. Si el título es una clave de idioma, se mostrará un campo adicional, representando la traducción de esa clave para la configuración regional del usuario.

### Pestaña Editar Paso

#### Panel Izquierdo

- **Descripción** Aquí es donde ingresas la descripción del paso, usualmente una explicación detallada o ayuda para el paso. La descripción del paso puede ser una clave de idioma. En este caso, un campo secundario presenta la descripción traducida de esa clave para la configuración regional del usuario.

#### Panel Derecho

- **Posición** La posición del paso en relación a la información a la que apunta.
  - **Abajo** El paso se muestra debajo del objetivo.
  - **Centro** El paso se muestra en el centro de la pantalla. Cuando falta un objetivo, esta es la posición predeterminada.
  - **Izquierda** El paso se muestra a la izquierda del objetivo.
  - **Derecha** El paso se muestra a la derecha del objetivo.
  - **Arriba** El paso se muestra encima del objetivo.
- **Objetivo** El elemento de la pantalla al que apunta el paso. Utiliza sintaxis CSS.

  Por ejemplo, *.button-new* apuntará al botón de la página que tiene la clase *button-new*.

  Si el objetivo no es único, se usará el primer objetivo encontrado. Al crear pasos interactivos, asegúrate de que el objetivo sea enfocable para la accesibilidad. Puedes usar varios selectores, separados por comas. El primer selector válido se convertirá en el objetivo (un selector es válido si: se encuentra en la página, no está deshabilitado, no es de solo lectura y no está oculto). Si se ha establecido un objetivo pero no se encuentra o no es válido, la guía no se romperá pero mostrará el paso en el centro de la pantalla.
- **Tipo** El tipo de paso.
  - **Siguiente** El usuario que está realizando la guia pasará al siguiente paso.
  - **Redirigir** El paso se redirigirá a otra página.
  - **Interactivo** El paso requiere interacción del usuario, como ingresar datos.
- **URL** La URL a la que redirigir para un paso de tipo *Redirigir*. Por ejemplo, *administrator/index.php?option=com_users&view=user&layout=edit* redirigirá el paso a la pantalla de edición de usuario.
- **Tipo Interactivo** El tipo de interacción para un paso interactivo.
  - **Enviar Formulario** El objetivo es un botón que envía un formulario.
  - **Campo de Texto** El objetivo es un campo de entrada de texto. Si el campo es obligatorio, la persona que está realizando la guía no podrá continuar al siguiente paso hasta que se ingresen datos.
  - **Botón** El objetivo es un botón en la pantalla.
  - **Otro** El objetivo es cualquier otro elemento de formulario.

### Pestaña de Opciones

![Opciones de edición de los pasos de tours guiados](../../../es/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Consejos

- Usa **GUIDEDTOUR** en las claves de idioma como convención siempre que se utilicen claves de idioma (para el título y la descripción).

*Traducido por openai.com*

