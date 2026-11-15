# Guion de Grabación – Lección 4: Introducción a CSS

**Duración:** 10:06  
**Herramienta en línea:** CodePen  
**Video (No listado):** `https://youtu.be/u8W6fZHI9uI`  
**Archivo base:** `starter-files/leccion4-starter.html`  
**Ejemplo terminado:** `completed-examples/leccion4-completo.html`

---

## Bloque 1 – Bienvenida y qué es CSS (~0:00 – 2:00)

> "¡Hola! Bienvenido a la lección 4. En las lecciones anteriores aprendimos a escribir HTML: títulos, párrafos, listas, imágenes y enlaces. Nuestra página ya tiene contenido, pero se ve muy simple, ¿verdad?
>
> Hoy vamos a darle estilo con **CSS**. Recuerda la comparación de la casa: HTML es la estructura, las paredes y las habitaciones; CSS es la decoración, los colores, los muebles y la distribución.
>
> CSS significa *Cascading Style Sheets*, o en español, hojas de estilo en cascada. Con CSS le decimos al navegador cómo debe verse cada elemento de la página."

---

## Bloque 2 – Selectores, propiedades y valores (~2:00 – 4:30)

> "Una regla de CSS tiene tres partes. Primero el **selector**, que indica a qué elemento le vamos a dar estilo, por ejemplo `body` o `h1`. Después, entre llaves, escribimos la **propiedad**, que es lo que queremos cambiar, por ejemplo `color`. Y por último el **valor**, que es cómo lo queremos, por ejemplo `blue`.
>
> Se escribe así: `h1 { color: blue; }`. Fíjate en los dos puntos entre la propiedad y el valor, y en el punto y coma al final. Ese punto y coma es muy importante: si lo olvidas, la regla puede dejar de funcionar.
>
> También podemos seleccionar elementos por su **clase**. En nuestro HTML el contenido está dentro de un `div` con `class="perfil"`. Para darle estilo a esa clase, escribimos un punto antes del nombre: `.perfil { ... }`."

---

## Bloque 3 – Colores, fuentes y fondo (~4:30 – 6:30)

> "Abre el enlace de CodePen que está en la descripción. Ya tiene el HTML listo y una zona vacía para el CSS.
>
> **Paso 1.** Vamos a cambiar el fondo de toda la página. Escribimos el selector `body` y dentro `background-color: #eaf4ff;` y `font-family: Arial, sans-serif;`. Los colores pueden escribirse con su nombre, como `blue`, o con un código que empieza con `#`, como `#eaf4ff`. Mira cómo cambió toda la página al instante."

---

## Bloque 4 – La tarjeta: espacio, bordes y centrado (~6:30 – 8:30)

> "**Paso 2.** Ahora le damos estilo a la tarjeta con el selector `.perfil`.
>
> - `background-color: white;` pone el fondo blanco.
> - `padding: 20px;` crea espacio *dentro* de la tarjeta, entre el borde y el texto.
> - `margin: 40px auto;` crea espacio *fuera* de la tarjeta; el valor `auto` en los lados la centra en la página.
> - `max-width: 400px;` evita que la tarjeta se estire demasiado.
> - `text-align: center;` centra el texto.
> - `border: 2px solid #2563eb;` dibuja un borde azul de 2 píxeles.
> - `border-radius: 12px;` redondea las esquinas.
>
> **Paso 3.** Para terminar, cambiamos el color del título con `h1 { color: #2563eb; }` y el de los párrafos con `p { color: #444444; }`."

---

## Bloque 5 – Reto práctico y cierre (~8:30 – 10:06)

> "¡Llegó tu turno! **Pausa el video por 3 minutos**, abre el enlace de CodePen de la descripción y haz tres cosas:
> 1. Cambia el color del título.
> 2. Cambia el color de fondo de la página.
> 3. Cambia el color y el grosor del borde de la tarjeta.
>
> Si quieres experimentar, prueba con `border-radius: 30px;` o con otro tamaño de letra usando `font-size`.
>
> ¡Genial! Ya sabes cómo darle estilo a una página. En la **lección 5** vamos a combinar HTML y CSS para crear una página de perfil personal completa. ¡Nos vemos en el próximo video!"
