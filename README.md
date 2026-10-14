# Programación Concurrente - Grupo 7

## Actividad de la sesión 25

En esta actividad investigamos tres aplicaciones que utilizan tareas concurrentes y elaboramos un boceto de un monitor de tareas.

El objetivo es comprender cómo funcionan los procesos en segundo plano y cómo permiten que una aplicación realice diferentes operaciones sin interrumpir su funcionamiento.

## Aplicaciones investigadas

### 1. Spotify

Spotify permite reproducir música mientras descarga canciones o listas de reproducción en segundo plano, sin interrumpir la reproducción.

[Ver investigación de Spotify](spotify.md)

### 2. Google Chrome

Google Chrome permite descargar archivos mientras el usuario continúa navegando por diferentes páginas web.

[Ver investigación de Chrome](chrome)

### 3. WhatsApp

WhatsApp permite recibir mensajes, descargar imágenes y enviar archivos mientras el usuario continúa utilizando otras conversaciones.

[Ver investigación de WhatsApp](whatsapp)

## Monitor de tareas

Diseñamos un boceto de una interfaz que permite visualizar y administrar tareas concurrentes.

La interfaz cuenta con las siguientes funciones:

- **Iniciar:** comienza la ejecución de una tarea.
- **Estado:** permite consultar si una tarea está pendiente, en ejecución, completada o detenida.
- **Detener:** permite solicitar la cancelación de una tarea.
- **Barra de progreso:** muestra el avance de la operación.
- **Registro de eventos:** muestra las actividades realizadas durante la ejecución.

[Ver monitor de tareas](monitor/)

## Conclusión

Las tareas concurrentes permiten que una aplicación realice diferentes operaciones durante un mismo período de tiempo. Esto es importante porque evita que el usuario tenga que esperar a que termine una operación para continuar utilizando otras funciones.

Con esta investigación comprendimos cómo aplicaciones que usamos diariamente aprovechan la concurrencia y cómo se podría administrar mediante una interfaz gráfica.

## Integrantes

- Adolfo Carlos Ramirez Arauz: Investigación de Spotify.
- Carlos Fernando Torres Gonzales: Investigación de Google Chrome.
- Andy Steven Diaz Montenegro: Investigación de WhatsApp.
- Alexa Sofia Loaisiga Torrez: Diseño y explicación del monitor de tareas.
