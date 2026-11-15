# Guion de grabación: Lección 3

**Tema:** Añadir más elementos HTML.

**Público:** Estudiantes de 12 a 17 años sin experiencia.

**Duración prevista:** 8 a 10 minutos; ajustar con un ensayo.

**Herramienta para la demostración:** CodePen en el navegador.

**Resultado:** Una página con tres pasatiempos, una imagen con descripción y un enlace.

## Preparación

- Plantilla: [leccion3-starter.html](../starter-files/leccion3-starter.html).
- Referencia terminada: [leccion3-completo.html](../completed-examples/leccion3-completo.html).
- Para CodePen, copiar solo lo que está entre `<body>` y `</body>` al panel HTML. No pegar las etiquetas `body` ni la cabecera del documento. Dejar CSS y JavaScript vacíos.
- Mostrar el código y su vista previa. Escribir los ejemplos por partes mientras se explica su efecto.
- Los tiempos incluyen escritura y demostración. El texto es una ayuda para hablar con naturalidad, no una duración garantizada.

## Bloque 1: Lo que construiremos (0:00 a 1:00)

**Pantalla y acciones:** Mostrar brevemente el ejemplo terminado. Cambiar a la plantilla con el título y los párrafos de la lección anterior.

**Texto en pantalla:** «Listas + imágenes + enlaces».

**Voz:**

> ¡Hola! En la lección anterior aprendimos a crear títulos y párrafos. Hoy vamos a continuar esa página con tres cosas que vemos todos los días en internet: listas, imágenes y enlaces.
>
> Imagina una página sobre tus pasatiempos. Puedes escribir un párrafo sobre ellos, pero también puedes organizarlos en una lista, añadir una imagen y dejar un enlace para aprender más. Eso es lo que construiremos juntos.
>
> Solo necesitas tu navegador. Abre la práctica que está en la descripción. A la izquierda tenemos el código HTML y, al lado, el resultado. Puedes pausar el video cuando necesites más tiempo. Empezamos con el título y los párrafos que ya conocemos.

## Bloque 2: Una lista de pasatiempos (1:00 a 3:15)

**Pantalla y acciones:** Escribir primero el encabezado y una lista con un solo elemento. Esperar a que se actualice la vista previa. Añadir los otros dos elementos. Señalar qué apertura corresponde a cada cierre.

```html
<h2>Mis actividades favoritas</h2>
<ul>
  <li>Jugar videojuegos</li>
  <li>Escuchar música</li>
  <li>Construir robots</li>
</ul>
```

**Texto en pantalla:** «ul = lista con viñetas» y «li = un elemento de la lista».

**Voz:**

> Primero escribimos un subtítulo con h2: Mis actividades favoritas. El h1 sigue siendo el título principal. Este h2 anuncia una parte de nuestra página.
>
> Ahora piensa en una lista de compras. Cada producto ocupa su propia línea. Para organizar nuestros pasatiempos de esa manera usamos ul. Es una lista sin orden numérico: aquí no estamos diciendo cuál actividad va primero o cuál es mejor.
>
> Dentro escribimos li. Cada li representa un elemento de la lista. Voy a escribir Jugar videojuegos y cerrar con barra, li. Mira la vista previa: ya apareció una viñeta. No tuve que escribir ese punto, el navegador lo añadió.
>
> Agreguemos dos elementos más: Escuchar música y Construir robots. Cada uno tiene su propia apertura y cierre. Todos están dentro de la misma lista ul.
>
> Los espacios al principio de estas líneas nos ayudan a leer el código. Vemos que los tres elementos pertenecen a la lista. No son esos espacios los que crean las viñetas: son las etiquetas.
>
> Hagamos un cambio. Voy a reemplazar Construir robots por Dibujar personajes. El código cambia aquí y la página se actualiza allá. Para personalizar tu lista, puedes cambiar esos textos. ¿Qué escribirías tú? Si quieres una cuarta actividad, añade otro li antes del cierre de ul.

**Demostración:** Cambiar el tercer pasatiempo y volver a «Construir robots», para que el resultado coincida con la referencia.

### Ampliación breve de las listas

El PDF pide listas y menciona ul en el ejemplo de la lección 3. La lista ordenada dentro de un pasatiempo es una ampliación breve. Dedicar unos 45 a 60 segundos, ajustando el ensayo para mantener la lección entre 8 y 10 minutos.

**Pantalla y acciones:** Conservar los tres pasatiempos: Jugar videojuegos, Escuchar música y Construir robots. Dentro del li Jugar videojuegos, añadir una lista ol con los juegos favoritos en orden de preferencia. Este es el código conjunto al terminar el bloque de listas:

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
```

**Voz:**

> Nuestra lista de pasatiempos usa ul porque no estamos indicando un orden. Dentro de Jugar videojuegos voy a añadir mis juegos favoritos por preferencia: primero Mario Bros, después Sonic y luego Legend of Zelda.
>
> Para numerarlos usamos ol, de ordered list, que significa lista ordenada. Cada juego sigue siendo un li, un elemento de la lista. El navegador añade los números uno, dos y tres.
>
> Esta lista de juegos pertenece a Jugar videojuegos. Por eso colocamos ol dentro de ese li y lo cerramos antes de pasar a Escuchar música. Construir robots se queda como nuestro tercer pasatiempo.

**Transición:** Después del cierre de la lista principal ul, continuar con el h2 Mi espacio para crear y la imagen del siguiente bloque.

## Bloque 3: Una imagen y su descripción (3:15 a 5:30)

**Pantalla y acciones:** Escribir el subtítulo. Añadir `img` por partes: primero `src`, luego `alt`. Explicar las comillas y mostrar la imagen. Añadir las dimensiones al final como detalle breve.

```html
<h2>Mi espacio para crear</h2>
<img
  src="https://placehold.co/320x180/png?text=Mi+zona+creativa"
  alt="Recuadro con el texto Mi zona creativa"
  width="320"
  height="180"
