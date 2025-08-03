<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Untuk Komang Ayu Dealova ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: linear-gradient(to right top, #ffe4ec, #ffe0f0, #ffe0f5);
      font-family: 'Segoe UI', sans-serif;
      color: #d6336c;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px 15px;
    }

    .photo-container img {
      width: 100%;
      max-width: 400px;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(0,0,0,0.15);
    }

    .heart {
      font-size: 50px;
      animation: pulse 1s infinite;
      margin: 20px 0;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    .card {
      background-color: white;
      border-radius: 20px;
      padding: 25px;
      max-width: 500px;
      text-align: center;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      margin-top: 20px;
    }

    .message {
      font-size: 1.2em;
      white-space: pre-line;
      margin-top: 20px;
    }

    button {
      margin-top: 25px;
      padding: 10px 20px;
      font-size: 1em;
      background-color: #ff85a2;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }

    button:hover {
      background-color: #ff4f7a;
    }

    footer {
      margin-top: 25px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>

  <div class="photo-container">
    <img src="foto_kita.jpg" alt="Foto bersama Komang Ayu Dealova">
  </div>

  <div class="heart">❤️</div>

  <div class="card">
    <h2>Untuk Komang Ayu Dealova 🌷</h2>
    <div class="message" id="message"></div>
    <button onclick="nextMessage()">Lanjut Pesan</button>
  </div>

  <footer>
    Dibuat khusus untukmu, Komang Ayu Dealova 💌
  </footer>

  <script>
    const messages = [
      "Hai Komang Ayu Dealova...",
      "Aku cuma mau bilang satu hal kecil tapi penting.",
      "Sejak kamu hadir, semuanya terasa lebih hangat dan berarti.",
      "Kamu seperti `True` di setiap kondisi hidupku — selalu tepat, selalu kuat.",
      "Foto kita ini cuma sepotong kenangan, tapi rasa sayangku nggak akan habis.",
      "Jadi... maukah kamu tetap jadi bagian dari script hidupku, selamanya? ❤️"
    ];

    let i = 0;

    function nextMessage() {
      const msgBox = document.getElementById("message");
      if (i < messages.length) {
        msgBox.innerHTML += messages[i] + "\n\n";
        i++;
      } else {
        alert("Akhir dari pesan... tapi bukan akhir dari rasa 💘");
      }
    }
  </script>

</body>
</html>
