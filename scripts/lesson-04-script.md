# Guión — Lección 4: Introducción a CSS
**Duración estimada:** 10 minutos

---

### PORTADA
**LOCUTOR:** ¡Hola de nuevo! En la lección pasada le pusimos contenido a nuestra página con listas, imágenes y enlaces. Pero se ve un poco simple, ¿verdad? Hoy viene lo divertido: ¡vamos a darle ropa a nuestra página con CSS! Aprenderás a cambiar colores, tipos de letras, bordes y espacios. ¡Vamos!

---

### ¿QUÉ ES CSS?
**LOCUTOR:** CSS funciona mediante reglas de estilo. Cada regla tiene tres partes muy importantes que debes aprenderte de memoria:
- **El selector:** dice a quién le aplico el cambio (por ejemplo, a todos los títulos).
- **La propiedad:** dice qué quiero cambiar (como el color o el tamaño).
- **El valor:** dice cómo quiero que quede (por ejemplo, morado o de 20 píxeles).

Es como decir: *“A todos los títulos [selector], cámbiales el color [propiedad] a morado [valor]”*.  
Se escribe así: `h1 { color: purple; }`. ¡Y el título cambia al instante! Ojo con los detalles: **no olviden el punto y coma** al final de cada línea, porque si falta, la regla no funciona.

¿Y qué pasa si quiero cambiar solo una cosa específica? Para eso usamos **clases**. Si a una foto le ponemos un apodo o clase (por ejemplo, `class="foto"`), la llamamos en CSS usando un punto: `.foto`. ¡Así de fácil!

---

### CONECTAR EL CSS
**LOCUTOR:** Una duda común es cómo se une todo esto. En herramientas como CodePen no hay que conectar nada: el cuadro de CSS ya viene unido a tu HTML de forma automática. Es como enchufar un celular a un cargador que ya está listo en la pared.

Pero en un proyecto real, en los archivos de tu computadora, se conecta desde el HTML usando una etiqueta `<link>` dentro del `<head>`, apuntando directamente a tu archivo de estilos. Así es como lo hacemos en el repositorio oficial del curso.

---

### COLORES Y FUENTES
**LOCUTOR:** ¡Comencemos a diseñar! Con la propiedad `color` cambiamos el color del texto, y con `background-color` le damos color al fondo de la página o de una sección.  
Para las letras usamos `font-family` para el tipo de fuente, y `font-size` para el tamaño.

Los colores se pueden escribir por su nombre en inglés, como `red` o `blue`, o usando códigos de color precisos, como `#6c5ce7`. Un consejo de diseño: un fondo amarillo suave con letra morada se ve moderno y se lee súper bien. Además, **siempre agreguen una fuente de respaldo** al final (como `sans-serif`), por si la primera fuente no está disponible en la computadora de quien visita tu página.

---

### BORDES, CENTRADO Y ESPACIO
**LOCUTOR:** ¿Quieres que tus elementos se vean ordenados? Para poner un borde usamos la propiedad `border`, indicando el grosor, el estilo y el color. Si usas `border-radius`, puedes redondear las esquinas; de hecho, si le pones un `50%` a una imagen cuadrada, ¡se vuelve un círculo perfecto!

Para organizar el texto usamos `text-align: center;` y queda centrado al instante.  
¿Y los espacios? Aquí hay dos conceptos que suelen confundir, pero son sencillos:
- **Padding:** es el espacio *dentro* de la caja (piénsalo como el relleno mullido de un cojín).
- **Margin:** es el espacio *hacia afuera*, la distancia que hay entre ese elemento y los demás (como la distancia entre tu pupitre y el de tu compañero).

---

### ¡TU TURNO! PRÁCTICA 4
**LOCUTOR:** ¡Es tu turno de vestir tu página! Pausa el video y abre tu editor. Primero, cambia el color de tu título `h1`. Segundo, ponle un color de fondo al `body`. Tercero, elige una fuente bonita. Cuarto, agrégale un borde a tu imagen. Y si quieres un reto extra, ¡centra todo!  
Tienes tres minutos. Prueba combinaciones: un fondo oscuro con texto claro, o colores pasteles. ¡Cada página va a quedar totalmente diferente! ¡Dale play cuando termines!

*(Al volver)*  
**LOCUTOR:** ¿Qué tal quedó? ¿Alguien se animó a probar un borde con estilo punteado o *dashed*? ¡Seguro que se ve genial!

---

### RESUMEN DE LA LECCIÓN
**LOCUTOR:** Repasemos lo que aprendimos hoy: ya sabes cómo se compone una regla de CSS, cómo conectar tus estilos, y cómo cambiar colores, fuentes, bordes, márgenes y rellenos.  
En el próximo video vamos a juntar todo lo que has aprendido en HTML y CSS para construir tu propia página de perfil personal. ¡Hasta pronto!