# Guion de la Lección 2: Elemenots HTML comunes

## Detalles de la Lección
* **Duración aproximada:** 12 minutos
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
* **Herramientas:** CodePen (100% en línea)

---

## Estructura del Video

### Bloque 1: Jerarquía de Encabezados, Párrafos y Énfasis
- **[En pantalla]:** Entorno de CodePen abierto con el proyecto de la lección anterior (estructura base de perfil personal). Vista dividida con el editor HTML a la izquierda y la vista previa en vivo a la derecha. Escritura en directo de las etiquetas `<h1>` a `<h6>`, `<p>` y `<strong>`.
- **[Texto de apoyo visual / Superposiciones]:** 
  * `<h1> a <h6> = Niveles de encabezado (Mayor a menor importancia)`
  * `<p> = Párrafo`
  * `<strong> = Texto en negrita / Énfasis importante`
- **[Narración (Voz en off)]:** 
> "¡Hola de nuevo a todos! Ya sabemos cómo funciona la estructura base y una etiqueta HTML, así que ahora vamos a llenar nuestra página con los elementos más comunes y útiles de la web. 
> 
> Piensa en un periódico o en una revista: no todo el texto tiene el mismo tamaño ni la misma jerarquía visual. Hay titulares de portada grandes, subtítulos de sección y texto de lectura normal. En HTML contamos exactamente con 6 niveles de encabezados, que van desde el `<h1>` hasta el `<h6>`. 
> 
> En nuestra página de perfil usaremos un `<h1>` para el título principal con nuestro nombre, etiquetas `<h2>` para los subtítulos de cada sección (como 'Sobre mí' o 'Mis Pasatiempos') y la etiqueta `<p>` para redactar nuestras biografías en párrafos legibles. Además, si queremos que una palabra clave o frase resalte en negrita para llamar la atención del lector, la envolvemos dentro de la etiqueta `<strong>`."

---
### Bloque 2: Listas Ordenadas y Desordenadas
- **[En pantalla]:** Escritura en vivo en CodePen dentro del panel HTML. Se escribe primero un bloque `<ul>` con elementos `<li>` y se observa la aparición de viñetas en la vista previa. Luego se escribe un bloque `<ol>` con `<li>` para mostrar la numeración automática.
- **[Texto de apoyo visual / Superposiciones]:** 
  * `<ul> = Unordered List (Viñetas / Puntos)`
  * `<ol> = Ordered List (Numerada: 1, 2, 3...)`
  * `<li> = List Item (Elemento individual)`
- **[Narración]:** 
> "¿Qué pasa si queremos organizar ideas, mostrar una serie de pasatiempos o compartir nuestras metas del año? Para eso existen las listas en HTML.
> 
> Cuando el orden de los elementos no altera el significado —por ejemplo, una lista de compras o tus pasatiempos libres— utilizamos `<ul>` (*Unordered List*), que genera una lista con viñetas o puntos. 
> 
> En cambio, si queremos presentar un ranking o un paso a paso donde el orden sí importa —como tu 'Top 3 de videojuegos o películas'— recurrimos a `<ol>` (*Ordered List*). Esta etiqueta numera automáticamente cada línea con 1, 2, 3, sin necesidad de que escribas los números a mano. 
> 
> La regla de oro en ambos casos es la misma: cada elemento individual que pongas dentro de la lista debe ir obligatoriamente envuelto en una etiqueta `<li>` (*List Item*)."

---

### Bloque 3: Imágenes y Enlaces (Hipervínculos)
- **Tiempo estimado:** [00:06:00] – [00:09:30]
- **[En pantalla]:** Demostración en vivo insertando `<img>` con su `src` y `alt`. Se muestra la renderización inmediata de la foto. Posteriormente se redacta el hipervínculo con `<a>`, atributos `href` y `target="_blank"`, haciendo clic en el enlace para comprobar que abre la pestaña correspondiente.
- **[Texto de apoyo visual / Superposiciones]:** 
  * `<img src="URL" alt="Descripción visual"> (Etiqueta sin cierre)`
  * `<a href="URL" target="_blank">Texto del enlace</a>`
