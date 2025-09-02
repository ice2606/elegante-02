<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Cuadro con Texto y Botones + Fondo de Video</title>
  <style>
    /* Fondo de video */
    body, html {
      height: 100%;
      margin: 0;
      padding: 0;
      overflow: hidden;
    }
    .video-bg {
      position: fixed;
      top: 0; left: 0; min-width: 100vw; min-height: 100vh;
      width: 100vw; height: 100vh;
      object-fit: cover;
      z-index: -1;
    }
    /* Cuadro con texto y botones */
    .cuadro {
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      background: rgba(255,255,255,0.87);
      padding: 2rem 2.5rem;
      border-radius: 16px;
      box-shadow: 0 8px 32px rgba(0,0,0,0.25);
      text-align: center;
    }
    .cuadro h2 {
      margin-top: 0;
    }
    .botones {
      margin-top: 1.5rem;
    }
    .botones a {
      display: inline-block;
      background: #437be8;
      color: #fff;
      padding: 0.7em 1.4em;
      border-radius: 6px;
      margin: 0 0.5em;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.2s;
    }
    .botones a:hover {
      background: #2455b7;
    }
  </style>
</head>
<body>
  <!-- Fondo de video (reemplaza src por tu video o uno libre de derechos) -->
  <video class="video-bg" src="vip 01.mp4" autoplay loop muted playsinline></video>

  <!-- Cuadro con texto y botones -->
  <div class="cuadro">
    <h2>Bienvenido a Mi Sitio</h2>
    <p>Esto es un cuadro elegante con texto y botones. ¡Personalízalo como quieras!</p>
    <div class="botones">
      <a href="https://google.com" target="_blank">Ir a Google</a>
      <a href="https://github.com" target="_blank">Ir a GitHub</a>
    </div>
  </div>
</body>
</html>
