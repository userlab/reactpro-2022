# ReactPro Tickets

Es una aplicación para llevar control de tickets. En el ticket se describe el trabajo que un usuario debe realizar.

Un ticket puede tener 3 estados: Abierto, En Progreso y Completado:

- Cuando el ticket se crea comienza en estado "Abierto".
- Cuando el usuario comienza el trabajo lo coloca en estado "En Progreso".
- Cuando el usuario termina el trabajo lo coloca en estado "Completado".

# Entidades

## Ticket

- Título
- Descripción
- Estado
- Encargado

## Usuario

- Nombre
- Correo

# Relaciones

- Un ticket tiene un encargado
- Un usuario tiene asignados muchos tickets

# Funciones

- Crear usuario
- Editar usuario
- Crear ticket
- Editar ticket
- Cambiar ticket de estado
- Borrar ticket

# Pantallas

- Listado de tickets
- Detalle de ticket
- Perfil de usuario
- Crear/Editar ticket
- Crear/Editar usuario