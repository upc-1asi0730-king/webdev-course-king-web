# Lección 05 - Imágenes y enlaces

## Objetivo de la lección

Completar el contenido HTML principal de una página web personal agregando una imagen y un enlace.

Al finalizar la lección, el estudiante debe poder usar la etiqueta `img` para mostrar imágenes y la etiqueta `a` para crear enlaces.

## Conceptos clave

- Imagen con `img`.
- Dirección de imagen con `src`.
- Texto alternativo con `alt`.
- Enlace con `a`.
- Dirección de enlace con `href`.
- Apertura en nueva pestaña con `target`.
- Buena práctica con `rel`.
- Atributos HTML.

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
/* Los estilos CSS se trabajarán en próximas lecciones */
```

## Explicación sugerida

La lección continúa desde el avance anterior, donde ya existen secciones de presentación, hobbies y metas.

Primero se agrega una sección para mostrar una imagen usando la etiqueta `img`.

Luego se explica que `src` indica la dirección de la imagen y que `alt` describe la imagen mediante texto.

Después se agrega una sección con un enlace usando la etiqueta `a`.

Se explica que `href` indica la dirección del enlace, que `target="_blank"` abre el enlace en otra pestaña y que `rel="noopener noreferrer"` es una buena práctica cuando se usa `target="_blank"`.

## Práctica para el estudiante

Cambiar el texto alternativo de la imagen y modificar el texto visible del enlace por una frase más clara.

## Conexión con la siguiente lección

En la siguiente lección se empezará a usar CSS para modificar los colores, la fuente y el fondo de la página.
