# Cómo grabar la lección 3

## Qué es obligatorio y qué recomienda la guía

El enunciado exige demostraciones en un editor gratuito en línea, lenguaje para principiantes, narración en off, texto y anotaciones en pantalla, pausas de práctica y publicación en YouTube como no listado. La descripción debe incluir el enlace directo a la práctica precargada. No incluir referencias a los autores ni branding en el video o en el código.

La PPT propone 8 a 10 minutos para esta lección, grabación a 1080p, zoom de 150 a 175 %, una placa de pausa y cuatro preguntas de autoevaluación. Son decisiones del modelo de trabajo. El enunciado permite lecciones de 5 a 15 minutos y pide aproximadamente una hora para el curso completo.

No se exige mostrar el rostro. Puedes grabar pantalla y voz. La restricción de no instalar herramientas se refiere a la experiencia del estudiante: su práctica debe funcionar con el navegador.

## 1. Prepara la práctica en línea

1. Abre CodePen en el navegador.
2. Crea un Pen para la lección. Titúlalo «Lección 3: listas, imágenes y enlaces», sin nombres de autores en el material.
3. Abre [la plantilla](../starter-files/leccion3-starter.html) como texto y copia solamente el contenido entre `<body>` y `</body>` al panel HTML de CodePen. No pegues el documento completo en ese panel.
4. Deja CSS y JavaScript vacíos. Muestra el panel HTML y la vista previa con suficiente espacio.
5. Guarda la plantilla y copia su enlace directo. Para prepararla y guardarla puede ser necesaria una cuenta del creador.
6. Abre ese enlace en una ventana privada. Comprueba que un estudiante puede ver y modificar el ejemplo sin instalar programas ni pasar por una barrera de pago. Verifica el comportamiento real antes de prometer que no necesita registrarse.
7. Prepara una copia de trabajo o un Pen separado para la grabación. Conserva la plantilla inicial para que el enlace del estudiante no termine mostrando el ejercicio resuelto.
8. Prepara [el ejemplo terminado](../completed-examples/leccion3-completo.html) en otra pestaña como referencia. Comprueba que carga la imagen y funciona el enlace.

La práctica aún no tiene una URL publicada en este repositorio. Crear y comprobar ese Pen es un paso pendiente; los archivos HTML no sustituyen el enlace directo exigido.

## 2. Ajusta pantalla y sonido

1. Cierra pestañas ajenas a la clase y silencia las notificaciones.
2. Oculta datos de perfil, nombres de cuentas y marcadores personales del área grabada. Comprueba también la vista previa y cualquier pestaña que vayas a abrir.
3. Ajusta el zoom para leer el código. La guía sugiere comenzar entre 150 y 175 %. Si no cabe el código, ajusta paneles y tamaño del texto.
4. Configura tu grabador de pantalla con micrófono. La guía propone OBS o el grabador de Windows; usa el que tengas disponible.
5. Si tu equipo lo permite, graba a 1920 × 1080 y 30 fotogramas por segundo.
6. Haz una prueba de 20 segundos. Escúchala y comprueba que el código se lee a tamaño normal.

## 3. Ensaya una vez

Lee [el guion](leccion3-guion.md) y recorre el ejemplo en CodePen. Habla como si se lo explicaras a alguien que nunca escribió HTML. Mide el ensayo completo con escritura y demostraciones. Ajusta las explicaciones para quedar entre 8 y 10 minutos, sin acelerar la voz ni añadir silencios largos.

El guion contiene frases sugeridas. Puedes decirlas con tus propias palabras, conservando su significado.

## 4. Graba por bloques

| Bloque | Qué debe verse | Acción principal |
|---|---|---|
| 1. Introducción | Resultado final y después plantilla | Explicar qué se construirá y dónde abrir la práctica. |
| 2. Listas | HTML y vista previa | Escribir ul y tres li, señalando sus aperturas y cierres. |
| 3. Imagen | Código y resultado | Añadir img, explicar src y alt y comprobar que carga. |
| 4. Enlace | Código y destino | Añadir a con href y demostrar el clic desde la vista previa. |
| 5. Reto | Página terminada e instrucciones | Pedir tres pasatiempos, una imagen con alt y un enlace. |

Puedes grabar cada bloque por separado y unirlos después. Si te equivocas, detente y repite la frase o la acción. Evita pegar todo el ejercicio de golpe: el estudiante debe ver cómo aparece cada parte.

## 5. Edita lo necesario

- Recorta los errores y los tiempos de espera que no aporten.
- Añade títulos breves: «Listas», «src: dirección de la imagen», «alt: descripción» y «href: destino».
- Usa el cursor o un resaltado para señalar el código que estás explicando.
- Muestra el reto durante unos cinco segundos y di «Pausa el video para practicar». No es necesario grabar tres minutos de espera.
- Revisa que ningún rótulo tape el código ni que la música, si la usas, impida escuchar la voz.

## 6. Revisa antes de publicar

- La explicación continúa los títulos y párrafos de la lección 2.
- Se distinguen ul, li, img, a, src, alt y href.
- Se ven las tres viñetas, la imagen y un enlace funcional.
- La voz se entiende y el texto se lee sin esfuerzo.
- Hay un reto y una conexión con la lección 4 de CSS.
- No aparecen nombres de autores ni branding en el contenido grabado.
- El enlace precargado de práctica está probado fuera de la sesión del creador.

## 7. Sube el video y completa los enlaces

1. Sube el archivo a YouTube con visibilidad **No listado**.
2. Título sugerido: **Lección 3: listas, imágenes y enlaces en HTML**.
3. Sustituye los campos entre corchetes de la descripción siguiente por enlaces reales. No publiques los marcadores.

```text
Aprende a añadir listas, imágenes y enlaces a tu primera página HTML.
Solo necesitas tu navegador y la práctica en línea.

Práctica inicial: [URL REAL DEL PEN PRECARGADO]
Curso y código: https://github.com/upc-pre-202620-1asi0730-8084-Developers/webdev-course

Reto: crea una lista con tres pasatiempos, añade una imagen con una
descripción alt adecuada y un enlace a una página que te interese.
Pausa el video para practicar y comprueba el resultado.
```

4. Comprueba el video y la práctica desde una ventana privada.
5. Reemplaza los pendientes de la lección 3 en README.md por el enlace del video y el Pen.
6. Si el equipo sigue el reparto de la PPT, traslada [las cuatro preguntas](leccion3-cuestionario.md) a Google Forms y entrega al equipo el enlace comprobado.

## 8. Integra siguiendo Git Flow

El material se prepara en `feature/leccion-3`, creada desde `develop`. Después de revisarlo, abre un pull request con base `develop`. La publicación final del curso se prepara en una rama `release/...`, se integra en `main` y se devuelve a `develop`, con el tag de la versión acordada. No presentar el curso como terminado mientras falten videos o prácticas.

## Referencias del encargo

- Social Responsibility Assignment Statement, versión 1.0: requisitos, páginas 3 y 4; rúbrica, página 5; modelo de plan, página 6.
- Guía y guiones del trabajo complementario: reparto de roles, diapositiva 4; lección 3, diapositiva 8; grabación, diapositiva 12.

Estas referencias describen el encargo proporcionado al equipo. Los documentos originales no se incluyen en este repositorio.
