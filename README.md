<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carregando...</title>
  <style>
    body {
      margin: 0;
      background-color: #121212;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
      flex-direction: column;
    }

    .loader {
      border: 6px solid #333;
      border-top: 6px solid #00ff99;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      animation: spin 1s linear infinite;
      margin-bottom: 20px;
    }

    @keyframes spin {
      to {
        transform: rotate(360deg);
      }
    }

    .text {
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <div class="loader"></div>
  <div class="text">Carregando, por favor aguarde...</div>

  <script>
    setTimeout(() => {
      window.location.href = "https://keepo.io/minebot_terms";
    }, 3000); // 3000ms = 3 segundos
  </script>
</body>
</html>
