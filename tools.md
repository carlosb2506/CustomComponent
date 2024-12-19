# SampleController

Es un controlador encargado de controlar el comportamiento de la interfaz de usuario.

## Propiedades

- 'paneColor': Un contenedor Pane que se cambia su color de fondo y se rota.
- 'btnCambiaColor': Un boton que, al ser presionado, cambia los colores y rota los  dos Pane.
- 'paneGrande': Un contenedor Pane que tambien cambia su color de fondo y se rota.

### btnCambiaColor()

Este método se llama cuando se presiona el botón 'btnCambiaColor'. Genera un número aleatorio entre 1 y 4, ambos incluidos, y cambia los colores de los dos Pane basándose en este número y también rota los Pane.