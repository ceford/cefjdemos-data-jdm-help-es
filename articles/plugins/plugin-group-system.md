<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group  / Display title: Groupe Système -->

## Descripción del Grupo

### Sistema - Funciones Adicionales de Accesibilidad

Este complemento añade una barra de herramientas de accesibilidad a tu sitio con opciones de accesibilidad adicionales.

![Formulario de funciones adicionales de accesibilidad del sistema](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Sistema - Depuración

Este complemento proporciona información de depuración. El informe se muestra debajo de la pantalla principal de las interfaces del frontend y backend de una instalación de Joomla!.

#### Pestaña del Plugin

![Formulario de depuración del sistema pestaña de plugin](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Grupos Permitidos** Grupos de usuarios que verán la información de depuración cuando esté habilitada.
- **Mostrar Perfilado** Si se muestra o no la información de los puntos de referencia del perfilado.
- **Mostrar Consultas** Si se incluye o no el registro de consultas SQL en la información de depuración.
- **Mostrar Uso de Memoria** Si se incluye o no los datos de uso de memoria en la información de depuración.

#### Pestaña de Idioma

![Formulario de depuración del sistema pestaña de idioma](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Mostrar errores al analizar archivos de idioma** Si se muestra o no una lista de archivos de idioma con errores debido a que no cumplen con la especificación del archivo de idioma de Joomla!.
- **Mostrar Archivos de Idioma** Si se muestran o no los archivos de idioma que se han cargado para generar la página.
- **Mostrar Cadenas de Idioma** Si se incluyen o no cadenas de idioma indefinidas en la información de depuración.
- **Eliminar Primera Palabra** Si siempre elimina o no la primera palabra en cadenas de varias palabras.
- **Eliminar Desde el Inicio** Elimina las palabras especificadas del comienzo de la cadena de idioma. Para múltiples palabras separe cada palabra con el carácter de barra vertical ( | ) así: palabra1|palabra2
- **Eliminar Desde el Final** Elimina las palabras especificadas del final de la cadena de idioma. Para múltiples palabras separe cada palabra con el carácter de barra vertical ( | ) así: palabra1|palabra2

#### Pestaña de Registro

![Formulario de depuración del sistema pestaña de registro](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### Sistema - Campos

El complemento de campos del sistema que se requiere para mostrar los campos personalizados.

### Sistema - Encabezados HTTP

Este complemento puede establecer Encabezados de Seguridad HTTP. Por favor, consulte la documentación de Gestión de Encabezados HTTP para más detalles sobre este complemento.

![Formulario de encabezados http del sistema](../../../en/images/plugins/plugin-group-system-http-headers.png)

### Sistema - Resaltar

Complemento del sistema para resaltar términos especificados.

### Sistema - Planificador de Tareas

Este complemento busca tareas de complementos para ejecutar.

![Formulario de planificador de tareas del sistema](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Frecuencia (en minutos)** Configure a cero para ejecutar en cada carga de página (para pruebas).
- **Webcron** Configure en Sí para llamarlo como un comando CLI. Para más información vea Escribir una Aplicación CLI.
- **Clave de Activación** La clave que se debe pasar en un comando Webcron.

### Sistema - Estadísticas de Joomla!

![Formulario de estadísticas de joomla](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **ID Único** Un identificador que permite al proyecto Joomla! contar instalaciones únicas del complemento. Esto se envía con las estadísticas de vuelta al servidor.
- **Intervalo (horas)** Las estadísticas se enviarán cada X horas. El valor predeterminado es 12.
- **Modo** Seleccione la forma en que desea que se envíen las estadísticas.

### Sistema - Notificación de Actualización de Joomla!

![Formulario de notificación de actualización de joomla](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Emails de Super Usuarios** Una lista separada por comas de las direcciones de correo electrónico que recibirán los emails de notificación de actualización. Las direcciones en la lista DEBEN pertenecer a usuarios existentes en su sitio que tengan el privilegio de Super Usuario. Si ninguno de los correos electrónicos listados pertenece a Super Usuarios, o si se deja en blanco, todos los Super Usuarios de este sitio recibirán el email de notificación de actualización.
- **Idioma del Email** Si elige Automático (predeterminado), el email de notificación de actualización a Super Usuarios estará en el idioma del sitio en el momento en que se active el complemento. Al seleccionar un idioma aquí, está forzando a que los emails de notificación de actualización se envíen en este idioma específico.

### Sistema - Código de Idioma

Proporciona la capacidad de cambiar el código de idioma en el documento HTML generado para mejorar el SEO. Los campos aparecerán cuando el complemento esté habilitado y guardado. Más información en W3.org.

### Sistema - Filtro de Idioma

![Formulario de filtro de idioma del sistema](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Selección de Idioma para nuevos Visitantes** Si se elige el idioma predeterminado del sitio o se detectan automáticamente los ajustes del navegador.
- **Cambio Automático de Idioma** Esta opción cambiará automáticamente el idioma del contenido usado en el Frontend cuando se cambie el idioma del sitio del usuario.
- **Asociaciones** Permite la asociación de elementos al cambiar de un idioma a otro.
- **Añadir Meta Tags Alternativas** Añadir meta tags alternativas para ítems de menú con ítems de menú asociados en otros idiomas.
- **Añadir Meta Tag x-default** Añadir meta tag x-default para mejorar el SEO.
- **Idioma x-default** Elija su idioma x-default.
- **Eliminar Código de Idioma de URL** Si se elimina o no el Código de Idioma de la URL definido (por ejemplo, your_domain_name/en) de su Idioma de Contenido que corresponde al idioma predeterminado del sitio cuando la URL SEF se establece en *Sí*.
- **Duración de la Cookie** Las cookies de idioma se pueden configurar para que expiren al final de la *Sesión* o después de un *Año*.

### Sistema - Rotación de Registros

![Formulario de rotación de registros del sistema](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Rotación de Registros (en días)** Con qué frecuencia se deben rotar los registros.
- **Máximo de Registros** El número máximo de registros antiguos a mantener.

### Sistema - Cerrar Sesión

El complemento de cerrar sesión del sistema permite a Joomla redirigir al usuario a la página de inicio si elige cerrar sesión mientras está en una página de acceso protegido.

### Sistema - Caché de Página

Este complemento permite la caché de página. La caché de página permite al servidor web guardar instantáneas de las páginas y utilizarlas al servir páginas web. Esto mejora el rendimiento de su sitio web y reduce la carga del servidor. Este complemento tiene las siguientes opciones:

![Formulario de caché de página del sistema](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Usar Caché del Navegador** Si se usa o no el mecanismo para almacenar una caché de página en el navegador local. El valor predeterminado es *No*.
- **Excluir Ítems del Menú** Seleccione qué ítems del menú desea excluir de la caché.

### Sistema - Consentimiento de Privacidad

Este complemento permite recoger el consentimiento de sus usuarios a la política de privacidad del sitio y gestionar la expiración del consentimiento.

![Formulario de consentimiento de privacidad del sistema](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Política de Privacidad Breve** Le permite ingresar un resumen de su política de privacidad o mantener la existente.
- **Tipo de Privacidad** Elija entre Artículo e Ítem de Menú. Dependiendo de la elección, uno u otro de los dos campos siguientes estarán presentes.
- **Artículo de Privacidad** Seleccione o cree un Artículo para su política de privacidad para enlazarlo con el formulario de su usuario.
- **Ítem de Menú de Privacidad** Seleccione o cree un Ítem de Menú vinculado a un Artículo que contenga su política de privacidad.
    - *Nota:* Tenga mucho cuidado con los sitios multilingües. Es mejor asegurarse de que el Artículo o el Ítem de Menú ocurran como Asociaciones en todos los idiomas.
- **Mensaje de Redirección** El mensaje que se mostrará en la redirección. Ingrese su propio mensaje o mantenga el existente.

![Formulario de consentimiento de privacidad del sistema pestaña de expiración](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Habilitar** (Sí/No) La expiración está deshabilitada por defecto. Habilítela si desea realizar comprobaciones para la expiración de los consentimientos de privacidad.
- **Verificación periódica (días)** (0 a 120 días) 30 días por defecto. Si la expiración está habilitada, defina el número de días para realizar la verificación.
- **Expiración** (180 a 720 días) 360 días por defecto. Si la expiración está habilitada, defina el número de días cuando el consentimiento de privacidad expira.
- **Recordatorio** (0 a 120 días) 30 días por defecto. Si la expiración está habilitada, defina el número de días cuando se debe enviar un recordatorio antes de la expiración del consentimiento de privacidad.

### Sistema - Redirigir

![Formulario de redirigir del sistema](../../../en/images/plugins/plugin-group-system-redirect.png)

- **Recoger URLs** Estas opciones controlan la recopilación de URLs. Esto es útil para evitar una carga innecesaria en la base de datos.
- **Incluir Nombre de Dominio en URLs Expiradas** Guardar la URL expirada como absoluta (incluye dominio) o relativa (excluye dominio).
- **Excluir URLs** Defina expresiones regulares o términos que deben excluirse al guardar.

### Sistema - Recordarme

Este complemento proporciona la funcionalidad de *Recordarme*. Esto permite que el sitio web *recuerde* su nombre de usuario y contraseña para que pueda iniciar sesión automáticamente cuando regrese al sitio. Este complemento no tiene opciones.

### Sistema - SEF

Este complemento agrega soporte SEF a los enlaces en el documento. Funciona directamente en el HTML y no requiere una etiqueta especial. Tiene las siguientes opciones:

![Formulario de sef del sistema](../../../en/images/plugins/plugin-group-system-sef.png)

- **Dominio del Sitio** Si su sitio se puede acceder a través de más de un dominio, ingrese el dominio preferido (a veces conocido como canónico) aquí. Nota: https://example.com y https://www.example.com son diferentes dominios.

### Sistema - Purga de Datos de Sesión

![Formulario de purga de datos de sesión del sistema](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Habilitar Limpieza de Datos de Sesión** Cuando está habilitado, este complemento intentará purgar los datos expirados según la frecuencia calculada por la probabilidad y el divisor.
- **Habilitar Limpieza de Metadatos de Sesión** Cuando está habilitado, este complemento limpiará los metadatos de sesión opcionales de la base de datos. Tenga en cuenta que esta operación no se ejecutará cuando se use el manejador de base de datos, ya que esos datos se eliminan como parte de la operación de Limpieza de Datos de Sesión.
- **Probabilidad** En combinación con el campo divisor, estos dos campos se usan para determinar la frecuencia de la operación de limpieza de datos de sesión que se activa en una solicitud.
- **Divisor** En combinación con el campo de probabilidad, estos dos campos se usan para determinar la frecuencia de la operación de limpieza de datos de sesión que se activa en una solicitud. La probabilidad se calcula utilizando probabilidad/divisor, por ejemplo, 1/100 significa que hay un 1% de probabilidad de que el proceso se ejecute en cada solicitud.

### Sistema - Saltar a la Navegación

El complemento crea un menú desplegable que consiste en los enlaces a los lugares importantes en una página web dada. Esto facilita a los usuarios de teclado y de lectores de pantalla saltar rápidamente al lugar deseado eligiéndolo de la lista de opciones.

![Formulario de saltar a la navegación del sistema](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### Sistema - Registro de Acciones de Usuarios

![Formulario de registro de acciones de usuarios del sistema](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Días para eliminar registros después de** Ingrese cuántos días deben mantenerse los registros antes de que se eliminen. Ingrese 0 si no desea eliminar los registros.

### Sistema - Registro de Usuarios

![Formulario de registro de usuarios del sistema](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Registrar Nombres de Usuario** Esta opción registrará el nombre de usuario utilizado cuando falla una autenticación.

*Traducido por openai.com*

