<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio Profesional - Jhon Alexander Fonseca Murillo</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background-color: #0b0f19;
      color: #fff;
    }

    /* Header */
    header {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: rgba(10, 20, 40, 0.95);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
      letter-spacing: 2px;
      color: #00aaff;
      text-transform: uppercase;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 25px;
      transition: color 0.3s, border-bottom 0.3s;
      padding-bottom: 4px;
    }

    nav a:hover {
      color: #00aaff;
      border-bottom: 2px solid #00aaff;
    }

    /* Inicio */
    .inicio {
      padding-top: 120px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #0a1a3d, #001a30);
      min-height: 100vh;
      color: white;
      animation: fadeIn 1s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .perfil {
      display: flex;
      align-items: center;
      gap: 50px;
      max-width: 1000px;
      transition: transform 0.5s;
    }

    .perfil:hover {
      transform: scale(1.02);
    }

    .perfil img {
      width: 300px;
      height: 300px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #00aaff;
      box-shadow: 0 0 25px rgba(0,170,255,0.3);
    }

    .texto-perfil h1 {
      font-size: 45px;
      color: #00aaff;
    }

    .texto-perfil h3 {
      font-weight: 400;
      margin: 10px 0;
      color: #cfd9ff;
    }

    .texto-perfil p {
      color: #dce3ff;
      line-height: 1.7;
      margin-top: 10px;
      max-width: 600px;
    }

    /* Secciones generales */
    section {
      padding: 100px 10%;
      text-align: center;
    }

    h2 {
      font-size: 30px;
      margin-bottom: 30px;
      color: #00aaff;
      position: relative;
    }

    h2::after {
      content: "";
      display: block;
      width: 80px;
      height: 3px;
      background: #00aaff;
      margin: 10px auto;
      border-radius: 3px;
    }

    p {
      color: #e0e0e0;
      line-height: 1.7;
      font-size: 16px;
    }

    /* Tarjetas generales */
    .tarjetas {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .tarjeta {
      background-color: #111a2c;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      transition: transform 0.4s, background-color 0.4s, box-shadow 0.4s;
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .tarjeta img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      border: 2px solid #00aaff;
      object-fit: cover;
    }

    .tarjeta:hover {
      transform: translateY(-8px);
      background-color: #142850;
      box-shadow: 0 0 20px rgba(0,170,255,0.4);
    }

    .tarjeta h3 {
      color: #00aaff;
      margin-bottom: 5px;
    }

    /* Contacto */
    .contacto a {
      color: #00aaff;
      font-weight: bold;
      text-decoration: none;
      transition: color 0.3s;
    }

    .contacto a:hover {
      color: #ffffff;
    }

    .redes img {
      width: 40px;
      margin: 15px;
      transition: transform 0.3s, filter 0.3s;
    }

    .redes img:hover {
      transform: scale(1.2);
      filter: brightness(1.3);
    }

    /* Footer */
    footer {
      background: #000814;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #999;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .perfil {
        flex-direction: column;
        text-align: center;
      }

      .perfil img {
        width: 220px;
        height: 220px;
      }

      .tarjeta {
        flex-direction: column;
        text-align: center;
      }

      .tarjeta img {
        width: 100px;
        height: 100px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">JHON ALEXANDER FONSECA MURILLO</div>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#acerca">Acerca de mí</a>
      <a href="#estudios">Estudios</a>
      <a href="#proyectos">Proyectos</a>
      <a href="#experiencia">Experiencia</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio" class="inicio">
    <div class="perfil">
      <img src="imagenes/personal.jpeg" alt="Foto de Alex">
      <div class="texto-perfil">
        <h1>Jhon Alexander Fonseca Murillo</h1>
        <h3>Emprendedor | Creador de Contenido | Estudiante de Ingeniería de Sistemas</h3>
        <p>
          Tengo 18 años, soy una persona emprendedora, responsable y apasionada por el crecimiento personal. 
          Estudio Ingeniería de Sistemas en la Universidad Minuto de Dios y un técnico en Emprendimiento 
          y Fomento Empresarial en el SENA. 
          Soy creador de contenido digital, líder en Yanbal y auxiliar administrativo y contable.
        </p>
      </div>
    </div>
  </section>

  <section id="acerca" class="acerca">
    <h2>Acerca de mí</h2>
    <p>
      Me considero una persona comprometida, honesta y dedicada a mis metas. 
      Manejo herramientas de ofimática (Word, Excel, Office), edición de video (CapCut) y 
      plataformas empresariales como WhatsApp Business y Meta Business Suite. 
      Actualmente desarrollo mi liderazgo en Yanbal formando un grupo de mujeres emprendedoras rumbo a la dirección.
    </p>
  </section>

  <section id="estudios" class="estudios">
    <h2>Estudios</h2>
    <div class="tarjetas">
      <div class="tarjeta">
        <h3>Bachiller Académico</h3>
        <p>Graduado en noviembre de 2023.</p>
      </div>
      <div class="tarjeta">
        <h3>Ingeniería de Sistemas</h3>
        <p>Universidad Minuto de Dios (Febrero 2024 - Presente).  
        Enfocado en desarrollo de software, análisis de sistemas y gestión tecnológica.</p>
      </div>
      <div class="tarjeta">
        <h3>Técnico en Emprendimiento y Fomento Empresarial</h3>
        <p>SENA (Junio 2025 - Presente).</p>
      </div>
    </div>
  </section>

  <section id="proyectos" class="proyectos">
    <h2>Proyectos</h2>
    <div class="tarjetas">
      <div class="tarjeta">
        <img src="imagenes/yanbal.webp" alt="Alex proyecto Yanbal">
        <div class="contenido">
          <h3>Liderazgo Yanbal</h3>
          <p>Desarrollo de liderazgo, formación de equipo y proyección a ser Director Regional.</p>
        </div>
      </div>
      <div class="tarjeta">
        <img src="imagenes/prisma.webp" alt="Alex proyecto Prisma">
        <div class="contenido">
          <h3>Marca de ropa “PRISMA”</h3>
          <p>Proyecto de moda sostenible y moderna, que busca crear empleo y promover el diseño colombiano.</p>
        </div>
      </div>
      <div class="tarjeta">
        <img src="imagenes/aplicacion.png" alt="Alex proyecto App">
        <div class="contenido">
          <h3>App para Emprendedores</h3>
          <p>Aplicación diseñada para gestionar ventas, pagos, envíos y análisis de datos en un solo ecosistema digital.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="experiencia" class="experiencia">
    <h2>Experiencia Laboral</h2>
    <div class="tarjetas">
      <div class="tarjeta">
        <img src="imagenes/cocina.jpg" alt="Alex experiencia cocina">
        <div class="contenido">
          <h3>Auxiliar de Cocina</h3>
          <p>2023</p>
        </div>
      </div>
      <div class="tarjeta">
        <img src="imagenes/lider.jpg" alt="Alex experiencia Yanbal">
        <div class="contenido">
          <h3>Consultor Emprendedor Sénior - Yanbal</h3>
          <p>Febrero 2024 - Presente</p>
        </div>
      </div>
      <div class="tarjeta">
        <img src="imagenes/contabilidad.jpg" alt="Alex experiencia contable">
        <div class="contenido">
          <h3>Auxiliar Administrativo y Contable</h3>
          <p>Noviembre 2025 - Presente</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <p><strong>Correo:</strong> alex.emprendedor@gmail.com</p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/573054395826" target="_blank">Enviar mensaje</a></p>
    <div class="redes">
      <a href="https://www.instagram.com/yaxxboy" target="_blank"><img src="imagenes/instagram.webp" alt="Instagram"></a>
      <a href="https://www.facebook.com/share/1AHCUXPBmy/?mibextid=wwXIfr" target="_blank"><img src="imagenes/face.webp" alt="Facebook"></a>
      <a href="https://www.tiktok.com/@yaxxboy" target="_blank"><img src="imagenes/tiktok.jpg" alt="TikTok"></a>
    </div>
  </section>

  <footer>
    <p>© 2025 Alex - Portafolio Profesional</p>
  </footer>
</body>
</html>
