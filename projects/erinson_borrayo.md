# ReactPro Tickets

Es una aplicación para llevar control de tickets, donde los usuarios puedan crear tickets para diferentes categorias para una empresa.
Por ejemplo precios, horarios, direcciones, entre otros.

Un ticket puede tener 3 estados: Abierto, En Progreso y Completado:

- Cuando el ticket se crea comienza en estado "Abierto".
- Cuando el usuario comienza el trabajo lo coloca en estado "En Progreso".
- Cuando el usuario termina el trabajo lo coloca en estado "Completado".

Se podra llevar un manejo de usuarios y departamentos, asi mismo una catogria sera administrada por uno o multiples departamentos en los cuales
existira diferentes tipos de roles entre los cuales estan: swa, admin, cliente, editor, cada uno podra realizar diferentes opciones.

Un usuario podra registrarse o no en el sistema, por lo cual al registrarse podra tener la opción de poder visualizar todo lo relacionado con el ticket
y tmabien podra responder cuando el lo necesite.

# Entidades

## Ticket

- id (pk)
- user (fk)
- name
- firstname
- lastname
- email
- phone
- status (fk)
- category (fk)
- comment
- create_date

## Rol

- id (pk)
- name

## User

- id (pk)
- username
- firstname
- lastname
- email
- phone
- password
- rol (fk)
- status

## Status

- id (pk)
- name

## Category

- id (pk)
- name

## Departments

- id (pk)
- name
- description

## Response

- id (pk)
- ticket (fk)
- create_date
- comment
- user (fk)

# Relaciones

- Un ticket tiene puede tener una categoria
- Un ticket tendra un estado asignado
- Una categoria puede tener varios departamentos encargados
- Un departamento puede tener multiples usuarios
- Un usuario puede tener un rol
- Un ticket puede estar relacionado a un usuario

# Funciones

- Crear usuario
- Editar usuario
- Crear ticket
- Editar ticket
- Cambiar ticket de estado
- Borrar ticket
- Administrar permisos
- Administrar departamentos
- Administrar categorias
- Asignar usuarios a departamentos
- Administrar departamentos para categorias

# Pantallas

- Listado de tickets
- Detalle de ticket
- Perfil de usuario
- Crear/Editar ticket
- Crear/Editar usuario
- Crear/Editar departamentos
- Crear/Editar categorias
- Crear/editar estados
- Iniciar sesión
- Registrarse
- Dashboard
