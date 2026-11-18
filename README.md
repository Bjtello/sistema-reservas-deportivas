# Sistema de Reservas de Canchas Sintéticas y Espacios Deportivos

Plataforma web full-stack diseñada para la administración integral de complejos deportivos, gestión de canchas sintéticas y control de reservas en tiempo real. El sistema permite evitar cruces de horarios mediante validaciones en base de datos y calcula automáticamente tarifas diferenciadas según el horario (diurno/nocturno) o día de la semana.

## Stack Tecnológico
* **Frontend:** Angular (TypeScript, HTML5, CSS3)
* **Backend:** Java con Spring Boot (Spring Web, Spring Data JPA)
* **Base de Datos:** PostgreSQL

## Estructura del Proyecto (Modelo de Entidades)
El núcleo del sistema se basa en cuatro entidades principales relacionadas en PostgreSQL:
* `ComplejoDeportivo`: Información general de la sede o complejo deportivo (nombre, dirección, teléfono, horario de atención).
* `Cancha`: Espacios deportivos asociados a un complejo (nombre/número, tipo de superficie, capacidad, tarifa diurna y tarifa nocturna).
* `Cliente`: Registro de usuarios que realizan las reservaciones (nombres, cédula/identificación, teléfono, correo electrónico).
* `Reserva`: Gestión de agendamientos que vincula a un `Cliente` con una `Cancha` específica (fecha, hora de inicio, hora de fin, tarifa calculada y estado de la reserva).

## Integrantes del Equipo y Ramas
Cada integrante cuenta con su propia rama de desarrollo independiente en este repositorio:
* `bryan-tello` — Bryan Tello
* `andres-maldonado` — Andrés Maldonado
* `marielena-vasquez` — Marielena Vasquez
