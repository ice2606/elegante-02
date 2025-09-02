

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
  </style>
</head>
<body>
  <!-- Cambia el src="video.mp4" por la ruta o enlace de tu video corto -->
  <video class="video-bg" src="vip 01.mp4" autoplay muted loop></video>

  <div class="contenido">
    <h1></h1>
    <p></p>
  </div>
</body>
</html>


