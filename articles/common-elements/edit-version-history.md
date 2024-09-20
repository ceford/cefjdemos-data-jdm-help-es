<!-- Filename: Help4.x:Components_Version_History / Display title: Editar historial de versiones -->

## Descripción

Un pop-up de Historial de Versiones muestra las versiones anteriores del elemento que se está editando. Está
disponible para Artículos, Banners y Clientes, Contactos, Fuentes de Noticias, Notas de Usuario
y todas las Categorías.

Cada vez que se guarda un elemento, se crea automáticamente una nueva versión. El número
de versiones que se deben conservar para cada elemento se establece en las Opciones del componente. Una o
más versiones pueden marcarse para conservarse para siempre. Dichas versiones no se eliminarán
automáticamente, incluso si se excede el número máximo de versiones ingresado en las opciones.

**Nota:** Si se utiliza versionado, los campos personalizados no se almacenan en diferentes versiones.

## Cómo Acceder

Seleccione el botón **Versiones** en la barra de herramientas de una página de edición de elementos.

## Captura de Pantalla

![Pop-up de historial de versiones](../../../es/images/common-elements/articles-edit-versions.png)

## Encabezados de Columnas

- **Casilla de verificación** Marque esta casilla para seleccionar uno o más elementos. Para seleccionar todos
los elementos, marque la casilla en el encabezado de la columna. Una vez que las casillas estén marcadas,
seleccione un botón de la barra de herramientas para realizar una acción sobre los elementos seleccionados.
- **Fecha** La fecha y hora en que se guardó la versión. Al seleccionar este
enlace, se abrirá la vista previa de esa versión en una ventana emergente. Tenga en cuenta que una
de las fechas estará seguida de un símbolo de estrella. Esto indica que esta
es la versión que está guardada actualmente y se está editando.
- **Nota de Versión** Una Nota de Versión se puede usar para ayudar a identificar la naturaleza de los
cambios de una versión a la siguiente. Una Nota de Versión ingresada antes de guardar un
elemento se mostrará en esta columna.
- **Conservar para Siempre** Esta columna muestra si la versión ha sido marcada para
Conservar para Siempre. Normalmente, cada versión se conservará de acuerdo con
la configuración en la página de opciones del componente. La configuración predeterminada es
conservar un máximo de 10 versiones anteriores de un elemento. Cuando se guarda un elemento que
ya tiene 10 versiones guardadas, la versión más antigua se elimina. Si una versión está
marcada como Conservar para Siempre, no se contará como una de las versiones guardadas y
no se eliminará cuando se alcance el número máximo.
  - Para alternar el estado de Conservar para Siempre, seleccione un botón *No* o *Sí* o marque
la casilla de verificación de la versión y luego seleccione el botón Conservar Activado/Desactivado en la barra de herramientas.
- **Autor** El usuario que guardó esta versión.
- **Recuento de Caracteres** El total de caracteres guardados en esta versión. Tenga en cuenta
que esto incluye los nombres de las columnas de la base de datos, así como los
caracteres realmente escritos.

## Barra de Herramientas

- **Restaurar** La versión actual del elemento está marcada con una estrella a la
derecha de la Fecha. Para restaurar una de las otras versiones guardadas,
marque la casilla de verificación de la versión deseada y seleccione el
botón Restaurar. La versión actual del elemento será reemplazada por
la versión seleccionada, y la pantalla de edición se recargará con la versión
restaurada cargada en el editor.
- **Vista Previa** Para previsualizar una versión, seleccione la columna Fecha de la versión deseada
o marque la casilla de verificación y luego el botón Vista Previa. Se cargará una ventana emergente
separada que mostrará la versión seleccionada del elemento.
- **Comparar** Para comparar dos versiones y ver qué cambió, seleccione las
casillas de verificación de cada una de las versiones y luego el botón Comparar. Una
nueva ventana del navegador se abrirá mostrando una lista de campos modificados y los cambios
realizados en esos campos.
  - La primera columna es el nombre del campo, la segunda es la versión más antigua,
la tercera es la versión más reciente y la última columna resalta las
diferencias entre las dos versiones.
- **Conservar Activado/Desactivado** Este botón activa o desactiva la función Conservar para Siempre para una
versión. Normalmente, la versión más antigua de un elemento se eliminará automáticamente
cuando se haya excedido el número máximo de versiones (establecido en las Opciones del componente).
Si establece la propiedad Conservar para Siempre para una versión, nunca
se eliminará automáticamente.
- **Eliminar** Este botón permite eliminar manualmente una o más versiones. Marque
la casilla de verificación de las versiones a eliminar y luego seleccione el botón Eliminar. Tenga en cuenta que esto *no* elimina el elemento que se está editando. Solo elimina
el historial de versiones del elemento.
