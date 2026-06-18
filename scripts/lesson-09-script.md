# Lección 09 - Centrado y diseño simple

## Objetivo de la lección

Mejorar el diseño general de una página web personal centrando el contenido principal, controlando su ancho y ajustando la presentación de la imagen y el enlace.

Al finalizar la lección, el estudiante debe poder usar propiedades CSS como `max-width`, `margin`, `padding`, `text-align` y `display` para ordenar visualmente una página sencilla.

## Conceptos clave

- Margen general con `margin`.
- Espacio interno con `padding`.
- Ancho máximo con `max-width`.
- Centrado horizontal con `margin: 0 auto`.
- Centrado de texto con `text-align`.
- Imagen como bloque con `display: block`.
- Imagen adaptable con `max-width: 100%`.
- Estilo básico para enlaces.

## Código que se desarrollará

### HTML

```html
<header>
  <h1>Mi Perfil Web</h1>
  <p>Una página para presentarme al mundo.</p>
</header>

<main class="profile-card">
  <section>
    <h2>Sobre mí</h2>

    <p class="intro">
      Hola, esta es mi primera página web.
    </p>

    <p>
      Estoy aprendiendo <span class="highlight">HTML y CSS</span>
      para crear mis propias páginas.
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
  margin: 0;
  padding: 32px;
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

header {
  text-align: center;
}

img {
  display: block;
  width: 220px;
  max-width: 100%;
  margin: 16px auto;
  border-radius: 12px;
}

.profile-card {
  background-color: white;
  border: 2px solid #dbeafe;
  border-radius: 16px;
  padding: 24px;
  max-width: 650px;
  margin: 0 auto;
}

.intro {
  font-size: 18px;
  color: #4b5563;
}

.highlight {
  color: #2563eb;
  font-weight: bold;
}

section {
  border-top: 1px solid #e5e7eb;
  padding-top: 16px;
  margin-top: 16px;
}

a {
  color: #2563eb;
  font-weight: bold;
}
```

## Explicación sugerida

La lección continúa desde la página con bordes, márgenes y espaciado creada anteriormente.

Primero se ajusta el `body` usando `margin: 0` para quitar el margen automático del navegador y `padding` para agregar espacio interno general.

Luego se modifica `.profile-card` agregando `max-width` para controlar el ancho máximo de la tarjeta y `margin: 0 auto` para centrarla horizontalmente.

Después se usa `text-align: center` en `header` para centrar el título y la frase inicial.

Luego se mejora la imagen usando `display: block`, `width`, `max-width` y `margin: 16px auto`.

Finalmente, se agrega un estilo básico al enlace usando `color` y `font-weight`.

## Práctica para el estudiante

Cambiar el valor de `max-width` de la tarjeta y modificar el ancho de la imagen usando la propiedad `width`.

## Conexión con la siguiente lección

En la siguiente lección se realizará la revisión final del proyecto y se explicarán errores comunes para principiantes.
