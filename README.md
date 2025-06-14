
<html lang="es">
<head>
<meta charset="UTF-8" /> 
<meta name="description" content="Orión Eléctri.com" /> 
<meta name="robots" content="index,follow" />
<title>Orion Electric</title>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0; padding: 0;
    color: #333;
  }

  header {
    position: relative;
    background-image: url('imag_ht/energia.avif');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: white;
    padding: 30px 20px;
    min-height: 150px;
  }

  /* Capa semitransparente para mejor legibilidad */
  header::before {
    content: "";
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 1;
  }

  .contenedor-header {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    z-index: 2; /* para estar encima del overlay */
  }

  .titulo-header {
    text-align: center;
    flex: 1;
    color: white;
  }

  .titulo-header h1 {
    margin: 0;
    font-size: 2rem;
  }

  .titulo-header p {
    margin: 5px 0 0;
    font-size: 1.1rem;
  }

  header img {
    height: 120px;
    width: auto;
  }

  nav {
    background-color: #6062e5;
    padding: 10px;
    text-align: center;
  }

  nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
  }

  section {
    padding: 20px;
    max-width: 900px;
    margin: 20px auto;
    background-color: white;
    border-radius: 5px;
  }

  footer {
    background-color: #002244;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
  }

  /* Responsive para móviles */
  @media (max-width: 600px) {
    .contenedor-header {
      flex-direction: column;
      align-items: center;
    }
    .titulo-header {
      margin: 15px 0;
    }
  }
</style>
</head>
<body>

<header>
  <div class="contenedor-header">
    <div style="width:120px;"></div> <!-- espacio a la izquierda -->
    <div class="titulo-header">
      <h1>Orión Eléctric</h1>
      <p>Ingeniería, Automatización y Mantenimiento Eléctrico</p>
    </div>
    <img src="imag_ht/IAME.jpeg" alt="Logo de Orión Electric" />
  </div>
</header>

<nav>
  <a href="#servicios">Servicios</a>
  <a href="#nosotros">Nosotros</a>
  <a href="#testimonios">Testimonios</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="servicios">
  <h2>⚡ Nuestros Servicios</h2>
  <ul>
    <li>Instalaciones eléctricas residenciales y comerciales</li>
    <li>Mantenimiento y detección de fallas</li>
    <li>Instalación de paneles solares</li>
    <li>Iluminación LED eficiente</li>
    <li>Instalación de cargadores para autos eléctricos</li>
    <li>Generadores y sistemas de respaldo</li>
    <li>Instalación y medición de SPT</li>
    <li>Automatización de sistemas eléctricos</li>
  </ul>
</section>

<section id="nosotros">
  <h2>🧰 Sobre Nosotros</h2>
  <p>Somos una empresa comprometida con la seguridad y la eficiencia energética. Con más de 10 años de experiencia, brindamos soluciones eléctricas modernas y sustentables.</p>
</section>

<section id="testimonios">
  <h2>💬 Testimonios</h2>
  <blockquote>“Excelente atención, resolvieron un problema complejo en menos de una hora.” – Marta L.</blockquote>
  <blockquote>“Instalaron todo el sistema de luces de mi local y quedó impecable.” – Ricardo T.</blockquote>
</section>

<section id="contacto">
  <h2>📞 Contacto</h2>
  <p>Correo: <a href="mailto:orion.electric01@gmail.com">orion.electric01@gmail.com</a></p>
  <p>WhatsApp: +52 221 111 7971</p>
  <p>Atención lunes a domingo</p>
  <p>Horario: de 9:00 a.m. a 7:00 p.m.</p>
  <p>Síguenos en: Instagram @orion.electric – Facebook: Orion Electric</p>
</section>

<footer>
  <p>&copy; 2025 Orión Eléctric – Todos los derechos reservados</p>
</footer>

</body>
</html>
