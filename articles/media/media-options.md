<!-- Filename: Help4.x:Media:_Options / Display title: Multimedia: Opciones -->

## Descripción

La página de *Opciones de Medios* se utiliza para configurar los parámetros globales de medios.

### Elementos Comunes

Algunos aspectos de esta página se cubren en artículos de ayuda separados:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La pestaña de permisos](jdocmanual?article=help/common-elements/edit-permissions).

## Cómo acceder

- Selecciona **Contenido → Medios** desde el menú del Administrador.
- Selecciona el botón **Opciones** en la barra de herramientas.

## Captura de pantalla

![Opciones de Medios](../../../es/images/media/media-options.png)

## Campos del formulario

### Medios

- **Tamaño máximo (en MB)** Usa cero para no tener límite. Nota: El servidor tiene un límite máximo.
- **Ruta a la carpeta de archivos** Introduce la ruta a la carpeta de archivos relativa a la raíz de tu espacio web. No comiences la ruta con una barra. Cambiar a otra ruta diferente de la predeterminada *images* puede romper tus enlaces.
- **Ruta a la carpeta de imágenes** Introduce la ruta a la carpeta de imágenes relativa a la raíz de tu espacio web. No comiences la ruta con una barra.
- **Restringir subidas** Restringe las subidas para usuarios de menor nivel que administrador a imágenes si `Fileinfo` o `MIME Magic` no están instalados.
  - **Extensiones permitidas** Restringe las subidas para usuarios de menor nivel que administrador a los archivos en la lista.
  - **Verificar tipos MIME** Usa `Fileinfo` o `MIME Magic` para intentar verificar archivos. Intenta deshabilitar esto si recibes errores de tipo MIME inválido.
- **Extensiones legales de imágenes (Tipos de archivo)** Extensiones de imágenes (tipos de archivo) que tienes permitido subir (separadas por comas). Se utilizan para verificar cabeceras de imágenes válidas y para seleccionar imágenes.
- **Extensiones legales de audio (Tipos de archivo)** Extensiones de audio (tipos de archivo) que tienes permitido subir (separadas por comas). Se utilizan para verificar cabeceras de audio válidas y para seleccionar archivos de audio.
- **Extensiones legales de video (Tipos de archivo)** Extensiones de video (tipos de archivo) que tienes permitido subir (separadas por comas). Se utilizan para verificar cabeceras de video válidas y para seleccionar videos.
- **Extensiones legales de documentos (Tipos de archivo)** Extensiones de documentos (tipos de archivo) que tienes permitido subir (separadas por comas). Se utilizan para verificar cabeceras de documentos válidas y para seleccionar documentos.
- **Extensiones ignoradas** Extensiones de archivo ignoradas para la verificación de tipo MIME y subidas restringidas.
- **Tipos MIME legales** Una lista separada por comas de los tipos MIME legales para subir.

## Consejos

- Si eres un usuario principiante, puedes mantener los valores predeterminados hasta que aprendas más sobre el uso de las opciones globales.
- Si eres un usuario avanzado, puedes ahorrar tiempo creando buenos valores predeterminados aquí.
