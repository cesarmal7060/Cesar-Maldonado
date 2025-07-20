![foto4](https://github.com/user-attachments/assets/c9953df5-1d66-4f65-8495-94d88f205602)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Currículum César Maldonado</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f0f2f5;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      background-color: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }
    .photo {
      text-align: center;
      margin-bottom: 20px;
    }
    .photo img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #2c3e50;
    }
    h2 {
      margin-top: 30px;
      color: #2c3e50;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    ul li {
      margin-bottom: 8px;
    }
    .buttons {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }
    .btn {
      background-color: #2980b9;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn:hover {
      background-color: #1c5f86;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>César Gustavo Maldonado Solano</h1>
  <p>Profesional en informática, música y servicios empresariales</p>
</header>

<div class="container">

  <div class="photo">
    <img src="foto1.jpg" alt="Foto de César Gustavo Maldonado">
  </div>

  <div class="buttons">
    <a href="https://wa.me/593968610113" class="btn">WhatsApp</a>
    <a href="mailto:cesar@email.com" class="btn">Correo</a>
    <a href="CV-Cesar-Maldonado.pdf" class="btn" download>Descargar CV</a>
  </div>

  <h2>Datos Personales</h2>
  <ul>
    <li><strong>Cédula:</strong> 0925301012</li>
    <li><strong>Nacimiento:</strong> 21 de mayo de 1984, Guayaquil</li>
    <li><strong>Estado civil:</strong> Casado</li>
    <li><strong>Licencia de conducir:</strong> Sí</li>
  </ul>

  <h2>Resumen Profesional</h2>
  <p>Soy un profesional con experiencia en el sector comercial y educativo, con habilidades en informática, programación, música, liderazgo y atención al cliente. Busco una oportunidad para seguir creciendo y aportar con responsabilidad, empatía y productividad.</p>

  <h2>Formación Académica</h2>
  <ul>
    <li>Bachiller Técnico – Comercio y Administración</li>
    <li>Operador Técnico en Computación</li>
    <li>Informática – Liceo Cristiano de Guayaquil</li>
  </ul>

  <h2>Experiencia Laboral</h2>
  <ul>
    <li><strong>Uber</strong> – Chofer (3 años)</li>
    <li><strong>Telecity</strong> – Administrador local (5 años)</li>
    <li><strong>Liceo Cristiano</strong> – Director Musical (3 años)</li>
    <li><strong>Consorcio del Austro (MIDUVI)</strong> – Jefe de Bodega (1 año)</li>
  </ul>

  <h2>Conocimientos Técnicos</h2>
  <ul>
    <li>Programas: Office, Photoshop, Saint, Axis, Google Maps</li>
    <li>Lenguajes: Visual Basic, Fox Pro, C++, Dreamweaver</li>
  </ul>

  <h2>Habilidades Musicales</h2>
  <ul>
    <li>Piano (18 años), Saxofón, Guitarra, Bajo</li>
    <li>Experiencia como profesor y director musical</li>
  </ul>

  <h2>Galería Musical</h2>
  <div class="gallery">
    <img src="foto1.jpg" alt="Foto 1">
    <img src="foto2.jpg" alt="Foto 2">
    <img src="foto3.jpg" alt="Foto 3">
    <img src="foto4.jpg" alt="Foto 4">
    <img src="foto5.jpg" alt="Foto 5">
    <img src="foto6.jpg" alt="Foto 6">
    <img src="foto7.jpg" alt="Foto 7">
    <img src="foto8.jpg" alt="Foto 8">
  </div>

</div>

</body>
</html>

