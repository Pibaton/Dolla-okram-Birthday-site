<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Deviya 🎉</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #2196f3, #0d47a1);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    /* Background emoji decorations */
    .emoji-bg {
      position: absolute;
      font-size: 4rem;
      opacity: 0.05;
      animation: float 15s infinite linear;
      pointer-events: none;
    }

    .emoji-bg:nth-child(1) {
      top: 10%;
      left: 10%;
      animation-delay: 0s;
    }
    .emoji-bg:nth-child(2) {
      top: 30%;
      right: 10%;
      animation-delay: 5s;
    }
    .emoji-bg:nth-child(3) {
      bottom: 20%;
      left: 30%;
      animation-delay: 10s;
    }

    @keyframes float {
      0% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(-20px) rotate(10deg); }
      100% { transform: translateY(0) rotate(0deg); }
    }

    .card {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(12px);
      border-radius: 20px;
      padding: 40px;
      max-width: 600px;
      text-align: center;
      box-shadow: 0 0 25px rgba(0,0,0,0.3);
      animation: fadeIn 2s ease-out;
      z-index: 1;
    }

    h1 {
      font-size: 2.8em;
      margin-bottom: 20px;
      color: #fff;
    }

    p {
      font-size: 1.2em;
      margin: 15px 0;
      font-weight: bold;
      line-height: 1.6em;
    }

    .redirect-msg {
      margin-top: 30px;
      font-size: 1em;
      color: #ffc107;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: scale(0.95);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }
  </style>
</head>
<body>

  <!-- Background floating emojis -->
  <div class="emoji-bg">🎁</div>
  <div class="emoji-bg">❤️</div>
  <div class="emoji-bg">🎂</div>

  <div class="card">
    <h1>🎂 Happy Birthday <b>Dolla Okram@Deviya</b> 🎉</h1>
    <p><b> August 08, 2006</b></p>
    <p>Wishing you the best today!</p>
    <p>Even though we're far apart, you deserve a <b>great birthday</b>.</p>
    <p>May your day be filled with <b>laughter, sweet surprises</b>, and beautiful moments.</p>
    <p>You deserve every bit of joy the world has to offer.</p>
    <p>You gave me something priceless on my birthday.<br> I’m returning the love your way.</p>
    <p><b>Multiplied with happiness and warmth 💙</b></p>
    <p><b>Have a fantastic day, Dolla Okram @Deviya!</b></p>
    <p class="redirect-msg">🔁 Redirecting you to a little surprise…</p>
  </div>

  <script>
    // Redirect to Instagram after 7 seconds
    setTimeout(function() {
      window.location.href = "https://instagram.com/dola.chanu";
    }, 7000);
  </script>

</body>
</html>
