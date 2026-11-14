# Guion de Grabación – Lección 2: Introducción a HTML

**Duración:** 5:55  
**Herramienta en línea:** CodePen (`https://codepen.io/cursoweb-html/pen/ByWEaPY?editors=1000`)  
**Video (No listado):** `https://www.youtube.com/watch?v=4hkSICE5we8`

---

## Bloque 1 – Bienvenida y Anatomía de una Etiqueta (~0:00 – 1:15)

> "¡Hola! Bienvenido a la lección 2 del curso de desarrollo web. En la lección anterior vimos de qué están hechas las páginas de internet y que HTML es el encargado de darle estructura y contenido a todo lo que leemos. Hoy vamos a aprender a escribir nuestras primeras líneas de HTML desde cero, sin instalar nada, usando solo nuestro navegador y CodePen.
>
> Para entender HTML, imagina que le estás dando instrucciones a un robot muy literal. No basta con escribir texto suelto; tienes que decirle qué es cada cosa: esto es un título, esto es un párrafo, esto es una imagen. Y para eso usamos **etiquetas**.
>
> Mira la imagen en pantalla. Casi todas las etiquetas en HTML vienen en pareja, como si fueran las tapas de un sándwich o un par de paréntesis. Primero va la **etiqueta de apertura**, encerrada entre los signos menor que y mayor que, por ejemplo `<p>`. En el medio va el **contenido**, que es el texto real que verá la persona que visite tu página, como "Hola mundo". Y al final va la **etiqueta de cierre**, que es igual a la primera, pero lleva una **barra inclinada `/`** justo después del primer signo, así: `</p>`. Esa barra le avisa al navegador: *hasta aquí llega este elemento*. Nunca olvides esa barra, porque dentro de un momento veremos qué pasa si te la saltas."

---

## Bloque 2 – La Estructura Básica de toda página (~1:15 – 3:15)

> "Ahora que sabemos cómo funciona una etiqueta, veamos el **esqueleto básico** que tiene prácticamente cualquier página web profesional en internet.
>
> En la primera línea siempre escribimos `<!DOCTYPE html>`. Esto no es una etiqueta normal que requiera cierre; es simplemente un aviso en la puerta que le dice al navegador: *oye, este documento usa HTML5 moderno, léelo con las reglas actuales*.
>
> Justo debajo abrimos la etiqueta `<html>` y, si te fijas abajo del todo, la cerramos con `</html>`. Todo nuestro código vivirá dentro de esta pareja. Además, le añadimos un detalle llamado **atributo**: `lang="es"`. Los atributos dan información extra dentro de la etiqueta de apertura. En este caso, `lang` viene de *language* (idioma) y `"es"` indica español. Eso ayuda a Google y a los traductores automáticos a saber en qué idioma está escrita tu página.
>
> Dentro de `<html>` dividimos la página en dos grandes partes, igual que una persona: la cabeza y el cuerpo. Primero está el `<head>`, o cabeza. Piensa en el `<head>` como el cerebro o la ficha técnica invisible: lo que pongas aquí **no aparece dentro de la hoja blanca de la página**, pero el navegador lo necesita. Por ejemplo, ahí colocamos `<meta charset="UTF-8">`, una etiqueta especial que no necesita cierre y sirve para que tu página muestre bien las tildes, las eñes y los emojis sin símbolos raros. Y también ponemos `<title>Mi primera página</title>`, que es el texto que aparece arriba en la pestaña del navegador.
>
> Debajo del cierre `</head>` viene el `<body>`, o cuerpo. Y aquí está la regla de oro: **todo lo que quieras que el usuario vea, lea o toque en la pantalla debe ir obligatoriamente dentro de `<body>` y `</body>`**."

---

## Bloque 3 – Títulos `<h1>`, Párrafos `<p>` y Error Común (~3:15 – 5:00)

> "Hagamos que nuestra página cobre vida escribiendo dentro del `<body>`.
>
> Primero queremos un título grande de bienvenida. En HTML los encabezados se llaman `h` (de *heading* en inglés) y van del `<h1>` al `<h6>`, siendo `<h1>` el título principal más importante y grande de la página. Así que escribimos `<h1>¡Hola, mundo!</h1>`.
>
> Debajo queremos presentarnos con dos ideas separadas. Si escribiéramos todo en un bloque sin etiquetas, HTML juntaría el texto en una sola línea amontonada. Para ordenarlo usamos la etiqueta `<p>`, de *paragraph* o párrafo. Escribimos `<p>Me llamo Sofía y estoy aprendiendo desarrollo web.</p>` y en la siguiente línea otro párrafo: `<p>Me apasionan los videojuegos y la robótica.</p>`.
>
> Fíjate cómo al instante, en la parte inferior de CodePen, el navegador interpreta nuestras etiquetas: el `<h1>` sale grande y en negrita, y cada `<p>` aparece en su propia línea con un espacio limpio entre ellos.
>
> Ahora un truco de depuración muy común para principiantes: ¿qué pasa si por accidente borro la barra `/` o me olvido cerrar `</h1>`? Mira lo que ocurre en la vista previa: el navegador cree que **todo lo que sigue sigue siendo parte del título**, así que tus párrafos también se vuelven gigantes y en negrita. Por eso, cuando algo se vea raro en tu web, lo primero que debes revisar es si cerraste bien tus etiquetas."

---

## Bloque 4 – Reto Práctico y Cierre (~5:00 – 5:55)

> "La mejor forma de aprender código es escribiéndolo tú mismo, así que ¡llegó tu turno de practicar!
>
> En la descripción de este video te dejamos el enlace directo al proyecto en CodePen con la plantilla ya lista, sin necesidad de crearte una cuenta ni descargar ningún programa.
>
> Cuando termines de escuchar esto, **pausa el video por 3 minutos**, abre ese enlace y haz tres cosas:
> 1. Cambia el `<title>` por un nombre divertido para tu pestaña.
> 2. Modifica el `<h1>` para poner tu propio saludo o tu nombre.
> 3. Edita los dos párrafos `<p>` contando cuáles son tus pasatiempos, música o videojuegos favoritos. Y si quieres experimentar, prueba añadir un tercer `<p>` debajo o cambiar el `<h1>` por un `<h2>` para ver cómo cambia el tamaño.
>
> ¿Ya lo probaste? ¡Genial, acabas de escribir tu primera página web real! En la **lección 3** llevaremos esta misma página al siguiente nivel aprendiendo a agregar listas ordenadas, imágenes y enlaces a tus sitios favoritos. ¡Nos vemos en el próximo video!"
