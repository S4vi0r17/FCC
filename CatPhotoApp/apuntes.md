# Descripción del código HTML

## <!DOCTYPE html>
- Esta declaración define el tipo de documento y la versión de HTML que se está utilizando. En este caso, se indica que es un documento HTML5.

## <html lang="en">
- Esta etiqueta envuelve todo el contenido de la página y define que el idioma utilizado es el inglés ("en").

## <head>
- Esta sección contiene metadatos y enlaces a recursos externos que no se muestran en la página web pero son importantes para su funcionamiento y SEO.

## <meta charset="UTF-8">
- Este elemento establece la codificación de caracteres utilizada en el documento como UTF-8, que incluye una amplia gama de caracteres para admitir diferentes idiomas.

## <title>CatPhotoApp</title>
- Define el título de la página que se muestra en la pestaña o barra de título del navegador.

## <body>
- El contenido visible de la página se coloca dentro de esta etiqueta. Aquí es donde se encuentra toda la información y elementos que se muestran en la página web.

## <main>
- Es una etiqueta de HTML5 que indica el contenido principal de la página.

## <h1>CatPhotoApp</h1>
- Es un encabezado de nivel 1 que muestra el título principal de la página, que en este caso es "CatPhotoApp".

## <section>
- Esta etiqueta define una sección en la página web que agrupa contenido relacionado.

## <h2>Cat Photos</h2>
- Es un encabezado de nivel 2 que indica el título de la sección de fotos de gatos.

## <!-- TODO: Add link to cat photos -->
- Es un comentario en HTML que no se muestra en la página. Sirve como recordatorio o nota para el desarrollador para agregar un enlace a las fotos de gatos.

## <p>See more [cat photos](https://freecatphotoapp.com) in our gallery.</p>
- Es un párrafo de texto que contiene un enlace que redirige al usuario a "https://freecatphotoapp.com". El atributo `target="_blank"` hace que el enlace se abra en una nueva pestaña.

## <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
- Es un enlace que contiene una imagen. Cuando el usuario hace clic en la imagen, se redirige al sitio "https://freecatphotoapp.com". La imagen se muestra si el enlace no es accesible o si el usuario no puede ver imágenes.

## <h2>Cat Lists</h2>
- Es un encabezado de nivel 2 que indica el título de la sección de listas de gatos.

## <h3>Things cats love:</h3>
- Es un encabezado de nivel 3 que indica una lista de cosas que a los gatos les gusta.

## <ul>
- Es una lista no ordenada que contiene elementos que enumeran cosas que a los gatos les gusta.

## <li>cat nip</li>
- Es un elemento de lista que muestra "cat nip".

## <li>laser pointers</li>
- Es un elemento de lista que muestra "laser pointers".

## <li>lasagna</li>
- Es un elemento de lista que muestra "lasagna".

## <figure>
- Es un elemento de HTML5 que representa contenido independiente, como imágenes, diagramas, gráficos, etc.

## <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
- Es una etiqueta de imagen que muestra una imagen de lasaña. El atributo `src` especifica la URL de la imagen, y el atributo `alt` proporciona una descripción alternativa para la imagen, que se muestra si la imagen no se carga o si el usuario no puede verla.

## <figcaption>Cats *love* lasagna.</figcaption>
- Es una leyenda para la imagen que resalta el hecho de que a los gatos les encanta la lasaña. La etiqueta `<em>` se utiliza para enfatizar la palabra "love".

## <h3>Top 3 things cats hate:</h3>
- Es un encabezado de nivel 3 que indica una lista de las tres principales cosas que a los gatos les disgustan.

## <ol>
- Es una lista ordenada que contiene elementos que enumeran cosas que a los gatos no les gusta.

## <li>flea treatment</li>
- Es un elemento de lista que muestra "flea treatment".

## <li>thunder</li>
- Es un elemento de lista que muestra "thunder".

## <li>other cats</li>
- Es un elemento de lista que muestra "other cats".

## <figure>
- Es un elemento de HTML5 que representa contenido independiente, como imágenes, diagramas, gráficos, etc.

## <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
- Es una etiqueta de imagen que muestra una imagen de cinco gatos mirando alrededor de un campo. El atributo `src` especifica la URL de la imagen, y el atributo `alt` proporciona una descripción alternativa para la imagen, que se muestra si la imagen no se carga o si el usuario no puede verla.

## <figcaption>Cats **hate** other cats.</figcaption>
- Es una leyenda para la imagen que resalta el hecho de que a los gatos les disgustan otros gatos. La etiqueta `<strong>` se utiliza para enfatizar la palabra "hate".

## <h2>Cat Form</h2>
- Es un encabezado de nivel 2 que indica el título de la sección de formulario de gatos.

## <form action="https://freecatphotoapp.com/submit-cat-photo">
- Es un formulario que envía los datos ingresados por el usuario al sitio web "https://freecatphotoapp.com/submit-cat-photo" cuando se envía.

## <fieldset>
- Es un elemento que agrupa elementos relacionados en un formulario.

## <legend>Is your cat an indoor or outdoor cat?</legend>
- Es una leyenda que proporciona una descripción para el grupo de elementos de radio que sigue. En este caso, pregunta si el gato es un gato de interior o exterior.

## <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
- Es un elemento de radio que permite al usuario seleccionar si el gato es un gato de interior. La etiqueta `<label>` proporciona un texto descriptivo para el elemento de radio. El atributo `checked` indica que este es el valor predeterminado seleccionado.

## <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
- Es un elemento de radio que permite al usuario seleccionar si el gato es un gato de exterior.

## <fieldset>
- Es un elemento que agrupa elementos relacionados en un formulario.

## <legend>What's your cat's personality?</legend>
- Es una leyenda que proporciona una descripción para el grupo de elementos de casilla de verificación que sigue. En este caso, pregunta sobre la personalidad del gato.

## <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
- Es un elemento de casilla de verificación que permite al usuario seleccionar la personalidad "Loving" de su gato. La etiqueta `<label>` proporciona un texto descriptivo para la casilla de verificación. El atributo `checked` indica que esta casilla de verificación está seleccionada por defecto.

## <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
- Es un elemento de casilla de verificación que permite al usuario seleccionar la personalidad "Lazy" de su gato.

## <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
- Es un elemento de casilla de verificación que permite al usuario seleccionar la personalidad "Energetic" de su gato.

## <input type="text" name="catphotourl" placeholder="cat photo URL" required>
- Es un campo de entrada de texto donde los usuarios pueden ingresar la URL de una foto de su gato. El atributo `placeholder` proporciona un texto de ejemplo para guiar al usuario, y el atributo `required` indica que este campo es obligatorio y debe completarse antes de enviar el formulario.

## <button type="submit">Submit</button>
- Es un botón que, cuando se hace clic, envía el formulario al sitio web "https://freecatphotoapp.com/submit-cat-photo".

## <footer>
- Es una etiqueta que define el pie de página de la página web.

## <p>No Copyright - [freeCodeCamp.org](https://www.freecodecamp.org)</p>
- Es un párrafo que contiene un enlace que redirige al usuario al sitio web "https://www.freecodecamp.org". El pie de página muestra el mensaje "No Copyright" y el enlace a freeCodeCamp.org.
