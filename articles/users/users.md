<!-- Filename: Help4.x:Users / Display title: Usuarios -->

## Descripción

The Users list is used to find, add, and edit users.

## Cómo acceder
Seleccionar **Panel de inicio → Site → Usuarios**

To add a User:

- Clic el botón **Nuevo** en la Barra de Herramientas

To edit a User:

- select a **Name** from the list

## Captura de pantalla

<img
src="https://docs.joomla.org/images/thumb/9/99/Help-4x-Users-screen-es.png/800px-Help-4x-Users-screen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/99/Help-4x-Users-screen-es.png/1200px-Help-4x-Users-screen-es.png 1.5x, https://docs.joomla.org/images/thumb/9/99/Help-4x-Users-screen-es.png/1600px-Help-4x-Users-screen-es.png 2x"
data-file-width="2618" data-file-height="1500" width="800" height="458"
alt="Users screen" />

## Encabezados de columna

- **Checkbox**. Check this box to select users. To select all users,
  check the box in the column heading. After boxes are checked the
  toolbar button 'Actions' get active.
- **Nombre**. The full name of the user.
  - **Añadir una nota**. Create a Note for the user.
    - **Mostrar la lista de notas**. Show the
      <a href="https://docs.joomla.org/Help4.x:User_Notes/es" class="new"
      title="Special:MyLanguage/Help4.x:User Notes/es (page does not exist)">User
      Notes</a> for the user as a list.
    - **Mostrar nota**. Show the User Notes for the user in a window and
      stays in the current screen.
- **Usuario**. The name the user will log in as.
- **Habilitado**. Whether or not the user is enabled.
- **Activado**. Whether or not the user is activated. Normally when a
  user registers from the Frontend, some type of activation is required.
  This is controlled by the 'New User Account Activation' parameter in
  the Users: Options.
- **Grupos**. The list of groups that the user belongs to. Note that a
  user may belong to more than one group.
- **Correo electrónico**. Aquí se muestra la dirección de correo
  electrónico del usuario.
- **Última visita**. Aquí se puede ver la fecha en la cual, el usuario,
  se conectó por última vez.
- **Registro**. The date the user was registered.
- **ID**. A unique identification number for this user, you cannot
  change this number.

## Filtros de lista

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Opciones de filtro**. Click to display the additional filters.
- **Limpiar**. Has clic en el botón 'Limpiar' para borrar el campo de
  Filtro y restaurar la lista a su estado sin filtrar.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- Number to DisplayGlobal Configuration.

### Opciones de filtro

Near the top of the page you will see the filter bar shown in the
Screenshot above.

- **Seleccionar estado**. Select from Enabled / Disabled.
- **Seleccionar estado activo**. Select from Activated / Unactivated.
- **Seleccionar grupo**. Select from the list box to list only users who
  are members of that group.
- **Seleccionar última fecha de visita**. Select from a list to show
  only users who visited in a selected time frame.
- **Seleccionar fecha de registro**. Select from a list to show only
  users who registered in a selected time frame.

### Paginación

**Page Controls**. When the number of articles is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Números de página**. Has clic para ir a la página deseada.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Nuevo**. Opens the editing screen to create a new user.
- **Acciones**. Reveals a list of actions for selected users. Check one
  or more users checkboxes to activate the list.
  - **Activar**. Activates multiple users. Select all the users required
    using their checkboxes then click this button. An email will be sent
    to the user notifying that their account has been activated
  - **Bloquear**. Blocks one or more users. Select the users to be
    blocked using their checkboxes then click this button.
  - **Desbloquear**. Unblocks one or more users. Select the users to be
    unblocked using their checkboxes then click this button.
  - **Lote**. Batch processes the selected users.
  - **Borrar**. Deletes the selected users.
- **Opciones**. Opens Users: Options.
- **Ayuda**. Se abre esta pantalla de ayuda.

## Proceso por lotes

The Batch Process allows a change in settings for a group of selected
users.

<img
src="https://docs.joomla.org/images/thumb/e/e2/Help-4x-Users-batch-subscreen-es.png/600px-Help-4x-Users-batch-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e2/Help-4x-Users-batch-subscreen-es.png/900px-Help-4x-Users-batch-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/e/e2/Help-4x-Users-batch-subscreen-es.png/1200px-Help-4x-Users-batch-subscreen-es.png 2x"
data-file-width="1598" data-file-height="717" width="600" height="269"
alt="Users batch subscreen" />

**How to Batch Process** a group of users:

1.  Select one or more users on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Selecciona uno o más de los siguientes valores:
    - To change the **User Group**, select the desired new user group
      from the Select Group list box.
    - Choose to do the desired action.
      - Añadir al grupo
      - Borrar del grupo
      - Mover al grupo
    - Decide if a **Password Reset** is wanted.
4.  Cuando todos los parámetros hayan sido ajustados, haz clic en
    *procesar* para realizar los cambios. Un mensaje **"Proceso por
    lotes completado correctamente."** se mostrará.

## Consejos Rápidos

- Click on the name of a user to edit the user's properties.
- Click on the icon in the Enabled column to toggle between Enabled and
  Disabled status.
