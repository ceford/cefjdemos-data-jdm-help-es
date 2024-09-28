<!-- Filename: Help4.x:Privacy_Dashboard  / Display title: Tableau de bord de confidentialité -->

## Descripción

La página del *Tablero de Privacidad* enumera el Tipo de Solicitud de Privacidad del Usuario, el Estado y 
el Número de solicitudes.

### Tutoriales

- [Esquema de Privacidad - Contenido y Flujo de Trabajo](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [La Suite de Herramientas de Privacidad](https://docs.joomla.org/J3.x:Privacy/en)
  (Tutorial Detallado de Joomla 3)
- [Flujo de Trabajo de Solicitudes de Información](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Tutorial Detallado de Joomla 3)

## Cómo acceder

- Seleccione **Usuarios → Icono del Panel de Privacidad** desde el menú del Administrador.

## Captura de pantalla

![tablero de privacidad](../../../es/images/privacy/privacy-dashboard.png)

## Paneles del Tablero

### Estado de Privacidad

- **Política de Privacidad Publicada** Indica si hay disponible una Política de Privacidad. Navega a *Plugins → Sistema - Consentimiento de Privacidad* y selecciona tu Artículo de Privacidad. Una vez publicado, puedes editar tu artículo de Política de Privacidad desde esta página.
- **Elemento del Menú del Formulario de Solicitud Publicado** Indica si el Elemento del Menú (que permite a los usuarios enviar solicitudes) está publicado o no. Para crearlo, navega a tu Menú → Agregar Nuevo Elemento de Menú → Tipo de Elemento de Menú: Crear Solicitud. Una vez publicado, puedes editar tu elemento del menú desde esta pantalla.
- **Solicitudes Urgentes Pendientes** Número de solicitudes urgentes que son anteriores al número de días establecido en las Opciones del Componente (de 10 a 29 días).
- **Envío de Correos Habilitado**
- **Cifrado de la conexión a la base de datos**

### Solicitudes de Privacidad

- **Tipo de Solicitud** Muestra los dos tipos diferentes de solicitud
  - *Exportar* cuando un usuario ha enviado una solicitud para exportar sus datos
  - *Eliminar* cuando un usuario ha enviado una solicitud para ser eliminado.
- **Estado** Muestra el estado de la solicitud
  - *Inválido* un Super usuario ha invalidado la solicitud
  - *Pendiente* cuando un usuario ha enviado una solicitud pero aún no ha confirmado su solicitud. Los usuarios tienen dos maneras de confirmar: visitando la URL mencionada en el correo electrónico enviado al usuario o copiando el token del correo electrónico y pegándolo en el formulario en la URL dada. El token es válido por 24 horas.
  - *Confirmado* el usuario ha confirmado su solicitud.
  - *Completado* un Super usuario ha completado la solicitud.
- **\# de solicitudes** Muestra el número de solicitudes para cada tipo. Este bloque también muestra el número total de solicitudes y el número de solicitudes activas.

## Consejos

- Selecciona un Tipo de Solicitud para ver la lista de solicitudes de ese tipo.

*Traducido por openai.com*

