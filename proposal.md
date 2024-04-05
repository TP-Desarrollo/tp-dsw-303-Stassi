# Propuesta TP DSW

## Grupo
### Integrantes
* legajo - Apellido(s), Nombre(s)
* 47894 - Stassi, José Ignacio
* 47901 - Sinopoli, Martina
* 48038 - Tabini, Azul
* 48237 - Gonzalez, Luciano

### Repositorios
* [frontend app](https://github.com/TP-Desarrollo/Backend-tp-DSW)
* [backend app](https://github.com/TP-Desarrollo/Frontend-tp-DSW)

## Tema
* Alquiler de autos
### Descripción
* Plataforma de alquiler de autos ubicada en Argentina que ofrece una amplia variedad de vehículos para satisfacer las necesidades de los clientes, donde pueden gestionar sus alquileres y la concesionaria puede llevar un control de los mismos.

### Modelo
* Imagen del modelo: https://drive.google.com/file/d/1YAH6TvcWhzhRybeVuIafzx-yVvWhy0Pw/view?usp=drive_link

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Vehiculo<br>2. CRUD Alquiler<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Vehiculo {depende de} CRUD Tipo Vehiculo<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de vehiculos filtrado por tipo de vehiculo, muestra codigo, tipo de vehiculo y estado => detalle info Vehiculo<br> 2. Listado de reservas filtrado por rango de fecha, muestra cod de vehiculo, fecha inicio y fin alquiler, estado y nombre del cliente => detalle muestra datos completos de la reserva, del alquiler y del cliente|
|CUU/Epic|1. Alquilar un vehiculo<br>2. Realizar inicio alquiler|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Vehiculo<br>2. CRUD Alquiler<br>3. CRUD Localidad<br>4. CRUD Empleado<br>5. CRUD <br>6. CRUD Vehiculo<br>|
|CUU/Epic|1. Alquiler de un vehiculo<br>2. Realizar inicio del alquiler<br>3. Realizar fin alquiler y facturación <br> 4. Cancelar alquiler|


### Alcance Adicional Voluntario (A evaluar con profesor)

|Req|Detalle|
|:-|:-|
|Listados |1. TBD|
|CUU/Epic|1. Solicitud de asistencia en ruta <br>2. Seguimiento del estado alquiler|
|Otros|1. TBD|
