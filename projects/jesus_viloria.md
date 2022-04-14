# Delivertory (Delivery Inventory)

Es una aplicación para llevar control del inventario y entrega de insumos a la flota motorizada de una empresa de delivery, con opción de ver cantidad de items entregados por motorizado y cantidad de items disponibles en inventario.

App conformada por:
-Inventario de insumos catalogado por items.
-Listado de motorizados con clasificación y cantidad de items entregados.

Los items son creados y añadidos manualmente por un administrador.

Cada vez que se le asigne una cantidad de un item a un motorizado esta restará la disponibilidad de el item especifico en el inventario disponible.


# Entidades

## Inventario de items

- Listado de items
- Resumen de cantidades de items

## Items

- Título de item
- Descripción
- Cantidad a disposición
- Cantidad historica entregada

## Inventario de motorizados

- Listado de motorizados
- Resumen de datos del motorizado

## Motorizado

- Fotografía
- Nombre
- Número de identificación
- Correo
- Listado de items recibidos

# Relaciones

- El inventario está compuesto por una lista de items
- Los motorizados poseén una lista de items única que han recibido
- Listado de motorizados está compuesto por un listado de motorizados con un resumen de sus datos

# Funciones

- Crear motorizado
- Crear item
- Editar motorizado
- Editar item
- Editar item en perfil del motorizado
- Borrar motorizado
- Borrar item
- Cálculos automaticos según items entregados

# Pantallas

- Listado de items
- Listado de motorizados
- Resumen de información de motorizados
- Resumen de información de items
- Crear/Editar items
- Crear/Editar motorizados
