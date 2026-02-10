# ultah<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Selamat Ulang Tahun Niswa 🎉</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #333;
    }

    .card {
      background: white;
      border-radius: 20px;
      padding: 30px 25px;
      max-width: 420px;
      width: 90%;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      text-align: center;
      animation: fadeIn 1.2s ease;
    }

    .photo {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #ff5e78;
      margin-bottom: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    h1 {
      margin-bottom: 10px;
      color: #ff5e78;
    }

    .subtitle {
      font-size: 15px;
      margin-bottom: 25px;
    }

    .message {
      background: #fff5f7;
      border-radius: 15px;
      padding: 15px;
      margin-bottom: 15px;
    }

    .from {
      margin-top: 8px;
      font-weight: bold;
      color: #ff5e78;
      font-size: 14px;
    }

    footer {
      margin-top: 20px;
      font-size: 13px;
      opacity: 0.8;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <div class="card">

    <!-- FOTO BARENG -->
    <img src="foto-bareng.jpg" alt="Foto Bareng" class="photo">

    <h1>🎉 Selamat Ulang Tahun!</h1>
    <div class="subtitle">
      Buat <strong>Niswa</strong> ✨  
      Semoga hari ini penuh senyum dan tawa 💖
    </div>

    <div class="message">
      Semoga di umur yang baru ini kamu makin bahagia, makin kuat ngejalanin hidup,
      dan semua hal baik pelan-pelan datang ke kamu. Jangan lupa istirahat dan
      bahagiain diri sendiri juga ya!
      <div class="from">— Yahya</div>
    </div>

    <div class="message">
      Happy birthday, Niswa! Terima kasih udah jadi teman yang selalu bisa diajak cerita,
      ketawa, dan kadang curhat random. Semoga semua mimpi kamu satu-satu tercapai.
      Kamu pantas dapet yang terbaik 🤍
      <div class="from">— Dika</div>
    </div>

    <div class="message">
      Selamat bertambah usia 🎂  
      Semoga tahun ini lebih banyak momen seru, lebih sedikit drama,
      dan lebih banyak hal yang bikin kamu bangga sama diri sendiri.
      Jangan berubah ya, tetap jadi Niswa yang kami kenal!
      <div class="from">— Della</div>
    </div>

    <footer>
      🎁 Dari Yahya, Dika, dan Della
    </footer>
  </div>

</body>
</html>
