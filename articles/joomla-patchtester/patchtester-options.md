<!-- Filename: Help4.x:Components_Patch_Tester_Options  / Display title: Options de Testeur de Patch -->

## Descripción

El *Joomla! Patch Tester* es utilizado por los Testers para verificar que los parches de código producidos por los Desarrolladores realmente hagan lo que se supone que deben hacer sin efectos secundarios no deseados. La página de *Opciones* se usa para configurar la conexión de Github.

### Elementos Comunes

Algunos elementos de esta página se cubren en artículos de ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Pestaña de Permisos](jdocmanual?article=help/common-elements/edit-permissions).

Más Información: [Guía para Principiantes sobre la Prueba de Errores en Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Cómo Acceder

- Selecciona **Componentes → Probador de Parches** desde el menú del Administrador.
  - Selecciona el botón *Opciones* en la Barra de Herramientas.

## Captura de pantalla

![Formulario de opciones de Patchtester](../../../es/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Campos del Formulario

### Pestaña del Repositorio de GitHub

- **Repositorio de GitHub** El valor predeterminado es `Joomla! CMS`. Úsalo.

### Pestaña de Autenticación de GitHub

Necesitas una cuenta de GitHub y un Token de GitHub. Todo gratis - consulta la pestaña de Autenticación de GitHub para más detalles.

![Opciones de Patchtester pestaña de autenticación de GitHub](../../../es/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Método de Autenticación de GitHub** Elige el método de Token. El
  método de Credenciales no funcionará a partir de septiembre de 2020.
- **Token de GitHub** Pega el Token obtenido de GitHub.

### Pestaña de Configuración del Servidor CI

Estas configuraciones se utilizan para pruebas automáticas. Usa los valores predeterminados para pruebas manuales.

![Opciones de Patchtester pestaña de configuración del servidor CI](../../../es/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Dirección del Servidor CI** Predeterminado: `https://ci.joomla.org`
- **Interruptor de Integración CI** Predeterminado: Apagado


*Traducido por openai.com*

