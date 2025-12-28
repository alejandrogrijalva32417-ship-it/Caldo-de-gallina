<!DOCTYPE html>  
<html lang="es">  
<head>  
  <meta charset="UTF-8">  
  <title>Para ti esta noche</title>  
  <style>  
    body {  
      margin: 0;  
      height: 100vh;  
      display: flex;  
      justify-content: center;  
      align-items: center;  
      background: linear-gradient(135deg, #fbc2eb, #a6c1ee);  
      font-family: Arial, sans-serif;  
      text-align: center;  
      color: #333;  
    }  
    .card {  
      background: white;  
      padding: 30px;  
      border-radius: 15px;  
      max-width: 360px;  
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);  
    }  
    h1 {  
      font-size: 24px;  
    }  
    p {  
      font-size: 16px;  
      line-height: 1.4;  
    }  
    button {  
      margin-top: 20px;  
      padding: 12px 22px;  
      border: none;  
      border-radius: 25px;  
      background: #ff7eb3;  
      color: white;  
      font-size: 15px;  
      cursor: pointer;  
    }  
    button:hover {  
      opacity: 0.9;  
    }  
  </style>  
</head>  
<body>  
  
  <div class="card">  
    <h1>Hola tú 🌙</h1>  
    <p id="texto">  
      Sé que hoy tienes muchas cosas en la cabeza.<br>  
      Solo quería recordarte que eres especial.  
    </p>  
    <button onclick="cambiarTexto()">Toca aquí ✨</button>  
  </div>  
  
  <script>  
    function cambiarTexto() {  
      document.getElementById("texto").innerHTML =  
        "Respira profundo.<br>Todo va a estar bien.<br><br>Que tengas una noche tranquila 🤍";  
    }  
  </script>  
  
</body>  
</html>  
