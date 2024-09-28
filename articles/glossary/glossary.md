<!-- Filename: Help4.x:Glossary  / Display title: Glossaire -->

Le glossaire de Joomla! est utile pour expliquer les termes couramment utilisés dans les tutoriels Joomla!, les écrans d'aide et la documentation avancée.

## Lista de Control de Acceso

## Alias en Spa

## Ancla

Un ancla se crea utilizando la etiqueta `<a>` en HTML. Un ancla te permite 
colocar un marcador dentro de una página HTML. En Joomla!, puedes colocar un 
ancla dentro de un artículo (por ejemplo, usando el editor TinyMCE). Esto te permite 
crear un enlace que irá directamente a ese punto en el artículo.

El código fuente HTML para un ancla se ve de la siguiente manera:

    <a name="mi_ancla" title="Mi Ancla"></a>

Puedes enlazar a un ancla desde la misma página usando el código HTML

    <a href="#mi_ancla"></a>

Al hacer clic en ese enlace, te llevará directamente a la ubicación de la etiqueta de ancla.

Puedes enlazar a un ancla en una página diferente agregando "#" más el
nombre del ancla al final de la URL. En el ejemplo anterior, si la URL del
artículo era `http://www.misitio.com/mi_articulo.html`, entonces podrías
enlazar directamente al ancla en esa página con la URL
`http://www.misitio.com/mi_articulo.html#mi_ancla`.

## Artículo

## Hoja de Estilo en Cascada (CSS)

Una Hoja de Estilo en Cascada o CSS se utiliza para controlar la presentación de una
página XHTML. Por ejemplo, un archivo CSS a menudo controla la fuente,
márgenes, color, gráficos de fondo y otros aspectos de la apariencia de una página web.
CSS te permite separar el contenido de una página XHTML de
su apariencia. En Joomla!, los archivos CSS (por ejemplo, template.css) son
normalmente parte de la plantilla.

**Ver también:** Plantilla, Sufijo de Clase de Página, Sufijo de Clase de Módulo

## Categoría

Cada parte de un sitio web impulsado por Joomla! o cualquier tipo de CMS 
necesita un método para mostrar y almacenar su contenido de manera lógica. 
El método usual es por categorías y subcategorías. Joomla! permite múltiples formas 
de mostrar y usar contenido controlado por categorización. Algunos de los 
tipos de contenido que tienen categorización son Artículos (el contenido principal 
de las páginas web), Banners y Contactos.

Una categoría nombrada *Sin Categoría* es la categoría predeterminada asignada 
a la mayoría de los tipos de contenido. La categoría *Sin Categoría* no es descriptiva 
y debe utilizarse según sea necesario para tipos de contenido que no caigan
bajo una categoría específica.

Al crear y asignar categorías, deberías tener una estructura planificada. 
Como ejemplo, esta es una manera de categorizar varios artículos sobre aves:

- Crear dos categorías de artículos de nivel superior nombradas *Animales* y 
  *Plantas*.
- Bajo la categoría *Animales*, crear subcategorías nombradas *Aves* y 
  *Mamíferos*.
- Bajo la subcategoría *Aves*, crear categorías tituladas *Halcones*, *Loros* 
  y *Gorriones*. Esta es la estructura de categoría resultante:

```
- Animales
  - Aves
    - Halcones
    - Loros
    - Gorriones
  - Mamíferos
```

Ahora puedes crear múltiples artículos en las subcategorías de Halcón, Loro y Gorrión 
usando los diferentes géneros o nombres comunes de los tipos específicos de estas 
aves.

## Chrome

Las características de la interfaz gráfica visible de una aplicación a veces se denominan *chrome*.

## Componente

## Núcleo

La palabra *núcleo* en Joomla! se refiere a los archivos distribuidos que son necesarios para crear y administrar un sitio web impulsado por el CMS Joomla. El núcleo de Joomla contiene toda la funcionalidad necesaria para crear y gestionar un nuevo sitio web de manera rápida y sencilla.

## Prefijo de la Tabla de la Base de Datos

El prefijo de la tabla de la base de datos es una cadena (de unos pocos caracteres de largo) que se antepone al nombre de las tablas de Joomla!. Usar un prefijo permite ejecutar múltiples instalaciones de Joomla! utilizando una sola base de datos.

