# ReactPro Hospital

Esta aplicación se utilizará para llevar un registro sobre los doctores y pacientes, asi como tener registro de las visitas medicas y los diagnosticos.

Se podran asignar pacientes a sus respectivas camas dependiendo el estado que estara la cama, estas podran estar libres u ocupadas. Se tendran un registro de su historial medico asi como su historial de visitas medicas adjuntando el medico que atendió a la persona.

# Entidades

## Paciente

- Id de paciente
- DPI
- Nombre
- Apellido
- Fecha de nacimiento
- Telefono

## Planta
- Id de planta
- Nombre
- Numero de camas

## Cama
- Id de cama
- id de Planta

## Historia

- Id de Historia
- Fecha entrada
- Fecha salida
- Id de paciente

## Visita Medica
- Id de visita
- Diagnostico
- Id de medico
- Id de cama del paciente

## Medico

- Id de medico
- DPI
- Nombre
- Apellido
- Telefono

## Cama de paciente
- Id cama del paciente
- Fecha entrada
- Id de Cama
- Id de Historia
- Estado

# Funciones

- Crear pacientes
- Modificar pacientes
- Crear historial
- Modificar historial
- Crear medicos
- Modificar Medicos
- Crear visita medica
- Modificar visita medica
- Crear asignacion de cama a paciente
- Modificar asignacion de cama a paciente
- Crear Cama
- Modificar Cama
- Crear planta
- Modificar planta

# Pantallas

- Listado de doctores
- Listado de Pacientes
- Listado de historial y visita medica de pacientes
- listados de plantas y camas (ocupadas o libres)
- crear/editar doctores
- crear/editar pacientes
- crear/editar planta
- crear/editar historial/visita medica
- crear/editar asignación de cama a paciente

