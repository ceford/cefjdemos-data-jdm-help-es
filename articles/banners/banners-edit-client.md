<!-- Filename: Help4.x:Banners:_New_or_Edit_Client  / Display title: Bannières : Modifier le client -->

## Descripción

El formulario de Edición de Clientes de Banners se utiliza para ingresar o cambiar los datos de los Clientes de Banners. Se requiere al menos un Cliente de Banners antes de poder crear un Banner.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de Ayuda separados:

* [Barras de Herramientas](jdocmanual?article=help/common-elements/toolbars).
* [La Ventana Emergente de Historial de Versiones](jdocmanual?article=help/common-elements/edit-version-history).

## Cómo Acceder

- Seleccione **Componentes → Banners → Clientes** en el menú del Administrador.
  - Para crear un nuevo Cliente, seleccione el botón **Nuevo** en la barra de herramientas.
  - Para editar un Cliente existente, seleccione el **nombre** en la columna de Clientes.

## Captura de pantalla

![Banners editar cliente](../../../es/images/banners/banners-edit-client-details-tab.png)

## Campos del Formulario

- **Nombre** El nombre de este cliente.

### Pestaña de Detalles

- **Nombre de Contacto** El nombre de la persona de contacto para este cliente.
- **Correo Electrónico de Contacto** La dirección de correo electrónico del cliente del banner.
- **Tipo de Compra** El tipo de compra del banner. Esto se usa para
  indicar cómo el cliente del banner compró el tiempo de exhibición para el
  banner - mensual, anual, etc.
- **Rastrear Impresiones** Si se debe rastrear o no el número de veces que
  el banner se muestra a los visitantes del sitio web.
- **Rastrear Clics** Si se debe rastrear o no el número de veces que
  los visitantes del sitio web hacen clic en el banner.
- **Información Adicional** Introduce cualquier información adicional que quieras
  guardar para este cliente.
- **Estado** Estado de publicación del artículo. Los valores posibles son:
  - *Publicado*: El artículo está publicado. Este es el único estado que permitirá
    a los usuarios normales del sitio web ver este artículo.
  - *No Publicado*: El artículo no está publicado.
  - *Archivado*: El artículo ha sido archivado.
  - *En la Papelera*: El artículo ha sido enviado a la Papelera.
- **Nota de Versión** Campo opcional para identificar esta versión del artículo
  en la ventana del Historial de Versiones del artículo.

### Pestaña de Metadatos

![Pestaña de edición de metadatos del cliente de banners](../../../es/images/banners/banners-edit-client-metadata-tab.png)

- **Palabras Clave** Entrada opcional para palabras clave. Deben ingresarse separadas
  por comas (por ejemplo, "gatos, perros, mascotas") y pueden ingresarse en
  mayúsculas o minúsculas. (Por ejemplo, "GATOS" coincidirá con "gatos" o
  "Gatos"). Las palabras clave pueden usarse de varias maneras:
  1.  Para ayudar a los motores de búsqueda y otros sistemas a clasificar el contenido del
      artículo.
  2.  En combinación con etiquetas de Banners, para mostrar Banners específicos en función
      del contenido del artículo. Por ejemplo, supongamos que tienes un Banner con un anuncio
      de productos para perros y otro Banner para productos de gatos. Puedes hacer que tu Banner
      para perros se muestre cuando un usuario esté viendo un artículo relacionado con perros y tu
      Banner para gatos se muestre para un artículo relacionado con gatos. Para hacer esto, debes:
      - Añadir las palabras clave "perro" y "gato" a los artículos apropiados.
      - Añadir las Etiquetas "perro" y "gato" a los Banners apropiados en
        Banners: Editar.
      - Establecer el parámetro del módulo Banner 'Buscar por Etiquetas' en "Sí" en
        la lista de Módulos del Sitio: Banners.
  3.  Solo para artículos, en combinación con el módulo Artículos - Relacionados,
      para mostrar artículos que compartan al menos una palabra clave en común. Por
      ejemplo, si el artículo actual mostrado tiene las palabras clave "gatos,
      perros, monos", cualquier otro artículo con al menos una de estas
      palabras clave se mostrará en el módulo 'Artículos - Relacionados'.
- **Usar Prefijo Propio** Si se debe usar o no el prefijo del banner o del
  cliente. Selecciona *No* si deseas usar el prefijo del cliente del banner.
- **Prefijo de Palabra Clave Meta** Al coincidir las palabras clave meta, solo buscar
  palabras clave meta con estos prefijos opcionales. Esto mejora el rendimiento.

*Traducido por openai.com*

