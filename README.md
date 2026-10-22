# WEB-DEV.---Practice-Activity-10
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio - Capítulo 10</title>

  <style>
    html {
      font-size: 16px;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
    }

    h1 {
      font-family: 'Georgia', 'Times New Roman', serif;
      font-size: 2.5rem;
    }

    h2 {
      font-family: 'Georgia', 'Times New Roman', serif;
      font-size: 2rem;
    }

    p {
      font-size: 1rem;
    }

    code {
      font-family: 'Courier New', monospace;
    }

    input, select, textarea, button {
      font-family: inherit;
    }

    .tagline {
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    nav a {
      text-transform: uppercase;
      font-size: 0.85rem;
    }

    blockquote {
      font-style: italic;
      line-height: 1.8;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mi Sitio Web</h1>
    <p class="tagline">Desarrollo y Diseño Web Profesional</p>
    <nav>
      <a href="#inicio">Inicio</a> | 
      <a href="#proyectos">Proyectos</a> | 
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <section id="inicio">
      <h2>Sobre Mí</h2>
      <p>Este es el cuerpo de texto principal de la página, configurado con una tipografía limpia y un interlineado que facilita la lectura en cualquier pantalla.</p>
      
      <blockquote>
        "El diseño no es solo lo que se ve y lo que se siente. El diseño es cómo funciona."
      </blockquote>
    </section>

    <section id="proyectos">
      <h2>Habilidades Técnicas</h2>
      <p>Actualmente utilizo etiquetas como <code>&lt;header&gt;</code> y propiedades enlazadas por herencia en elementos del sistema.</p>
    </section>

    <section id="contacto">
      <h2>Formulario de Contacto</h2>
      <form>
        <input type="text" placeholder="Tu Nombre">
        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

</body>
</html>
