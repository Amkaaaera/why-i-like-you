# why-i-like-you
This is the reason why i like you most
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>100 Reasons Why I Like You 🌸</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-image: url('https://images.unsplash.com/photo-1592928303034-318c92ffbfc2?auto=format&fit=crop&w=1200&q=80'); /* 🌸 Pink Lily from Unsplash */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      color: #fff;
      text-align: center;
      margin: 0;
      padding: 20px;
      overflow: hidden;
    }

    /* ✨ Glowing Line Animation */
    .glow-line {
      position: absolute;
      width: 2px;
      height: 100%;
      background: linear-gradient(180deg, rgba(255,182,193,0), rgba(255,255,255,0.9), rgba(255,182,193,0));
      animation: moveGlow 6s linear infinite;
      filter: blur(1px);
      opacity: 0.7;
    }

    @keyframes moveGlow {
      0% { transform: translateY(-100%) rotate(0deg); }
      100% { transform: translateY(100%) rotate(0deg); }
    }

    .glow-line:nth-child(1) { left: 10%; animation-delay: 0s; }
    .glow-line:nth-child(2) { left: 30%; animation-delay: 1.5s; }
    .glow-line:nth-child(3) { left: 50%; animation-delay: 3s; }
    .glow-line:nth-child(4) { left: 70%; animation-delay: 4.5s; }
    .glow-line:nth-child(5) { left: 90%; animation-delay: 6s; }

    h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
      text-shadow: 2px 2px 10px #ffb6c1;
      position: relative;
      z-index: 2;
    }

    ul {
      list-style: none;
      padding: 0;
      max-width: 600px;
      margin: auto;
      text-align: left;
      background: rgba(0,0,0,0.5);
      border-radius: 12px;
      padding: 25px;
      box-shadow: 0 0 25px rgba(255,192,203,0.4);
      position: relative;
      z-index: 2;
    }

    li {
      margin: 10px 0;
      font-size: 1.1em;
      line-height: 1.4em;
    }

    footer {
      margin-top: 20px;
      font-style: italic;
      position: relative;
      z-index: 2;
    }

    /* 🎶 Hide embedded YouTube */
    iframe {
      position: fixed;
      width: 1px;
      height: 1px;
      opacity: 0;
      pointer-events: none;
    }
  </style>
</head>
<body>
  <!-- ✨ Glowing Lines -->
  <div class="glow-line"></div>
  <div class="glow-line"></div>
  <div class="glow-line"></div>
  <div class="glow-line"></div>
  <div class="glow-line"></div>

  <h1>🌸 100 Reasons Why I Like You 🌸</h1>

  <ul>
    <li>1. Your smile makes my heart light up 💖</li>
    <li>2. You’re kind and gentle like a pink lily</li>
    <li>3. You make even cloudy days bright</li>
    <li>4. You’re honest and true</li>
    <li>5. You make life feel magical ✨</li>
    <li>6. You care deeply for others</li>
    <li>7. You’re beautiful inside and out</li>
    <li>8. You make my heart bloom like spring 🌷</li>
    <li>9. You make me feel calm and happy</li>
    <li>10. You’re simply you — and that’s enough 💞</li>
    <!-- Keep going up to 100 -->
  </ul>

  <footer>Made with ❤️ for you by [Your Name]</footer>

  <!-- 🎵 Hidden YouTube Background Music -->
  <iframe 
    src="https://www.youtube.com/embed/FjHGZj2IjBk?autoplay=1&loop=1&playlist=FjHGZj2IjBk"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen>
  </iframe>
</body>
</html>
