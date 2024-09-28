<!-- Filename: Help4.x:Users:_Edit_Profile  / Display title: Utilisateurs : Nouveau ou Modifier -->

## Descripción

La página *Usuarios: Nuevo o Editar* se utiliza para crear un nuevo usuario o editar un usuario existente.

### Elementos Comunes

Algunos elementos de esta página se abordan en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

Para editar un usuario existente:

- Selecciona **Usuarios → Administrar** en el menú del Administrador. Luego...
  - Busca al usuario requerido y selecciona el enlace del nombre en la
    columna **Nombre**.

Para crear un nuevo usuario:

- Selecciona **Usuarios → Administrar** en el menú del Administrador. Luego...
  - Selecciona el botón **Nuevo** en la Barra de herramientas.
- O... Selecciona **Usuarios → Administrar → Icono de más** en el
  menú del Administrador.
- O... Selecciona **Usuarios → Icono del Dashboard** en el menú del
  Administrador. Luego...
  - Selecciona el icono **Más** en el panel de Usuarios.
- O... Selecciona **Panel Principal → Panel del Sitio → Icono de Usuarios Más**
  empezando desde el menú del Administrador.

## Captura de pantalla

![editar detalles del usuario](../../../es/images/users/users-edit-account-details-tab.png)

## Campos de Formulario

### Detalles de la Cuenta

- **Nombre** Introduce el nombre del usuario.
- **Nombre de Usuario** Introduce el nombre de usuario para el usuario.
- **Contraseña** Rellena este campo con una (nueva) contraseña. Aunque este campo no es
  obligatorio, el usuario no podrá iniciar sesión si no se establece una contraseña.
- **Confirmar Contraseña** Introduce de nuevo la contraseña del campo anterior
  para verificarla. Este campo es obligatorio cuando hayas llenado el campo 
  Nueva contraseña.
- **Correo Electrónico** Introduce una dirección de correo electrónico para el usuario.
- **Fecha de Registro** Fecha de registro del usuario.
- **Última Visita** Fecha en la que el usuario visitó el sitio por última vez.
- **Fecha del Último Restablecimiento** Fecha y hora del último restablecimiento de contraseña.
- **Contador de Restablecimiento de Contraseña** Número de restablecimientos de contraseña 
  desde el último restablecimiento.
