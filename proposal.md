# Propuesta TP DSW

## Grupo
### Integrante
* 47894 - Stassi, José Ignacio

Aclaracion: El resto del grupo no participó en el desarrollo por lo que fueron descartados del TP Integrador.

### Repositorios
* [Frontend app](https://github.com/TP-Desarrollo/Frontend-tp-DSW)
* [Backend app](https://github.com/TP-Desarrollo/Backend-tp-DSW)

## Tema
* Alquiler de autos
  
### Descripción
* Plataforma de alquiler de autos ubicada en Rosario que ofrece una amplia variedad de vehículos para satisfacer las necesidades de los clientes, donde estos pueden realizar alquileres del vehiculo deseado por el tiempo que necesite.

### Modelo
* Imagen del modelo: https://drive.google.com/file/d/1YAH6TvcWhzhRybeVuIafzx-yVvWhy0Pw/view?usp=drive_link

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Vehiculo<br>2. CRUD Alquiler<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Vehiculo {depende de} CRUD Tipo Vehiculo<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de vehiculos filtrado por tipo de vehiculo, muestra codigo, tipo de vehiculo y estado => detalle info Vehiculo|
|CUU/Epic|1. Alquilar un vehiculo|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Vehiculo<br>2. CRUD Alquiler<br>3. CRUD Localidad<br>4. CRUD Empleado<br>5. CRUD Cliente<br>6. CRUD Vehiculo<br>|
|CUU/Epic|EN REVISION, NO SON LOS FINALES<br>1. Alquiler de un vehiculo<br>2. Cancelar alquiler|
