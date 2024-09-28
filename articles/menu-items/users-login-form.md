<!-- Filename: Help4.x:Menu_Item:_Login_Form  / Display title: Formulaire de Connexion -->

## Descripción

El tipo de elemento de menú **Formulario de Inicio de Sesión** se utiliza para crear una página que contiene un formulario de inicio de sesión.

### Elementos Comunes

Algunos aspectos de esta página están cubiertos en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Detalles](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Pestaña Tipo de Enlace](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Pestaña de Visualización de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Pestaña de Metadatos](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Pestaña de Asociaciones](jdocmanual?article=help/common-elements/edit-associations).
* [La Pestaña de Asignación de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Cómo Acceder

Para crear un nuevo elemento de menú **Formulario de Inicio de Sesión**:

- Selecciona **Menús → \[nombre del menú\]** desde el menú del Administrador
  (por ejemplo, **Menús → Menú Principal**). Luego...
  - Selecciona el botón Nuevo en la Barra de Herramientas. Luego...
  - Selecciona el botón Seleccionar Tipo de Elemento de Menú.
  - En el cuadro de diálogo modal selecciona el elemento Usuarios para abrir una lista y luego
    selecciona el elemento **Formulario de Inicio de Sesión**.

Para editar un elemento de menú existente del Formulario de Inicio de Sesión:

- Selecciona su Título en la lista *Menús: Elementos*.

## Captura de pantalla

![Pestaña de detalles del formulario de inicio de sesión](../../../es/images/menu-items/users-login-form-details-tab.png)

## Campos del Formulario

### Pestaña Opciones

![Pestaña de detalles del formulario de inicio de sesión](../../../es/images/menu-items/users-login-form-options-tab.png)

#### Panel de Inicio de Sesión

- **Elegir Tipo de Redirección de Inicio de Sesión** Esto puede ser un *Elemento del Menú* o una *URL Interna*.
  Los siguientes campos cambian dependiendo de la configuración de este parámetro. Para 
  un sitio multilingüe, se recomienda *Elemento del Menú*.
  - **Elemento del Menú de Redirección de Inicio de Sesión** Seleccione o cree un elemento del menú para la página 
    a la que redirigir después de un inicio de sesión exitoso. Si no se selecciona ningún elemento de menú, 
    los usuarios serán redirigidos a su perfil después del inicio de sesión.
  - **Redirección de Inicio de Sesión** Seleccione una URL interna a la que redirigir después del inicio de sesión.
- **Descripción de Inicio de Sesión** Mostrar u ocultar la descripción de inicio de sesión.
- **Texto de Descripción de Inicio de Sesión** Ingresar el texto a mostrar en la página de inicio de sesión.
- **Imagen de Inicio de Sesión** Seleccionar o subir una imagen para mostrar en la página de inicio de sesión.
- **Descripción de la Imagen (Texto Alt)** Necesario para lectores de pantalla por motivos de accesibilidad.
- **Sin Descripción** Un cuadro para marcar si la imagen es puramente decorativa y no requiere explicación.

#### Panel de Cierre de Sesión

Este panel utiliza los mismos encabezados de campos para controlar el proceso de cierre de sesión.

## Consejos

- La **URL de Iniciar y Cerrar Sesión** se puede usar para enviar a un usuario a una página específica creada para proporcionar algún tipo de retroalimentación al usuario. Por ejemplo, una página titulada *Ya has iniciado sesión* con información general. El uso de un Módulo de Usuario para mostrar enlaces para Actualizar Perfil de Usuario, Ver Perfil de Usuario y otras funciones de Usuario podría mostrarse en esta página, mejorando la experiencia del usuario en el sitio.

*Traducido por openai.com*

