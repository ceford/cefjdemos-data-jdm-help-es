<!-- Filename: Help4.x:Languages:_Edit_Override  / Display title: Langues : Modifier le remplacement -->

## Descripción

En el código de Joomla, las cadenas de texto que deben aparecer en la
Interfaz de Usuario, ya sea en la interfaz del Sitio o en la interfaz del
Administrador, se expresan como constantes de cadena. Por ejemplo, la cadena
*Su sesión ha expirado. Por favor, inicie sesión de nuevo.* se expresa como
`JLIB_ENVIRONMENT_SESSION_EXPIRED`. La cadena de texto puede ser traducida
a cualquier idioma. El idioma predeterminado es inglés británico. Hay miles
de tales cadenas en una instalación de Joomla.

Si una cadena no se adapta a su sitio, puede usar la función de Anulación de
Idioma para reemplazar la original. La página *Idiomas: Anulaciones* muestra una
lista de anulaciones existentes, por lo que al principio está vacía.

### Elementos Comunes

Algunos aspectos de esta página se tratan en artículos de Ayuda por separado:

* [Barras de herramientas](jdocmanual?article=help/common-elements/toolbars).

## Cómo Acceder

- Selecciona **Sistema → Administrar Panel → Sobrescrituras de Idioma**. Luego...
  - Selecciona un **Idioma y Cliente** de la lista desplegable. Luego...
    - Selecciona el botón **Nuevo** en la Barra de herramientas para crear una nueva sobrescritura.
      O...
    - Selecciona el enlace constante en la columna **Constante** para editar una
      sobrescritura existente.

## Captura de pantalla

![Editar idioma anulando](../../../es/images/languages/languages-edit-override.png)

## Campos del Formulario

### Panel Derecho: Busca el texto que deseas cambiar

- **Buscar** ¡Comienza aquí! Es más probable que conozcas el Valor 
  (expirado) que el Constante (`_EXPIRED`). En cualquier caso, la búsqueda 
  es insensible a mayúsculas y minúsculas para la cadena parcial.
- **Texto de Búsqueda** Ingresa el texto para buscar y selecciona el botón *Buscar*.
- **Resultados de la Búsqueda** Una lista de cadenas que contienen el término 
  de búsqueda aparece en un panel de Resultados separado debajo del panel Derecho. Selecciona 
  la que estás buscando. El constante y el texto se copiarán en el 
  *panel izquierdo* para ser actualizados y guardados.

### Panel Izquierdo: Crea una Nueva Reemplazo o Edita este Reemplazo

- **Idioma** y **Ubicación** Estos se seleccionaron antes de abrir este 
  formulario de edición y no se pueden cambiar.
- **Constante del Idioma** Esta es la cadena utilizada en el código por el 
  desarrollador. Si el valor no existe en el código, la cadena nunca 
  se utilizará.
- **Texto** Aquí es donde anulas el término predeterminado con tu 
  versión.
- **Para Ambas Ubicaciones** Selecciona para aplicar el reemplazo tanto en el front-end como en el 
  back-end.
- **Archivo** Esto muestra dónde se encuentra el archivo de reemplazo en el sistema de 
  archivos. Podrías necesitar saber esto para la resolución de problemas.

*Traducido por openai.com*

