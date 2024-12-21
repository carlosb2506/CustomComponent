# Componente

Este proyecto de Carlos Barroso es una app de JavaFX que cambia los colores y rota dos cuadrados al presionar un botón.

## Descripción

Al presionar el botón, se genera un número aleatorio entre 1 y 4. Dependiendo del número, los paneles cambiarán sus colores de la siguiente manera:

- 1: el panel chico se vuelve azul y el panel grande se vuelve verde.
- 2: el panel chico se vuelve amarillo y el panel grande se vuelve rojo.
- 3: el panel chico se vuelve verde y el panel grande se vuelve amarillo.
- 4: el panel chico se vuelve rojo y el panel grande se vuelve azul.

Además de cambiar los colores, se aplica una rotación a ambos paneles:

- el panel chico se rota 15 grados mientras que el panel grande se rota -45 grados.

### Manejo de Errores

El componente también incluye una función para mostrar alertas de error. La función muestra una alerta de tipo error con un mensaje personalizado y el detalle de la excepción.

private void showErrorAlert(String header, Exception e)
{
    Alert alerta = new Alert(Alert.AlertType.ERROR);
    alerta.setHeaderText(header);
    alerta.setTitle("ERROR");
    alerta.setContentText("Formato incorrecto");
    alerta.showAndWait();
}
