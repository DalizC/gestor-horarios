# Brief del usuario (2026-11-19)

Texto original del pedido, sin reinterpretar. La especificación (`docs/specs/`) sale de aquí, del estudio de mercado y de las respuestas del usuario.

> Quiero hacer un proyecto que me permita crear y organizar turnos de empleados. Esto debe ser idealmente un proyecto sin persistencia (sin BFF) de solo front, donde luego yo pueda descargar el horario, o pueda cargar uno previamente hecho para modificarlo, en un formato Excel, JSON, CSV o TXT. El sitio debe tener un repo en mi GitHub y desplegarse mediante Pages como sitio estático. Debe ser lindo, moderno e intuitivo. Debe poder añadir personas a un equipo, designar si tiene turnos rotativos o no, cuál es su contrato de trabajo (cantidad de horas a la semana, días libres, etc.) y su rol. Supongamos que es para un café, por ende debe haber un grupo de meseras, cocina, mesón, etc. El sitio debe ser capaz de, bajo ciertas configuraciones, generar los turnos del mes (configurable para extender o minimizar el tiempo, a semana por ejemplo). Debe ser capaz también de prever si esa persona tiene vacaciones o días libres. La idea es generar un horario de trabajo lo más justo posible y con la menor cantidad de roce. Actualmente los turnos pueden ser casi al azar, teniendo que abrir algunas veces y otras cerrar. La idea es configurar eso para que una semana abra, y la otra cierre, etc.
>
> La idea es que el desarrollo sea lo más autónomo posible y solo evaluar al inicio y al final, dejando que el sitio se construya en base a la descripción que di, a las preguntas iniciales que tenga y a una averiguación de mercado de cómo otras aplicaciones similares funcionan y cómo es en general la resolución de estos conflictos.

## Decisiones ya tomadas (usuario, 2026-11-19)
- Repo **público** `DalizC/gestor-horarios` + GitHub Pages (Pages desde repo privado exige GitHub Pro).
- Angular + `@dalizc/ui`, con un tema propio: segundo consumidor del design system.
- Se construye como **épica**: estudio de mercado, preguntas en tandas y dirección estética al inicio; el usuario aprueba la spec; oleadas autónomas; revisión final del usuario.