- **[Narración]:** 
> "Una web compuesta únicamente de texto plano se vuelve monótona rápidamente, así que vamos a darle vida agregando imágenes. Para ello usamos la etiqueta `<img>`. 
> 
> Notarás algo especial en `<img>`: no tiene etiqueta de cierre (`</img>`), sino que es una etiqueta autocontenida. Sin embargo, requiere dos atributos indispensables:
> 1. `src` (*source* o fuente), donde colocamos la dirección web completa de la foto.
> 2. `alt` (*alternative text*), donde describimos en pocas palabras lo que se ve en la imagen. Esto es crucial si la conexión falla o para personas con discapacidad visual que navegan usando lectores de pantalla.
> 
> Por último, lo que conecta a todo internet en una verdadera 'red mundial' son los enlaces o hipervínculos. Usamos la etiqueta `<a>` (*anchor*) con el atributo `href` apuntando a la URL que deseamos visitar. Si agregamos además el atributo `target="_blank"`, el enlace se abrirá en una pestaña nueva, evitando que el usuario abandone nuestra página."

---

### Bloque 4: Pausa Interactiva, Retos en CodePen y Cierre
- **[En pantalla]:** Zoom sobre el código completo terminado en CodePen y su resultado visual. Cartel en pantalla con instrucciones claras del reto y llamada a la acción para abrir el enlace de la descripción.
- **[Texto de apoyo visual / Superposiciones]:** 
  * `¡RETO EN CODEPEN! Abre el enlace en la descripción y pausa el video`
  * `Reto 1: Agrega un 4to <li> a tus pasatiempos`
  * `Reto 2: Personaliza tu Top 3 en <ol>`
  * `Reto 3: Cambia el enlace y descripción de <img>`
- **[Narración]:** 
> "¡Ahora es tu turno de poner manos al código! En la descripción de este video te he dejado el enlace directo a este proyecto en CodePen para que practiques de inmediato sin registrarte ni descargar nada.
> 
> Pausa el video durante unos minutos y completa estos desafíos:
> 1. Agrega un cuarto elemento `<li>` dentro de la lista desordenada con otro de tus pasatiempos.
> 2. Modifica la lista ordenada con tu propio Top 3 de videojuegos, series o canciones preferidas.
> 3. Busca en internet la imagen de tu personaje favorito y reemplaza la dirección en el atributo `src` y la descripción en el `alt`.
> 
> *(Breve pausa de silencio en el video)*
> 
> ¿Pudiste resolverlo? ¡Excelente trabajo! Tu perfil web ahora cuenta con títulos organizados, listas, imágenes y enlaces funcionales. En la siguiente lección daremos el gran salto al diseño visual: aprenderemos a aplicar colores, fuentes y estilos a estos elementos usando CSS. ¡Nos vemos en la próxima lección!"

---

## Código de Referencia para la Lección

**Código de Demostración y Práctica (CodePen):**
```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Perfil Web - Lección 2</title>
  </head>
  <body>
    <!-- Encabezado principal y presentación -->
    <h1>Mi Perfil Digital</h1>
    <p>¡Hola! Soy estudiante y me encanta la <strong>tecnología</strong> y el desarrollo web.</p>

    <!-- Sección de Pasatiempos (Lista Desordenada) -->
    <h2>Mis Pasatiempos Favoritos</h2>
    <ul>
      <li>Programar páginas interactivas</li>
      <li>Escuchar música</li>
      <li>Aprender idiomas</li>
      <!-- RETO 1: Agrega aquí un cuarto elemento <li> con tu hobby -->
    </ul>

    <!-- Sección de Ranking (Lista Ordenada) -->
    <h2>Mi Top 3 de Videojuegos / Series</h2>
    <ol>
      <li>Hollow Knight</li>
      <li>Minecraft</li>
      <li>Portal 2</li>
      <!-- RETO 2: Personaliza este Top 3 con tus favoritos -->
    </ol>

    <!-- Sección Multimedia y Enlace Externo -->
    <h2>Mi Imagen Favorita</h2>
    <!-- RETO 3: Reemplaza el enlace de la imagen y actualiza el texto alternativo -->
    <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&w=400&q=80" alt="Consola y mandos de videojuegos retro sobre un escritorio">

    <p>
      Para aprender más sobre desarrollo, visita la 
      <a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank">documentación oficial de MDN Web Docs</a>.
    </p>
  </body>
</html>
```