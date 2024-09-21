<!-- Filename: Help4.x:Media / Display title: Media -->

## Descripción

El componente de Medios es una herramienta para gestionar archivos en la carpeta de imágenes y otras carpetas locales definidas por el usuario. Las acciones disponibles incluyen:

- Subir una nueva imagen (o documento)
- Eliminar una imagen existente
- Renombrar una imagen
- Editar una imagen
- Obtener un enlace de imagen
- Crear una nueva carpeta

### Elementos Comunes

Algunos aspectos de esta página se cubren en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo acceder

- **Panel de inicio → Sitio → Medios**.

## Captura de pantalla

![Medios](../../../es/images/media/media.png)

## Área de Visualización de Imágenes

### Local

Esta área muestra la estructura de las carpetas locales del sitio, por defecto la carpeta *images*.

La carpeta actualmente seleccionada se muestra en las *Migas de pan* arriba del área de visualización de imágenes.

### Barra Superior

- **Checkbox** Seleccionar o deseleccionar todas las imágenes. Después de la selección, las imágenes individuales pueden ser deseleccionadas.
- **Migas de Pan** Selecciona un elemento de migas de pan para volver en la jerarquía de carpetas.
- **Buscar**. Escribe parte del nombre de una imagen en el cuadro de búsqueda. El filtro funciona de manera progresiva; por ejemplo, ingresar la letra `k` en el cuadro de búsqueda reducirá instantáneamente las imágenes mostradas a aquellas que contienen la letra `k`.
- **Iconos de Lupa** Disminuir o aumentar el tamaño visible de las miniaturas de las imágenes.
- **Iconos de Vista de Lista o Vista de Miniaturas** Alterna entre vista de miniaturas y vista de lista; el ícono cambia en consecuencia.
- **Ícono de Información** Muestra información sobre lo que está seleccionado. Si se selecciona una imagen, mostrará el nombre del archivo, la ruta de la carpeta, el tamaño y varias otras propiedades. Selecciona para abrir o cerrar el panel de información.

### Acciones

Pasa el cursor sobre una imagen y selecciona el botón de menú etiquetado con una elipsis (...). Se mostrarán seis íconos que ofrecen las siguientes acciones:

1. **Vista Previa** Selecciona el ícono de lupa: la imagen se mostrará a tamaño completo en un diálogo.
2. **Editar** Selecciona el ícono de lápiz para abrir la ventana de edición de Medios. Permite recortar, redimensionar o rotar la imagen.
3. **Descargar** Selecciona el ícono de descarga; tu computadora responderá preguntándote qué quieres hacer con la descarga. O puede simplemente guardarla o abrirla en una aplicación de visualización de imágenes.
4. **Obtener un enlace para compartir** Selecciona el ícono de enlace para obtener un enlace a la imagen que se utilizará para compartir. Un diálogo te permitirá copiar el enlace al portapapeles para pegarlo en un correo electrónico o documento.
5. **Renombrar** Selecciona el ícono de renombrar para abrir un diálogo que permita renombrar la imagen.
6. **Eliminar** Selecciona el ícono de papelera para eliminar la imagen. Se te pedirá que confirmes. ¡Una vez eliminada, se va para siempre! También se puede usar para eliminar una carpeta.

## Consejos

- Si deseas mantener imágenes y documentos en carpetas locales separadas:
  1. Crea una carpeta en la raíz de tu sitio, por ejemplo, **files**.
  2. Ve al plugin de Sistema de Archivos - Local y añade **files** bajo **Seleccionar directorios**.
  3. Regresando al componente de Medios, verás *images* y *files* como elementos separados en el panel Local.
- El tamaño máximo de subida de Medios se puede cambiar a una cantidad diferente de `10 MB` en las Opciones de Medios.
- Puedes subir o eliminar múltiples archivos al mismo tiempo.
