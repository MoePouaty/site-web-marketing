# site-web-marketing
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mini Site</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
      background-color: #f0f0f0;
    }
    h1 {
      color: #333;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
    }
    #message {
      margin-top: 20px;
      font-size: 18px;
      color: #555;
    }
  </style>
</head>
<body>
  <h1>Bienvenue sur mon mini site !</h1>
  <button onclick="afficherMessage()">Clique ici</button>
  <div id="message"></div>

  <script>
    function afficherMessage() {
      document.getElementById("message").innerText = "Merci d'avoir cliqué ! 😊";
    }
  </script>
</body>
</html>
