# ReactPro - MegaPaste

Es una aplicación para crear pastes (una mezcla de PasteBin y Multipaste) especialmente útil para compartir enlaces en sitios web de naturaleza warez (descargas)

Un paste puede contener N cantidad de subpastes (y se organizan en pestañas)

El proyecto consumirá una API creado por mi (.NET CORE)

# Entidades

## Paste

- Título
- Contraseña
- Fecha
- Url
- Visitas
- Fecha de creación
- Fecha de actualización
- Creado por

## Sub Paste

- Id Paste
- Contenido
- Fecha de creación
- Fecha de actualización
- Creado por

## Reportes/Problemas

- Id Paste
- Nombre
- Contenido
- Correo electrónico
- Fecha
- Resuelto?
- Fecha de resolución
- Fecha de creación

## Usuarios

- Id Paste
- Nombres
- Apellidos
- Correo electrónico
- Contraseña
- Id Rol

## Roles

- Titulo
- Descripcion
- Activo?
- Fecha de creación
- Fecha de actualización

## Roles y permisos

- Id Rol
- Id Permiso
- Descripcion
- Fecha de creación
- Fecha de actualización

## Permisos

- Titulo
- Descripcion
- Activo?
- Fecha de creación
- Fecha de actualización

# Relaciones

- Un usuario tiene un rol
- Un rol puede tener muchos permisos
- Un usuario puede tener muchos pastes
- Un paste puede tener muchos subpastes
- Un paste puede tener muchos reportes

# Funciones

- Crear usuarios
- Listar usuarios
- Editar usuarios
- Borrar usuarios
- Crear pastes
  - Crear subpastes
  - Listar subpastes
  - Modificar subpastes
  - Borrar subpastes
- Listar pastes
- Editar pastes
- Borrar pastes
- Crear reportes
- Resolver reporte

# Pantallas

- Panel Administración
- Listado de pastes
- Detalle de paste
- Perfil de usuario
- CRUD pastes / subpastes

# Planes futuros

- Contenido en BBcodes (permite insertar imágenes, videos, etc)
- Plantillas (para agregar contenido más fácilmente)
- Múltiples usuarios y rol de administrador
- Detección y conversión de enlaces (incluido YouTube)
- Sistema de reportes/problemas por paste y por sub-paste
- Protección de paste con Captcha
- Protección de enlaces con Click' n Load de JDownloader
- Espacios publicitarios editables
- Ids numéricos o texto
