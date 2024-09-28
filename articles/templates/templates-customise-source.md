<!-- Filename: Help4.x:Templates:_Customise_Source  / Display title: Modèles : Personnaliser la source -->

<div class="alert alert-warning">
Cette page apparaît dans l’index des pages d’aide mais n’est pas utilisée via un bouton d’aide.
Ceci est un bug qui sera probablement corrigé.
</div>

## Descripción

La página *Plantillas: Personalizar Fuente* es donde se edita el código fuente de los archivos de plantilla. Proporciona una interfaz de texto plano para editar los archivos de plantilla. La sintaxis de programación HTML y PHP se resalta para facilitar la lectura de los archivos de código fuente. En la barra de título, la palabra *Fuente* aparece como el nombre de la plantilla, por ejemplo *(Cassiopeia)*.

## Cómo Acceder

- Selecciona **Sistema → Panel de Plantillas → Plantillas de Sitio** desde el menú del Administrador. O...
- Selecciona **Sistema → Panel de Plantillas → Plantillas de Administrador** desde el menú del Administrador. Luego...
  - Selecciona un nombre de plantilla de la columna **Plantillas**. Luego...
    - Selecciona un archivo para editar desde la pestaña del Editor.

## Captura de pantalla

![Plantillas personalizar pestaña del editor de Cassiopeia](../../../es/imágenes/plantillas/plantillas-personalizar-cassiopeia-editar-componente-pestaña-editor.png)

## Campos del Formulario

### Pestaña del Editor

- Selecciona un archivo para editar. El área de edición muestra texto con resaltado de sintaxis para la mayoría de los tipos de archivos.

### Pestaña Crear Sobrescrituras

- Selecciona un elemento para sobrescribir. Si se selecciona una carpeta, ésta se expande para mostrar una lista de archivos. Si se selecciona un archivo, se copia inmediatamente en la carpeta html sin pedir confirmación. La sobrescritura se coloca en la ubicación apropiada. Hay un mensaje de confirmación, por ejemplo: *Sobrescritura creada en /templates/cassiopeia/html/mod_whosonline*.

### Pestaña Archivos Actualizados

Si no ha habido actualizaciones en la plantilla desde que se crearon las sobrescrituras, esta pestaña contendrá un mensaje simple:

- **Aviso** Los archivos sobrescritos están actualizados. No se ha cambiado nada en la última extensión o actualización de Joomla.

Si ha habido actualizaciones, una tabla mostrará una lista de sobrescrituras que necesitan ser revisadas.

### Pestaña Descripción de la Plantilla

- **Miniatura y Descripción** Información sobre esta plantilla.

## Barra de Herramientas

Los iconos de la Barra de Herramientas cambian según la acción que se esté realizando. Puedes ver:

- **Guardar** Guarda el elemento y permanece en la pantalla actual.
- **Guardar y Cerrar** Guarda el elemento y cierra la pantalla actual.
- **Copiar Plantilla** Copia la plantilla actual. Un cuadro de diálogo solicita
  un nuevo nombre.
- **Vista Previa de la Plantilla** Selecciona para abrir el Sitio en una nueva pestaña del navegador.
- **Gestionar Carpetas** Permite la creación y eliminación de carpetas de plantillas
  usando un cuadro de diálogo.
- **Archivo Nuevo** Permite subir un archivo desde tu computadora a la
  jerarquía de archivos de la plantilla usando un cuadro de diálogo.
- **Renombrar Archivo** Selecciona un archivo para editarlo. Selecciona el botón de Renombrar para
  solicitar un nuevo nombre.
- **Eliminar Archivo** Se te pedirá Confirmar o Cancelar.
- **Cerrar Archivo** Cierra el archivo abierto y regresa a la pestaña del Editor.
- **Ayuda** Abre esta pantalla de ayuda.

## Consejos

- Importante: No elimines los archivos de plantilla predeterminados usando FTP porque
  genera un error tanto en el frontend como en el backend.
- Antes de editar el archivo HTML y CSS de la plantilla, es una buena
  idea hacer una copia de seguridad del archivo que estás editando. Además, puedes editar
  estos archivos fuera de Joomla! utilizando el editor de HTML o CSS de tu
  preferencia.

*Traducido por openai.com*

