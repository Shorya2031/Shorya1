<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Birthday Wish</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #8b5cf6, #06b6d4);
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      overflow: hidden;
    }

    .container {
      background: rgba(255 255 255 / 0.1);
      border-radius: 32px;
      padding: 48px 64px;
      max-width: 480px;
      text-align: center;
      box-shadow: 0 8px 32px rgba(8, 35, 85, 0.4);
      backdrop-filter: blur(14px) saturate(180%);
      -webkit-backdrop-filter: blur(14px) saturate(180%);
    }

    h1 {
      font-size: 3.5rem;
      margin-bottom: 16px;
      text-shadow: 0 0 10px rgba(255 255 255 / 0.8);
    }

    p {
      font-size: 1.25rem;
      margin-bottom: 40px;
      color: #d3d3ff;
      line-height: 1.6;
    }

    button {
      font-size: 1.2rem;
      padding: 14px 36px;
      border: none;
      border-radius: 14px;
      background: linear-gradient(135deg, #6b46c1 0%, #1e3a8a 100%);
      color: white;
      cursor: pointer;
      box-shadow: 0 8px 15px rgba(107, 70, 193, 0.4);
      transition: all 0.3s ease;
    }

    button:hover,
    button:focus {
      background: linear-gradient(135deg, #a78bfa 0%, #3b82f6 100%);
      box-shadow: 0 12px 24px rgba(107, 70, 193, 0.75);
      outline: none;
      transform: translateY(-3px);
    }

    /* Confetti container */
    .confetti-container {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      pointer-events: none;
      overflow: visible;
      z-index: 100;
    }

    .confetti {
      position: absolute;
      width: 10px;
      height: 10px;
      background-color: #fff;
      opacity: 0.8;
      border-radius: 3px;
      will-change: transform;
      animation-timing-function: linear;
    }
  </style>
</head>
<body>
  <div class="container" role="main">
    <h1>Happy Birthday!</h1>
    <p>Wishing you a day filled with love, joy, and unforgettable memories. May your year ahead be as wonderful as you are.</p>
    <button id="wishButton" aria-label="Celebrate birthday with confetti">Celebrate</button>
  </div>

  <div class="confetti-container" aria-hidden="true"></div>

  <script>
    const confettiContainer = document.querySelector('.confetti-container');
    const button = document.getElementById('wishButton');
    const colors = ['#ff00dc', '#8098ff', '#ff0a00', '#8fff00', '#ff1f00', '#00abff'];

    function createConfettiPiece() {
      const confetti = document.createElement('div');
      confetti.classList.add('confetti');
      confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
      confetti.style.left = Math.random() * window.innerWidth + 'px';
      confetti.style.width = confetti.style.height = (6 + Math.random() * 6) + 'px';
      confetti.style.opacity = Math.random() + 0.5;

      // Animation duration and speed
      const fallDuration = 3000 + Math.random() * 2000;
      confetti.style.animationDuration = fallDuration + 'ms';
      confetti.style.transform = `rotate(${Math.random() * 360}deg)`;

      // Animate falling
      confetti.animate(
        [
          { transform: `translateY(0) rotate(${Math.random() * 360}deg)` },
          { transform: `translateY(${window.innerHeight + 20}px) rotate(${Math.random() * 360 + 360}deg)` },
        ],
        { duration: fallDuration, iterations: 1, easing: 'linear' }
      );

      confettiContainer.appendChild(confetti);

      // Remove confetti after animation
      setTimeout(() => {
        confetti.remove();
      }, fallDuration);
    }

    function throwConfetti() {
      const count = 100;
      for (let i = 0; i < count; i++) {
        setTimeout(createConfettiPiece, i * 15);
      }
    }

    button.addEventListener('click', () => {
      throwConfetti();
      // Optional: add a short celebratory message or sound here
    });
  </script>
</body>
</html>

