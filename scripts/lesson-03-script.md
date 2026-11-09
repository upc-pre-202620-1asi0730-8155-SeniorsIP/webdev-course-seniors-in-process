# Guion de la Lección 3: Introducción a CSS (Paso a Paso con Código)

## Detalles de la Lección
- **Duración aproximada:** 12 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** CodePen (100% en línea)

---

## Estructura del Video y Guion Técnico

### Bloque 1: ¿Qué es CSS y cuál es su sintaxis? (0:00 - 3:00)

- **[En pantalla]:** Mostrar nuestra página del Video 2 (en blanco y negro / sin estilos) al lado de la misma página ya estilizada con colores vibrantes y modo oscuro. Posteriormente, hacer zoom y enfocar el panel CSS del editor CodePen.
- **[Texto de apoyo visual / Código en pantalla]:**
  ```css
  selector {
    propiedad: valor;
  }
  ```
- **[Narración (Voz en off)]:**  
  > "¡Bienvenidos a la tercera lección! Ya tenemos toda nuestra información en HTML, pero seamos sinceros: todavía parece un documento de texto desactualizado. Aquí entra **CSS** (*Cascading Style Sheets* o Hojas de Estilo en Cascada). 
  > 
  > En CodePen, el panel de CSS ya está conectado automáticamente a nuestro HTML. La regla de oro en CSS es muy fácil: escribimos un **selector** (a quién queremos cambiarle el estilo), abrimos llaves `{ }`, y adentro escribimos la **propiedad** (qué queremos cambiar), dos puntos `:`, el **valor** (cómo lo queremos) y cerramos siempre con punto y coma `;`."

---

### Bloque 2: Tipos de Selectores: Etiqueta, Clase e ID (3:00 - 6:30)

- **[En pantalla]:** Mostrar el panel HTML que contiene la estructura inicial:
  ```html
  <h1 id="titulo-principal">Perfil de Creador Digital</h1>
  <p class="destacado">¡Hola! Me apasiona la tecnología, la música y el diseño de mundos virtuales.</p>
  <p>Aquí comparto mis aprendizajes creando páginas desde cero con HTML y CSS.</p>
  <h2>Mis Pasatiempos</h2>
  <ul>
    <li>Escuchar música electrónica y rock</li>
    <li>Aprender programación web</li>
    <li>Dibujo digital</li>
  </ul>
  ```
- **[Texto de apoyo visual]:**
  ```css
  p { }              /* Etiqueta */
  .mi-clase { }      /* Clase */
  #mi-id { }         /* ID */
  ```
- **[Narración]:**  
  > "Hay tres formas principales de seleccionar elementos en CSS. 
  > 
  > La primera es por **nombre de etiqueta**: si escribo `p`, absolutamente todos los párrafos de la página cambiarán."

- **[Código que se escribe de prueba en CSS]:**
  ```css
  p {
    color: red;
  }
  ```

- **[Narración]:**  
  > "¿Pero qué pasa si solo quiero pintar un párrafo en especial? Usamos el atributo `class` en HTML y en CSS lo llamamos con un **punto** adelante, por ejemplo `.destacado`. Las clases se pueden reutilizar muchas veces."

- **[Código que se actualiza en CSS]:**
  ```css
  .destacado {
    color: green;
  }
  ```

- **[Narración]:**  
  > "Y si tenemos un elemento único en toda la página, usamos su atributo `id` y en CSS lo llamamos con el símbolo de **numeral o michi (`#`)**, como `#titulo-principal`."

- **[Código que se agrega en CSS]:**
  ```css
  #titulo-principal {
    color: blue;
  }
  ```

---

### Bloque 3: Propiedades de Color, Tipografía y Diseño Básico (6:30 - 10:00)

- **[En pantalla]:** Limpiar las reglas de prueba anteriores en el panel CSS para escribir la hoja de estilos definitiva mientras se ven los cambios en tiempo real en la vista previa.

- **[Narración]:**  
  > "Vamos a transformar nuestra página. Seleccionamos `body` y usamos `background-color: #1e1e2e;` para darle un fondo modo oscuro moderno, y `color: #cdd6f4;` para que las letras sean claras. Esos códigos con el símbolo `#` se llaman colores hexadecimales, ¡y te permiten elegir entre millones de tonos!"

- **[Código que se escribe en el panel CSS]:**
  ```css
  /* 1. Selector de etiqueta: aplica a todo el cuerpo de la página */
  body {
    background-color: #1e1e2e; /* Color de fondo oscuro */
    color: #cdd6f4;            /* Color de texto claro */
  }
  ```

- **[Narración]:**  
  > "Ahora cambiemos la letra: usamos `font-family: 'Segoe UI', sans-serif;` para quitar esa letra antigua por defecto y poner una limpia y moderna. Con `font-size` controlamos el tamaño de las letras en píxeles (`px`) y con `line-height` damos un respiro entre renglones para que sea cómodo de leer."

