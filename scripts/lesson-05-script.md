# Guion de la Lección 5: Proyecto Final y Recomendaciones

## Detalles de la Lección
* **Duración aproximada:** 11 minutos
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
* **Herramientas:** Editor CodePen (100% en línea)

---

## Estructura del Video

### Bloque 1: Introducción y Agregando Insignias al Perfil (00:01 - 02:10)
* **[En pantalla]:** Mostrar la vista dividida en CodePen con el código inicial.
* **[Texto de apoyo visual]:** `Lección 5: Proyecto Final y Consejos para Principiantes`
* **[Narración (Voz en off)]:** 
> "Hola, bienvenidos a la quinta y última lección de nuestro curso de desarrollo web. Hasta ahora hemos recorrido un camino largo, aprendimos qué es el código HTML, cómo insertar imágenes, listas y enlaces, cómo darle color con selectores de CSS y cómo centrar cajas con bordes redondeados. Ahora vamos a unir todas esas piezas para terminar una página web completa.
>
> Combinaremos nuestra tarjeta de perfil con una entrada de blog personal y en la segunda mitad veremos los errores más comunes al programar y cómo solucionarlo en segundos. Empezaremos dándole un toque especial a nuestra tarjeta de perfil. Queremos mostrar tres pequeñas etiquetas o insignias con las tecnologías que ya hemos dominado, que son HTML5, CSS3 y diseño web.
>
> En el panel de HTML, debajo de nuestra biografía, creamos una caja `<div class="insignias">`. Adentro de dicha caja, usamos la etiqueta `<span>` con la clase `insignia`. ¿Por qué usamos la etiqueta `<span>` y no la etiqueta `<p>` o la etiqueta de párrafo? Porque la etiqueta `<p>` ocupa todo el renglón y empuja el siguiente elemento hacia abajo, mientras que la etiqueta `<span>` coloca los elementos uno al costado del otro en la misma línea.
>
> Ahora bajamos al panel de CSS para darles estilo a insignias. Le damos un `margin-top` de 20 píxeles para separarlo del texto. Y a cada insignia le ponemos un fondo gris oscuro con el código del color. El código de `#313244`, que es el texto amarillo suave, o el `#F9E2AF`, que es un relleno interno con `padding` de 6 píxeles a 14 píxeles y un `border-radius` de 20 píxeles para que tengan forma de píldora."

### Bloque 2: Creando la Sección de Entrada de Blog en HTML (02:10 - 03:06)
* **[En pantalla]:** Agregar la etiqueta `<article class="entrada-blog">` dentro de `<main>`.
* **[Texto de apoyo visual]:** `<article> = Contenido independiente (como un post de blog o noticia)`
* **[Narración]:**
> "Miren a la derecha cómo quedaron alineadas. Ahora vamos a construir la segunda mitad de nuestra página web, nuestra primera entrada de blog. Justo debajo del cierre de sección, pero todavía dentro de etiqueta principal `<main>`, abrimos una etiqueta llamada `<article>` con la clase de `entrada-blog`. En HTML moderno usamos la etiqueta de `<article>` cuando creamos una publicación de blog o una noticia adentro.
>
> Colocamos todo lo que aprendimos en la lección 2, un subtítulo de etiqueta `<h2>` que diga 'Mi primera entrada de blog: ¡Creé mi web!', un párrafo con la clase `fecha` para indicar cuándo se publicó, un párrafo introductorio y una lista desordenada de etiqueta `<ul>` con tres elementos de la etiqueta `<li>` resumiendo lo que aprendimos en el curso."

### Bloque 3: Estilizando el Blog y el Efecto Interactivo (03:06 - 05:48)
* **[En pantalla]:** Aplicar estilos CSS a la entrada del blog, incluyendo `border-left` y la pseudoclase `:hover`.
* **[Texto de apoyo visual]:** `:hover = Cambia el estilo cuando pasas el cursor por encima`
* **[Narración]:**
> "Finalmente, cerramos con un enlace de etiqueta `<a>` que tiene la clase `boton-enlace` apuntando a la enciclopedia web MDN, sin olvidar el atributo `target="_blank"` para que abra en una nueva pestaña. Como ven en la vista previa, el texto del blog apareció, pero aún no tiene forma de tarjeta. Vamos al panel de CSS para darle diseño.
>
> Seleccionamos punto de `entrada-blog`. Le ponemos el mismo color de fondo, un relleno interno de 28 píxeles y esquinas redondeadas de 16 píxeles. Pero aquí haremos algo diferente, en vez de ponerle borde por los cuatro lados, escribiremos `border-left`, 6 píxeles `solid` y el código del color que queramos. Esto dibuja una elegante franja verde únicamente en el borde izquierdo, muy típica de los blogs de tecnología.
>
> Pintamos el título `<h2>` de verde claro. A la clase punto fecha, le damos un tono gris suave con la letra de 14 píxeles. Y convertimos nuestro enlace de punto `boton-enlace` en un botón real usando `display: inline-block`, fondo azul, texto oscuro y `text-decoration: none` para quitar el subrayado. Y como toque final agregamos `.boton-enlace:hover`.
>
> La palabra `hover` después de los dos puntos le dice al navegador: cuando el usuario pase el mouse por encima de este botón cambia su color de fondo a un tono más brillante. Miren cómo reacciona el botón al pasar el cursor. Nuestra página web ya está 100% terminada. Como se puede evidenciar, aquí está toda la página web."

