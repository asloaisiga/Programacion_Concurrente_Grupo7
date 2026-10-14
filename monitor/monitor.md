# Monitor de tareas - Boceto

## ¿Qué es el monitor de tareas?

Es una propuesta de interfaz gráfica que permite visualizar y controlar diferentes tareas que se ejecutan en segundo plano.

El objetivo es mostrar cómo una aplicación puede administrar varias operaciones concurrentes sin bloquear su interfaz.

## Diseño de la interfaz

El boceto contiene una tabla que muestra las aplicaciones, sus operaciones y el estado de cada tarea.

También incluye una sección de detalles, una barra de progreso y tres botones principales.

![Boceto del monitor de tareas](boceto-monitor.png)

## Funciones de los botones

### Iniciar

Permite comenzar la ejecución de una tarea seleccionada.

### Estado

Permite consultar el estado actual de una tarea, por ejemplo:

- Pendiente.
- En ejecución.
- Completada.
- Detenida.

### Detener

Permite solicitar la cancelación de una tarea que se encuentra en ejecución.

## Barra de progreso

Muestra el porcentaje de avance de una operación. Por ejemplo, cuando se descarga un archivo, permite observar cuánto falta para finalizar.

## Registro de eventos

Muestra información sobre las operaciones realizadas, como el inicio de una tarea, su progreso y su finalización.

## Ejemplo de funcionamiento

El usuario selecciona una tarea de descarga y presiona Iniciar. La aplicación comienza la operación en segundo plano mientras la interfaz continúa disponible.

Durante la ejecución, el usuario puede consultar el estado o solicitar que la tarea se detenga.

## Conclusión

Este boceto representa una forma sencilla de administrar tareas concurrentes mediante una interfaz gráfica que permite iniciar, consultar y detener operaciones.
