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
    <a href="#servicios">chinelas</a>
    <a href="#galeria">zapatos</a>
    <a href="#contacto">sandalias</a>
     <a href="#contacto">sandalias de tacon</a>
       <a href="#contacto">ropa</a>
  </nav>
  <!-- Cambia el src="video.mp4" por la ruta o enlace de tu video corto -->
  <video class="video-bg" src="vip 01.mp4" autoplay muted loop></video>

  <div class="contenido">
    <h1></h1>
    <p></p>
  </div>
</body>
</html>
