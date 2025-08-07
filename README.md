<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🎂 Happy Birthday Deviya 🎉</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Roboto:wght@300;500&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(to right, #001f3f, #004080);
      color: #ffffff;
      font-family: 'Roboto', sans-serif;
      text-align: center;
      padding: 40px;
      overflow-x: hidden;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 4em;
      color: #00e6e6;
      text-shadow: 2px 2px 5px #000;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 1.4em;
      color: #cccccc;
      margin-bottom: 30px;
    }

    .card {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 30px;
      max-width: 800px;
      margin: auto;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
      animation: fadeIn 1.5s ease-in-out;
    }

    p {
      font-size: 1.3em;
      line-height: 1.8;
      color: #f0f0f0;
      margin-bottom: 15px;
    }

    .highlight {
      color: #ffd700;
      font-weight: bold;
    }

    button {
      margin-top: 30px;
      background: #00c3ff;
      border: none;
      padding: 12px 25px;
      font-size: 1em;
      border-radius: 30px;
      color: white;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #008ecf;
    }

    .surprise {
      display: none;
      margin-top: 25px;
      font-size: 1.4em;
      color: #ffcc00;
      animation: pulse 1s infinite alternate;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes pulse {
      from { opacity: 0.7; transform: scale(1); }
      to { opacity: 1; transform: scale(1.05); }
    }
  </style>
</head>
<body>
  <h1>Happy Birthday Deviya 🎉</h1>
  <h2>@Deviya Okram | Born August 08, 2006</h2>

  <div class="card">
    <p>Wishing you the <span class="highlight">best today</span>!</p>
    <p>Even though we're far apart, you deserve a great birthday.</p>
    <p>May your day be filled with laughter, sweet surprises, and beautiful moments.</p>
    <p>You deserve every bit of joy the world has to offer.</p>
    <p>You gave me something priceless on my birthday.</p>
    <p>I’m returning the love your way — <span class="highlight">multiplied with happiness and warmth</span>.</p>
    <p><strong>Have a fantastic day, Dolla Okram @Deviya 💙</strong></p>

    <button onclick="revealSurprise()">Tap for a Surprise 🎁</button>
    <div class="surprise" id="surprise">🌟 You're truly special. Never forget how loved you are 💖</div>
  </div>

  <script>
    function revealSurprise() {
      document.getElementById("surprise").style.display = "block";
    }
  </script>
</body>
</html>
