# ReactPro Magazine Website

Sitio web estandar destinado a noticias, reseñas, guías, reportajes, etc. para cualquier tipo de temática general (videjuegos, deportes,, etc.). 

Los usuarios pueden visitar el sitio sin necesidad de registrar una cuenta personal. Los usuarios registrados pueden usar el foro de las distintas noticias y valorar el contenido de las mismas. Los usuarios administradores crean contenido y pueden moderar los foros. Los usuarios editores pueden crear articulos y modificar su contenido.

# Entidades

## Tipo usuario

- id
- descripción (admin, autor/redactor, invitado, miembro).

## usuario

- id
- usuario
- nombre
- apellido
- fecha nacimiento
- correo

## Tipo publicación/artículo/reseña
- id
- descripción (opinión, análisis, reportaje, etc.)

## publicación/artículo/reseña

- id
- título
- fecha publicación
- fecha actualización
- autor

## contenido/layout

- id
- tamaño de contenido (1/2/3/4 columnas respecto ventana)
- publicacion (texto/imágen)

# Relaciones

- Un usuario solo puede ser de un tipo (admin, autor/redactor, invitado, miembro)
- Un usuario administrador o redactor puede crear una o muchas publicaciones/artículos/reseñas
- Una publicación puede tener uno o muchos contenidos/layouts
- Una publicación puede ser de un tipo (opinión, análisis, reportaje, etc.)
-

# Funciones

- Crear usuario
- Editar usuario
- Desactivar usuario
- Crear publicación
- Editar publicación
- Desactivar publicación
- Crear tipo publicación

# Pantallas

- Pantalla de inicio
- Pantalla CRUD de artículos
- Pantalla CRUD de usuarios
- Pantalla de tipo publicación y publicación
- Crear/Editar usuario
- Pantalla de login
