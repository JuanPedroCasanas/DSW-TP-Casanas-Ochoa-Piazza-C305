# Propuesta TP DSW

## Grupo
### Integrantes
* 50373 - Casañas, Juan Pedro
* 50452 - Ochoa, María Sofía
* 50330 - Piazza, Nair Antonella

### Repositorios
* [fullstack app](https://github.com/JuanPedroCasanas/DSW-App-Fullstack)

## Tema
### Descripción
Sistema de gestión de consultorios y turnos que administra tanto el alquiler de consultorios de un espacio a profesionales, como la asignación de turnos a pacientes que se atiendan por los mismos

### Modelo
![imagen del modelo](https://github.com/JuanPedroCasanas/DSW-TP-Casanas-Ochoa-Piazza-C305/blob/main/ART_DMCL_v2.png)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Persona<br>2. CRUD Profesional<br>3. CRUD Consultorio|
|CRUD dependiente|1. CRUD Turno {depende de} CRUD Profesional y CRUD Persona<br>2. CRUD Modulo {depende de} CRUD Profesional y CRUD Consultorio|
|Listado<br>+<br>detalle| 1. Listado de turnos filtrado por:  Profesional, paciente, consultorio y/o fecha <br> 2. Listado de modulos filtrado por: Profesional, tipo de modulo, mes y/o consultorio|
|CUU/Epic|1. Reservar un turno para un profesional<br>2. Reservar un módulo en un consultorio|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Modulo<br>2. CRUD Obra Social<br>3. CRUD Especialidad|
|CUU/Epic|1. Reservar un turno para un profesional<br>2. Reservar un módulo en un consultorio<br>3. Registrar nuevo paciente|


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|
|Listados |1. Listar Personas filtradas por Obra Social <br> 2. Listado de turnos filtrado por profesional y rango de fecha, muestra fecha y hora de turno, estado del mismo y apellido de Persona|
|CUU/Epic|1. Cancelar turno<br>2. Registrar profesional|
|Otros|1. Envío de recordatorio de turno por email|

