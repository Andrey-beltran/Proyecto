# Proyecto
Proyecto IA
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Empresa Tecnológica</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 15px 0;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin: 0 10px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
    }
    section {
      padding: 20px;
    }
    .service-image {
      width: 100%;
      max-width: 300px;
      display: block;
      margin: 20px auto;
    }
    footer {
      background-color: #f1f1f1;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form label {
      margin-top: 10px;
    }
    form input, form textarea {
      margin-top: 5px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      margin-top: 10px;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mi Empresa Tecnológica</h1>
    <nav>
      <ul>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#nosotros">Nosotros</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>
  <section id="servicios">
    <h2>Servicios</h2>
    <img src="images/servicios.png" alt="Servicios tecnológicos" class="service-image">
    <p>Ofrecemos una amplia gama de servicios tecnológicos para satisfacer las necesidades de tu negocio.</p>
    <ul>
      <li>Desarrollo de Software</li>
      <li>Consultoría Tecnológica</li>
      <li>Soporte Técnico</li>
      <li>Soluciones en la Nube</li>
    </ul>
  </section>
  <section id="nosotros">
    <h2>Nosotros</h2>
    <img src="images/nosotros.png" alt="Nosotros" class="service-image">
    <p>Somos una empresa dedicada a proporcionar soluciones tecnológicas innovadoras y de alta calidad.</p>
  </section>
  <section id="contacto">
    <h2>Contacto</h2>
    <img src="images/contacto.png" alt="Contacto" class="service-image">
    <form id="contact-form">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>
  <footer>
    <p>&copy; 2025 Mi Empresa Tecnológica. Todos los derechos reservados.</p>
  </footer>
  <script>
    document.getElementById('contact-form').addEventListener('submit', function(event) {
      event.preventDefault();
      alert('Mensaje enviado. ¡Gracias por contactarnos!');
    });
  </script>
</body>
</html>
