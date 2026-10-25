# Guion de la Lección 1: Introducción al Desarrollo Web y Estructura HTML Básica

## Detalles de la Lección
* **Duración aproximada:** 10 minutos
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
* **Herramientas:** Diapositivas visuales y CodePen (100% en línea)

---

## Estructura del Video

### Bloque 1: ¿Qué es un sitio web? 
* **[En pantalla]:** Mostrar Diapositiva 1 (Navegadores y concepto de sitio web).
* **[Texto de apoyo visual]:** `Sitio Web = Estructura + Diseño`
* **[Narración (Voz en off)]:** 
> "¡Hola a todos y bienvenidos a nuestro curso de fundamentos de desarrollo web! Alguna vez te has preguntado, cuando entras a YouTube, buscas información para el colegio o entras a tu red social favorita, ¿cómo es que existen esas páginas en internet? Todo lo que ves y usas en la red es un sitio web o una aplicación web.
> 
> Funciona así: tu navegador web —ya sea Chrome, Edge, Firefox o Safari— actúa como un traductor. Recibe archivos con líneas de código y los transforma al instante en botones, textos, fotos y videos con los que puedes interactuar.
> 
> Y tengo una excelente noticia: para aprender a crear tus propias páginas web hoy no necesitas instalar ningún programa ni descargar nada en tu computadora. Solo necesitamos nuestro navegador y **CodePen**, un editor gratuito 100% en línea donde cada cambio que escribamos se verá reflejado en tiempo real."

### Bloque 2: La Casa Digital - HTML y CSS 
* **[En pantalla]:** Mostrar Diapositiva 2 (Analogía de la casa: HTML y CSS).
* **[Texto de apoyo visual]:** `HTML (Contenido) + CSS (Estilo)`
* **[Narración]:** 
> "Para construir cualquier sitio web desde cero, usamos dos tecnologías fundamentales que trabajan en equipo. Imagina que vamos a construir una casa.
> 
> Primero necesitamos los cimientos, los ladrillos, las columnas y las paredes que dividen las habitaciones. En el mundo web, a esa estructura la llamamos **HTML** (HyperText Markup Language). HTML se encarga de definir el contenido: dónde va un título, dónde va un párrafo y dónde va una imagen.
> 
> Pero una casa solo de ladrillos grises se vería muy simple, ¿verdad? Ahí entra el segundo ingrediente: **CSS**. CSS es la pintura de las paredes, la iluminación y la decoración. Es el lenguaje que le da color, tipos de letra y estilo visual a nuestra página. En resumen: HTML pone el contenido y la estructura, y CSS pone el estilo. En esta primera lección dominaremos las bases de HTML."

### Bloque 3: Etiquetas, Elementos y Atributos 
* **[En pantalla]:** Mostrar Diapositiva 3 (Anatomía del código HTML).
* **[Texto de apoyo visual]:** Señalar `<p>` (Etiqueta), `id="mensaje"` (Atributo), y la frase completa (Elemento).
* **[Narración]:** 
> "¿Y cómo le damos órdenes al navegador usando HTML? Lo hacemos mediante etiquetas, elementos y atributos. Mira este ejemplo en pantalla:
> 
> 1. **Las Etiquetas:** Piensa en ellas como cajas con nombre que le dicen al navegador qué tipo de contenido estamos guardando. Se escriben entre símbolos de menor y mayor que. Casi siempre vienen en pareja: una etiqueta de apertura al inicio (como `<p>`, que significa párrafo) y una etiqueta de cierre al final (`</p>`), que es idéntica pero incluye una barra inclinada para indicar que ahí termina la caja.
> 2. **El Elemento:** Cuando juntamos la etiqueta de apertura, el contenido que va en el medio y la etiqueta de cierre, a todo ese bloque completo lo llamamos elemento HTML.
> 3. **Los Atributos:** ¿Ves ese texto amarillo que dice `id="mensaje"` dentro de la etiqueta de apertura? Eso es un atributo. Los atributos son configuraciones o datos extra que le damos a una etiqueta. Siempre se colocan dentro de la etiqueta de apertura siguiendo la fórmula nombre igual a valor entre comillas.
> 
> Ahora que ya conocemos las piezas, ¡vamos a CodePen para escribir nuestro propio código!"

