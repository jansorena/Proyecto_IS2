# Proyecto_IS2

# Links a repositorios de trabajo

- https://github.com/Primo18/project-IS2-frontend
- https://github.com/jansorena/project-IS2-backend

# Visión del producto

Plataforma web que permite optimizar la gestión de un gimnasio, permitiendo a administradores gestionar miembros y equipamiento, a entrenadores personales crear y monitorear rutinas y evaluaciones, y a clientes visualizar sus entrenamientos personalizados. 
Esta plataforma multifuncional facilita la administración de suscripciones y pagos, el seguimiento de la disponibilidad de máquinas y la planificación de sesiones.
La plataforma está a disposición de los entrenadores y clientes en los distintos computadores distribuidos en el gimnasio.

# Sprint 1: Configuración y funcionalidad básica de la plataforma

El sprint 1 esta orientado a la configuración del proyecto, del entorno de desarrollo y funcionalidades básicas para el software. Se enfocara principalmente en el desarrollo de los sistemas de autenticación y roles (administrador, entrenador, cliente) y la creación de la interfaz básica para el manejo de los clientes.
## Historias de usuario y tareas asociadas
### US1
Como administrador quiero entrar a la plataforma mediante un login para poder gestionar usuarios, sesiones de entrenamiento y datos de las máquinas.
#### Criterio de aceptación
Administrador ingresa mediante un login con sus credenciales. Tras la verificación, el administrador es redirigido a la página principal del panel de administración.
#### Tareas
- [ ] Diseño de las interfaces de usuario para el administrador.
- [ ] Implementación de las interfaces de usuario.
### US2
Como administrador quiero poder registrar a los nuevos clientes (nombre, sexo, edad, diagnosticos, etc), para que los entrenadores puedan acceder a esta información y personalizar los entrenamientos.
#### Criterio de aceptación
Cuando el administrador esté logueado, al ingresar un nuevo cliente podré especificar sus datos: rut, nombre, sexo, historial médico, fecha nacimiento, los cuales son almacenados en la plataforma y serán visibles por administradores y entrenadores
#### Tareas
- [ ] Diseño de la base de datos.
- [ ] Modelamiento de la base de datos.
- [ ] Desarrollo de funcionalidades para añadir y gestionar clientes.
### US3
Como administrador quiero actualizar o registrar una membresía posterior al pago de esta para gestionar suscripciones.
#### Criterio de aceptación:
El administrador accede a un formulario donde pueda ingresar o actualizar los detalles de la membresía, incluyendo: Fecha de inicio y fecha de vencimiento de la membresía. Estos datos son almacenados en la plataforma.
#### Tareas
- [ ] Crear formulario para registrar membresías y fechas de inicio y vencimiento.
- [ ] Implementar la funcionalidad para ingresar y actualizar detalles de membresías.
### US4
Como administrador quiero manejar datos del Entrenador y sus horarios para poder agendar sesiones de entrenamiento y evaluaciones.
(Como administrador quiero saber que cliente está a cargo de un determinado Entrenador (máximo 4 por Entrenador)).
#### Criterio de aceptación
El administrador puede acceder al horario específico de un entrenador y agendar o borrar una sesión de entrenamiento o evaluación. La plataforma registra y guarda las modificaciones al horario del entrenador. 
#### Tareas
- [ ] Diseñar la interfaz para manejar datos de entrenadores y sus horarios.
- [ ] Implementar la funcionalidad para agendar sesiones de entrenamiento y evaluaciones.
## Tecnologias
- Backend: Nodejs Express, PostgreSQL
- Frontend: Svelte, React.
## Demo
- Demostración de inicio de sesión para diferentes roles.
- Función de añadir un nuevo cliente y gestionar sus membresías.
- Función de manejar datos del Entrenador, incluyendo los horarios.

# Modificación del sprint (22/04/2024)

## Visión del sprint 1

El sprint 1 está orientado a atacar directamente la problemática principal y abarcar las funcionalidades básicas que podrá realizar el entrenador como registrar y ver rutinas de los clientes y ver las horas agendadas de sesiones. Además el cliente puede ver sus rutinas diarias junto a su progreso en sus mediciones estereométricas.

### US1
Como Entrenador quiero registrar y ver la rutina y/o evaluación de un cliente para tener registro de lo realizado en la sesión.
- Modelar e implementar Base de Datos Relacional.
- Desarrollo de funcionalidades para registrar rutinas y evaluación

### US2
Como cliente quiero poder ver mi rutina de ejercicios diaria para recordar qué ejercicios hacer.
- Diseñar e implementar interfaz con rutinas actuales e históricas.
- Diseñar e implementar dashboard de progreso.

### US3
Como Entrenador deseo revisar las horas agendadas para organizar mi horario y las sesiones.
- Diseño e implementación de interfaz para revisar horas agendadas.
