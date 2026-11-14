# Guión — Lección 3: Añadir más elementos HTML

**Duración estimada**: 10 minutos

## PORTADA

**LOCUTOR:** ¡Hola de nuevo! En la lección anterior creaste tu primera página con títulos y párrafos. Hoy vamos a darle más vida: aprenderás a crear listas, a insertar imágenes y a agregar enlaces. Son los elementos que hacen que una página se sienta como un sitio web de verdad. ¡Vamos!

---

## LISTAS

**LOCUTOR:** Las listas sirven para organizar información. Tenemos dos tipos:

* **`<ul>`**: crea una lista con viñetas, o sea, con puntitos. Es ideal cuando el orden no importa, como tus juegos favoritos.
* **`<ol>`**: crea una lista numerada. Es ideal cuando el orden sí importa, como un top 3 de canciones.

Y cada ítem de la lista va dentro de una etiqueta `<li>`. Fíjate en esto: los `<li>` siempre van dentro de un `<ul>` o de un `<ol>`, nunca solos.

Escribimos `<ul>`, luego tres `<li>` con nuestros juegos favoritos, y cerramos con `</ul>`. Mira el resultado: aparecen los puntitos. Ahora cambiamos `ul` por `ol`, y los puntitos se vuelven números. ¡Con solo cambiar una etiqueta cambia toda la lista!

---

## IMÁGENES

**LOCUTOR:** Para mostrar una imagen usamos la etiqueta `<img>`. Esta etiqueta es especial: no necesita cierre, porque no tiene contenido adentro. Lleva dos atributos, o sea, dos ajustes extra:

* **`src`**: dice dónde está la imagen. Por ejemplo, `src="avatar.png"`.
* **`alt`**: es una descripción de la imagen. Por ejemplo, `alt="Perrito negro sentado"`.

El `alt` es muy importante para la accesibilidad: si una persona ciega usa un lector de pantalla, escuchará lo que escribiste ahí. Y si la imagen no carga, ese texto aparece en su lugar.

Escribimos la etiqueta con su `src` y su `alt`, y la imagen aparece en el resultado. Si nos equivocamos en el enlace del `src`, la imagen no aparece, así que hay que copiarlo con cuidado.

Un consejo: usa solo imágenes tuyas, imágenes libres o un avatar. No subas fotos de otras personas sin su permiso ni pongas datos personales.

---

## ENLACES

**LOCUTOR:** Los enlaces se crean con la etiqueta `<a>`. La `a` viene de la palabra inglesa *anchor*, que significa ancla, porque une una página con otra.

El atributo `href` indica a dónde lleva el enlace, y el texto que escribes entre las etiquetas es lo que la persona ve y toca. Por ejemplo: `<a href="https://developer.mozilla.org/es/">Aprende más</a>`.

Si agregamos `target="_blank"`, el enlace se abre en una pestaña nueva y tu página no se cierra. Lo probamos y ¡se abre en otra pestaña! Puedes hacer un enlace a tu canal de aprendizaje favorito o a una guía de HTML.

---

## ¡TU TURNO! AGREGA MÁS A TU PÁGINA

**LOCUTOR:** ¡Tu turno! Pausa el video y abre el enlace. Primero, agrega una lista `<ul>` con tres cosas que te gustan. Segundo, inserta una imagen con `<img>`; si no tienes una a la mano, usa la del enlace de la descripción. Y tercero, agrega un enlace a tu sitio favorito de aprendizaje.

Recuerda cerrar cada etiqueta que lo necesite. Si la imagen no se ve, revisa tu `src`; si la lista se ve rara, revisa que cerraste el `</ul>`. ¡Dale play cuando termines!

---

## REPASO RÁPIDO: ¿VERDADERO O FALSO?

**LOCUTOR:** Tres preguntas rápidas. Primera: `<ol>` hace viñetas, ¿verdadero o falso? Falso: `<ol>` hace números; las viñetas las hace `<ul>`.

Segunda: el `alt` describe la imagen. Verdadero. Y tercera: `href` indica a dónde lleva un enlace. Verdadero.

---

## RESUMEN DE LA LECCIÓN

**LOCUTOR:** Repasemos: `<ul>` crea listas con viñetas, `<ol>` listas numeradas y cada ítem va en un `<li>`; `<img>` inserta imágenes con `src` y `alt`; y `<a>` crea enlaces con `href`.

En la próxima lección le daremos ropa a tu página: colores, letras y bordes con CSS. ¡Hasta pronto!
