# pagina_deportes
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Clases Deportivas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 2rem;
      margin: 0;
      background-image: url('https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=1350&q=80');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #fff;
    }
    h1 {
      text-align: center;
      color: #fff;
    }
    .clases, .formulario {
      margin: 2rem 0;
      padding: 1rem;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }
    iframe {
      width: 100%;
      height: 600px;
      border: none;
    }
    ul {
      list-style: square;
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <h1>Bienvenido a las Clases Deportivas</h1>

  <div class="clases">
    <h2>Actividades Disponibles</h2>
    <ul>
      <li>Yoga</li>
      <li>Pilates</li>
      <li>Entrenamiento Funcional</li>
      <li>Cardio</li>
    </ul>
  </div>

  <div class="formulario">
    <h2>Elige tus horarios preferidos</h2>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeywlxgRpH9628STTX6_0vpyEQXHLpTz9oGc9Necntl1Ppq_A/viewform?usp=header" loading="lazy">Cargando…</iframe>
  </div>

</body>
</html>
