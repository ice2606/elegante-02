<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    body, html {
      height: 100%;
      margin: 0;
      padding: 0;
      overflow: hidden;
    }
    .video-bg {
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      object-fit: cover;
      z-index: -1;
    }
    .contenido {
      position: relative;
      z-index: 1;
      color: #fff;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.7);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: sans-serif;
    }
    /* Barra de navegación */
    .navbar {
      width: 100%;
      background: #2d044d;
      overflow: hidden;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 2;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .navbar a {
      display: block;
      color: #fff;
      background: #8e24aa;
      padding: 14px 24px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
      border-radius: 30px;
      margin: 8px 8px;
      transition: background 0.2s, color 0.2s;
    }
    .navbar a:hover {
      background: #6d1b7b;
      color: #fffbe8;
    }
    @media (max-width: 600px) {
      .navbar {
        flex-direction: column;
        align-items: stretch;
      }
      .navbar a {
        margin: 8px 16px;
        font-size: 1.1rem;
        text-align: center;
      }
      .contenido {
        padding-top: 80px;
      }
    }
    @media (min-width: 601px) {
      .contenido {
        padding-top: 60px;
      }
    }
  </style>
</head>
<body>
  <!-- Barra de navegación -->
  <nav class="navbar">
    <a href="https://ice2606.github.io/elegante-01/">atras</a>
  </nav>
  <!-- Cambia el src="video.mp4" por la ruta o enlace de tu video corto -->
  <video class="video-bg" src="vip 01.mp4" autoplay muted loop></video>

  <div class="contenido">
    <h1></h1>
    <p></p>
  </div>
</body>
</html>




<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Cuadro con texto y botones morados</title>
  <style>
    body {
      background: #f3f3f4;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .cuadro-responsive {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 24px rgba(80, 0, 120, 0.13);
      padding: 2rem;
      max-width: 400px;
      width: 90vw;
      min-width: 250px;
      margin: 1rem;
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
      align-items: stretch;
    }
    .cuadro-responsive textarea {
      width: 100%;
      min-height: 80px;
      resize: vertical;
      padding: 0.75rem;
      border: 1.5px solid #d1b3ff;
      border-radius: 8px;
      font-size: 1rem;
      color: #4b006e;
      outline-color: #a259e6;
    }
    .botones {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      justify-content: flex-end;
    }
    .boton-morado {
      background: linear-gradient(90deg, #a259e6 0%, #7b2ff2 100%);
      color: #fff;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      padding: 0.7em 1.5em;
      text-decoration: none;
      cursor: pointer;
      transition: background 0.2s, box-shadow 0.2s;
      box-shadow: 0 2px 8px rgba(126, 87, 194, 0.15);
      min-width: 80px;
      text-align: center;
      font-weight: 500;
    }
    .boton-morado:hover, .boton-morado:focus {
      background: linear-gradient(90deg, #7b2ff2 0%, #a259e6 100%);
      box-shadow: 0 4px 16px rgba(126, 87, 194, 0.22);
    }
    @media (max-width: 450px) {
      .cuadro-responsive {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="cuadro-responsive">
    <textarea placeholder="Escribe tu texto aquí..."></textarea>
    <div class="botones">
      <a href="https://ejemplo1.com" class="boton-morado" target="_blank">Botón 1</a>
      <a href="https://ejemplo2.com" class="boton-morado" target="_blank">Botón 2</a>
    </div>
  </div>
</body>
</html>


