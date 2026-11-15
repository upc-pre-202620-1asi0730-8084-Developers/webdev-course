
# Guion de Grabación — Lección 6: Consejos y Próximos Pasos

**Duración:** ~10:00  
**Herramienta en línea:** CodePen  
**Video (No listado):** https://youtu.be/cxNP9bcKNB8 
**Archivo base:** `starter-files/leccion6-starter.html`  
**Ejemplo terminado:** `completed-examples/leccion6-completo.html`

---

## Bloque 1 — Bienvenida e introducción (~0:00 - 0:55)

> ¡Hola! Bienvenidos a la sexta y última lección de nuestro curso de desarrollo web.
>
> A lo largo de estas lecciones hemos aprendido cómo funcionan las páginas web, cómo utilizar HTML para organizar su contenido y cómo aplicar CSS para mejorar su apariencia.
>
> Además, en la lección anterior pusimos en práctica todo lo aprendido creando nuestra propia página de perfil personal.
>
> Sin embargo, cuando comenzamos a programar, es bastante normal cometer algunos errores. Por ejemplo, puede suceder que un título aparezca de manera incorrecta, que un color no cambie o que una imagen no se muestre como esperábamos.
>
> Pero no te preocupes, porque equivocarse también forma parte del aprendizaje.
>
> Por eso, en esta última lección vamos a revisar cinco errores bastante comunes al utilizar HTML y CSS. Aprenderemos cómo identificarlos, cómo corregirlos y también veremos algunos consejos para seguir mejorando nuestras páginas web.
>
> ¡Así que comencemos!

---

## Bloque 2 — Error 1: No cerrar correctamente las etiquetas HTML (~0:55 - 2:10)

> Vamos a comenzar con uno de los errores más frecuentes cuando estamos aprendiendo HTML: olvidarnos de cerrar correctamente una etiqueta.
>
> Como recordarán, muchas etiquetas HTML tienen una apertura y un cierre. Por ejemplo, cuando utilizamos la etiqueta h1 para crear un título, debemos indicar dónde comienza y dónde termina.
>
> Aquí tenemos un pequeño ejemplo donde queremos mostrar un título que diga "Hola, mundo" y, debajo, un párrafo de bienvenida.
>
> Sin embargo, si observamos nuestro código, podemos notar que hemos olvidado cerrar la etiqueta del título.
>
> ¿Y qué sucede entonces? Bueno, el navegador intenta interpretar nuestro código de todas maneras, pero el resultado puede ser diferente de lo que esperábamos. En este caso, el párrafo puede terminar mostrándose como parte del encabezado.
>
> Para solucionarlo, simplemente agregamos la etiqueta de cierre correspondiente, utilizando una barra inclinada antes del nombre de la etiqueta.
>
> Y ahora sí, podemos observar que nuestro título y nuestro párrafo se muestran correctamente.
>
> Entonces, como primer consejo, recuerda siempre revisar que las etiquetas que necesitan un cierre estén escritas correctamente.

---

## Bloque 3 — Error 2: Escribir incorrectamente los selectores CSS (~2:10 - 3:35)

> Pasemos ahora al segundo error, que está relacionado con CSS.
>
> Como ya aprendimos, CSS nos permite cambiar la apariencia de nuestros elementos HTML. Sin embargo, para aplicar estos estilos, necesitamos indicar correctamente a qué elemento queremos modificar.
>
> Por ejemplo, imaginemos que tenemos un título al que hemos asignado una clase llamada "titulo".
>
> Una clase es básicamente un nombre que podemos utilizar para identificar uno o varios elementos y aplicarles determinados estilos.
>
> En este caso, queremos cambiar el color de nuestro título a azul.
>
> Pero fíjense qué sucede si en CSS escribimos solamente el nombre "titulo", sin colocar ningún símbolo antes.
>
> Como podemos observar, el color no cambia, porque CSS está buscando un elemento llamado "titulo", en lugar de seleccionar nuestra clase.
>
> Para solucionar este problema, simplemente colocamos un punto antes del nombre de la clase.
>
> Y listo, ahora nuestro título cambia correctamente a color azul.
>
> Entonces, recuerda lo siguiente: cuando queremos seleccionar una clase en CSS, debemos colocar un punto antes de su nombre.
>
> Es un detalle bastante pequeño, pero puede hacer una gran diferencia cuando estamos diseñando nuestra página.

