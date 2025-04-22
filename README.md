<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bienvenido a mi GitHub</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f4f8;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    h1 {
      font-size: 3em;
      color: #007acc;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      text-align: center;
    }
    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #888;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    body {
  animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}
h1 {
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
a {
  transition: transform 0.2s ease;
}
a:hover {
  transform: translateY(-2px);
}
  </style>
</head>
<body>
  <header>
    <h1>¡Hola! 👋</h1>
    <p>Soy un estudiante de ASIR (Administración de Sistemas Informáticos en Red) empezando en el mundo de GitHub.</p>
  </header>

  <p>
    Aquí compartiré mis proyectos, prácticas y avances a medida que aprendo más sobre administración de sistemas, redes, y desarrollo. ¡Gracias por pasarte por aquí!
  </p>

  <footer>
    © 2025 - <a href="https://github.com/SalvadorBL2">GitHub</a>
  </footer>
</body>
</html>
