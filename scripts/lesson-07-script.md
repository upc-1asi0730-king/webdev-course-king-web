# Lección 07 - Selectores y propiedades CSS

## Objetivo de la lección

Aplicar estilos a partes específicas de una página web usando clases en HTML y selectores de clase en CSS.

Al finalizar la lección, el estudiante debe poder agregar el atributo `class` a elementos HTML y crear selectores de clase en CSS usando el punto antes del nombre de la clase.

## Conceptos clave

- Selector por etiqueta.
- Selector por clase.
- Atributo `class`.
- Clase reutilizable.
- Selector `.profile-card`.
- Selector `.intro`.
- Selector `.highlight`.
- Propiedades `background-color`, `font-size`, `color` y `font-weight`.
- Etiqueta `span`.

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

.profile-card {
  background-color: white;
}

.intro {
  font-size: 18px;
  color: #4b5563;
}

.highlight {
  color: #2563eb;
  font-weight: bold;
}
```

## Explicación sugerida

La lección continúa desde los estilos básicos creados en la lección anterior.

Primero se recuerda que los selectores por etiqueta, como `h1`, `p` o `img`, aplican estilos a todos los elementos de ese tipo.

Luego se introduce el atributo `class` en HTML para identificar partes específicas de la página.

Después se agrega la clase `profile-card` al elemento `main` y se crea el selector `.profile-card` en CSS para aplicar un fondo blanco al contenido principal.

Luego se agrega la clase `intro` a un párrafo y se crea el selector `.intro` para modificar solo ese párrafo.

Finalmente, se usa `span` con la clase `highlight` para resaltar una parte específica de un texto.

## Práctica para el estudiante

Cambiar el color de la clase `highlight` y agregar la clase `intro` a otro párrafo para observar cómo se reutiliza el mismo estilo.

## Conexión con la siguiente lección

En la siguiente lección se usarán bordes, márgenes y espaciado para que la página empiece a verse como una tarjeta.