---

## Bloque 4 — Error 3: Olvidar el atributo alt en las imágenes (~3:35 - 4:50)

> El tercer error que vamos a revisar está relacionado con las imágenes.
>
> Como vimos en las lecciones anteriores, podemos utilizar la etiqueta img para agregar imágenes a nuestra página web.
>
> Para hacerlo, utilizamos un atributo llamado src, que indica la dirección donde se encuentra la imagen.
>
> Sin embargo, existe otro atributo bastante importante que muchas veces olvidamos agregar, y se llama alt.
>
> Este atributo nos permite escribir una descripción de la imagen. Su función es especialmente importante para la accesibilidad, ya que ayuda a las personas que utilizan lectores de pantalla a comprender el contenido visual.
>
> Además, cuando una imagen no se puede cargar, su texto alternativo puede mostrarse en su lugar.
>
> Entonces, para mejorar nuestro código, simplemente agregamos el atributo alt y escribimos una descripción breve de lo que representa nuestra imagen.
>
> En este caso, hemos escrito "Imagen de ejemplo de una página web".
>
> De esta manera, estamos haciendo que nuestra página sea más accesible y fácil de comprender.
>
> Como consejo, recuerda que no solamente debemos preocuparnos por cómo se ve nuestra página, sino también por que diferentes personas puedan utilizarla correctamente.

---

## Bloque 5 — Error 4: Olvidar el punto y coma en CSS (~4:50 - 6:05)

> Ahora vamos con el cuarto error, que consiste en olvidarnos de separar correctamente las declaraciones de CSS.
>
> En CSS podemos modificar diferentes características de un elemento, como su color, su tamaño o su tipo de letra.
>
> Por ejemplo, aquí queremos que nuestro título tenga un color azul y un tamaño de 24 píxeles.
>
> Sin embargo, si observamos el código, podemos notar que después de indicar el color azul nos hemos olvidado de colocar el punto y coma.
>
> Este símbolo se utiliza para separar las declaraciones dentro de una regla CSS.
>
> Cuando no lo colocamos entre dos propiedades, el navegador puede interpretar incorrectamente nuestras instrucciones y algunos estilos podrían dejar de funcionar.
>
> Para solucionarlo, colocamos un punto y coma después de la primera declaración.
>
> Y ahora podemos observar cómo nuestros estilos se aplican correctamente.
>
> Algo importante es que el punto y coma final de una regla no siempre es obligatorio. Sin embargo, es una buena práctica utilizarlo siempre, porque nos ayuda a mantener nuestro código ordenado y evitar errores cuando agregamos nuevas propiedades.

---

## Bloque 6 — Error 5: Escribir incorrectamente los nombres de las etiquetas (~6:05 - 7:10)

> El quinto error que vamos a revisar ocurre cuando escribimos incorrectamente el nombre de una etiqueta HTML.
>
> Cuando estamos comenzando a programar, es bastante fácil confundirnos con los nombres de algunas etiquetas o escribir alguna letra o número de más.
>
> Por ejemplo, imaginemos que queremos crear el título principal de nuestra página utilizando la etiqueta h1.
>
> Pero, por accidente, escribimos h11, con dos números uno.
>
> ¿Qué ocurre entonces? Bueno, el navegador no reconoce h11 como uno de los encabezados estándar de HTML. Por esa razón, el texto no tendrá el comportamiento normal que esperamos de un título principal.
>
> Para solucionarlo, solamente necesitamos escribir el nombre correcto de la etiqueta, que en este caso es h1.
>
> Y listo, ahora nuestro título aparece correctamente.
>
> Recuerda que HTML tiene etiquetas con funciones específicas. Por ejemplo, h1 se utiliza para un encabezado principal, p para los párrafos e img para las imágenes.
>
> Por eso, cuando algún elemento no se muestre como esperabas, revisa primero que hayas escrito correctamente el nombre de la etiqueta.

