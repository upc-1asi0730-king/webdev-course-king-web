# Lección 10 - Proyecto final y errores comunes

## Objetivo de la lección

Finalizar el proyecto de página web personal agregando detalles finales y revisando errores comunes de HTML y CSS.

Al finalizar la lección, el estudiante debe poder revisar la estructura general de su página, agregar un `footer`, mejorar pequeños detalles visuales y reconocer errores frecuentes al trabajar con etiquetas, atributos, clases y reglas CSS.

## Conceptos clave

- Revisión final de estructura HTML.
- Etiqueta `footer`.
- Estilo de cierre de página.
- Efecto `hover` en enlaces.
- Separación de elementos de lista con `margin-bottom`.
- Errores comunes de HTML.
- Errores comunes de CSS.
- Relación entre clases HTML y selectores CSS.

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

<footer>
  <p>Gracias por visitar mi primera página web.</p>
</footer>
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

a:hover {
  color: #1d4ed8;
}

li {
  margin-bottom: 8px;
}

footer {
  text-align: center;
  margin-top: 24px;
  font-size: 14px;
  color: #6b7280;
}
```

## Explicación sugerida

La lección inicia revisando la estructura final de la página: `header`, `main`, varias `section` y el contenido creado durante las lecciones anteriores.

Luego se agrega un `footer` como cierre de la página.

Después se aplica estilo al `footer` usando `text-align`, `margin-top`, `font-size` y `color`.

También se agrega un efecto `hover` al enlace para que cambie de color cuando el cursor pasa encima.

Luego se mejora la separación de los elementos de lista usando `margin-bottom`.

Finalmente, se explican errores comunes para principiantes, como olvidar cerrar etiquetas, escribir mal atributos como `src`, olvidar el atributo `alt`, no relacionar correctamente una clase HTML con su selector CSS, olvidar llaves o punto y coma en CSS, y usar imágenes demasiado grandes.

## Práctica para el estudiante

Revisar que todas las etiquetas estén cerradas, que la imagen tenga `src` y `alt`, que las clases usadas en CSS también existan en el HTML, y personalizar un texto, color o enlace de la página.

## Conexión final

Con esta lección se completa el proyecto principal del curso: una página web personal básica creada con HTML y CSS.
