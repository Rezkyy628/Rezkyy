
Believe you can and you're halfway there." — Theodore Roosevelt

HTML

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>REZKY ADIYA | Personal Website</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #10110f;
  color: #f5f5f0;
  line-height: 1.7;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 7%;
  border-bottom: 1px solid #333;
  position: sticky;
  top: 0;
  background: #10110f;
  z-index: 10;
}

.logo {
  color: #c9fa65;
  font-weight: bold;
  font-size: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-size: 12px;
  margin-left: 10px;
}

section {
  padding: 65px 7%;
}

.tag {
  color: #c9fa65;
  font-size: 13px;
  letter-spacing: 2px;
  margin-bottom: 15px;
}

.hero {
  min-height: 88vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}

h1 {
  font-size: clamp(42px, 10vw, 76px);
  line-height: 1.12;
  margin-bottom: 20px;
}

h1 span {
  color: #c9fa65;
}

p {
  color: #bcbeb5;
  margin-bottom: 18px;
}

.btn {
  display: inline-block;
  padding: 11px 20px;
  background: #c9fa65;
  color: #10110f;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
  margin: 8px 5px 8px 0;
  border: none;
  cursor: pointer;
}

.btn-outline {
  background: transparent;
  border: 1px solid #c9fa65;
  color: #c9fa65;
}

.profile {
  width: 100%;
  max-width: 320px;
  height: 350px;
  object-fit: cover;
  border-radius: 18px;
  margin-top: 28px;
  background: #252720;
}

h2 {
  font-size: 34px;
  line-height: 1.2;
  margin-bottom: 22px;
}

.card {
  background: #191a17;
  border: 1px solid #36382f;
  border-radius: 16px;
  padding: 23px;
  margin-top: 18px;
}

.card h3 {
  color: #c9fa65;
  margin-bottom: 10px;
}

.card img {
  width: 100%;
  height: 190px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 12px;
  background: #252720;
}

.info {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.info-item {
  padding: 14px;
  border: 1px solid #36382f;
  border-radius: 10px;
  overflow-wrap: anywhere;
}

.info-item strong {
  display: block;
  color: #c9fa65;
  font-size: 13px;
}

.info-item a {
  color: white;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 25px 7%;
  color: #888;
  border-top: 1px solid #333;
  font-size: 13px;
}
</style>
</head>

<body>

<header>
  <div class="logo">REZKY.</div>
  <nav>
    <a href="#tentang">Profil</a>
    <a href="#hobi">Hobi</a>
    <a href="#kontak">Kontak</a>
  </nav>
</header>

<section class="hero">
  <div class="tag">✦ PERSONAL WEBSITE</div>

  <h1>HALO,<br>SAYA <span>REZKY ADIYA.</span></h1>

  <p>
    Selamat datang di website pribadi saya.
    Kenali saya lebih dekat melalui profil,
    hobi, dan media sosial saya.
  </p>

  <div>
    <a href="#tentang" class="btn">Tentang Saya ↓</a>
    <a href="#kontak" class="btn btn-outline">Hubungi Saya</a>
  </div>

  <!-- Ganti foto.jpg dengan foto kamu -->
  <img src="foto.jpg" alt="Foto REZKY ADIYA"
       class="profile">
</section>

<section id="tentang">
  <div class="tag">01 — PROFIL</div>
  <h2>Tentang Saya.</h2>

  <div class="card">
    <h3>REZKY ADIYA</h3>
    <p>
      Halo semuanya! Nama saya Rezky Adiya.
      Saya adalah siswa kelas XII TKJ 1.
      Website ini merupakan halaman pribadi
      untuk memperkenalkan diri dan hobi saya.
    </p>
  </div>

  <div class="info">
    <div class="info-item">
      <strong>NAMA LENGKAP</strong>
      REZKY ADIYA
    </div>

    <div class="info-item">
      <strong>KELAS</strong>
      XII TKJ 1
    </div>

    <div class="info-item">
      <strong>HOBI</strong>
      Bermain bola, jalan-jalan, dan menonton sport
    </div>
  </div>
</section>

<section id="hobi">
  <div class="tag">02 — AKTIVITAS</div>
  <h2>Hobi Saya.</h2>
  <p>Beberapa hal yang saya suka lakukan.</p>

  <div class="card">
    <img src="bola.jpg" alt="Bermain bola">
    <h3>01. Bermain Bola ⚽</h3>
    <p>
      Menikmati olahraga, bermain bersama teman,
      dan menjaga semangat sportif.
    </p>
  </div>

  <div class="card">
    <img src="jalan.jpg" alt="Jalan-jalan">
    <h3>02. Jalan-Jalan 🌄</h3>
    <p>
      Menjelajahi tempat baru dan menikmati
      pengalaman yang menyenangkan.
    </p>
  </div>

  <div class="card">
    <img src="sport.jpg" alt="Menonton sport">
    <h3>03. Menonton Sport 🏆</h3>
    <p>
      Menonton pertandingan dan menikmati
      keseruan dunia olahraga.
    </p>
  </div>
</section>

<section id="kontak">
  <div class="tag">03 — HUBUNGI SAYA</div>
  <h2>Mari Terhubung.</h2>
  <p>Silakan hubungi atau kunjungi media sosial saya.</p>

  <div class="info">
    <div class="info-item">
      <strong>WHATSAPP</strong>
      <a href="https://wa.me/6283897256809"
         target="_blank" rel="noopener">
        0838-9725-6809 ↗
      </a>
    </div>

    <div class="info-item">
      <strong>INSTAGRAM</strong>
      <a href="https://instagram.com/kyy_cavalry"
         target="_blank" rel="noopener">
        @kyy_cavalry ↗
      </a>
    </div>
  </div>

  <a class="btn"
     href="https://wa.me/6283897256809"
     target="_blank" rel="noopener">
    Chat WhatsApp
  </a>

  <a class="btn btn-outline"
     href="https://instagram.com/kyy_cavalry"
     target="_blank" rel="noopener">
    Instagram Saya
  </a>
</section>

<footer>
  © 2026 REZKY ADIYA — Personal Website
</footer>

</body>
</html>

