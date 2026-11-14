# Fundamentos de Desarrollo Web

Curso introductorio de HTML y CSS en video para estudiantes de secundaria. En 6 lecciones cortas, cada estudiante crea su primera página web desde cero y termina con una página de perfil personal.

No hay nada que instalar: todo se hace desde el navegador.

- **Duración total**: ~60 minutos
- **Público objetivo**: Estudiantes de 12 a 17 años sin experiencia en programación
- **Prerrequisitos**: Ninguno
- **Herramientas necesarias**: Solo un navegador web (Chrome, Firefox, Safari o Edge)
- **Editor en línea**: [CodePen](https://codepen.io), gratuito

**Plan del curso**: [course-plan.md](course-plan.md), con los videos y las prácticas de cada lección.

## Estructura del repositorio

```text
webdev-course-databit/
├── README.md               Documentación del repositorio
├── course-plan.md          Plan del curso: lecciones, videos y prácticas
├── starter-files/          Código inicial de cada práctica, con pasos en comentarios
│   ├── lesson-01/
│   ├── lesson-02/
│   ├── lesson-03/
│   ├── lesson-04/
│   ├── lesson-05/
│   └── lesson-06/
├── completed-examples/     Resultado esperado de cada lección
│   ├── lesson-02/
│   ├── lesson-03/
│   ├── lesson-04/
│   ├── lesson-05/
│   └── lesson-06/
└── scripts/                Guiones de cada video
```

La Lección 1 no tiene ejemplo completo porque su práctica consiste en cambiar un solo texto. El código de `starter-files/lesson-06/` tiene errores a propósito: es la práctica de depuración.

## Cómo usar este repositorio

1. Abre [course-plan.md](course-plan.md) y sigue las lecciones en orden.
2. En cada lección, mira el video y abre su enlace de CodePen para practicar.
3. Si te atrasas o algo no funciona, compara tu código con `completed-examples/`.

## Configuración

No necesitas instalar nada ni crear una cuenta para practicar.

### En CodePen

1. Abre el enlace de la práctica en [course-plan.md](course-plan.md). El código inicial ya viene cargado.
2. Si prefieres empezar desde cero, abre un [Pen nuevo](https://codepen.io/pen/) y copia el código de `starter-files/`.
3. CodePen ya incluye `<html>`, `<head>` y `<body>`. En el cuadro HTML pega solo lo que va dentro de `<body>`.
4. En el cuadro CSS pega el contenido de `styles.css`, si la lección lo tiene.
5. El resultado se actualiza solo mientras escribes.

### En tu computadora (opcional)

Descarga el repositorio y abre con tu navegador el archivo `index.html` de la lección. Si la lección tiene `styles.css`, ya está conectado con la etiqueta `<link>`.