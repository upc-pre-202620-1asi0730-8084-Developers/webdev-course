# Guion breve de la lección 3

**Tema:** Listas, imágenes y enlaces.

**Duración orientativa:** 6 minutos con escritura y demostraciones. Ensayar y ajustar dentro de los 5 a 15 minutos por lección que pide el enunciado.

Continuar desde el contenido terminado de la lección 2. No volver a explicar títulos, párrafos, estructura HTML ni el concepto general de atributo. Usar únicamente CodePen en el navegador.

## Código conjunto para CodePen

Pegar en el panel HTML. CSS y JavaScript quedan vacíos. Durante la enseñanza, añadir el contenido por bloques.

```html
<h1>¡Hola, mundo!</h1>
<p>Estoy aprendiendo a crear mi primera página web.</p>
<p>Me gustan los videojuegos y la robótica.</p>

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
<img
  src="https://www.infobae.com/resizer/v2/AWR5GN3IYREQVHYM22WCQFYACE.png?auth=e519c915660f123c03cc4c3414fba9c4d6fe8ae0ae2d55573b20120bd41d75c3&amp;smart=true&amp;width=1200&amp;height=900&amp;quality=85"
  alt="Robot con forma de pato"
  width="320"
  height="240"
>

<p>
  Para conocer este robot, lee
  <a href="https://www.infobae.com/tecno/2026/10/24/los-robots-pato-de-nvidia-que-duermen-y-juegan-tuvieron-20000-pedidos-de-preventa-en-un-dia/" target="_blank" rel="noopener">
    la noticia del robot pato en Infobae
  </a>.
</p>
```

## Inicio

**Tiempo orientativo:** 0:00 a 0:20.

**Acción:** Muestra la página de la lección 2 ya preparada en CodePen.

**Diálogo:**

> ¡Hola! Continuaremos nuestra página añadiendo una lista de pasatiempos, la imagen de un robot y un enlace para conocerlo. Abre la práctica de la descripción para acompañarme.

## Lista de pasatiempos

**Tiempo orientativo:** 0:20 a 2:10.

**Acción:** Escribe primero el ul con los tres pasatiempos. Luego añade el ol dentro de Jugar videojuegos y señala la numeración.

**Diálogo:**

> Agrupo mis pasatiempos con ul, de unordered list: lista sin orden numérico. Cada li, de list item, es un elemento. Dentro de Jugar videojuegos añado mis favoritos por preferencia: Mario Bros, Sonic y Legend of Zelda. Uso ol, de ordered list, para que aparezcan los números. Esa lista va dentro del li de Jugar videojuegos. Escuchar música y Construir robots siguen siendo los otros pasatiempos.

## El robot deseado

**Tiempo orientativo:** 2:10 a 4:10.

**Acción:** Escribe el h2. Busca robot pato NVIDIA en Google Imágenes, selecciona el resultado de Infobae y abre la noticia. Sobre la foto de la noticia, clic derecho y Copiar dirección de imagen. Pega la dirección entre las comillas de src y completa img. Evita copiar la miniatura de Google.

**Diálogo:**

> Mi robot deseado es este robot con forma de pato. Lo busco en Google Imágenes y abro la noticia de Infobae. Primero necesito su imagen: hago clic derecho sobre la foto y copio la dirección de imagen. La pego en src, de source, que indica su origen. Añado alt, texto alternativo, con la descripción Robot con forma de pato. img viene de image y no lleva cierre. width y height indican ancho y alto. Mira la vista previa: ya aparece el robot.

## Enlace a la noticia

**Tiempo orientativo:** 4:10 a 5:40.

**Acción:** Vuelve a la noticia y copia su URL de la barra de direcciones. En CodePen escribe el párrafo con a, pega la URL en href y prueba el enlace desde la vista previa.

**Diálogo:**

> Ahora quiero que quien vea la imagen pueda leer más sobre este robot. Vuelvo a la noticia, copio la dirección de la barra superior y la pego en href. La etiqueta a, de anchor, crea el enlace; href indica el destino. El texto visible será la noticia del robot pato en Infobae. target con guion bajo blank lo abre en otra pestaña y rel con noopener evita que la página nueva acceda a la ventana original. Hago clic en la vista previa y se abre la noticia. src lleva a la imagen; href, a la información.

## Reto y cierre

**Tiempo orientativo:** 5:40 a 6:00.

**Acción:** Muestra el resultado y el texto Pausa y practica durante cinco segundos.

**Diálogo:**

> Tu turno: cambia los pasatiempos y los juegos, elige una imagen con su descripción y añade un enlace para conocer más. Pausa el video y comprueba que todo funciona. En la siguiente lección le daremos estilo con CSS. ¡Nos vemos!

## Distinción importante

Copiar **dirección de imagen**, no Copiar imagen. Para href, copiar la dirección de la noticia desde la barra del navegador. Los resultados de Google pueden cambiar; identificar el resultado de Infobae por su procedencia.
