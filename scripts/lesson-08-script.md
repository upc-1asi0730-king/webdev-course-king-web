# Lección 08 - Bordes, márgenes y espaciado

## Objetivo de la lección

Mejorar la presentación visual de una página web personal usando bordes, márgenes y espaciado en CSS.

Al finalizar la lección, el estudiante debe poder usar `border`, `border-radius`, `padding` y `margin` para dar forma visual a un bloque de contenido.

## Conceptos clave

- Borde con `border`.
- Esquinas redondeadas con `border-radius`.
- Espacio interno con `padding`.
- Espacio externo con `margin`.
- Separación de secciones con `border-top`.
- Diferencia entre espacio interno y espacio externo.
- Mejora visual de imágenes con `border-radius`.

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
  border-radius: 12px;
}

.profile-card {
  background-color: white;
  border: 2px solid #dbeafe;
  border-radius: 16px;
  padding: 24px;
  margin: 32px;
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
```

## Explicación sugerida

La lección continúa desde el uso de clases y selectores de clase en CSS.

Primero se mejora la clase `.profile-card` agregando un borde con `border`.

Luego se usa `border-radius` para redondear las esquinas de la tarjeta.

Después se agrega `padding` para crear espacio interno entre el borde y el contenido.

También se agrega `margin` para crear espacio externo alrededor de la tarjeta.

Luego se usa `section` para separar visualmente las secciones con `border-top`, `padding-top` y `margin-top`.

Finalmente, se mejora la imagen aplicando `border-radius`.

## Práctica para el estudiante

Cambiar el valor de `padding` para observar el espacio interno y modificar `border-radius` para probar esquinas más o menos redondeadas.

## Conexión con la siguiente lección

En la siguiente lección se centrará la tarjeta y se mejorará el diseño general de la página.
