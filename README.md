# Proyecto_IS2

# Links a repositorios de trabajo

- [GitHub - Primo18/project-IS2-frontend](https://github.com/Primo18/project-IS2-frontend)
- [GitHub - jansorena/project-IS2-backend](https://github.com/jansorena/project-IS2-backend)
- [Figma](https://www.figma.com/file/hqd7Pbv1qLVgRzGOzsYRqX/12-22-FE1-(Copy)?type=design&node-id=0%3A1&mode=design&t=IfhCDQoqRic3OwGH-1 "https://www.figma.com/file/hqd7Pbv1qLVgRzGOzsYRqX/12-22-FE1-(Copy)?type=design&node-id=0%3A1&mode=design&t=IfhCDQoqRic3OwGH-1")
- [Demo de la pagina web](https://project-is2.netlify.app/ "https://project-is2.netlify.app/")

## Anexos

- [Registro de Scrum Meetings](Scrum_Meetings.md)
- [Video Demostracion Sprint 1 G2](https://youtu.be/ngeV_ontQPQ)

# Visión del producto

Plataforma web que permite optimizar la gestión de un gimnasio, permitiendo a administradores gestionar miembros y equipamiento, a entrenadores personales crear y monitorear rutinas y evaluaciones, y a clientes visualizar sus entrenamientos personalizados. 
Esta plataforma multifuncional facilita la administración de suscripciones y pagos, el seguimiento de la disponibilidad de máquinas y la planificación de sesiones.
La plataforma está a disposición de los entrenadores y clientes en los distintos computadores distribuidos en el gimnasio.

# Product Backlog

## Historias de usuario:

### Administrador

- Como administrador quiero entrar a la plataforma mediante un login para poder gestionar usuarios, sesiones de entrenamiento y datos de las máquinas.
  
  - CA: Administrador ingresa mediante un login con sus credenciales. Tras la verificación, el administrador es redirigido a la página principal del panel de administración.

- Como administrador quiero poder registrar a los nuevos clientes (nombre, sexo, edad, diagnosticos, etc), para que los entrenadores puedan acceder a esta información y personalizar los entrenamientos.
  
  - CA: Cuando el administrador esté logueado, al ingresar un nuevo cliente podré especificar sus datos: rut, nombre, sexo, historial médico, fecha nacimiento, los cuales son almacenados en la plataforma y serán visibles por administradores y entrenadores

- Como administrador quiero actualizar o registrar una membresía posterior al pago de esta para gestionar suscripciones.
  
  - CA: El administrador accede a un formulario donde pueda ingresar o actualizar los detalles de la membresía, incluyendo: Fecha de inicio y fecha de vencimiento de la membresía. Estos datos son almacenados en la plataforma.

- Como administrador quiero manejar a los clientes inscritos para modificar posibles cambios asociados al cliente.
  
  - CA: El administrador puede acceder al cliente específico y puede modificar cualquier dato que desee o borrar al cliente. Luego la plataforma registra los cambios

- Como administrador quiero manejar datos de las máquinas y sus estados para que el Entrenador pueda crear rutinas con el uso de una máquina y clientes sepan la disponibilidad de una máquina.

- Como administrador quiero manejar datos que vinculan zonas del cuerpo trabajadas con las respectivas máquinas.
  
  - CA: El administrador puede acceder a la máquina específica y puede modificar cualquier dato que desee o borrar la máquina. Luego la plataforma registra los cambios.

- Como administrador quiero manejar datos del Entrenador y sus horarios para poder agendar sesiones de entrenamiento y evaluaciones.

- Como administrador quiero saber que cliente está a cargo de un determinado Entrenador (máximo 4 por Entrenador).
  
  - CA: El administrador puede acceder al horario específico de un entrenador y agendar o borrar una sesión de entrenamiento o evaluación. La plataforma registra y guarda las modificaciones al horario del entrenador.

### Entrenador

- Como Entrenador quiero entrar a la plataforma mediante un login para planificar los entrenamientos de los clientes.
  
  - CA: Entrenador ingresa mediante un login con sus credenciales. Tras la verificación, el entrenador es redirigido a la página principal del panel de entrenador donde puede ver su agenda y las rutinas asignadas.

- Como Entrenador quiero registrar y ver la rutina y/o evaluación de un cliente para tener registro de lo realizado en la sesión.
  
  - CA: El entrenador tiene acceso a un formulario donde puede registrar o modificar las rutinas de los clientes. Estas rutinas incluyen ejercicios, series, repeticiones y observaciones. Una vez guardadas, estas rutinas son accesibles para consulta futura tanto por el entrenador como por el cliente.

- Como Entrenador deseo revisar las horas agendadas para organizar mi horario y las sesiones.
  
  - CA: El entrenador puede acceder a un calendario interactivo que muestra todas las sesiones programadas. Puede visualizar detalles de cada sesión, incluyendo el cliente asociado, la hora y la duración de la sesión. El entrenador puede confirmar asistencia o reprogramar sesiones desde esta vista.

- Como Entrenador quiero saber el estado de las máquinas para saber qué ejercicios se pueden realizar.
  
  - CA: El entrenador tiene acceso a una sección del sistema donde puede ver el estado actualizado de cada máquina. Esta información ayuda al entrenador a planificar adecuadamente las rutinas de ejercicios que dependen del uso de máquinas específicas.

### Cliente

- Como cliente quiero poder ver mi progreso y rutina de ejercicios diaria para recordar qué ejercicios hacer.
  
  - CA: El cliente puede acceder a su perfil donde se muestra la rutina diaria asignada por su entrenador. Esta incluye detalles como los ejercicios, número de series, repeticiones y cualquier nota adicional del entrenador.

# Sprint 1

> Modificación del Sprint 1 (22/04/2024)

## Visión del sprint 1

El sprint 1 está orientado a atacar directamente la problemática principal y abarcar las funcionalidades básicas que podrá realizar el entrenador como registrar y ver rutinas de los clientes y ver las horas agendadas de sesiones. Además el cliente puede ver sus rutinas diarias junto a su progreso en sus mediciones estereométricas.

### US1

Como Entrenador quiero registrar y ver la rutina y/o evaluación de un cliente para tener registro de lo realizado en la sesión.

- Modelar e implementar Base de Datos Relacional.
- Desarrollo de funcionalidades para registrar rutinas y evaluación

### US2

Como cliente quiero poder ver mis evaluaciones y rutina de ejercicios diaria para recordar qué ejercicios hacer.

- Diseñar e implementar interfaz con rutinas actuales e históricas.
- Diseñar e implementar dashboard de progreso.

### US3

Como Entrenador deseo revisar las horas agendadas para organizar mi horario y las sesiones.

- Diseño e implementación de interfaz para revisar horas agendadas.

# Sprint 2

# Sprint 3
