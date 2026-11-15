
# Fundamentos de Desarrollo Web

## Resumen del Curso

¡Bienvenido a nuestro curso de desarrollo web!

Este curso está dirigido a estudiantes de secundaria que desean aprender a crear sus primeras páginas web utilizando HTML y CSS.

A través de seis lecciones aprenderás cómo funcionan los sitios web, cómo organizar su contenido y cómo personalizar su apariencia. Al finalizar, podrás crear tu propia página de perfil.

**Duración total:** 60 minutos

**Público objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación.

**Prerrequisitos:** Ninguno.

**Herramientas necesarias:** Un navegador web y CodePen, una herramienta gratuita en línea que permite escribir HTML y CSS sin instalar programas.

**Repositorio de código fuente:** [webdev-course](https://github.com/upc-pre-202620-1asi0730-8084-Developers/webdev-course)

---

## Secuencia de Lecciones

### Lección 1: ¿Qué es el desarrollo web? (5 minutos)

**Descripción:** Conoceremos qué es una página web, cómo funciona Internet y para qué sirven HTML y CSS. También identificaremos ejemplos de sitios web que utilizamos diariamente.

**Objetivos de aprendizaje:**
- Comprender qué es el desarrollo web.
- Diferenciar HTML y CSS.
- Reconocer ejemplos de páginas web.

**Conceptos principales:**
- Sitios web.
- Navegadores web.
- Frontend y backend.
- HTML: estructura y contenido.
- CSS: apariencia y diseño.

**Ejemplo:** Compararemos una página web con una casa: HTML representa su estructura y CSS se encarga de su decoración.

**Video:** [Pendiente de grabación]

**Actividad:** Identifica tres páginas web que utilizas frecuentemente y observa cómo están organizadas.

---

### Lección 2: Introducción a HTML (6 minutos)

**Descripción:** Aprenderemos qué es HTML y cómo utilizar etiquetas para organizar el contenido de nuestra primera página web.

**Objetivos de aprendizaje:**
- Comprender la estructura básica de HTML.
- Reconocer etiquetas, elementos y atributos.
- Crear títulos y párrafos.

**Conceptos principales:**
- Etiquetas HTML.
- Elementos y atributos.
- Estructura HTML.
- Encabezados y párrafos.

**Código de ejemplo:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi primera página</title>
</head>
<body>
    <h1>¡Hola, mundo!</h1>
    <p>Me llamo Sofía y estoy aprendiendo desarrollo web.</p>
    <p>Me apasionan los videojuegos y la robótica.</p>
</body>
</html>
```

**Video:** [Ver Lección 2 (5:55)](https://www.youtube.com/watch?v=4hkSICE5we8)

**Práctica en CodePen:** [Clic para programar](https://codepen.io/cursoweb-html/pen/ByWEaPY?editors=1000)

**Archivo base:** [`starter-files/leccion2-starter.html`](starter-files/leccion2-starter.html)  
**Ejemplo terminado:** [`completed-examples/leccion2-completo.html`](completed-examples/leccion2-completo.html)

**Reto práctico:** Modifica el título y los párrafos utilizando tu nombre y tus intereses.

---

### Lección 3: Añadir más elementos HTML (8 minutos)

**Descripción:** Aprenderemos a mejorar nuestras páginas agregando listas, imágenes y enlaces.

**Objetivos de aprendizaje:**
- Crear listas de elementos.
- Insertar imágenes.
- Agregar enlaces hacia otras páginas.

**Conceptos principales:**
- Listas con viñetas: `<ul>` y `<li>`.
- Ampliación breve: listas numeradas con `<ol>` y listas dentro de un `<li>`.
- Imágenes: `<img>`.
- Enlaces: `<a>`.
- Atributos `src`, `alt` y `href`.

**Código de ejemplo:**

```html
<h2>Mis actividades favoritas</h2>
<ul>
  <li>
    Jugar videojuegos
    <ol>
      <li>Mario Bros</li>
      <li>Sonic</li>
      <li>Legend of Zelda</li>
    </ol>
  </li>
  <li>Escuchar música</li>
  <li>Construir robots</li>
</ul>

<h2>El robot deseado</h2>
<img src="https://www.infobae.com/resizer/v2/AWR5GN3IYREQVHYM22WCQFYACE.png?auth=e519c915660f123c03cc4c3414fba9c4d6fe8ae0ae2d55573b20120bd41d75c3&amp;smart=true&amp;width=1200&amp;height=900&amp;quality=85"
     alt="Robot con forma de pato"
     width="320"
     height="240">

<p>
    Para conocer este robot, lee
    <a href="https://www.infobae.com/tecno/2026/10/24/los-robots-pato-de-nvidia-que-duermen-y-juegan-tuvieron-20000-pedidos-de-preventa-en-un-dia/" target="_blank" rel="noopener">
        la noticia del robot pato en Infobae
    </a>.
</p>
```

**Video:** [Pendiente de grabación]

**Práctica en CodePen:** [Pendiente de crear]

**Material de la lección:**
- [Plantilla inicial](starter-files/leccion3-starter.html).
- [Ejemplo terminado](completed-examples/leccion3-completo.html).
- [Guion con acciones, tiempos y narración](scripts/leccion3-guion.md).
- [Cuatro preguntas de autoevaluación](scripts/leccion3-cuestionario.md).

**Uso en CodePen:** Copia al panel HTML solamente el contenido entre `<body>` y `</body>` de la plantilla. Deja CSS y JavaScript vacíos. El enlace precargado de la práctica se añadirá cuando esté guardado y probado.

**Duración de grabación prevista:** 8 a 10 minutos, según el ensayo.

**Alcance de las listas:** El enunciado pide listas y su ejemplo menciona `<ul>`. Las listas numeradas y anidadas se incluyen como una ampliación breve para distinguir el contenedor (`<ul>` o `<ol>`) de cada elemento (`<li>`). Una lista interior debe estar dentro del `<li>` al que pertenece.

**Reto práctico:** Crea una lista con tres pasatiempos favoritos, agrega una imagen con una descripción `alt` adecuada y un enlace con texto claro. Pausa el video para practicar y comprueba el resultado.

---

### Lección 4: Introducción a CSS (12 minutos)

**Descripción:** Aprenderemos a utilizar CSS para cambiar los colores, las fuentes, los bordes y la distribución de los elementos de una página web.

**Objetivos de aprendizaje:**
- Comprender qué es CSS.
- Utilizar selectores, propiedades y valores.
- Personalizar elementos HTML.

**Conceptos principales:**
- Selectores CSS.
- Propiedades y valores.
- Colores y fondos.
- Fuentes y tamaños.
- Márgenes, bordes y alineación.

**Código HTML de ejemplo:**

```html
<div class="perfil">
    <h1>Mi rincón creativo</h1>
    <p>Bienvenido a mi primera página con CSS.</p>
    <p>Me encanta aprender cosas nuevas.</p>
</div>
```

**Código CSS de ejemplo:**

```css
body {
    background-color: #eaf4ff;
    font-family: Arial, sans-serif;
}

.perfil {
    background-color: white;
    padding: 20px;
    margin: 40px auto;
    max-width: 400px;
    text-align: center;
    border: 2px solid #2563eb;
    border-radius: 12px;
}

h1 {
    color: #2563eb;
}

p {
    color: #444444;
}
```

**Video:** [Pendiente de grabación]

**Práctica en CodePen:** [Pendiente de crear]

**Reto práctico:** Cambia el color del título, el fondo y el borde de tu página.

---

### Lección 5: Crear una página web sencilla (15 minutos)

**Descripción:** Aplicaremos lo aprendido en HTML y CSS para construir una página de perfil personal.

**Objetivos de aprendizaje:**
- Combinar HTML y CSS.
- Crear una tarjeta de presentación.
- Personalizar una página web.

**Proyecto:** Mi Perfil Digital.

**Código HTML:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="tarjeta-perfil">
        <img
            src="https://placehold.co/150x150"
            alt="Foto de perfil"
            class="foto-perfil"
        >

        <h1>¡Hola, soy Sofía!</h1>

        <p>Estudiante de secundaria</p>

        <h2>Sobre mí</h2>

        <p>
            Me gusta la tecnología, el dibujo
            y aprender a crear páginas web.
        </p>

        <h2>Mis pasatiempos</h2>

        <ul>
            <li>Escuchar música</li>
            <li>Dibujar</li>
            <li>Jugar videojuegos</li>
        </ul>

        <a href="https://www.wikipedia.org" target="_blank">
            Mi página favorita
        </a>
    </div>

</body>
</html>
```

**Código CSS:**

```css
body {
    background-color: #eaf4ff;
    font-family: Arial, sans-serif;
}

.tarjeta-perfil {
    background-color: white;
    max-width: 350px;
    padding: 25px;
    margin: 40px auto;
    text-align: center;
    border-radius: 15px;
    box-shadow: 0 4px 10px #cccccc;
}

.foto-perfil {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid #2563eb;
}

h1 {
    color: #2563eb;
}

h2 {
    color: #444444;
}

p {
    color: #555555;
}

ul {
    text-align: left;
}

a {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #2563eb;
    color: white;
    text-decoration: none;
    border-radius: 8px;
}
```

**Video:** [https://youtu.be/g07elFqfz8E](https://youtu.be/g07elFqfz8E)

**Proyecto en CodePen:** [https://codepen.io/editor/Elizabeth-Apaza-the-decoder/pen/01a1dbf6-c3b5-72d7-8baa-904846895597](https://codepen.io/editor/Elizabeth-Apaza-the-decoder/pen/01a1dbf6-c3b5-72d7-8baa-904846895597)]

**Reto práctico:** Personaliza tu perfil utilizando tu nombre, tus pasatiempos y tus colores favoritos.

---

### Lección 6: Consejos, errores comunes y próximos pasos (10 minutos)

**Descripción:** Revisaremos los errores más comunes al escribir HTML y CSS y aprenderemos cómo solucionarlos.

**Objetivos de aprendizaje:**
- Identificar errores frecuentes.
- Corregir problemas básicos.
- Conocer recursos para seguir aprendiendo.

**Errores comunes:**

**1. No cerrar etiquetas HTML**

Incorrecto:

```html
<h1>Hola, mundo
```

Correcto:

```html
<h1>Hola, mundo</h1>
```

**2. Escribir incorrectamente un selector CSS**

Incorrecto:

```css
titulo {
    color: blue;
}
```

Correcto, para una clase llamada `titulo`:

```css
.titulo {
    color: blue;
}
```

**3. Olvidar el atributo `alt` en las imágenes**

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

**4. No colocar el punto y coma en CSS**

```css
h1 {
    color: blue;
    font-size: 24px;
}
```

**5. Escribir incorrectamente los nombres de las etiquetas**

```html
<title>Mi página</title>
```

**Video:** [Pendiente de grabación]

**Práctica en CodePen:** [Pendiente de crear]

**Actividad final:** Revisa tu página de perfil, identifica posibles errores y realiza mejoras.

**Próximos pasos:**
- Seguir practicando HTML y CSS.
- Aprender sobre diseño adaptable.
- Introducirse a JavaScript.
- Explorar la documentación de MDN Web Docs.

---

## Recursos Adicionales

**Editor de código:** https://codepen.io/

**Documentación HTML:** https://developer.mozilla.org/es/docs/Web/HTML

**Documentación CSS:** https://developer.mozilla.org/es/docs/Web/CSS

**Repositorio GitHub:** [webdev-course](https://github.com/upc-pre-202620-1asi0730-8084-Developers/webdev-course)

---

## Elaboración del Equipo

**Universidad:** Universidad Peruana de Ciencias Aplicadas

**Carrera:** Ingeniería de Software

**Curso:** Aplicaciones Web (1ASI0730)

**Ciclo académico:** 202620

**NRC:** [Completar]

**Nombre del equipo:** [Completar]

**Team Leader:** [Completar]

**Integrantes:**
- [Integrante 1]
- [Integrante 2]
- [Integrante 3]
- [Integrante 4]
- [Integrante 5]

**Fecha de entrega:** [Completar]
