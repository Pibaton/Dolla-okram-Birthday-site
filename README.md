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
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    /* Floating blurred emojis */
    .emoji-bg {
      position: absolute;
      font-size: 5rem;
      opacity: 0.06;
      filter: blur(4px);
      pointer-events: none;
      animation: float 15s infinite linear;
    }

    .emoji-bg:nth-child(1) { top: 10%; left: 8%; animation-delay: 0s; }
    .emoji-bg:nth-child(2) { top: 30%; right: 15%; animation-delay: 4s; }
    .emoji-bg:nth-child(3) { bottom: 25%; left: 25%; animation-delay: 8s; }
    .emoji-bg:nth-child(4) { bottom: 10%; right: 10%; animation-delay: 2s; }

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
      font-size: 2.6em;
      margin-bottom: 20px;
      color: #fff;
    }

    p {
      font-size: 1.2em;
      margin: 15px 0;
      font-weight: bold;
      line-height: 1.6em;
    }

    .redirect-icon {
      margin-top: 25px;
    }

    .redirect-icon a {
      color: pink;
      font-size: 1.2rem;
      font-weight: bold;
      text-decoration: none;
      transition: transform 0.3s;
      border: 2px solid pink;
      padding: 10px 20px;
      border-radius: 30px;
      display: inline-block;
    }

    .redirect-icon a:hover {
      transform: scale(1.1);
      background: rgba(255, 192, 203, 0.1);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>

  <!-- Blurred floating emojis -->
  <div class="emoji-bg">💝</div>
  <div class="emoji-bg">❤️</div>
  <div class="emoji-bg">🎉</div>
  <div class="emoji-bg">🎂</div>

  <div class="card">
    <h1>🎂 Happy Birthday <b>Deviya Okram@Deviya</b> 🎉</h1>
    <p><b> August 08 </b></p>
    <p>Wishing you the best today!</p>
    <p>Even though we're far apart, you deserve a <b>great birthday</b>.</p>
    <p>May your day be filled with <b>laughter, sweet surprises</b>, and beautiful moments.</p>
    <p>You deserve every bit of joy the world has to offer.</p>
    <p>You gave me something priceless on my birthday.<br> I’m returning the love your way.</p>
    <p><b>Multiplied with happiness and warmth 💙</b></p>
    <p><b>Have a fantastic day, Dolla Okram@Deviya!</b></p>

    <div class="redirect-icon">
      <a href="https://instagram.com/dola.chanu" target="_blank">B’Day User ID</a>
    </div>
  </div>

  <!-- Confetti effect -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
  <script>
    const duration = 6 * 1000;
    const end = Date.now() + duration;

    (function frame() {
      confetti({
        particleCount: 4,
        angle: 60,
        spread: 55,
        origin: { x: 0 }
      });
      confetti({
        particleCount: 4,
        angle: 120,
        spread: 55,
        origin: { x: 1 }
      });

      if (Date.now() < end) {
        requestAnimationFrame(frame);
      }
    })();
  </script>

</body>
</html>
