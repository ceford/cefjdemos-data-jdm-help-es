<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group  / Display title: Groupe d'Authentification -->

## Descripción del Grupo

Los plugins en este grupo se utilizan para el inicio de sesión estándar de usuario en las interfaces del Sitio o del Administrador. El predeterminado es la Autenticación de Joomla. El método *Cookie* se usa junto con la función *Recordarme* solo para el inicio de sesión del Sitio. La cookie se establece después del primer inicio de sesión con uno de los otros métodos.

## Autenticación - Cookie

![plugin de autenticación con cookie](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Duración de la Cookie** El número de días hasta que la cookie de autenticación expire. Otros factores pueden hacer que expire antes de esto. Duraciones más largas son menos seguras.
- **Longitud de la Clave** La longitud de la clave que se utiliza para cifrar la cookie. Longitudes más largas son más seguras, pero ralentizarán el rendimiento.

## Autenticación - Joomla

Este plugin procesa el método de autenticación de usuario predeterminado en Joomla. No tiene opciones.

## Autenticación - LDAP

Este plugin procesa la autenticación de usuarios contra un servidor LDAP.

![plugin de autenticación ldap](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Host** La URL del host. Por ejemplo, `openldap.mycompany.org`.
- **Puerto** El número de puerto. El predeterminado es 389.
- **LDAP V3** Indica si este host usa la versión 3 de LDAP. El predeterminado es LDAP v2.
- **Negociar TLS** Indica si se debe usar cifrado TLS con este host. Si se establece en *Sí*, todo el tráfico hacia y desde este servidor debe estar cifrado.
- **Seguir Referencias** Indica si se debe configurar el indicador LDAP_OPT_REFERRALS en Sí o No. Para hosts con Windows 2003, esto debe estar configurado en No.
- **Método de Autorización** *Vinculación Directa como Usuario* o *Vinculación y Búsqueda*.
- **Base DN** El DN base de tu servidor LDAP.
- **Cadena de Búsqueda** Una cadena de consulta utilizada para buscar un usuario dado. La palabra clave `[search]` es reemplazada por el inicio de sesión escrito por el usuario. Por ejemplo: `uid=[search]`. Se puede ingresar más de una cadena de búsqueda. Sepáralas con un carácter de punto y coma `;`. Esto solo se usa cuando se realiza la búsqueda.
- **DN del Usuario** La palabra clave [username] se reemplaza dinámicamente por el nombre de usuario escrito por el usuario. Una cadena de ejemplo es: `uid=[username], dc=[my-domain], dc=[com]`. Se puede ingresar más de una cadena. Sepáralas con un carácter de punto y coma `;`. Esto solo se usa si el Método de Autorización anterior está configurado en *Vinculación Directa como Usuario*.
- **Nombre de Usuario de Conexión y Contraseña de Conexión** Estos definen los parámetros de conexión para la fase de búsqueda de DN. Para una búsqueda anónima, deja ambos campos en blanco. Para una conexión administrativa, el *Nombre de Usuario de Conexión* es el nombre de usuario de una cuenta administrativa (por ejemplo, *Administrador*). En este caso, la *Contraseña de Conexión* es la contraseña real de esta cuenta administrativa.
- **Mapear: Nombre Completo** El atributo LDAP que contiene el nombre completo del usuario.
- **Mapear: Correo Electrónico** El atributo LDAP que contiene la dirección de correo electrónico del usuario.
- **Mapear: ID de Usuario** El atributo LDAP que contiene el ID de inicio de sesión del usuario. Para Active Directory, esto es `sAMAccountName`.
- **Depurar** Habilita la depuración codificada a nivel 7.

*Traducido por openai.com*

