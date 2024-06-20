# Proyecto_IS2

# Links a repositorios de trabajo

- [GitHub - Primo18/project-IS2-frontend](https://github.com/Primo18/project-IS2-frontend)
- [GitHub - jansorena/project-IS2-backend](https://github.com/jansorena/project-IS2-backend)
- [Figma](https://www.figma.com/file/hqd7Pbv1qLVgRzGOzsYRqX/12-22-FE1-(Copy)?type=design&node-id=0%3A1&mode=design&t=IfhCDQoqRic3OwGH-1 "https://www.figma.com/file/hqd7Pbv1qLVgRzGOzsYRqX/12-22-FE1-(Copy)?type=design&node-id=0%3A1&mode=design&t=IfhCDQoqRic3OwGH-1")
- [Demo de la pagina web](https://project-is2.netlify.app/ "https://project-is2.netlify.app/")

`user: admin@email.com password:admin`

## Anexos

- [Registro de Scrum Meetings - Sprint1](Scrum_Meetings_Sprint1.md)
- [Registro de Scrum Meetings - Sprint2](Scrum_Meetings_Sprint2.md)
- [Registro de Scrum Meetings - Sprint3](Scrum_Meetings_Sprint3.md)
- [Video Demostracion Sprint 1 G2](https://youtu.be/ngeV_ontQPQ)

# Visión del producto

Plataforma web que permite optimizar la gestión de un gimnasio, permitiendo a administradores gestionar miembros y equipamiento, a entrenadores personales crear y monitorear rutinas y evaluaciones, y a clientes visualizar sus entrenamientos personalizados. 
Esta plataforma multifuncional facilita la administración de suscripciones y pagos, el seguimiento de la disponibilidad de máquinas y la planificación de sesiones.
La plataforma está a disposición de los entrenadores y clientes en los distintos computadores distribuidos en el gimnasio.

# Product Backlog

> Actualizado 27/05/2024

- [x] US1: Como Entrenador quiero registrar y ver la rutina y/o evaluación de un cliente para tener registro de lo realizado en la sesión.
  
  :checkered_flag: Criterio de aceptación: El entrenador tiene acceso a un formulario donde puede registrar o modificar las rutinas de los clientes. Estas rutinas incluyen ejercicios, series, repeticiones y observaciones. Una vez guardadas, estas rutinas son accesibles para consulta futura tanto por el entrenador como por el cliente.
  
  :heavy_exclamation_mark: Tareas:
  
  - [x] Modelar e implementar Base de Datos Relacional.
  
  - [x] Desarrollo de funcionalidades para registrar rutinas y evaluación.
  
  - [x] Adaptar la base de datos e interfaz para permitir el registro de rutinas que consideren tiempo y soporte circuitos.
  
  - [x] Realizar la conexión entre la interfaz y la base de datos. 

- [x] ~~US2: Como cliente quiero poder ver mi rutina de ejercicios diaria para recordar qué ejercicios hacer.~~
  
  ~~:checkered_flag: Criterio de aceptación:El cliente puede acceder a su perfil donde se muestra la rutina diaria asignada por su entrenador. Esta incluye detalles como los ejercicios, número de series, repeticiones y cualquier nota adicional del entrenador.~~
  
  ~~:heavy_exclamation_mark: Tareas:~~
  
  - [x] ~~Diseñar e implementar interfaz con rutinas actuales e históricas.~~
  
  - [x] ~~Diseñar e implementar dashboard de progreso.~~

- [x] ~~US3: Como Entrenador deseo revisar las horas agendadas para organizar mi horario y las sesiones.~~
  
  ~~:checkered_flag: Criterio de aceptación:El entrenador puede acceder a un calendario interactivo que muestra todas las sesiones programadas. Puede visualizar detalles de cada sesión, incluyendo el cliente asociado, la hora y la duración de la sesión. El entrenador puede confirmar asistencia o reprogramar sesiones desde esta vista.~~
  
  ~~:heavy_exclamation_mark: Tareas:~~
  
  - [x] ~~Diseño e implementación de interfaz para revisar horas agendadas.~~

- [x] US4: Como administrador quiero poder gestionar los datos de los clientes (registro y modificación), para que los entrenadores puedan acceder a esta información y personalizar los entrenamientos.
  
  :checkered_flag: Criterio de aceptación: Como administrador autenticado, puedo acceder a la sección de registro de clientes para ingresar sus datos y registrarlos en la base de datos, recibiendo una confirmación exitosa. También puedo acceder a la lista de clientes, seleccionar uno existente, modificar sus datos y recibir una confirmación de actualización exitosa. Además, puedo ver y actualizar los datos de clientes en la interfaz, con los cambios reflejándose instantáneamente. La interfaz de gestión de clientes me permite ver una lista de todos los clientes registrados, realizar búsquedas y filtrados, y acceder a las opciones de registro y modificación. Los administradores y entrenadores pueden acceder al sistema de gestión de clientes mediante un sistema de login con credenciales correctas, recibiendo un mensaje de error si son incorrectas. Como entrenador autenticado, puedo ver y gestionar las rutinas de entrenamiento personalizadas vinculadas a cada cliente.
  
  :heavy_exclamation_mark: Tareas:
  
  - [x] Implementar funcionalidades para el registro, modificación y actualización de datos de los clientes.
  
  - [x] Crear una interfaz conectada a la base de datos para la gestión de clientes. 
  
  - [x] Vincular y visualizar usuarios con sus rutinas. 

- [x] US5: Como usuario de la plataforma (administrador, entrenador, cliente) quiero que entrar a la plataforma y que la plataforma sea usable para facilitar la interacción y entrada de datos.
  
  :checkered_flag: Criterio de aceptación: La plataforma debe ofrecer una interfaz intuitiva que permita a los usuarios nuevos realizar tareas básicas sin ayuda externa. Las páginas deben tener una carga rápida, cargando en menos de 2 segundos, y proporcionar feedback claro con mensajes explícitos y útiles para acciones exitosas y errores. Todas las funcionalidades deben ser compatibles con dispositivos móviles y la página debe ser responsiva. Además, los elementos de la interfaz deben mantener una consistencia de diseño, con un estilo y comportamiento coherentes en toda la plataforma. Los formularios deben incluir una validación de datos adecuada para asegurar que los datos sean correctos antes de enviarlos
  
  :heavy_exclamation_mark: Tareas:
  
  - [x] Realizar diseño figma para la planificación previa de la interfaz general.
  
  - [x] Mejorar el diseño general para hacerlo más ameno al usuario.
  
  - [x] Implementar un sistema de login para los distintos usuarios.

---

Pendientes de actualización y revisión con el cliente

- [ ] US6: Como administrador quiero manejar datos de las máquinas y sus estados para que el Entrenador pueda crear rutinas con el uso de una máquina y clientes sepan la disponibilidad de una máquina.
  
  :checkered_flag: Criterio de aceptación:
  
  :heavy_exclamation_mark: Tareas:
  
  - [ ] Actualizar la vista de detalles de rutina para incluir información de las máquinas utilizadas.
  
  - [ ] Actualizar la base de datos para incluir información sobre máquinas.
  
  - [ ] Vincular el frontend con la base de datos para mostrar las maquinas junto a las rutinas.

- [ ] US7: Como administrador quiero actualizar o registrar una membresía posterior al pago de esta para gestionar suscripciones.
  
  :checkered_flag: Criterio de aceptación:
  
  :heavy_exclamation_mark: Tareas:

- [ ] US8: Como administrador quiero manejar datos que vinculan zonas del cuerpo trabajadas con las respectivas máquinas.
  
  :checkered_flag: Criterio de aceptación:
  
  :heavy_exclamation_mark: Tareas:

- [ ] US9: Como administrador quiero manejar datos del Entrenador y sus horarios para poder agendar sesiones de entrenamiento y evaluaciones.
  
  :checkered_flag: Criterio de aceptación:
  
  :heavy_exclamation_mark: Tareas:

- [ ] US10: Como Entrenador quiero saber el estado de las máquinas para saber qué ejercicios se pueden realizar.
  
  :checkered_flag: Criterio de aceptación:
  
  :heavy_exclamation_mark: Tareas:

# Sprint 1

> Modificación del Sprint 1 (22/04/2024)

## Visión del sprint 1

El sprint 1 está orientado a atacar directamente la problemática principal y abarcar las funcionalidades básicas que podrá realizar el entrenador como registrar y ver rutinas de los clientes y ver las horas agendadas de sesiones. Además el cliente puede ver sus rutinas diarias junto a su progreso en sus mediciones estereométricas.

### US1

Como Entrenador quiero registrar y ver la rutina y/o evaluación de un cliente para tener registro de lo realizado en la sesión.

- Modelar e implementar Base de Datos Relacional.
- Desarrollo de funcionalidades para registrar rutinas y evaluación

### US2

~~Como cliente quiero poder ver mis evaluaciones y rutina de ejercicios diaria para recordar qué ejercicios hacer.~~

- ~~Diseñar e implementar interfaz con rutinas actuales e históricas.~~
- ~~Diseñar e implementar dashboard de progreso.~~

### US3

Como Entrenador deseo revisar las horas agendadas para organizar mi horario y las sesiones.

- Diseño e implementación de interfaz para revisar horas agendadas.

# Sprint 2

## Visión del sprint 2

Inicialmente se mejorará el diseño de la interfaz de la plataforma web modificándose en conjunto con la base de datos para permitir el registro de rutinas con circuitos. Se terminará de abarcar la problemática principal, dejando funcional la interfaz de entrenadores, permitiéndoles añadir rutinas y evaluaciones que son registradas en la base de datos del gimnasio. Se pondrá en marcha la interfaz de administración, permitiendo el login de los administradores y la gestión de usuarios por parte de estos.

### US1

Como entrenador quiero registrar y ver la rutina y/o evaluación de un cliente considerando ejercicios en base a tiempos y circuitos para tener un registro más completo de lo realizado en la sesión.

Tareas:

- Adaptar la base de datos e interfaz para permitir el registro de rutinas que consideren tiempo y soporte circuitos.
- Realizar la conexión entre la interfaz y la base de datos.

### US4

Como administrador quiero poder gestionar los datos de los clientes  (registro, modificación y actualización), para que los entrenadores puedan acceder a esta información y personalizar los entrenamientos.

Tareas:

- Implementar funcionalidades para el registro, modificación y actualización de datos de los clientes.
- Crear una interfaz conectada a la base de datos para la gestión de clientes.
- Implementar un sistema de Login para administradores.
- Vincular y visualizar usuarios con sus rutinas.

### US5

Como usuario de la plataforma (administrador, entrenador, cliente) quiero que la usabilidad de la plataforma sea mejorada para facilitar la interacción y entrada de datos

Tareas:

- Realizar diseño figma para la planificación previa de la interfaz general.
- Mejorar el diseño general para hacerlo más ameno al usuario.

# Sprint 3