El prefijo de la tabla de la base de datos se puede establecer durante la instalación. Cambiarlo después es posible, pero requiere acceso a la base de datos a través de un medio no-Joomla o una extensión de Joomla como Akeeba Admin Tools y causará algún tiempo de inactividad.

Los desarrolladores de extensiones necesitan usar la cadena `#__` para representar el prefijo. Esta será reemplazada por el prefijo real en tiempo de ejecución.

## Extensión

## LDAP

## Lenguaje

Los lenguajes son quizás el tipo de extensión más básico y crítico. Los lenguajes se empaquetan como paquetes de idioma principal o paquetes de idioma de extensión. Estos paquetes consisten en archivos INI que contienen pares clave/valor para proporcionar la traducción de cadenas de texto estáticas dentro del código fuente de Joomla! Esto permite que tanto el núcleo de Joomla! como los componentes y módulos de terceros puedan internacionalizarse. Los paquetes de idioma principales también incluyen un archivo meta XML que describe el idioma y proporciona información sobre las fuentes que se deben usar para la generación de contenido en PDF.

## Menú

En Joomla!, un **Menú** es un módulo que contiene un conjunto de **elementos del menú** utilizados para la navegación. Cada elemento del menú define una URL a una página del sitio. Contiene configuraciones que controlan la visualización del contenido y el estilo de la página.

## Model-View-Controller

Joomla hace un uso extensivo del patrón de diseño
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a> (MVC).

Cuando se inicia Joomla para procesar una solicitud de un usuario, como
un GET para una página en particular, o un POST que contenga datos de un
formulario, una de las primeras cosas que hace Joomla es analizar la URL
para determinar qué componente será responsable de procesar la solicitud
y pasar el control a ese componente.

Si el componente ha sido diseñado de acuerdo al patrón MVC, pasará el
control al controlador. El controlador es responsable de analizar la
solicitud y determinar qué modelo(s) se necesitarán para satisfacer la
solicitud y qué vista debe usarse para devolver los resultados al
usuario.

El modelo encapsula los datos utilizados por el componente. En la mayoría
de los casos, estos datos provendrán de una base de datos, ya sea la
base de datos de Joomla o alguna base de datos externa, pero también es
posible que el modelo obtenga datos de otras fuentes, como a través de
una API de servicios web que se ejecuta en otro servidor. El modelo
también es responsable de actualizar la base de datos cuando sea
necesario. El propósito del modelo es aislar al controlador y a la vista
de los detalles de cómo se obtienen o modifican los datos.

La vista es responsable de generar la salida que el componente envía al
navegador. Llama al modelo para obtener cualquier información que
necesite y la formatea adecuadamente. Por ejemplo, una lista de elementos
de datos obtenidos del modelo podría envolverse en una tabla HTML por la
vista.

Dado que Joomla está diseñado para ser altamente modular, la salida del
componente generalmente es solo una parte de la página web completa que
el usuario verá finalmente. Una vez que la vista ha generado la salida,
el componente devuelve el control al marco de trabajo de Joomla, que
luego carga y ejecuta la plantilla. La plantilla combina la salida del
componente y cualquier módulo que esté activo en la página actual para
que pueda entregarse al navegador como una sola página.

Para proporcionar más poder y flexibilidad a los diseñadores web, que
pueden estar interesados solo en crear nuevos diseños en lugar de
manipular el código subyacente, Joomla divide la vista tradicional en
una vista y un diseño separados. La vista extrae datos del modelo, como
en un patrón MVC tradicional, pero luego simplemente pone esos datos a
disposición del diseño, que es responsable de formatear los datos para
su presentación al usuario. La ventaja de tener esta división es que el
sistema de plantillas de Joomla proporciona un mecanismo simple para
sobrescribir los diseños en la plantilla. Estas sobrescrituras de
diseño (a menudo llamadas "sobrescrituras de plantillas" porque forman
parte de la plantilla, aunque en realidad es el diseño lo que se está
sobrescribiendo) se agrupan con la plantilla y dan al diseñador de la
plantilla el control completo sobre toda la salida del núcleo de Joomla
y cualquier extensión de terceros instalada que cumpla con el patrón de
diseño MVC.

## Módulo

