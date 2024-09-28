<!-- Filename: Help4.x:Joomla_Update  / Display title: Mise à jour Joomla -->

## Descripción

Esta página permite actualizar Joomla! utilizando un paquete de actualización del 
repositorio de código de Joomla!. Es mejor y más seguro dejar que Joomla se actualice
a sí mismo usando este método.

## Cómo Acceder

En el **Panel de Notificaciones del Tablero de Inicio** el ícono de Joomla tendrá uno de dos mensajes:
- **Joomla está actualizado**
- **X.Y.Z Disponible - ¡Actualizar ahora!**

Selecciona el ícono.

Además, el **Sistema → Panel de Actualización → Joomla** mostrará una marca de verificación, indicando que está actualizado, o un número de versión, indicando que hay una nueva versión disponible.

## Captura de Pantalla

Si tu sitio está actualizado, verás esta pantalla:

![Subir & Actualizar](../../../en/images/joomla-update/upload-update-up-to-date.png)

Si hay una actualización disponible, verás esta pantalla:

![Subir & Actualizar](../../../en/images/joomla-update/upload-update-available.png)

Si estás actualizando una versión mayor o menor, verás una pantalla de verificación previa a la actualización:

![verificación previa a la actualización](../../../en/images/joomla-update/upload-update-pre-update-check.png)

Selecciona cada uno de los tres elementos del menú para ver si algo necesita atención.

## Iniciar Actualización

Si no tienes la última versión de Joomla, puedes instalar la última actualización desde esta página. Para hacerlo, asegúrate de haber tomado una copia de seguridad y marca la casilla de verificación **Soy consciente...** para indicar que lo has hecho. Luego, selecciona el botón **Iniciar Actualización** y Joomla instalará la última versión.

La pantalla de actualización muestra una barra de progreso mientras la actualización está en curso.

### Subir y Actualizar

Puedes usar este botón para actualizar Joomla si tu servidor está detrás de un cortafuegos o si no puede contactar con los servidores de actualización. Primero descarga el Paquete de Actualización de Joomla en formato ZIP desde la página oficial de descarga de Joomla.

Debes tener configurado tu *upload_max_filesize* y *post_max_size* de PHP a 64Mb y tu límite de memoria PHP a 256 Mb. De lo contrario, la actualización puede fallar. ¡Una buena razón para hacer esa copia de seguridad!

![subir e instalar](../../../en/images/joomla-update/upload-update-upload-install.png)

## Opciones de Actualización

El botón de Opciones de la Barra de Herramientas te permite seleccionar el tipo de actualización:

- **Por Defecto** Esto se utiliza para los sitios configurados para permanecer con la versión instalada.
- **Joomla Siguiente** Esto se utiliza para los sitios que normalmente pasan a la siguiente versión mayor tan pronto como se lanza una versión estable.
- **URL Personalizada** Para que los desarrolladores seleccionen una fuente de actualización.

*Traducido por openai.com*