### Bloque 4: Demostración en Vivo en CodePen 
* **[En pantalla]:** Cambiar a la vista de CodePen (zoom al 150%, solo panel HTML y Vista Previa). Escribir el código paso a paso.
* **[Textos flotantes en edición]:** 
  * `<h1> = Encabezado principal`
  * `<head> = Configuración invisible`
  * `<body> = Todo lo que el usuario ve`
* **[Narración]:** 
> "Ya estamos en CodePen. Probemos crear nuestro primer elemento: escribamos `<h1>¡Hola Mundo!</h1>`. ¡Mira cómo aparece un título grande! La etiqueta `h1` representa el encabezado más importante. Debajo agreguemos un párrafo con `<p>Bienvenido a mi primera pagina web.</p>`.
> 
> Ahora bien, aunque CodePen nos permite escribir etiquetas sueltas directamente, toda página web profesional tiene un esqueleto base que debemos conocer. Vamos a envolver nuestro código en esa estructura:
> * Arriba del todo escribimos `<!DOCTYPE html>`. Esta línea le avisa al navegador que estamos usando la versión más moderna de HTML.
> * Debajo abrimos la etiqueta raíz `<html>` y la cerramos al final con `</html>`. Todo nuestro sitio vive dentro de ella.
> * Adentro de `<html>` siempre hay dos grandes secciones: primero `<head>` (la cabeza). Lo que ponemos en `<head>` no se ve directamente dentro de la página, sino que sirve de configuración, como el `<title>`.
> * Y la segunda sección es `<body>` (el cuerpo). Adentro de `<body>` colocamos nuestro `<h1>` y nuestro `<p>`, porque todo lo que esté dentro de `<body>` es lo que el usuario verá en su pantalla.
> 
> Para terminar, pongamos a prueba los atributos:
> * En la etiqueta `<html>` agregamos `lang="es"` para indicar que nuestra página está en español.
> * En nuestro `<h1>` agreguemos el atributo `id="titulo-principal"`.

### Bloque 5: Pausa Interactiva y Cierre 
* **[En pantalla]:** Resaltar el código final en CodePen. Mostrar texto grande: `¡PAUSA PARA PRACTICAR! (Abre el enlace en la descripción)`.
* **[Narración]:** 
> "¡Ahora te toca a ti probar este código! En la descripción de este video encontrarás un enlace directo a este proyecto en CodePen —recuerda que no necesitas crearte una cuenta para usarlo—.
> 
> Ponle pausa al video durante un par de minutos y cumple estos 3 pequeños retos:
> 1. Cambia el texto que está dentro de `<h1>` por tu apodo gamer o tu pasatiempo favorito.
> 2. Cambia el texto del párrafo `<p>` contando en una línea qué tipo de página web te gustaría crear.
> 
> *(Breve pausa de silencio en el video)*
> 
> ¿Lo lograste? ¡Felicidades, acabas de escribir tu primera estructura HTML real! En la siguiente lección aprenderemos a agregar listas, imágenes y enlaces para que nuestra página tenga mucho más contenido. ¡Nos vemos en el próximo video!"

---

## Código de Referencia para la Lección

**Código de Inicio (Starter - Para el estudiante):**
```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Primera Web</title>
  </head>
  <body>
    <!-- RETO 1: Cambia el texto de este encabezado h1 por tu apodo o hobby -->
    <h1 id="titulo-principal">¡Hola, Mundo Digital!</h1>
    
    <!-- RETO 2: Cambia el texto del párrafo -->
    <p title="¡Escribe aquí tu propio mensaje secreto!">
      Bienvenido a mi primer espacio en internet creado con HTML.
    </p>
  </body>
</html>