<!-- Filename: Help4.x:Users:_Options / Display title: Usuarios: Opciones -->

## Descripción

La página de *Usuarios: Opciones* se utiliza para establecer opciones globales para todos los usuarios, incluyendo:

- Captcha,
- registro permitido y tipo de registro,
- grupo de usuarios predeterminado para nuevos usuarios,
- restablecer contador de contraseña o nombre de usuario,
- aviso por correo electrónico de registro de nuevos usuarios a la administración y más.

## Cómo Acceder

* Selecciona **Sitio → Usuarios** desde el *Panel de Inicio*. O...
* Selecciona **Usuarios → Gestionar** desde el menú del Administrador. Luego...
* Selecciona el botón de la barra de herramientas **Opciones**.

## Captura de Pantalla

![opciones de usuarios pestaña de opciones de usuario](../../../es/images/users/users-options-user-options-tab.png)

## Campos del Formulario

### Pestaña de Opciones de Usuario

- **Permitir Registro de Usuarios**
  - *Sí* Los usuarios pueden registrarse desde el Frontend del sitio utilizando el
    enlace *Crear una Cuenta* proporcionado en el formulario de inicio de sesión.
  - *No* El enlace *Crear una Cuenta* no se mostrará.
- **Grupo de Registro de Nuevos Usuarios** El grupo al que se asignan los usuarios por
  defecto cuando se registran en el sitio. Por defecto es *Registrado*.
- **Grupo de Usuarios Invitados** El grupo al que se asignan los invitados (los
  invitados son visitantes del sitio que no han iniciado sesión). Es posible
  crear contenido en el sitio que sea visible para los invitados pero no visible
  para los usuarios que han iniciado sesión.
- **Enviar Contraseña** Si se establece en *Sí*, la primera contraseña del usuario se
  enviará por correo electrónico como parte del correo de registro.
- **Activación de Cuenta de Nuevos Usuarios**
  - *Ninguna* La cuenta de usuario estará activa de inmediato sin que se requiera
    ninguna acción.
  - *Auto* El usuario recibirá un correo electrónico con un enlace de activación. La
    cuenta se activará cuando el usuario seleccione el enlace de activación.
  - *Administrador* El usuario recibirá un correo electrónico con un enlace de
    activación. Cuando el usuario seleccione este enlace, el Administrador del Sitio
    será notificado por correo electrónico y se le pedirá que active la cuenta del
    usuario.
- **Enviar Correo a Administradores** Enviar notificación por correo electrónico a
  los administradores con *Activación de Cuenta de Nuevos Usuarios* establecida en
  *Ninguna* o *Auto*.
- **Captcha** El plugin de Captcha para Registro de Cuentas de Usuario, recordatorio de Contraseña de Usuario y recordatorio de Nombre de Usuario.
- **Parámetros de Usuario en el Frontend**
  - *Mostrar* Los usuarios podrán modificar Configuraciones Básicas desde el frontend del sitio.
  - *Ocultar* El usuario no podrá cambiar estas configuraciones.
- **Idioma del Frontend** Mostrar u Ocultar el idioma del sitio. ...
- **Cambiar Nombre de Usuario** Permitir al usuario cambiar el Nombre de Usuario.

### Pestaña de Opciones de Dominio de Correo Electrónico

![opciones de usuarios pestaña de dominios de correo electrónico](../../../es/images/users/users-options-email-domain-options-tab.png)

- **Nombre de Dominio** Introducir una lista de dominios de correo electrónico permitidos y no permitidos.
  Por defecto, se permiten todos los dominios. Se admiten comodines (\*). Por
  ejemplo:
  - \* (Asterisco): Permite o no permite todos los dominios.
  - \*.com: Permite o no permite todos los dominios '.com'.
  - \*.joomla.org: Permite o no permite todos los subdominios 'joomla.org'.
- **Regla** Selecciona si permitir o no permitir el dominio.

### Pestaña de Opciones de Contraseña

![opciones de usuarios pestaña de opciones de contraseña](../../../es/images/users/users-options-password-options-tab.png)

- **Número Máximo de Restablecimientos** El número máximo de restablecimientos de contraseña permitidos
  dentro del período de tiempo. Cero indica sin límite.
