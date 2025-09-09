<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Paloma, casa comigo?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff0f5;
      text-align: center;
      padding: 50px;
    }

    h1 {
      color: #d63384;
      font-size: 2.5em;
    }

    .buttons {
      margin-top: 30px;
      position: relative;
    }

    button {
      padding: 15px 30px;
      font-size: 1.2em;
      margin: 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s ease;
    }

    #yesBtn {
      background-color: #28a745;
      color: white;
    }

    #noBtn {
      background-color: #dc3545;
      color: white;
      position: absolute;
    }

    #gifContainer {
      margin-top: 40px;
      display: none;
      animation: fadeIn 2s ease-in-out;
    }

    #emojis {
      font-size: 2em;
      margin-top: 20px;
      display: none;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <h1>Paloma, quer casar comigo?</h1>

  <div class="buttons">
    <button id="yesBtn">Sim 💍</button>
    <button id="noBtn">Não ❌</button>
  </div>

  <div id="emojis">🌹❤️🥰💑💒</div>

  <div id="gifContainer">
    <img src="https://media.giphy.com/media/l3vRfNA1p0rvhMSvS/giphy.gif" alt="A Dama e o Vagabundo" width="300" />
    <p>Assim como eles, vamos viver uma linda história de amor! 💕</p>
  </div>

  <script>
    const yesBtn = document.getElementById('yesBtn');
    const noBtn = document.getElementById('noBtn');
    const emojis = document.getElementById('emojis');
    const gifContainer = document.getElementById('gifContainer');

    yesBtn.addEventListener('click', () => {
      emojis.style.display = 'block';
      gifContainer.style.display = 'block';
    });

    noBtn.addEventListener('mouseover', () => {
      const x = Math.floor(Math.random() * 300);
      const y = Math.floor(Math.random() * 300);
      noBtn.style.left = `${x}px`;
      noBtn.style.top = `${y}px`;
    });
  </script>

</body>
</html>
