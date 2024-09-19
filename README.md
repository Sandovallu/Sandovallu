<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¡Feliz 21 de septiembre, Cielito!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f7e1a1;
      font-family: 'Arial', sans-serif;
    }

    h1 {
      color: #FFD700;
      font-size: 4rem;
      text-align: center;
      position: relative;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-20px);
      }
      100% {
        transform: translateY(0);
      }
    }

    .flower {
      position: absolute;
      top: 0;
      left: 50%;
      width: 60px;
      height: 60px;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/4/40/Sunflower_sky_backdrop.jpg'); /* Imagen de girasol amarillo */
      background-size: cover;
      animation: fall 5s linear infinite;
    }

    @keyframes fall {
      0% {
        transform: translateY(-100px) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* Varias flores */
    .flower:nth-child(2) { left: 25%; animation-delay: 1s; }
    .flower:nth-child(3) { left: 75%; animation-delay: 2s; }
    .flower:nth-child(4) { left: 10%; animation-delay: 3s; }
    .flower:nth-child(5) { left: 90%; animation-delay: 4s; }

  </style>
</head>
<body>
  <div class="flower"></div>
  <div class="flower"></div>
  <div class="flower"></div>
  <div class="flower"></div>
  <div class="flower"></div>
  
  <h1>¡Feliz 21 de septiembre, CIELITO!</h1>
</body>
</html>