- **Tiempo de Restablecimiento** El período de tiempo, en horas, para el contador de restablecimiento.
- **Longitud Mínima** Establecer la longitud mínima para una contraseña.
- **Mínimo de Enteros** Establecer el número mínimo de enteros que deben incluirse en una contraseña.
- **Mínimo de Símbolos** Establecer el número mínimo de símbolos (como !@#\$)
  requeridos en una contraseña.
- **Mínimo de Mayúsculas** Establecer el número mínimo de caracteres alfabéticos en mayúsculas requeridos para una contraseña.
- **Mínimo de Minúsculas** Establecer el número mínimo de caracteres alfabéticos en minúsculas requeridos para una contraseña.

### Pestaña de Autenticación Multifactor

![opciones de usuarios pestaña de autenticación multifactor](../../../es/images/users/users-options-multi-factor-authentication-tab.png)

- **Posiciones de Módulos Frontend Permitidas** Al mostrar la página de
  Autenticación Multifactor en el frontend, todos los módulos estarán ocultos excepto
  aquellos en las posiciones seleccionadas aquí.
- **Mostrar título en frontend** ¿Mostrar un título en la página de verificación de
  Autenticación Multifactor en el frontend? Ten en cuenta que el título
  siempre se muestra en el backend. Si necesitas cambiar el
  título, por favor sobreescribe la clave de idioma `COM_USERS_HEADING_MFA` usando
  Idiomas: Sobreescrituras.
- **Posiciones de Módulos Backend Permitidas** Al mostrar la página de
  Autenticación Multifactor en el backend, todos los módulos estarán ocultos excepto
  aquellos en las posiciones seleccionadas aquí. Ten en cuenta que los módulos en la
  posición `título` siempre se muestran: esto es necesario para mostrar el
  icono y título de la página del backend.
- **Deshabilitar Autenticación Multifactor** Cualquier usuario que pertenezca a *cualquiera*
  de los grupos de usuarios seleccionados estará exento de la Autenticación
  Multifactor. Incluso si han configurado métodos de Autenticación
  Multifactor, no se les pedirá que los utilicen al iniciar sesión,
  ni podrán verlos, eliminarlos o cambiar su
  configuración.
- **Forzar Autenticación Multifactor** Cualquier usuario que pertenezca a *cualquiera*
  de los grupos de usuarios seleccionados deberá habilitar la Autenticación
  Multifactor antes de poder usar el sitio.
- **Estilo de plantilla del frontend** Elegir el estilo de plantilla del frontend que se usará
  en la página de Autenticación Multifactor. Selecciona *Usar Predeterminado* para usar
  el estilo de plantilla del sitio predeterminado.
- **Autenticación Multifactor después de inicio de sesión silencioso** ¿Deberá el usuario
  pasar por la Autenticación Multifactor después de un inicio de sesión silencioso?
  Los inicios de sesión silenciosos son aquellos que no requieren un nombre de usuario y
  contraseña, como la función Recordarme, WebAuthn, etc.
- **Tipos de respuesta de autenticación para inicio de sesión silencioso (para expertos)** Para
  expertos. Una lista separada por comas de tipos de respuesta de autenticación de Joomla
  que se consideran inicios de sesión silenciosos. El valor predeterminado es `cookie` (la
  función Recordarme) y `passwordless` (WebAuthn).
- **Incorporar nuevos usuarios** Si el usuario aún no ha configurado la Autenticación
  Multifactor y esta opción está habilitada, se le redirigirá a la
  página de configuración de Autenticación Multifactor o a la URL personalizada que
  configures a continuación. Esto está destinado a ser una forma simple de informar a tus usuarios
  que la Autenticación Multifactor es una opción en tu sitio.
- **URL de redirección personalizada** Si no está vacío, redirige a esta URL
  en lugar de a la página de configuración de Autenticación Multifactor cuando la opción
  anterior está habilitada. Advertencia: Esto debe ser una URL dentro de tu sitio. No
  puedes iniciar sesión en un enlace externo o en un subdominio diferente.

### Pestaña de Historial de Notas de Usuario

![opciones de usuarios pestaña de historial de notas de usuario](../../../es/images/users/users-options-user-notes-history-tab.png)

- **Habilitar Versiones** Guardar historial de versiones para Notas de Usuario.
- **Número Máximo de Versiones** El número máximo de versiones a almacenar para una
  Nota de Usuario. Si se guarda una Nota de Usuario y se ha alcanzado el número máximo de versiones,
  la versión más antigua se eliminará automáticamente. Si se establece en 0, las versiones
  nunca se eliminarán automáticamente.

### Pestaña de Correo Masivo a Usuarios

![opciones de usuarios pestaña de correo masivo a usuarios](../../../es/images/users/users-options-mass-mail-users-tab.png)

- **Prefijo de Asunto** Introducir texto opcional que se insertará automáticamente
  antes del

 asunto del correo electrónico masivo.
- **Sufijo del Cuerpo del Correo** Introducir texto opcional que se insertará automáticamente
  después del cuerpo del correo electrónico (por ejemplo, una firma).

### Pestaña de Integración

![opciones de usuarios pestaña de integración](../../../es/images/users/users-options-integration-tab.png)

- **Habilitar Campos Personalizados** Habilitar la creación de campos personalizados.

## Consejos

Si eres un usuario novato, mantén los valores predeterminados aquí
hasta que aprendas más sobre el uso de las opciones globales.
