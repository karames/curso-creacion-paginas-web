## Ejercicio: Página Web Básica

### Objetivo

Crear una página web básica utilizando HTML y CSS que incluya un encabezado, un párrafo, una lista y un enlace.

### Instrucciones

1. Crea un archivo `index.html`.
2. Crea un archivo `styles.css`.

### Requisitos

#### HTML (`index.html`)

1. La página debe tener una estructura básica de HTML5.
2. Debe incluir un encabezado `<h1>` con el texto "Mi Página Web".
3. Debe incluir un párrafo `<p>` con algún texto descriptivo.
4. Debe incluir una lista no ordenada `<ul>` con al menos tres elementos `<li>`.
5. Debe incluir un enlace `<a>` que redirija a otra página web (por ejemplo, `https://www.example.com`).

#### CSS (`styles.css`)

1. El encabezado `<h1>` debe tener un color de texto azul.
2. El párrafo `<p>` debe tener un tamaño de fuente de 16px y un color de texto gris.
3. Los elementos de la lista `<li>` deben tener un margen inferior de 10px.
4. El enlace `<a>` debe cambiar de color al pasar el ratón por encima (hover).

### Archivos

#### `index.html`

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Mi Página Web</h1>
    <p>
      Este es un párrafo de ejemplo para describir el contenido de mi página
      web.
    </p>
    <ul>
      <li>Elemento 1</li>
      <li>Elemento 2</li>
      <li>Elemento 3</li>
    </ul>
    <a href="https://www.example.com">Visita Example.com</a>
  </body>
</html>
```

#### `styles.css`

```css
h1 {
  color: blue;
}

p {
  font-size: 16px;
  color: gray;
}

li {
  margin-bottom: 10px;
}

a:hover {
  color: red;
}
```

### Resultado Esperado

Al abrir el archivo `index.html` en un navegador web, deberías ver un encabezado azul, un párrafo gris, una lista con elementos espaciados y un enlace que cambia de color al pasar el ratón por encima.