- **Recibir Correos del Sistema** (*Sí*/*No*) Si se establece en sí, el usuario recibirá
  correos del sistema.
- **Estado del Usuario** (*Bloqueado*/*Habilitado*) Habilita o bloquea a este usuario.
- **Requiere Restablecimiento de Contraseña** (*Sí*/*No*) Si se establece en sí, el usuario 
  deberá restablecer su contraseña la próxima vez que inicie sesión en el sitio.
- **ID** Número de registro en la base de datos.

### Pestaña de Grupos de Usuarios Asignados

![editar usuario pestaña de grupos de usuarios asignados](../../../es/images/users/users-edit-assigned-user-groups-tab.png)

El valor predeterminado es *Registrado*, pero se puede cambiar en la página *Usuario: Opciones*.

### Configuración Básica

![editar usuario pestaña de configuración básica](../../../es/images/users/users-edit-basic-settings-tab.png)

- **Estilo de Plantilla del Backend** Selecciona un estilo de plantilla para la interfaz del 
  Administrador Backend. Esto solo afectará a este usuario.
- **Idioma del Backend** Selecciona el idioma para la interfaz del Administrador Backend.
  Esto solo afectará a este usuario.
- **Idioma del Frontend** Selecciona el idioma para la interfaz del Frontend.
  Esto solo afectará a este usuario.
- **Editor** Selecciona un editor para este usuario. El predeterminado es TinyMCE a no ser 
  que se cambie en la Configuración Global.
- **Zona Horaria** Hay una larga lista de zonas horarias para elegir, organizadas por
  continente, con Europa cerca del final. La zona horaria predeterminada del sitio se 
  establece en la Configuración Global.

### Configuración de Accesibilidad

![editar usuario pestaña de configuración de accesibilidad](../../../es/images/users/users-edit-accessibility-settings-tab.png)

- **Monocromo** Sí/No
- **Alto Contraste** Sí/No
- **Resaltar Enlaces** Sí/No
- **Aumentar Tamaño de Fuente** Sí/No

### Opciones del Registro de Acciones de Usuario

¡Esta pestaña está disponible solo para Super Usuarios!

- **Enviar notificaciones del Registro de Acciones de Usuario** Si se establece en sí,
  el usuario recibirá notificaciones del registro de acciones de usuario por correo electrónico.
- **Seleccionar eventos para notificar** Selecciona las notificaciones del registro 
  de acciones de usuario que se enviarán por correo electrónico.

### Inicio de sesión con Autenticación Web (WebAuthn) W3C

Esta pestaña solo está presente cuando se accede al sitio usando https. Para configurar
el inicio de sesión sin contraseña, necesitas un dispositivo de hardware, disponible en Amazon
y otros comercios similares por aproximadamente £15, o un dispositivo con reconocimiento de 
huella dactilar, reconocimiento facial o software biométrico similar. Puedes agregar más de un
autenticador. Una vez configurado, puedes iniciar sesión haciendo clic en el botón de 
Autenticación Web en el formulario de inicio de sesión y luego pulsando el botón en 
el dispositivo cuando se te solicite.

Esta pestaña está presente pero no se puede usar en el formulario de edición de Usuario 
porque el inicio de sesión sin contraseña solo puede ser configurado por el propio usuario 
a través del formulario Editar Perfil.

### Token de API de Joomla

Esta pestaña se usa para gestionar los tokens de seguridad usados para autenticar 
la aplicación de API de Joomla (acceso remoto a tu sitio). Si no estás seguro de lo que 
esto hace, probablemente no lo necesites y puedas ignorar estas configuraciones de manera segura.

El token solo es visible para tu propia cuenta.

### Autenticación Multifactor

![editar usuario pestaña de autenticación multifactor](../../../es/images/users/users-edit-multi-factor-authentication-tab.png)

Esta pestaña te permite configurar uno o más métodos para permitir el acceso a tu
cuenta después de iniciar sesión con Nombre de Usuario y Contraseña. Solo está presente 
cuando editas tu propio perfil. Hay varios métodos disponibles. Si pierdes acceso a un método 
por alguna razón, puedes elegir otro método desde la pantalla de verificación post-inicio de sesión.
¡Los métodos alternativos deben haberse configurado con anticipación!

#### Códigos de Respaldo

Este método genera un conjunto de números que puedes guardar o imprimir. Cada
número solo puede ser usado una vez, así que recuerda enmendar tu lista después de usarlo.

#### Código de Verificación

Un formulario adicional para rellenar con métodos alternativos de configuración del 
código. Echa un vistazo y haz clic en el botón Cancelar si decides no proceder.

#### Llave Yubi

Esto es para otro tipo de llave de hardware que proporciona un código en una
pantalla de visualización. Echa un vistazo y selecciona Cancelar si decides
no proceder.

#### Autenticación Web

Para un dispositivo de hardware con un botón para presionar. Echa un vistazo y selecciona
Cancelar si decides no proceder. Ten en cuenta que este método será ignorado si usas el 
método de Inicio de sesión con WebAuthn por separado.

#### Código por Correo Electrónico

Con este método se envía un código a tu dirección de correo electrónico. Se te
pedirá que ingreses ese código para obtener acceso al sitio. Es un código de una sola vez.
Se envía uno nuevo para cada inicio de sesión. Echa un vistazo y selecciona Cancelar 
si decides no proceder.

## Consejos

- Nombre, Nombre de usuario e Correo electrónico son obligatorios.
- Si no completaste un idioma en particular, editor, sitio de ayuda y/o
  zona horaria, se utilizarán las configuraciones predeterminadas de la Configuración Global,
  el Administrador de Idiomas y/o el Administrador de Plantillas.

*Traducido por openai.com*

