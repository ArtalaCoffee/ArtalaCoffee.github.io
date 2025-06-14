<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Artala Coffee</title>
  <link rel="stylesheet" href="style.css">
  <style>
    :root {
      --primary: #3c2f2f;         /* warna kopi gelap */
      --secondary: #c2a878;       /* warna krem/emas kopi */
      --background: #f9f6f1;      /* latar tenang */
      --accent: #8c5e3c;          /* aksen coklat hangat */
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--background);
      color: var(--primary);
    }

    header {
      background-color: var(--primary);
      color: var(--background);
      text-align: center;
      padding: 100px 20px;
    }

    header h1 {
      font-size: 48px;
      margin: 0;
    }

    header p {
      font-size: 20px;
      margin-top: 10px;
      color: var(--secondary);
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      background-color: var(--secondary);
      padding: 10px 0;
    }

    nav a {
      text-decoration: none;
      color: var(--primary);
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background-color: white;
      border-left: 5px solid var(--accent);
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      padding: 20px;
      transition: transform 0.2s;
    }

    .card:hover {
      transform: scale(1.02);
    }

    footer {
      text-align: center;
      font-size: 14px;
      padding: 20px;
      background-color: var(--secondary);
      color: var(--primary);
    }
  </style>
</head>
<body>
  <header>
     <img src="Artala.png" alt="Logo Artala.Coffee" style="width: 150px;">
    <h1>Artala.Coffee</h1>
    <p>Tenang di Luar, Fokus di Dalam</p>
  </header>

  <nav>
    <a href="#tentang">Tentang</a>
    <a href="#menu">Menu</a>
    <a href="#lokasi">Lokasi</a>
  </nav>

  <section id="tentang">
    <h2>Tentang Artala</h2>
    <p>Secara harfiah, "Artala" berarti orang yang memiliki cita-cita tinggi dan mulia seperti rembulan. Maka Artala.Coffee hadir sebagai tempat ngopi bagi mereka yang mengejar impian besar, namun tetap butuh jeda dan ketenangan.</p>

    <p>Artala.coffee lahir dari dua pikiran, ayah dan anak yang berbeda pandangan, tapi satu tujuan. Kenapa bisa begitu? Ya, itu bagian dari rahasianya… tapi yang pasti, dari perbedaan itu lahirlah satu visi: menciptakan ruang di mana mimpi dan kopi bisa tumbuh bersama.</p> 

<p>Nama Artala dipilih karena kami yakin bahwa seorang pemimpi yang mempunyai cita-cita tinggi layaknya rembulan (indah meski sulit dijangkau) selalu layak diperjuangkan.</p> 

<p>Artala dimulai pada Juni 2024 melalui GoFood, dan di Oktober 2025, hadir secara langsung di Pendem, Argomulyo.</p>

<p>Dengan hadirnya Artala, kami ingin lebih dari sekadar menjual kopi. Kami ingin menciptakan tempat di mana siapa pun bisa merasa "tenang di luar, fokus di dalam". Di Artala, kamu bisa beristirahat dari riuhnya dunia, menyalakan ide-ide yang sempat padam, atau sekadar menikmati diam ditemani aroma kopi.</p>

<p>Artala.coffee adalah rumah bagi mereka yang mencintai buku, seni, musik—dan tentu saja, kopi. Tempat bagi mereka yang punya mimpi, sedang mencarinya, atau sekadar ingin berhenti sejenak, lalu berjalan lagi.</p>
  </section>

  <section id="menu">
    <h2>Menu Kami</h2>
    <div class="menu">
      <div class="card"><h3>Amerikano</h3><p>Pahit jujur tanpa basa-basi.</p></div>
      <div class="card"><h3>Vietnam Drip</h3><p>Manis pelan, pahit belakangan—seperti ditinggal diam-diam.</p></div>
      <div class="card"><h3>Vanilla Latte</h3><p>Lembut dan manis, seperti harapan yang hampir jadi.</p></div>
      <div class="card"><h3>Caramel Macchiato</h3><p>Perpaduan manis dan bold yang bikin susah move on.</p></div>
      <div class="card"><h3>Mochacinno</h3><p>Kopi, susu, dan coklat dalam pelukan yang hangat.</p></div>
      <div class="card"><h3>Spanish Latte</h3><p>Susu manis dan espresso dalam rasa yang lembut dan creamy.</p></div>
      <div class="card"><h3>Spanish Aren Latte</h3><p>Tradisional bertemu modern dalam rasa manis yang membumi.</p></div>
      <div class="card"><h3>Capuccino</h3><p>Lembut berbusa, tapi tetap penuh karakter.</p></div>
      <div class="card"><h3>Cafelatte</h3><p>Rasa ringan dan hangat yang cocok untuk jeda harimu.</p></div>
      <div class="card"><h3>V60</h3><p>Diseduh perlahan, untuk kamu yang suka hal-hal sederhana tapi dalam.</p></div>
      <div class="card"><h3>Matcha (Non-Kopi)</h3><p>Bukan rasa rumput!</p></div>
      <div class="card"><h3>Coklat Latte (Non-Kopi)</h3><p>Manis lembut, seperti pelukan dalam bentuk minuman.</p></div>
      <div class="card"><h3>Kopi Mantan (Special)</h3><p>Dulu manis, sekarang dingin... tapi kamu tetap suka.</p></div>
      <div class="card"><h3>Kopi Langit Sore (Spesial)</h3><p>Sehangat senja, semanis perpisahan yang baik-baik.</p></div>
      <div class="card"><h3>Kopi Pagi (Menu spesial hari Sabtu)</h3><p>Pagi sederhana dengan rasa yang nggak pernah gagal.</p></div>
    </div>
  </section>

  <section id="lokasi">
    <h2>Lokasi & Jam Operasional</h2>
    <p>
      📍 Jl. ArgoBudoyo No.11, Pendem, Ledok, Kec. Argomulyo, Kota Salatiga, Jawa Tengah 50736<br>
      🕒 Selasa–Kamis: 17.00–22.00<br>
      🕒 Jumat: 14.00–22.00<br>
      🕒 Sabtu: 05.00-21.00<br>
      🕒 Minggu: 09.00-21.00<br>
      
      Senin tutup :D<br>
      <section id="instagram" style="text-align: center; margin-top: 30px;">
  <p>Temukan kami di Instagram:</p>
  <a href="https://www.instagram.com/artala.coffee" target="_blank" style="font-size: 18px; text-decoration: none; color: #b88c4f;">
    @artala.coffee
  </a>
</section>
    </p>
  </section>

  <footer>
    <p>© 2025 Artala.Coffee — kopi cita-cita tinggi.</p>
  </footer>
</body> </html>


