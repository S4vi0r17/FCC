# Descripción del código HTML

## `<!DOCTYPE html>`
- Esta declaración define el tipo de documento y la versión de HTML que se está utilizando. En este caso, se indica que es un documento HTML5.

## `<html lang="en">`
- Esta etiqueta envuelve todo el contenido de la página y define que el idioma utilizado es el inglés ("en").

## `<head>`
- Esta sección contiene metadatos y enlaces a recursos externos que no se muestran en la página web pero son importantes para su funcionamiento y SEO.

## `<meta charset="utf-8" />`
- Este elemento establece la codificación de caracteres utilizada en el documento como UTF-8, que incluye una amplia gama de caracteres para admitir diferentes idiomas.

## `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`
- Esta etiqueta establece la configuración de visualización del sitio en dispositivos móviles. El atributo `content="width=device-width, initial-scale=1.0"` indica que el ancho de la página debe ajustarse al ancho del dispositivo y que la escala inicial debe ser de 1.0.

## `<title>Cafe Menu</title>`
- Define el título de la página que se muestra en la pestaña o barra de título del navegador.

## `<link href="styles.css" rel="stylesheet" />`
- Es un enlace que conecta el archivo CSS "styles.css" con el documento HTML para aplicar estilos al contenido de la página.

## `<body>`
- El contenido visible de la página se coloca dentro de esta etiqueta. Aquí es donde se encuentra toda la información y elementos que se muestran en la página web.

## `<div class="menu">`
- Es un contenedor (`<div>`) con la clase "menu" que envuelve el contenido del menú del café.

## `<main>`
- Es una etiqueta de HTML5 que indica el contenido principal de la página.

## `<h1>CAMPER CAFE</h1>`
- Es un encabezado de nivel 1 que muestra el título principal del café, que es "CAMPER CAFE".

## `<p class="established">Est. 2020</p>`
- Es un párrafo de texto con la clase "established" que muestra la fecha de establecimiento del café, que es "Est. 2020".

## `<hr>`
- Es una etiqueta que representa una línea horizontal.

## `<section>`
- Esta etiqueta define una sección en la página web que agrupa contenido relacionado.

## `<h2>Coffee</h2>`
- Es un encabezado de nivel 2 que indica el título de la sección de opciones de café.

## `<img src="https://cdn.freecodecamp.org/curriculum/css-cafe/coffee.jpg" alt="coffee icon" />`
- Es una etiqueta de imagen (`<img>`) que muestra un ícono de café. El atributo `src` especifica la URL de la imagen, y el atributo `alt` proporciona una descripción alternativa para la imagen, que se muestra si la imagen no se carga o si el usuario no puede verla.

## `<article class="item">`
- Es un contenedor (`<article>`) con la clase "item" que envuelve un artículo de café con su sabor y precio.

## `<p class="flavor">French Vanilla</p><p class="price">3.00</p>`
- Son dos párrafos de texto, cada uno con su clase correspondiente ("flavor" y "price"), que muestra el sabor y el precio del café "French Vanilla".

## `<article class="item">`
- Es un contenedor (`<article>`) con la clase "item" que envuelve un artículo de café con su sabor y precio.

## `<p class="flavor">French Vanilla</p><p class="price">3.00</p>`
- Son dos párrafos de texto, cada uno con su clase correspondiente ("flavor" y "price"), que muestra el sabor y el precio del café "French Vanilla".

## `<hr class="bottom-line">`
- Es una etiqueta de línea horizontal con la clase "bottom-line" que se utiliza para agregar un separador adicional en la página.

## `<footer>`
- Es una etiqueta que define el pie de página de la página web.

## `<p><a href="https://www.freecodecamp.org" target="_blank">Visit our website</a></p>`
- Es un párrafo de texto que contiene un enlace (`<a>`) que redirige al usuario al sitio web "https://www.freecodecamp.org". El atributo `target="_blank"` hace que el enlace se abra en una nueva pestaña.

## `<p class="address">123 Free Code Camp Drive</p>`
- Es un párrafo de texto con la clase "address" que muestra la dirección del café, que es "123 Free Code Camp Drive".

## </div>
- Cierra el contenedor `<div>` con la clase "menu".

</body>
</html>

# Descripción del código CSS

## `body { ... }`
- Define estilos aplicados al cuerpo (body) de la página. Establece un fondo de imagen, el tipo de fuente, y un relleno de 20px.

## `h1 { ... }`
- Establece estilos para los encabezados de nivel 1 (h1), como el tamaño de fuente, margen superior e inferior, y el tipo de fuente.

## `h2 { ... }`
- Establece estilos para los encabezados de nivel 2 (h2), como el tamaño de fuente.

## `.established { ... }`
- Establece estilos para la clase "established", como la fuente en cursiva.

## `h1, h2, p { ... }`
- Establece estilos generales para los encabezados y párrafos, alineándolos al centro.

## `.menu { ... }`
- Define estilos para el contenedor con la clase "menu", como el ancho, el color de fondo, el margen y el relleno.

## `img { ... }`
- Establece estilos para las imágenes, como mostrarlas centradas y ajustar el margen superior.

## `hr { ... }`
- Define estilos para las líneas horizontales, como el color de fondo y el color del borde.

## `.bottom-line { ... }`
- Establece estilos para la clase "bottom-line", definiendo el margen superior.

## `.item p { ... }`
- Establece estilos para los párrafos dentro de elementos con la clase "item", incluyendo el margen superior e inferior y el tamaño de fuente.

## `.flavor, .dessert { ... }`
- Define estilos para las clases "flavor" y "dessert", estableciendo el alineamiento de texto y el ancho del elemento.

## `.price { ... }`
- Establece estilos para la clase "price", alineando el texto a la derecha y definiendo el ancho del elemento.

## `footer { ... }`
- Define estilos para el pie de página, estableciendo el tamaño de fuente.

## `.address { ... }`
- Establece estilos para la clase "address", definiendo el margen inferior.

## `a { ... }`
- Establece estilos para los enlaces, definiendo el color del texto.

## `a:visited { ... }`
- Establece estilos para los enlaces visitados, definiendo el color del texto.

## `a:hover { ... }`
- Define estilos para los enlaces al pasar el cursor sobre ellos, cambiando el color del texto.

## `a:active { ... }`
- Define estilos para los enlaces al hacer clic en ellos, cambiando el color del texto.