### Bloque 4: Pausa Interactiva (05:48 - 06:15)
* **[En pantalla]:** Resaltar el código final en CodePen.
* **[Texto de apoyo visual]:** `¡PAUSA PARA PRACTICAR! (Abre el enlace en la descripción)`
* **[Narración]:**
> "Pero ahora te toca a ti. Antes de pasar por los errores comunes, pausa este video un par de minutos y abre el enlace de CodePen que está en la descripción. Cambia el nombre Sam Rivera por tu nombre o apodo. Cambia las tres insignias por tus videojuegos, deportes o materias favoritas y escribe en la lista de blog qué fue lo que más te gustó aprender hoy.
> 
> *(Breve pausa de silencio en el video)*
> 
> Cuando termines, dale play de nuevo porque lo que viene te ahorrará horas de frustración en caso de cometas un error."

### Bloque 5: Demostración en Vivo de Errores Comunes (06:15 - 08:25)
* **[En pantalla]:** Borrar y restaurar elementos clave del código para forzar fallos visuales.
* **[Textos flotantes en edición]:** 
  * `[Error #1: Olvidar la etiqueta de cierre (ej. </h1>)]`
  * `[Error #2: Olvidar el punto y coma (;) al final en CSS]`
  * `[Error #3: Confundir .clase con #id en los selectores]`
  * `[Error #4: Atributos sin comillas o mala ortografía]`
* **[Narración]:**
> "Bueno, continuaremos con la demostración de los cuatro errores más comunes al momento de programar. Por ejemplo, en la sección de HTML, ¿qué pasaría si en la línea del `<h1>`, donde se instancia el nombre de Sam Rivera, ¿qué pasa si borramos el `</h1>` de cierre? En este caso, las letras se ponen en grande. Pero al quitar el error, vuelven a la normalidad.
>
> Otro de los errores más comunes en el CSS es olvidar poner el punto y coma al final. Por ejemplo, en `.tarjeta-perfil`, ¿qué pasaría si borráramos el punto y coma al final? Pues lo que pasa es que se pierde el `padding` de 30 píxeles de abajo. Pero al volver a poner el punto y coma, vuelve a la normalidad y se arregla.
>
> El tercer error más común en CSS es confundir el punto de clase con el numeral de ID. Por ejemplo, ¿qué pasa si cambiamos en `.entrada-blog` el punto por el numeral? Como se puede ver, la caja del blog pierde todo su diseño. Pero al corregir el error, vuelve la normalidad. El último y el cuarto error más común son errores de escritura en inglés o faltas de comillas. Por ejemplo, en el `text-align: center` o en el `src=""`. Nunca debe faltar las comillas o la escritura en inglés."

### Bloque 6: Recomendaciones Finales y Cierre (08:25 - 10:55)
* **[En pantalla]:** Mostrar la indentación del código y abrir la documentación web.
* **[Textos flotantes en edición]:** 
  * `[Buena Práctica: Indentación de código]`
  * `[Buena Práctica: Usar comentarios <!-- -->]`
  * `[Recurso útil: MDN Web Docs / W3C Validator]`
* **[Narración]:**
> "Para terminar con este curso, como verdaderos creadores web, quiero dejarles tres grandes recomendaciones que usan los profesionales todos los días. Primero, mantén tu código ordenado con sangría o indentación. Fíjate cómo en nuestro HTML dejamos dos espacios a la derecha cada vez que una etiqueta está dentro de otra. En CodePen, si seleccionas tu código y presionas la tecla `Tab`, se ordena hacia la derecha. Eso te permite ver de un solo vistazo qué caja está dentro de cuál.
>
> La segunda recomendación es usar comentarios para dejar notas, tanto en HTML como en CSS, se pueden dejar comentarios, se pueden dejar títulos explicando para qué sirve cada sección. Así cuando abras un proyecto, entenderás todo al instante. En este caso, no agregué comentarios.
>
> Recomendación número tres. No intentes memorizar todo. Usa la documentación. Ningún desarrollador web se sabe todas las etiquetas ni todas las propiedades de memoria. Cuando te preguntes cómo pongo una sombra o cómo hago una tabla, consulta sitios confiables como MDN Web Docs o el validador oficial de la W3C, que es el World Wide Web Consortium.
>
> En la descripción de este video encontrarás el enlace directo a este proyecto final en CodePen y agregaré títulos o notas. Y también encontrarás el enlace directo a nuestro repositorio de GitHub, donde están guardadas todos los códigos iniciales, los ejemplos terminados y las guías de las cinco lecciones. Anímate a modificar los colores, agregar más entradas a tu blog y compartir el enlace con tus amigos. Muchas gracias por acompañarnos en este curso y mucho éxito creando tus próximos sitios web."

---

## Código de Referencia para la Lección

**Código de Inicio (Starter - Para el estudiante):**

**HTML:**
```html
<main class="contenedor">
  <section class="tarjeta-perfil">
    <img class="avatar" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=300" alt="Foto de perfil">
    <h1 id="nombre">Sam Rivera</h1>
    <p class="subtitulo">Estudiante | Creador Web | Gamer</p>
    <p>¡Bienvenido a mi página personal! Creé este sitio web combinando estructura en <strong>HTML</strong> y diseño en <strong>CSS</strong>.</p>
  </section>
</main>
```

**CSS:**
```css
body {
  background-color: #11111b;
  color: #cdd6f4;
  font-family: 'Segoe UI', Tahoma, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 20px;
}
.contenedor {
  max-width: 600px;
  margin: 20px auto;
}
.tarjeta-perfil {
  background-color: #1e1e2e;
  padding: 30px;
  border: 2px solid #89b4fa;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 24px;
}
.avatar {
  width: 110px;
  height: 110px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #a6e3a1;
}
#nombre {
  color: #ffffff;
  font-size: 32px;
  margin-bottom: 4px;
}
.subtitulo {
  color: #89b4fa;
  font-weight: bold;
  margin-top: 0;
}
```
