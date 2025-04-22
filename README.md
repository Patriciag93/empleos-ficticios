<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EmpleActiva - Portal de Empleo Ficticio</title>
<style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: #004080; color: white; padding: 1rem; text-align: center; }
    nav { background-color: #f0f0f0; padding: 1rem; text-align: center; }
    nav a { margin: 0 1rem; text-decoration: none; color: #004080; font-weight: bold; }
    section { padding: 2rem; }
    .oferta { border: 1px solid #ccc; padding: 1rem; margin-bottom: 1rem; border-radius: 5px; }
    form { margin-top: 1rem; }
    label { display: block; margin: 0.5rem 0 0.2rem; }
    input, textarea, select { width: 100%; padding: 0.5rem; margin-bottom: 1rem; border: 1px solid #ccc; border-radius: 4px; }
    button { background-color: #004080; color: white; padding: 0.5rem 1rem; border: none; border-radius: 4px; cursor: pointer; }
    button:hover { background-color: #003366; }
    footer { background-color: #004080; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
</style>
</head>
<body>
<header>
<h1>EmpleActiva</h1>
<p>Tu portal de empleo simulado para prácticas y formación</p>
</header>
 
  <nav>
<a href="#ofertas">Ofertas de Empleo</a>
<a href="#candidato">Zona Candidato</a>
<a href="#empresa">Zona Empresa</a>
<a href="#orientacion">Orientación Laboral</a>
</nav>
 
  <section id="ofertas">
<h2>📋 Ofertas de Empleo</h2>
<div class="oferta">
<h3>Auxiliar Administrativo</h3>
<p><strong>Empresa:</strong> Novaequipos S.L.</p>
<p><strong>Ubicación:</strong> Valencia</p>
<p><strong>Jornada:</strong> Parcial (mañanas)</p>
<p><strong>Publicado:</strong> 20/04/2025</p>
<p><strong>Requisitos:</strong> FP de Grado Medio, manejo de Excel, proactividad</p>
<button onclick="alert('Postulación enviada correctamente (simulada).')">Postularme</button>
</div>
<div class="oferta">
<h3>Camarero/a de Sala</h3>
<p><strong>Empresa:</strong> Sabores del Sur</p>
<p><strong>Ubicación:</strong> Sevilla</p>
<p><strong>Jornada:</strong> Completa</p>
<p><strong>Publicado:</strong> 18/04/2025</p>
<p><strong>Requisitos:</strong> Experiencia mínima 1 año, buena actitud, carnet de manipulación</p>
<button onclick="alert('Postulación enviada correctamente (simulada).')">Postularme</button>
</div>
</section>
 
  <section id="candidato">
<h2>🧑‍💼 Zona Candidato</h2>
<form action="https://formsubmit.co/patricia.delcastillo@profesores.alapar.ong" method="POST">
<label for="nombre">Nombre completo:</label>
<input type="text" id="nombre" name="nombre" required>
 
      <label for="email">Correo electrónico:</label>
<input type="email" id="email" name="email" required>
 
      <label for="mensaje">Carta de presentación:</label>
<textarea id="mensaje" name="mensaje" rows="4" required></textarea>
 
      <input type="hidden" name="_captcha" value="false">
<input type="hidden" name="_next" value="https://tusitio.com/gracias.html">
 
      <button type="submit">Enviar solicitud</button>
</form>
</section>
 
  <section id="empresa">
<h2>🏢 Zona Empresa</h2>
<form action="https://formsubmit.co/patricia.delcastillo@profesores.alapar.ong" method="POST">
<label for="empresa">Nombre de la empresa:</label>
<input type="text" id="empresa" name="empresa" required>
 
      <label for="contacto">Correo de contacto:</label>
<input type="email" id="contacto" name="contacto" required>
 
      <label for="oferta">Descripción de la oferta:</label>
<textarea id="oferta" name="oferta" rows="4" required></textarea>
 
      <input type="hidden" name="_captcha" value="false">
<input type="hidden" name="_next" value="https://tusitio.com/gracias.html">
 
      <button type="submit">Publicar oferta</button>
</form>
</section>
 
  <section id="orientacion">
<h2>🎯 Orientación Laboral</h2>
<ul>
<li>Consejos para hacer un buen CV</li>
<li>Guía para entrevistas</li>
<li>Información sobre certificados de profesionalidad</li>
</ul>
</section>
 
  <footer>
<p>© 2025 EmpleActiva - Portal Ficticio para la Inserción Laboral</p>
</footer>
</body>
</html>
