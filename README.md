<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Valentine ❤️</title>
  <style>
    body {
      background: linear-gradient(to right, #ff758c, #ff7eb3);
      font-family: 'Arial', sans-serif;
      text-align: center;
      color: white;
      padding: 40px;
    }
    h1 {
      font-size: 3em;
    }
    p {
      font-size: 1.4em;
      max-width: 600px;
      margin: auto;
    }
    button {
      background: white;
      color: #ff4f7a;
      border: none;
      padding: 15px 25px;
      font-size: 1.2em;
      border-radius: 30px;
      cursor: pointer;
      margin-top: 30px;
    }
    button:hover {
      background: #ffe6ee;
    }
  </style>
</head>
<body>

  <h1>Happy Valentine’s Day ❤️</h1>

  <p>
    To my favorite human 🥺💕 <br><br>
    Every day with you feels like love in its purest form.
    I choose you today, tomorrow, and always.
  </p>

  <button onclick="showLove()">Click me 💌</button>

  <p id="secret"></p>

  <script>
    function showLove() {
      document.getElementById("secret").innerHTML =
        "You are my Valentine forever 💍💖<br>Love, your stupid boyfriend 😘";
    }
  </script>

</body>
</html>