## Sufijo de Clase del Módulo

Un Sufijo de Clase del Módulo es un parámetro utilizado en los módulos para añadir una nueva clase CSS a un módulo. Se utiliza junto con estilos definidos en un archivo user.css para cambiar la apariencia estándar de un módulo.

El nuevo nombre de clase puede ser utilizado para añadir cualquier estilo deseado al módulo sin necesidad de recrear todo el código CSS existente. Tenga en cuenta que, si crea un nuevo nombre de clase, asegúrese de que tenga un nombre único y no entre en conflicto con otros nombres de clase existentes.

## Posición del Módulo

## Módulo chrome

## PHP

PHP es un lenguaje de script de computadoras diseñado para crear páginas web dinámicas. PHP se utiliza ampliamente para el desarrollo web y puede integrarse en HTML. Generalmente, se ejecuta en un servidor web, tomando código PHP como entrada y creando páginas web como salida. Joomla! está escrito principalmente en el lenguaje PHP.

## Sufijo de Clase de Página

Un Sufijo de Clase de Página es un parámetro utilizado en los elementos del menú de contenido para añadir una nueva clase CSS al diseño de la página. Se utiliza junto con los estilos definidos en un archivo user.css para cambiar la apariencia estándar de un módulo.

El nuevo nombre de la clase puede utilizarse para añadir cualquier estilo deseado a la página sin la necesidad de re-crear todo el código CSS existente. Ten en cuenta que, si creas un nuevo nombre de clase, asegúrate de que tenga un nombre único y no entre en conflicto con ningún nombre de clase existente.

## Parches

## Complemento

## URLs Amigables para Motores de Búsqueda

Los URLs amigables para motores de búsqueda es un término comúnmente abreviado como URLs SEF
o simplemente SEF. Los URLs normales de Joomla! se ven algo así:

    http://www.tusitio.org/index.php?option=com_content&view=section&id=3&Itemid=41

Opcionalmente, puedes hacer que los URLs se muestren como páginas HTML estáticas, como esto:

    http://www.tusitio.org/preguntas-frecuentes.html

Hay opciones incorporadas para generar URLs SEF. Estas se habilitan en los 
*Configuración SEO* (Optimización para Motores de Búsqueda) en la pestaña del 
sitio de la página de Configuración Global. También hay extensiones de terceros que crean 
URLs SEF para Joomla!.

## Menús divididos

Un menú dividido es aquel en el que los diferentes niveles de un solo menú se muestran en dos o más ubicaciones en una sola página web.

Por ejemplo, un requisito común es que un menú de elementos de nivel superior aparezca en la parte superior de la página. Cuando se hace clic en uno de los elementos, el usuario es llevado a una página donde un menú secundario, digamos en la parte izquierda de la página, muestra elementos de segundo nivel dentro del ámbito del elemento de nivel superior.

Los menús aparecen en ubicaciones separadas en la página, pero están relacionados porque uno muestra solo elementos de nivel superior, mientras que el otro muestra elementos de segundo nivel. Esta idea se puede extender para incluir menús de elementos de tercer nivel y más allá.

Esto se puede implementar en Joomla usando un solo menú multinivel y luego creando más de un módulo de menú, cada uno refiriéndose a un nivel diferente.

## Plantilla

Una plantilla es un tipo de extensión de Joomla! que controla la apariencia de la página.
- Una plantilla del Sitio controla la apariencia pública del contenido del sitio.
- Una plantilla del Administrador controla la apariencia del sitio para tareas administrativas tales como: gestión de usuarios, menús, artículos, categorías, módulos, componentes, plugins y plantillas.

## Estilo de plantilla

## Paquete de Actualización

Un Paquete de Actualización en Joomla! es un paquete de archivos que contienen los archivos que han cambiado entre versiones de Joomla!. Cuando este archivo comprimido se descomprime, reemplaza la versión antigua de los archivos modificados con la nueva versión. Por ejemplo, si cincuenta archivos se cambiaran entre la versión 5.1 y 5.2, el paquete de actualización contendría estos cincuenta archivos y las instrucciones sobre cómo ejecutar la actualización. A veces, esto incluye actualizaciones de la base de datos y eliminación de archivos que ya no se usan.

*Traducido por openai.com*

