# Lección 06 - Introducción a CSS

## Objetivo de la lección

Iniciar el uso de CSS para modificar la apariencia visual de una página web personal.

Al finalizar la lección, el estudiante debe poder reconocer una regla CSS y usar selectores básicos para cambiar colores, fuente, fondo, separación de texto y tamaño de una imagen.

## Conceptos clave

- CSS como lenguaje de estilos.
- Regla CSS.
- Selector.
- Propiedad.
- Valor.
- Estilos generales con `body`.
- Estilos para títulos con `h1` y `h2`.
- Estilos para párrafos con `p`.
- Estilos para imágenes con `img`.

## Código que se desarrollará

### HTML

```html
<header>
  <h1>Mi Perfil Web</h1>
  <p>Una página para presentarme al mundo.</p>
</header>

<main>
  <section>
    <h2>Sobre mí</h2>

    <p>
      Hola, esta es mi primera página web.
    </p>

    <p>
      Estoy aprendiendo HTML para crear contenido
      y CSS para mejorar el diseño de mis páginas.
    </p>

    <p>
      Mi objetivo es construir una página sencilla para presentarme
      y compartir algunos intereses.
    </p>
  </section>

  <section>
    <h2>Mis hobbies</h2>
    <p>Estas son algunas actividades que disfruto:</p>

    <ul>
      <li>Escuchar música</li>
      <li>Jugar fútbol</li>
      <li>Dibujar</li>
      <li>Aprender sobre tecnología</li>
    </ul>
  </section>

  <section>
    <h2>Mis metas</h2>
    <p>Estos son algunos objetivos que quiero lograr:</p>

    <ol>
      <li>Aprender HTML</li>
      <li>Diseñar con CSS</li>
      <li>Crear mi primera página completa</li>
    </ol>
  </section>

  <section>
    <h2>Mi imagen favorita</h2>

    <img
      src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=640&q=80"
      alt="Laptop mostrando código en pantalla"
    >
  </section>

  <section>
    <h2>Mi recurso favorito</h2>

    <p>
      Puedes visitar
      <a
        href="https://developer.mozilla.org/es/"
        target="_blank"
        rel="noopener noreferrer"
      >
        MDN Web Docs
      </a>
      para aprender más sobre desarrollo web.
    </p>
  </section>
</main>
```

### CSS

```css
body {
  background-color: #eef2ff;
  color: #1f2937;
  font-family: Arial, sans-serif;
}

h1 {
  color: #2563eb;
}

h2 {
  color: #374151;
}

p {
  line-height: 1.6;
}

img {
  width: 260px;
}
```

## Explicación sugerida

La lección continúa desde el contenido HTML completo creado en la lección anterior.

Primero se presenta CSS como el lenguaje que permite cambiar la apariencia visual de una página web.

Luego se explica la estructura de una regla CSS: selector, propiedad y valor.

Después se aplican estilos generales al `body`, cambiando el fondo, el color del texto y la fuente.

Luego se agregan estilos para `h1` y `h2`, cambiando los colores de los títulos.

También se mejora la lectura de los párrafos usando `line-height`.

Finalmente, se controla el ancho de la imagen usando `width`.

## Práctica para el estudiante

Cambiar el color del `h1` y modificar el tamaño de la imagen cambiando el valor de `width`.

## Conexión con la siguiente lección

En la siguiente lección se usarán clases para aplicar estilos a partes específicas de la página.
