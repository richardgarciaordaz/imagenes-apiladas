# imagenes-apiladas
Galería de Imágenes Responsive con HTML y CSS

Descripción
Este proyecto es una galería interactiva de imágenes diseñada para principiantes en desarrollo front-end. Aquí aprenderás a utilizar HTML y CSS para crear una estructura simple y atractiva, mientras entiendes conceptos esenciales como Flexbox, transiciones CSS y diseños responsive.

Paso 1: La estructura HTML
¿Qué es HTML?
HTML es el lenguaje de marcado que usamos para estructurar el contenido de una página web. En este proyecto, lo usamos para crear los contenedores de nuestra galería.

![image](https://github.com/user-attachments/assets/9810ab46-de02-41c6-8e83-37d09958ea02)

Explicación del código:
Etiqueta <head>: Aquí configuramos los metadatos, el título de la página y enlazamos nuestro archivo CSS (style.css).
Contenedor principal: La clase imagenes-container envuelve todas las imágenes, organizándolas como un grupo.
Elemento de imagen: Cada imagen está dentro de un <div class="imagen"> que contiene:
La etiqueta <img> para la imagen.
Un <span class="nombre"> que sirve para mostrar un texto flotante al pasar el cursor.


Paso 2: El diseño CSS
¿Qué es CSS?
CSS se utiliza para diseñar el contenido creado con HTML. Aquí añadiremos estilos, transiciones y crearemos una interfaz responsive.

![image](https://github.com/user-attachments/assets/53f26dec-69b5-4083-90b9-3ae01cc196e6)

Explicación de los estilos iniciales:
Fondo de la página (body):
Color de fondo: aquamarine para un diseño limpio y fresco.
Fuente: Usamos una tipografía sans-serif para mantenerlo minimalista.
Contenedor de imágenes (.imagenes-container):
Usamos display: flex para alinear las imágenes en una fila.
Centramos vertical y horizontalmente con justify-content y align-items.
Estilo de cada imagen (.imagen):
position: relative: Necesario para posicionar el texto flotante respecto al contenedor de imagen.
flex-direction: column: Alineamos el contenido de forma vertical.

Efectos con CSS

![image](https://github.com/user-attachments/assets/7972a666-abdd-4cbf-ab8f-ed2c0584abe6)

Explicación:
Tamaño y forma de la imagen:
width y height: Aseguramos un tamaño uniforme (150x150px).
border-radius: 50%: Las imágenes se muestran en forma circular.
Sombras y bordes:
box-shadow: Agrega un efecto de sombra para destacar cada imagen.
border: Un borde blanco hace que resalten sobre el fondo.
Efecto al pasar el cursor:
transform: translateY(-20px): Al pasar el cursor, la imagen se eleva suavemente gracias a transition.

Texto flotante con CSS

![image](https://github.com/user-attachments/assets/58af33b5-95f7-4aa6-95f6-a70e6b79105d)

Explicación:
Posicionamiento del texto:
position: absolute: El texto flota encima de la imagen.
top: -60px: Lo colocamos justo arriba de la imagen.
Estilos visuales:
Fondo negro con texto blanco (background-color y color).
Bordes redondeados (border-radius) para un diseño limpio.
Mostrar al pasar el cursor:
Por defecto, display: none esconde el texto.
Al pasar el cursor (:hover), el texto aparece con una animación.

Paso 3: Responsive Design
Para que la galería funcione en dispositivos móviles, usamos media queries:

![image](https://github.com/user-attachments/assets/c6ac4f52-bde8-4929-b066-78e75ae9590e)


Explicación:
Condiciones para pantallas pequeñas:
Cuando el ancho sea menor a 680px, las imágenes se organizan en una columna.
Usamos gap para espaciar las imágenes.
Conclusión
Con este proyecto, aprendiste:

Crear estructuras básicas con HTML.
Diseñar con CSS, incluyendo efectos y transiciones.
Hacer tu diseño adaptable para diferentes dispositivos.
¿Tienes alguna duda o sugerencia? ¡Déjamela saber en los comentarios o abre un issue!






