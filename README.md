# DatosAbiertosColombia
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Portal de Estadísticas - Datos Abiertos Colombia</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f6f7;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      width: 360px;
      text-align: center;
    }

    h2 {
      color: #003366;
      margin-bottom: 20px;
    }

    input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      width: 100%;
      padding: 12px;
      background-color: #0072ce;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background-color: #005bb5;
    }

    .logo {
      width: 120px;
      margin-bottom: 20px;
    }

    .footer {
      margin-top: 20px;
      font-size: 12px;
      color: #999;
    }
  </style>
</head>
<body>

  <div class="container">
    <img src="https://datos.gov.co/themes/custom/datagov/logo.png" alt="Logo Datos Abiertos" class="logo">
    <h2>Acceso al portal de estadísticas</h2>
    <input type="text" placeholder="Correo institucional" id="email">
    <input type="password" placeholder="Contraseña" id="password">
    <button onclick="simulacionPhishing()">Iniciar sesión</button>
    <div class="footer">
      Simulación educativa · No introduzcas datos reales
    </div>
  </div>

  <script>
    function simulacionPhishing() {
      alert("⚠️ Has sido hackeado (simulación educativa).\n\nAsí funciona un sitio de phishing. Nunca introduzcas tus datos personales en sitios no verificados.");
      window.location.href = "https://caivirtual.policia.gov.co/caivirtual/consejos-de-ciberseguridad"; // Redirección a consejos reales
    }
  </script>

</body>
</html>