>
```

**Texto en pantalla:** «src = dirección de la imagen» y «alt = descripción de la imagen».

**Voz:**

> Ya tenemos una lista. Ahora agreguemos una imagen debajo. Escribimos otro subtítulo: Mi espacio para crear. Después usamos img, que sirve para insertar una imagen.
>
> Esta etiqueta necesita información extra. Esa información se escribe con atributos. El primero es src: indica dónde está la imagen. Piensa en él como una dirección que el navegador sigue para encontrarla. Escribimos src, el signo igual y la dirección entre comillas.
>
> Para este ejercicio usamos una imagen sencilla que dice Mi zona creativa. Puedes copiar su dirección desde la plantilla. Si usas otra imagen, necesitas una dirección que entregue la imagen, no la dirección de una página que contiene muchas fotos.
>
> El siguiente atributo es alt. Aquí describimos el contenido: Recuadro con el texto Mi zona creativa. Esta descripción ayuda a las personas que usan lectores de pantalla. El navegador también puede mostrarla si la imagen no carga.
>
> Por eso, si cambias la imagen por un robot, debes cambiar la descripción. Puedes escribir, por ejemplo, Robot pequeño sobre una mesa, si eso es lo que muestra. Poner solamente imagen o foto no ayuda mucho a entender su contenido.
>
> Fíjate en un detalle: img no lleva cierre. No escribimos barra img. Es un elemento vacío, porque no contiene texto ni otras etiquetas dentro. Existen otros elementos vacíos en HTML; img es el que necesitamos hoy.
>
> Añadimos width y height para indicar sus dimensiones en píxeles: 320 de ancho y 180 de alto. Para esta práctica usamos esos valores. En la siguiente lección veremos cómo CSS nos ayuda a cambiar la apariencia de una página.

## Bloque 4: Un enlace para explorar (5:30 a 7:30)

**Pantalla y acciones:** Escribir el párrafo y el enlace. Señalar la diferencia entre dirección y texto visible. Pulsar el enlace desde la vista previa y regresar al editor.

```html
<p>
  Para descubrir nuevos temas, visita
  <a href="https://es.wikipedia.org/" target="_blank" rel="noopener">
    Wikipedia en español
  </a>.
</p>
```

**Texto en pantalla:** «href = destino del enlace» y «Entre a y /a va el texto visible».

**Voz:**

> Nuestra página ya muestra información. ¿Cómo hacemos para que una persona pueda ir desde aquí a otro sitio? Con un enlace. La etiqueta que usamos se llama a.
>
> Dentro de su apertura escribimos href, igual y la dirección entre comillas. Este atributo indica el destino. En este caso usaremos Wikipedia en español.
>
> Entre la apertura y el cierre de a ponemos el texto que verá el visitante: Wikipedia en español. Ese texto puede ser diferente de la dirección. Conviene que diga adónde lleva el enlace, para que la persona sepa qué va a abrir.
>
> Vamos a probarlo en la vista previa. Pulso Wikipedia en español y se abre la página. Ya conectamos nuestro pequeño proyecto con otro sitio de internet.
>
> Agregamos target con el valor guion bajo blank para pedir que el destino se abra en otra pestaña. Así podemos mantener nuestra práctica abierta. También añadimos rel con el valor noopener, para que la página nueva no tenga acceso a la ventana que la abrió. Puedes copiar estos dos atributos del ejemplo. Lo principal de hoy es recordar que href indica el destino.
>
> Si no añades target, normalmente el enlace abre en el mismo marco o pestaña. Y si no funciona, revisa la dirección, las comillas y que hayas escrito href. Para una imagen usamos src; para el destino de un enlace usamos href.

## Bloque 5: Tu turno y cierre (7:30 a 8:30)

**Pantalla y acciones:** Mostrar la página terminada. Señalar una lista, la imagen y el enlace. Mostrar el reto durante cinco segundos; la práctica la realiza el estudiante al pausar.

**Texto en pantalla:**

> PAUSA Y PRACTICA
>
> 1. Escribe tres pasatiempos en una lista.
> 2. Añade una imagen con una descripción alt adecuada.
> 3. Añade un enlace y comprueba que abre el destino correcto.

**Voz:**

> Repasemos nuestra página. Con ul y li organizamos una lista. Con img mostramos una imagen: src indica su dirección y alt describe su contenido. Con a creamos un enlace y href indica adónde lleva.
>
> Ahora te toca practicar. Abre el enlace de la descripción y personaliza los tres pasatiempos. Añade una imagen y una descripción que coincida con ella. Por último, crea un enlace a una página que te interese, con un texto que explique el destino.
>
> Pausa el video y dedica unos tres minutos a probarlo. Puedes tomarte más tiempo si lo necesitas. Antes de terminar, revisa que aparezcan las tres viñetas, que cargue la imagen y que funcione el enlace.
>
> Si algo falla, vuelve al ejemplo y compara una línea a la vez. Ya sabes añadir más contenido a tu página. En la próxima lección aprenderemos a darle colores y estilo con CSS. ¡Nos vemos!

## Cuidados técnicos para la explicación

- Distinguir ul (viñetas), ol (numeración) y li (elemento). Presentar ol y la lista interior como una ampliación breve.
- No decir que img es la única etiqueta sin cierre.
- No presentar alt como un texto que aparece al pasar el cursor.
- No confundir href con src.
- No añadir estilos CSS ni JavaScript en esta demostración.
- No introducir nombres del expositor, códigos de estudiante o marcas del equipo en el contenido grabado.
