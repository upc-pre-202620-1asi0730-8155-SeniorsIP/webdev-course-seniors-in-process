# Guion de la Lección 4: Estilo Simple en CSS (Centrar Contenido, Colores y Bordes)

## Detalles de la Lección
* **Duración aproximada:** 10 a 12 minutos
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
* **Herramientas:** Diapositivas conceptuales y CodePen (100% en línea, sin instalaciones)

---

## Estructura del Video

### Bloque 1: El contenedor `<div>` y el problema del diseño plano
* **[En pantalla]:** Diapositiva 1 (Comparación visual: una página desordenada a la izquierda vs. una tarjeta de perfil centrada y moderna a la derecha).
* **[Texto de apoyo visual]:** `<div> = Caja contenedora invisible`
* **[Narración (Voz en off)]:** 

> "¡Hola a todos y bienvenidos a la cuarta lección de nuestro curso de desarrollo web! En los videos anteriores aprendimos a estructurar textos, listas e imágenes con HTML, y vimos cómo aplicar colores y fuentes con CSS. Pero si miramos nuestra pantalla, todo el contenido sigue pegado al borde izquierdo del navegador y ocupa todo el ancho de forma desorganizada.
> 
> En las redes sociales o en nuestros videojuegos favoritos, la información se organiza en tarjetas visuales limpias y atractivas. Para lograrlo en desarrollo web, usamos una etiqueta fundamental de HTML llamada `<div>`. 
> 
> Un `<div>` no cambia el aspecto del texto por sí solo: es una caja invisible que sirve para agrupar varios elementos (como una foto, un nombre y una descripción) y poder moverlos, darles fondo y estilizarlos juntos como un solo bloque. Hoy aprenderemos a tomar esa caja y darle vida con CSS."

---

### Bloque 2: La analogía del Modelo de Caja (*Box Model*)
* **[En pantalla]:** Diapositiva 2 (Ilustración didáctica de un cuadro colgado en una pared: Pintura = Contenido, Vidrio protector = *Padding*, Marco de madera = *Border*, Distancia con otros cuadros = *Margin*).
* **[Texto de apoyo visual]:** `Contenido + Padding (Relleno) + Border (Borde) + Margin (Margen)`
* **[Narración]:** 
> "Para dominar el diseño web hay que entender una regla de oro: en CSS, **absolutamente todo es una caja**. A esta regla la llamamos el Modelo de Caja o *Box Model*.
> 
> Imagina un cuadro decorativo en la pared de tu habitación:
> 1. **El Contenido (*Content*):** Es la pintura o el póster central: tu texto, tu foto o tu botón.
> 2. **El Relleno (*Padding*):** Es el espacio libre entre la pintura y el marco de madera. Sirve para que el contenido no quede asfixiado contra las orillas; es el aire interior de la caja.
> 3. **El Borde (*Border*):** Es el marco físico que rodea la caja. Podemos elegir qué tan grueso es, si es una línea continua o de puntos, y qué color tiene.
> 4. **El Margen (*Margin*):** Es la distancia entre este cuadro y los demás muebles u otros cuadros vecinos en la pared. Es el espacio exterior que separa una caja de otra.
> 
> Si aprendes a controlar el `padding`, el `border` y el `margin`, tendrás el control total sobre la apariencia de tu página web."
---

### Bloque 3: El gran secreto para centrar en la Web
* **[En pantalla]:** Diapositiva 3 (Gráfico explicativo: Centrar texto interno vs. Centrar la caja completa en la pantalla).
* **[Texto de apoyo visual]:** 
 * `text-align: center` ➔ Alinea texto e imágenes dentro de la caja
 * `margin: auto` ➔ Centra la caja completa en el navegador
* **[Narración]:** 
> "Una de las preguntas más comunes cuando comenzamos a programar es: ¿cómo centramos las cosas en la pantalla? 
> 
> Hay dos conceptos diferentes que no debemos confundir:
> * Si queremos centrar el texto o las imágenes que viven **adentro** de nuestra caja, usamos la propiedad `text-align: center;`.
> * Pero si queremos que **la caja entera** se ubique exactamente en el centro de la pantalla de la computadora, primero le definimos un ancho máximo con `max-width` (por ejemplo, 420 píxeles) y luego usamos la propiedad `margin: auto;`. La palabra `auto` le pide al navegador que mida el espacio sobrante a la izquierda y a la derecha y lo reparta en partes exactamente iguales. ¡Así de fácil logramos un centrado perfecto!
> 
> Pasemos de la teoría a la práctica en CodePen."

---

### Bloque 4: Demostración en vivo en CodePen
* **[En pantalla]:** Vista de CodePen (zoom al 150%, panel HTML con la estructura inicial, escribiendo en el panel CSS línea por línea mientras la vista previa se actualiza en vivo).
* **[Textos flotantes en edición]:** 
 * `.tarjeta = Selector de clase para la caja`
 * `padding: 30px = Relleno interno`
 * `border: 3px solid #89b4fa = Grosor, estilo y color`
 * `border-radius: 16px = Esquinas redondeadas`
 * `border-radius: 50% = Círculo perfecto`
