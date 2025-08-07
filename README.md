<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Deviya 🎉</title>
  <style>
    body {
      background-color: #001f3f; /* Deep Blue */
      color: white;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding: 40px;
    }

    h1 {
      font-size: 3em;
      color: #00c3ff;
    }

    .message {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 15px;
      max-width: 700px;
      margin: 30px auto;
      font-size: 1.2em;
      line-height: 1.6;
    }

    .surprise {
      display: none;
      margin-top: 30px;
      font-size: 1.3em;
      color: #ffd700;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #00c3ff;
      border: none;
      color: white;
      border-radius: 10px;
      cursor: pointer;
    }

    button:hover {
      background-color: #008ecf;
    }
  </style>
</head>
<body>
  <h1>🎂 Happy Birthday, Deviya! 🎉</h1>
  <p>@Deviya Okram | Born on August 08, 2006</p>

  <div class="message">
    <p>Wishing you the best today!</p>
    <p>Even though we're far apart, you deserve a great birthday.</p>
    <p>May your day be filled with laughter, sweet surprises, and beautiful moments.</p>
    <p>You deserve every bit of joy the world has to offer.</p>
    <p>You gave me something priceless on my birthday. I’m returning the love your way — multiplied with happiness and warmth.</p>
    <p><strong>Have a fantastic day, Dolla Okram @Deviya 💙</strong></p>
  </div>

  <button onclick="revealSurprise()">Click for a Surprise 🎁</button>

  <div id="surprise" class="surprise">
    🌟 You're truly special. Never forget how loved you are. 💖
  </div>

  <script>
    function revealSurprise() {
      document.getElementById("surprise").style.display = "block";
    }
  </script>
</body>
</html>