- **[Código que se actualiza en el bloque body]:**
  ```css
  body {
    background-color: #1e1e2e;
    color: #cdd6f4;
    font-family: 'Segoe UI', Tahoma, sans-serif;
    line-height: 1.6;
  }
  ```

- **[Narración]:**  
  > "Ahora daremos estilo a nuestro título con su ID, a los subtítulos `h2` con selector de etiqueta y a nuestro texto destacado con su clase."

- **[Código completo final en el panel CSS]:**
  ```css
  /* 1. Selector de etiqueta principal */
  body {
    background-color: #1e1e2e;
    color: #cdd6f4;
    font-family: 'Segoe UI', Tahoma, sans-serif;
    line-height: 1.6;
  }

  /* 2. Selector de ID (#) */
  #titulo-principal {
    color: #89b4fa;
    font-size: 36px;
  }

  /* 3. Selector de etiqueta para subtítulos */
  h2 {
    color: #f9e2af;
    font-size: 24px;
  }

  /* 4. Selector de Clase (.) */
  .destacado {
    background-color: #313244;
    color: #a6e3a1;
    font-size: 18px;
  }
  ```

---

### Bloque 4: Pausa Interactiva (10:00 - 11:00)

- **[En pantalla]:** Mostrar banner gráfico con el texto:  
  `⏸️ ¡PAUSA Y EXPERIMENTA! Cambia los colores y el tamaño de letra en CodePen`.
- **[Narración]:**  
  > "¡Abre el enlace de CodePen en la descripción! Pausa el video y prueba cambiar el color de `#titulo-principal` por tu color favorito (puedes escribir palabras en inglés como `gold`, `cyan` o `coral`, o usar códigos hexadecimales) y aumenta su `font-size` a `40px`."

---

### Bloque 5: Reto del Video y Cierre (11:00 - 12:00)

- **[En pantalla]:** Mostrar la interfaz de CodePen resaltando con un recuadro animado la zona del código donde los estudiantes aplicarán el reto.
- **[Texto de apoyo visual en pantalla]:**
  >  **¡RETO DE CÓDIGO!**
  > 1. Crea una clase llamada `.mi-tarjeta` y aplícala a uno de los párrafos.
  > 2. Dale un fondo diferente (ej. `#45475a`), bordes redondeados (`border-radius: 8px;`) y espacio interno (`padding: 15px;`).
  > 3. Cambia el color de la lista (`<ul>`) usando un selector de etiqueta.

- **[Demostración rápida en código]:**
  ```html
  <!-- En el panel HTML -->
  <p class="mi-tarjeta">Aquí comparto mis aprendizajes creando páginas desde cero con HTML y CSS.</p>
  ```
  ```css
  /* En el panel CSS */
  .mi-tarjeta {
    background-color: #45475a;
    padding: 15px;
    border-radius: 8px;
  }

  ul {
    color: #f5c2e7;
  }
  ```

- **[Narración]:**  
  > "¡Es momento de pasar de la teoría a la práctica con nuestro reto de hoy! Abre tu CodePen y haz lo siguiente: 
  > 
  > Primero, inventa una clase llamada `.mi-tarjeta`, añádela a uno de tus párrafos en el HTML, y en tu CSS dale un color de fondo único, un poco de relleno con `padding` y esquinas redondeadas con `border-radius`. 
  > 
  > Segundo, busca la lista `<ul>` o los elementos `<li>` y cámbiales el color para que combinen con tu estilo. 
  > 
  > ¡Comparte cómo quedó tu diseño en los comentarios o en el servidor de Discord! Nos vemos en el próximo video donde aprenderemos a centrar todo y crear tarjetas con bordes increíbles."

---

## Código Completo del Proyecto (Starter Kit)

### Panel HTML
```html
<h1 id="titulo-principal">Perfil de Creador Digital</h1>
<p class="destacado">¡Hola! Me apasiona la tecnología, la música y el diseño de mundos virtuales.</p>
<p>Aquí comparto mis aprendizajes creando páginas desde cero con HTML y CSS.</p>
<h2>Mis Pasatiempos</h2>
<ul>
  <li>Escuchar música electrónica y rock</li>
  <li>Aprender programación web</li>
  <li>Dibujo digital</li>
</ul>
```

### Panel CSS
```css
/* 1. Selector de etiqueta: aplica a todo el cuerpo de la página */
body {
  background-color: #1e1e2e; /* Color de fondo oscuro */
  color: #cdd6f4;            /* Color de texto claro */
  font-family: 'Segoe UI', Tahoma, sans-serif; /* Tipo de fuente */
  line-height: 1.6;          /* Espaciado entre líneas */
}

/* 2. Selector de ID (#): aplica a un elemento único */
#titulo-principal {
  color: #89b4fa;
  font-size: 36px;
}

/* 3. Selector de etiqueta para subtítulos */
h2 {
  color: #f9e2af;
  font-size: 24px;
}

/* 4. Selector de Clase (.): aplica a elementos con class="destacado" */
.destacado {
  background-color: #313244;
  color: #a6e3a1;
  font-size: 18px;
}
