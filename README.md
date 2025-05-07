# for-mila
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Hehehe...</title>
  <style>
    body {
      background-color: #111;
      color: #fff;
      text-align: center;
      font-family: 'Comic Sans MS', sans-serif;
      padding-top: 60px;
    }

    h1 {
      color: #ff4081;
      font-size: 42px;
      animation: goyang 1s infinite alternate;
    }

    @keyframes goyang {
      from { transform: rotate(-3deg); }
      to { transform: rotate(3deg); }
    }

    .emoji {
      font-size: 36px;
      animation: kedip 1s infinite;
    }

    @keyframes kedip {
      0% { opacity: 1; }
      50% { opacity: 0.3; }
      100% { opacity: 1; }
    }

    .btn-jail {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 18px;
      background-color: #ff4081;
      color: #fff;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .btn-jail:hover {
      transform: scale(1.1);
      background-color: #f50057;
    }
  </style>
</head>
<body>

  <h1>MILAAAAAA😡😡😡</h1>
  <p style="font-size: 22px;">serahkan papmu sekarang,sebanyak mungkin😝</p>
  <p class="emoji">🖕🏻💋🖕🏻</p>
  <p style="font-size: 20px;">Jangan senyum-senyum, keliatan bgt bapernya~</p>

  <button class="btn-jail" onclick="alert('Hayo! Kepencet! Kangen ya?')">
    Jangan Klik Ini!
  </button>

</body>
</html>