* **[Narración]:** 
> "Ya estamos en CodePen. En el panel de HTML ya tenemos preparado un contenedor `<div class="tarjeta">` que contiene una imagen, un encabezado `<h1>`, un párrafo y un enlace. En CSS solo tenemos el color de fondo oscuro del `body`.
> 
> Vamos a escribir el código de nuestra tarjeta paso a paso:
> 
> 1. **Damos forma a la caja:** Escribimos `.tarjeta {` y agregamos `background-color: #1e1e2e;`. ¡Mira cómo aparece un bloque grisáceo detrás del texto! Ahora limitamos su ancho con `max-width: 420px;` para que no ocupe toda la pantalla.
> 2. **Damos espacio interior:** El texto está chocando contra los bordes de la caja. Agregamos `padding: 30px;` y de inmediato la caja se expande por dentro, dejando respirar el contenido.
> 3. **Bordes y esquinas:** Añadimos `border: 3px solid #89b4fa;`. Esta propiedad resume tres datos: 3 píxeles de grosor, estilo sólido y color azul claro. Como las esquinas se ven muy rectas, añadimos `border-radius: 16px;` para suavizarlas.
> 4. **Centrado completo:** Para colocar la tarjeta en el centro de la pantalla usamos `margin: 50px auto;`. Y para alinear el texto y la foto en el eje central, agregamos `text-align: center;`. ¡Nuestra tarjeta ya tiene forma profesional!
> 5. **Avatar y botón:** Para la foto seleccionamos `.foto-perfil`. Le damos un tamaño cuadrado de 120 por 120 píxeles, `object-fit: cover;` para que no se deforme, y el truco clásico: `border-radius: 50%;` para volverla un círculo perfecto con su propio borde verde.
> 6. Finalmente, a nuestro enlace `.boton` le quitamos el subrayado con `text-decoration: none;`, le damos un color de fondo llamativo, un poco de `padding` para que parezca un botón real y esquinas redondeadas con `border-radius: 8px;`."

---

### Bloque 5: Pausa Interactiva y Cierre
* **[En pantalla]:** Código final en CodePen. Mostrar texto destacado: `¡PAUSA PARA PRACTICAR! (Abre el enlace en la descripción)`.
* **[Narración]:** 
> "¡Ahora es tu turno de experimentar con el diseño! En la descripción de este video encontrarás el enlace directo a este proyecto en CodePen.
> 
> Pausa el video durante un par de minutos y realiza estos 3 retos en tu código:
> 1. En la clase `.tarjeta`, cambia el estilo del borde de `solid` a `dashed` para ver una línea punteada, y prueba cambiar su color a un tono rosa o amarillo.
> 2. En la clase `.foto-perfil`, cambia el valor de `border-radius` de `50%` a `20px` para transformar el círculo en un cuadrado de bordes suaves.
> 3. En la clase `.boton`, cambia el color de fondo (`background-color`) por tu color favorito.
> 
> *(Breve pausa de silencio de 3 segundos en el video)*
> 
> ¿Pudiste ver cómo cambian las formas y colores al instante? Dominar el modelo de caja y el centrado es uno de los pasos más importantes en el diseño web. En la siguiente y última lección combinaremos todo lo aprendido para armar una página web completa con entrada de blog y revisaremos las mejores recomendaciones para principiantes. ¡Nos vemos en el próximo video!"

---

## Código de Referencia para la Lección

### 1. Archivo de Inicio (Starter File)

#### HTML:
```html
<div class="tarjeta">
 <img class="foto-perfil" src="[https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=300](https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=300)" alt="Avatar de perfil">
 <h1>Alex Coder</h1>
 <p class="bio">Creador de mundos digitales, fan de los videojuegos indie y estudiante de desarrollo web.</p>
 <a class="boton" href="[https://codepen.io](https://codepen.io)" target="_blank">Ver mis proyectos</a>
</div>

```

#### CSS:
```css
body {
 background-color: #181825;
 color: #cdd6f4;
 font-family: 'Segoe UI', sans-serif;
}

.tarjeta {
 background-color: #1e1e2e;
 max-width: 420px;
 margin: 50px auto;
 padding: 30px;
 /* RETO 1: Cambia 'solid' por 'dashed' y el color '#89b4fa' por '#f38ba8' (rosa) */
 border: 3px solid #89b4fa;
 border-radius: 16px;
 text-align: center;
}


.foto-perfil {
 width: 120px;
 height: 120px;
 object-fit: cover;
 /* RETO 2: Cambia '50%' por '20px' para ver un cuadrado con esquinas suaves */
 border-radius: 50%;
 border: 4px solid #a6e3a1;
}

.bio {
 color: #bac2de;
 margin-bottom: 25px;
}

.boton {

 /* RETO 3: Cambia el color del botón '#89b4fa' por '#f9e2af' (dorado) */
 background-color: #89b4fa;
 color: #11111b;
 text-decoration: none;
 padding: 10px 20px;
 border-radius: 8px;
 font-weight: bold;
}
```