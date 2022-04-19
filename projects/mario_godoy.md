# ReactPro Soporte Tecnico

Es una aplicación para llevar control de tickets del servicio que esta prestando. En el ticket se describe el trabajo que se debe realizar de parte de los Tecnicos.

Un ticket puede tener 3 estados: Abierto, En Progreso y Completado:

- Cuando el ticket se crea comienza en estado "Abierto" con el servicio a solicitar.
- Cuando el tecnico comienza el trabajo lo coloca en estado "En Progreso".
- Cuando el tecnico termina el trabajo lo coloca en estado "Completado".

## Herramientas a Utilizar:

### --Frontend--

-Reac

### --Backend--

-MySql

-Rest Api

# Entidades

## Usuario

-UserName

-Password

## Tecnico

-UserName

-Password

-rol

-Nombre

-Apellido

-Sexo

-Telefono

-Email

## Ticket

- Título
- Descripción
- Estado
- Encargado

## Relaciones

-Un Tecnico tiene asignado varios Ticket´s

-Un Tecnico tiene asignado un Usuario (y viceversa)

-Un Tecnico tiene asignado un rol

## Funciones

-Crear Usuario

-Editar Usuario

-Asignar Rol

-Crear Tecnico (Editar,Actualizar,Eliminar)

## Pantallas

-Login

-Create Account

-Listado de Ticket´s

-Listado de Roles

-Detalle de Tecnicos

-Crear/Editar Tecnico

-Crear/Editar Usuario
