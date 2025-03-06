## Ejercicio: Formulario de Contacto

### Objetivo

Crear un formulario de contacto utilizando HTML y CSS que incluya campos para el nombre, correo electrónico, mensaje y un botón de envío.

### Instrucciones

1. Crea un archivo `index.html`.
2. Crea un archivo `styles.css`.

### Requisitos

#### HTML (`index.html`)

1. La página debe tener una estructura básica de HTML5.
2. Debe incluir un encabezado `<h1>` con el texto "Formulario de Contacto".
3. Debe incluir un formulario `<form>` con los siguientes campos:
   - Un campo de texto `<input>` para el nombre con un `placeholder` que diga "Nombre".
   - Un campo de correo electrónico `<input>` para el correo con un `placeholder` que diga "Correo Electrónico".
   - Un área de texto `<textarea>` para el mensaje con un `placeholder` que diga "Mensaje".
   - Un botón de envío `<button>` con el texto "Enviar".

#### CSS (`styles.css`)

1. El encabezado `<h1>` debe tener un color de texto verde.
2. Los campos del formulario (`<input>`, `<textarea>`) deben tener un ancho del 100%, un margen inferior de 10px y un borde de 1px sólido gris.
3. El botón de envío `<button>` debe tener un fondo azul, un color de texto blanco y un efecto de hover que cambie el fondo a un azul más oscuro.

### Archivos

#### `index.html`

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulario de Contacto</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Formulario de Contacto</h1>
    <form>
      <input type="text" placeholder="Nombre" required />
      <input type="email" placeholder="Correo Electrónico" required />
      <textarea placeholder="Mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </body>
</html>
```

#### `styles.css`

```css
h1 {
  color: green;
}

form {
  width: 300px;
  margin: 0 auto;
}

input,
textarea {
  width: 100%;
  margin-bottom: 10px;
  border: 1px solid gray;
  padding: 8px;
  box-sizing: border-box;
}

button {
  background-color: blue;
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
}

button:hover {
  background-color: darkblue;
}
```

### Resultado Esperado

Al abrir el archivo `index.html` en un navegador web, deberías ver un formulario de contacto con un campo de nombre, un campo de correo electrónico, un área de texto para el mensaje y un botón de envío. El encabezado debe ser verde, los campos de formulario deben tener un borde gris y el botón de envío debe ser azul con un efecto de hover que lo oscurezca.
