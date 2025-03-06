## Ejercicio: Tarjeta de Producto

### Objetivo

Crear una tarjeta de producto utilizando HTML y CSS que incluya una imagen del producto, el nombre del producto, el precio, una breve descripción y un botón de compra.

### Instrucciones

1. Crea un archivo `index.html`.
2. Crea un archivo `styles.css`.

### Requisitos

#### HTML (`index.html`)

1. La página debe tener una estructura básica de HTML5.
2. Debe incluir una tarjeta `<div>` con la clase `product-card` que contenga:
   - Una imagen `<img>` con la clase `product-img` y un `src` de tu elección (puedes usar un enlace a una imagen en línea).
   - Un título `<h2>` con la clase `product-name` que contenga el nombre del producto.
   - Un párrafo `<p>` con la clase `product-price` que contenga el precio del producto.
   - Un párrafo `<p>` con la clase `product-description` que contenga una breve descripción del producto.
   - Un botón `<button>` con la clase `product-button` que contenga el texto "Comprar".

#### CSS (`styles.css`)

1. La tarjeta `.product-card` debe tener un ancho fijo de 300px, un padding de 20px, un borde de 1px sólido gris y un borde redondeado de 10px.
2. La imagen `.product-img` debe tener un ancho del 100% y un borde redondeado en la parte superior.
3. El título `.product-name` debe tener un tamaño de fuente de 24px y un margen superior de 10px.
4. El párrafo `.product-price` debe tener un tamaño de fuente de 20px, color verde y un margen superior de 10px.
5. El párrafo `.product-description` debe tener un tamaño de fuente de 16px y un margen superior de 10px.
6. El botón `.product-button` debe tener un fondo verde, un color de texto blanco, un borde sin estilo y un padding de 10px 15px. Debe cambiar de fondo a un verde más oscuro al pasar el ratón por encima (hover).

### Archivos

#### `index.html`

```html name=index.html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tarjeta de Producto</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="product-card">
      <img
        class="product-img"
        src="https://via.placeholder.com/300x200"
        alt="Imagen del Producto"
      />
      <h2 class="product-name">Nombre del Producto</h2>
      <p class="product-price">$99.99</p>
      <p class="product-description">
        Esta es una breve descripción del producto. Aquí puedes agregar más
        detalles sobre las características del producto.
      </p>
      <button class="product-button">Comprar</button>
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

.product-card {
  width: 300px;
  padding: 20px;
  border: 1px solid gray;
  border-radius: 10px;
  background-color: white;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.product-img {
  width: 100%;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.product-name {
  font-size: 24px;
  margin-top: 10px;
}

.product-price {
  font-size: 20px;
  color: green;
  margin-top: 10px;
}

.product-description {
  font-size: 16px;
  margin-top: 10px;
}

.product-button {
  background-color: green;
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  margin-top: 10px;
  border-radius: 5px;
}

.product-button:hover {
  background-color: darkgreen;
}
```

### Resultado Esperado

Al abrir el archivo `index.html` en un navegador web, deberías ver una tarjeta de producto centrada en la página con una imagen del producto, el nombre del producto, el precio, una descripción y un botón de compra. La tarjeta debe tener bordes redondeados y un sombreado, y el botón debe cambiar de color al pasar el ratón por encima.
