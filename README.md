# kelompok 4 dan kelompok 7 <!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Perpisahan untuk Pa Sigit</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans:wght@400;600&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to right, #c6ffdd, #fbd786, #f7797d);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .container {
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: fadeIn 2s ease-in;
      max-width: 700px;
      position: relative;
      z-index: 10;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin-bottom: 10px;
      color: #d35400;
    }

    h2 {
      font-size: 1.5em;
      color: #555;
      margin-bottom: 30px;
    }

    p {
      font-size: 1.1em;
      color: #444;
      line-height: 1.7;
    }

    .footer {
      margin-top: 30px;
      font-size: 0.95em;
      color: #666;
    }

    .fade-in {
      opacity: 0;
      animation: fadeIn 3s forwards;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* Sakura petals */
    .petal {
      position: absolute;
      width: 20px;
      height: 20px;
      background: url('https://cdn-icons-png.flaticon.com/512/616/616408.png') no-repeat center/contain;
      animation: fall linear infinite;
      opacity: 0.7;
      z-index: 1;
    }

    @keyframes fall {
      0% {
        transform: translateY(-50px) rotate(0deg);
        opacity: 0;
      }
      20% { opacity: 1; }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* Decorative icons */
    .icon {
      font-size: 2em;
      margin: 0 8px;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <!-- Falling petals -->
  <script>
    const createPetal = () => {
      const petal = document.createElement('div');
      petal.classList.add('petal');
      petal.style.left = Math.random() * 100 + 'vw';
      petal.style.animationDuration = 5 + Math.random() * 5 + 's';
      document.body.appendChild(petal);
      setTimeout(() => petal.remove(), 10000);
    };
    setInterval(createPetal, 500);
  </script>

  <div class="container fade-in">
    <h1>Terima Kasih, Pa Sigit</h1>
    <h2>Dari kami, Kelompok 4 dan Kelompok 7 <span class="icon">📖🖋️</span></h2>
    <p>
      Tak terasa waktu berlalu begitu cepat. Bimbingan dan ilmu yang Bapak berikan akan selalu kami kenang dan jadikan bekal untuk melangkah ke depan.<br><br>
      Ketegasan, kesabaran, dan perhatian Bapak menjadi cahaya dalam perjalanan belajar kami. Meski langkah kita akan berpisah, kenangan ini akan tetap tinggal.<br><br>
      Semoga Bapak selalu diberi kesehatan, kebahagiaan, dan kesuksesan di manapun berada. Kami bangga pernah menjadi murid Bapak.
    </p>
    <div class="footer">— Salam hangat dan hormat dari Kelompok 4 & 7 🎓</div>
  </div>
</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Perpisahan untuk Pa Sigit</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans:wght@400;600&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to right, #c6ffdd, #fbd786, #f7797d);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .container {
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: fadeIn 2s ease-in;
      max-width: 700px;
      position: relative;
      z-index: 10;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin-bottom: 10px;
      color: #d35400;
    }

    h2 {
      font-size: 1.5em;
      color: #555;
      margin-bottom: 30px;
    }

    p {
      font-size: 1.1em;
      color: #444;
      line-height: 1.7;
    }

    .footer {
      margin-top: 30px;
      font-size: 0.95em;
      color: #666;
    }

    .fade-in {
      opacity: 0;
      animation: fadeIn 3s forwards;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* Sakura petals */
    .petal {
      position: absolute;
      width: 20px;
      height: 20px;
      background: url('https://cdn-icons-png.flaticon.com/512/616/616408.png') no-repeat center/contain;
      animation: fall linear infinite;
      opacity: 0.7;
      z-index: 1;
    }

    @keyframes fall {
      0% {
        transform: translateY(-50px) rotate(0deg);
        opacity: 0;
      }
      20% { opacity: 1; }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* Decorative icons */
    .icon {
      font-size: 2em;
      margin: 0 8px;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <!-- Falling petals -->
  <script>
    const createPetal = () => {
      const petal = document.createElement('div');
      petal.classList.add('petal');
      petal.style.left = Math.random() * 100 + 'vw';
      petal.style.animationDuration = 5 + Math.random() * 5 + 's';
      document.body.appendChild(petal);
      setTimeout(() => petal.remove(), 10000);
    };
    setInterval(createPetal, 500);
  </script>

  <div class="container fade-in">
    <h1>Terima Kasih, Pa Sigit</h1>
    <h2>Dari kami, Kelompok 4 dan Kelompok 7 <span class="icon">📖🖋️</span></h2>
    <p>
      Tak terasa waktu berlalu begitu cepat. Bimbingan dan ilmu yang Bapak berikan akan selalu kami kenang dan jadikan bekal untuk melangkah ke depan.<br><br>
      Ketegasan, kesabaran, dan perhatian Bapak menjadi cahaya dalam perjalanan belajar kami. Meski langkah kita akan berpisah, kenangan ini akan tetap tinggal.<br><br>
      Semoga Bapak selalu diberi kesehatan, kebahagiaan, dan kesuksesan di manapun berada. Kami bangga pernah menjadi murid Bapak.
    </p>
    <div class="footer">— Salam hangat dan hormat dari Kelompok 4 & 7 🎓</div>
  </div>
</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Perpisahan untuk Pa Sigit</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans:wght@400;600&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to right, #c6ffdd, #fbd786, #f7797d);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      position: relative;
    }

    .container {
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: fadeIn 2s ease-in;
      max-width: 700px;
      position: relative;
      z-index: 10;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin-bottom: 10px;
      color: #d35400;
    }

    h2 {
      font-size: 1.5em;
      color: #555;
      margin-bottom: 30px;
    }

    p {
      font-size: 1.1em;
      color: #444;
      line-height: 1.7;
    }

    .footer {
      margin-top: 30px;
      font-size: 0.95em;
      color: #666;
    }

    .fade-in {
      opacity: 0;
      animation: fadeIn 3s forwards;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* Sakura petals */
    .petal {
      position: absolute;
      width: 20px;
      height: 20px;
      background: url('https://cdn-icons-png.flaticon.com/512/616/616408.png') no-repeat center/contain;
      animation: fall linear infinite;
      opacity: 0.7;
      z-index: 1;
    }

    @keyframes fall {
      0% {
        transform: translateY(-50px) rotate(0deg);
        opacity: 0;
      }
      20% { opacity: 1; }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* Decorative icons */
    .icon {
      font-size: 2em;
      margin: 0 8px;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <!-- Falling petals -->
  <script>
    const createPetal = () => {
      const petal = document.createElement('div');
      petal.classList.add('petal');
      petal.style.left = Math.random() * 100 + 'vw';
      petal.style.animationDuration = 5 + Math.random() * 5 + 's';
      document.body.appendChild(petal);
      setTimeout(() => petal.remove(), 10000);
    };
    setInterval(createPetal, 500);
  </script>

  <div class="container fade-in">
    <h1>Terima Kasih, Pa Sigit</h1>
    <h2>Dari kami, Kelompok 4 dan Kelompok 7 <span class="icon">📖🖋️</span></h2>
    <p>
      Tak terasa waktu berlalu begitu cepat. Bimbingan dan ilmu yang Bapak berikan akan selalu kami kenang dan jadikan bekal untuk melangkah ke depan.<br><br>
      Ketegasan, kesabaran, dan perhatian Bapak menjadi cahaya dalam perjalanan belajar kami. Meski langkah kita akan berpisah, kenangan ini akan tetap tinggal.<br><br>
      Semoga Bapak selalu diberi kesehatan, kebahagiaan, dan kesuksesan di manapun berada. Kami bangga pernah menjadi murid Bapak.
    </p>
    <div class="footer">— Salam hangat dan hormat dari Kelompok 4 & 7 🎓</div>
  </div>
</body>
</html>