---

## Bloque 7 — Actividad final: Revisemos nuestro perfil (~7:10 - 8:30)

> Ahora que ya conocemos estos cinco errores comunes, vamos a realizar una pequeña actividad utilizando el proyecto que desarrollamos en la lección anterior.
>
> Como pueden observar, aquí tenemos nuestra página de perfil personal. Tenemos una imagen, un título de bienvenida, algunos párrafos, una lista con nuestros pasatiempos y un enlace hacia otra página.
>
> También hemos aplicado diferentes estilos CSS para mejorar su apariencia, como los colores, los bordes y la distribución de los elementos.
>
> Lo que vamos a hacer ahora es revisar nuestro código para comprobar que todo esté funcionando correctamente.
>
> Primero, vamos a comprobar que nuestras etiquetas HTML estén correctamente cerradas.
>
> Después, revisaremos que las clases utilizadas en HTML coincidan con los nombres que hemos escrito en CSS.
>
> También verificaremos que nuestras imágenes tengan una descripción apropiada mediante el atributo alt.
>
> Y finalmente, comprobaremos que las propiedades CSS estén escritas correctamente y que los colores, tamaños y demás estilos aparezcan como esperamos.
>
> Como podemos observar, revisar nuestro código es una parte muy importante del desarrollo web, porque nos permite detectar pequeños problemas y mejorar el resultado final.
>
> Ahora te toca a ti. Puedes pausar este video durante unos minutos y revisar tu propia página de perfil.
>
> Intenta identificar algún detalle que puedas mejorar. Por ejemplo, puedes cambiar el color del título, modificar el fondo o agregar un nuevo pasatiempo a tu lista.
>
> Recuerda que no se trata solamente de copiar código, sino también de experimentar y comprender qué sucede cuando realizamos diferentes cambios.

---

## Bloque 8 — Próximos pasos: ¿Qué aprender después? (~8:30 - 9:35)

> Y bueno, ahora que hemos llegado al final de nuestro curso, seguramente te estarás preguntando qué puedes aprender después.
>
> Lo primero que te recomiendo es seguir practicando HTML y CSS. Puedes intentar crear nuevas páginas web, como una página sobre tus videojuegos favoritos, una presentación de tu mascota o incluso una página dedicada a tu deporte favorito.
>
> También puedes comenzar a explorar el diseño adaptable, que consiste en crear páginas web capaces de ajustarse a diferentes tamaños de pantalla, como computadoras, tablets y teléfonos celulares.
>
> Otro tema muy interesante que puedes aprender más adelante es JavaScript.
>
> Mientras que HTML organiza el contenido y CSS modifica su apariencia, JavaScript nos permite agregar comportamientos e interacciones a nuestras páginas web.
>
> Por ejemplo, podemos utilizarlo para crear botones que respondan a nuestros clics, mostrar mensajes o actualizar información sin tener que volver a cargar toda la página.
>
> Finalmente, si en algún momento tienes dudas sobre una etiqueta HTML o una propiedad CSS, puedes consultar MDN Web Docs.
>
> Esta es una documentación gratuita en línea donde encontrarás explicaciones, ejemplos y referencias para continuar aprendiendo sobre desarrollo web.

---

## Bloque 9 — Despedida y cierre del curso (~9:35 - 10:00)

> Y con esto llegamos al final de nuestro curso de fundamentos de desarrollo web.
>
> Durante estas seis lecciones aprendimos a crear contenido utilizando HTML, a personalizar nuestras páginas con CSS y a identificar algunos de los errores más comunes.
>
> Recuerda que lo más importante para seguir mejorando es practicar constantemente, probar nuevas ideas y no tener miedo de equivocarte.
>
> Espero que todo lo aprendido te sirva para continuar explorando el mundo del desarrollo web y crear tus propios proyectos.
>
> ¡Muchas gracias por acompañarnos durante este curso y nos vemos en una próxima oportunidad!
