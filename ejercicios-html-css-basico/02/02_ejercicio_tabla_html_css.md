## Ejercicio: Tabla de Datos

### Objetivo

Crear una tabla de datos utilizando HTML y CSS que incluya un encabezado, varias filas de datos y un estilo personalizado.

### Instrucciones

1. Crea un archivo `index.html`.
2. Crea un archivo `styles.css`.

### Requisitos

#### HTML (`index.html`)

1. La página debe tener una estructura básica de HTML5.
2. Debe incluir un encabezado `<h1>` con el texto "Tabla de Datos".
3. Debe incluir una tabla `<table>` con los siguientes elementos:
   - Un encabezado de tabla `<thead>` con una fila `<tr>` que contenga tres encabezados de columna `<th>`: "Nombre", "Edad" y "Ciudad".
   - Un cuerpo de tabla `<tbody>` con al menos tres filas `<tr>`, cada una con tres celdas de datos `<td>`.

#### CSS (`styles.css`)

1. La tabla debe tener un ancho del 100%, un borde colapsado y un margen superior de 20px.
2. Las celdas de la tabla (`<th>`, `<td>`) deben tener un borde de 1px sólido negro y un relleno de 8px.
3. Las filas de la tabla deben alternar colores de fondo (por ejemplo, blanco y gris claro).
4. El encabezado de la tabla (`<th>`) debe tener un fondo azul y un color de texto blanco.

### Archivos

#### `index.html`

```html name=index.html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tabla de Datos</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Tabla de Datos</h1>
    <table>
      <thead>
        <tr>
          <th>Nombre</th>
          <th>Edad</th>
          <th>Ciudad</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Ana</td>
          <td>25</td>
          <td>Madrid</td>
        </tr>
        <tr>
          <td>Juan</td>
          <td>30</td>
          <td>Barcelona</td>
        </tr>
        <tr>
          <td>María</td>
          <td>28</td>
          <td>Valencia</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

#### `styles.css`

```css name=styles.css
h1 {
  text-align: center;
  color: #333;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

th,
td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}

th {
  background-color: blue;
  color: white;
}

tbody tr:nth-child(odd) {
  background-color: #f2f2f2;
}
```

### Resultado Esperado

Al abrir el archivo `index.html` en un navegador web, deberías ver una tabla con tres columnas ("Nombre", "Edad", "Ciudad") y al menos tres filas de datos. La tabla debe tener bordes colapsados, las celdas deben tener relleno, y las filas deben alternar colores de fondo. El encabezado de la tabla debe tener un fondo azul y texto blanco.
