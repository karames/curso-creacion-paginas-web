## Ejercicio: Tarjeta de Información

### Objetivo

Crear una tarjeta de información utilizando HTML y CSS que incluya una imagen, un título, un párrafo descriptivo y un botón.

### Instrucciones

1. Crea un archivo `index.html`.
2. Crea un archivo `styles.css`.

### Requisitos

#### HTML (`index.html`)

1. La página debe tener una estructura básica de HTML5.
2. Debe incluir una tarjeta `<div>` con la clase `card` que contenga:
   - Una imagen `<img>` con la clase `card-img` y un `src` de tu elección (puedes usar un enlace a una imagen en línea).
   - Un título `<h2>` con la clase `card-title` que contenga el texto "Título de la Tarjeta".
   - Un párrafo `<p>` con la clase `card-description` que contenga una breve descripción.
   - Un botón `<button>` con la clase `card-button` que contenga el texto "Leer Más".

#### CSS (`styles.css`)

1. La tarjeta `.card` debe tener un ancho fijo de 300px, un padding de 20px, un borde de 1px sólido gris y un borde redondeado de 10px.
2. La imagen `.card-img` debe tener un ancho del 100% y un borde redondeado en la parte superior.
3. El título `.card-title` debe tener un tamaño de fuente de 24px y un margen superior de 10px.
4. El párrafo `.card-description` debe tener un tamaño de fuente de 16px y un margen superior de 10px.
5. El botón `.card-button` debe tener un fondo azul, un color de texto blanco, un borde sin estilo y un padding de 10px 15px. Debe cambiar de fondo a un azul más oscuro al pasar el ratón por encima (hover).

### Archivos

#### `index.html`

```html name=index.html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tarjeta de Información</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="card">
      <img
        class="card-img"
        src="https://via.placeholder.com/300x200"
        alt="Imagen de Tarjeta"
      />
      <h2 class="card-title">Título de la Tarjeta</h2>
      <p class="card-description">
        Esta es una breve descripción de la tarjeta. Aquí puedes agregar más
        detalles sobre el contenido de la tarjeta.
      </p>
      <button class="card-button">Leer Más</button>
    </div>
  </body>
</html>
```

#### `styles.css`

```css name=styles.css
body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background-color: #f4f4f4;
}

.card {
  width: 300px;
  padding: 20px;
  border: 1px solid gray;
  border-radius: 10px;
  background-color: white;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.card-img {
  width: 100%;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.card-title {
  font-size: 24px;
  margin-top: 10px;
}

.card-description {
  font-size: 16px;
  margin-top: 10px;
}

.card-button {
  background-color: blue;
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  margin-top: 10px;
  border-radius: 5px;
}

.card-button:hover {
  background-color: darkblue;
}
```

### Resultado Esperado

Al abrir el archivo `index.html` en un navegador web, deberías ver una tarjeta de información centrada en la página con una imagen, un título, una descripción y un botón. La tarjeta debe tener bordes redondeados y un sombreado, y el botón debe cambiar de color al pasar el ratón por encima.
