<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#071426">
  <meta name="description" content="ETHICA Learning Hub - Science, Math ও ICT শিক্ষার জন্য মানসম্মত গাইডলাইন।">
  <title>ETHICA Learning Hub | Learn • Practice • Improve</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: Arial, "Noto Sans Bengali", sans-serif;
      background: #f5f8fc;
      color: #17243a;
      line-height: 1.8;
    }
    a { text-decoration: none; }
    .nav {
      background: #071426;
      color: white;
      padding: 16px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
    }
    .brand { font-size: 21px; font-weight: bold; color: #64e6c0; }
    .nav-links { display: flex; gap: 18px; flex-wrap: wrap; }
    .nav-links a { color: white; font-size: 14px; }
    .hero {
      padding: 85px 7%;
      text-align: center;
      color: white;
      background: linear-gradient(135deg, #071426, #123e64, #087f8c);
    }
    .tag {
      display: inline-block;
      border: 1px solid #64e6c0;
      border-radius: 30px;
      padding: 5px 16px;
      color: #9ff5dc;
      margin-bottom: 18px;
    }
    .hero h1 { font-size: clamp(32px, 6vw, 55px); line-height: 1.3; }
    .hero p { max-width: 650px; margin: 18px auto; color: #e1edf7; }
    .btn {
      display: inline-block;
      background: #64e6c0;
      color: #071426;
      padding: 12px 22px;
      border-radius: 9px;
      font-weight: bold;
      margin: 8px 5px;
    }
    .btn-outline {
      border: 1px solid white;
      color: white;
      padding: 11px 22px;
      border-radius: 9px;
      display: inline-block;
      margin: 8px 5px;
    }
    section { padding: 65px 7%; }
    .section-title { text-align: center; margin-bottom: 30px; }
    .section-title h2 { font-size: 30px; color: #0b3150; }
    .section-title p { color: #66758a; }
    .about {
      max-width: 800px;
      text-align: center;
      margin: auto;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 25px;
      border-radius: 16px;
      border: 1px solid #e3ebf4;
      box-shadow: 0 8px 25px #102f4c0b;
    }
    .card .icon { font-size: 36px; }
    .card h3 { margin: 8px 0; color: #123e64; }
    .card p { color: #637187; font-size: 15px; }
    .admission {
      background: #e7f7f3;
      text-align: center;
    }
    .contact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 18px;
    }
    .contact-item {
      background: white;
      padding: 22px;
      border-radius: 12px;
      overflow-wrap: anywhere;
    }
    .contact-item h3 { color: #087f70; margin-bottom: 8px; }
    .phone { display: block; color: #075fba; margin: 5px 0; }
    footer {
      background: #071426;
      color: #d5e0eb;
      text-align: center;
      padding: 28px 15px;
    }
    footer strong { color: #64e6c0; }
    @media (max-width: 480px) {
      .nav { justify-content: center; }
      .nav-links { justify-content: center; gap: 12px; }
      .hero { padding: 60px 5%; }
      section { padding: 48px 5%; }
    }
  </style>
</head>
<body>

  <header class="nav">
    <a class="brand" href="#home">🎓 ETHICA</a>
    <nav class="nav-links">
      <a href="#home">হোম</a>
      <a href="#courses">কোর্স</a>
      <a href="#admission">ভর্তি</a>
      <a href="#contact">যোগাযোগ</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <span class="tag">Learn • Practice • Improve</span>
      <h1>ETHICA Learning Hub</h1>
      <p>Science • Math • ICT</p>
      <p>
        গুণগত শিক্ষা, যত্নশীল গাইডলাইন ও নিয়মিত অনুশীলনের মাধ্যমে
        আপনার সন্তানের একাডেমিক প্রস্তুতিকে আরও শক্তিশালী করুন।
      </p>
      <a class="btn" href="#courses">আমাদের কোর্স</a>
      <a class="btn-outline" href="#admission">ভর্তি সম্পর্কে জানুন</a>
    </section>

    <section id="about">
      <div class="section-title">
        <h2>আমাদের সম্পর্কে</h2>
        <p>শেখা হোক পরিকল্পিত, অনুশীলন হোক নিয়মিত</p>
      </div>
      <div class="about">
        <p>
          ETHICA Learning Hub-এ শিক্ষার্থীদের বিষয়ভিত্তিক ধারণা,
          নিয়মিত অনুশীলন এবং একাডেমিক প্রস্তুতির ওপর গুরুত্ব দেওয়া হয়।
          আমাদের লক্ষ্য হলো শিক্ষার্থীদের শেখার প্রতি আগ্রহী করে তোলা।
        </p>
      </div>
    </section>

    <section id="courses">
      <div class="section-title">
        <h2>আমাদের বিষয়সমূহ</h2>
        <p>আপনার শেখার যাত্রা শুরু হোক এখান থেকেই</p>
      </div>
      <div class="cards">
        <article class="card">
          <div class="icon">🔬</div>
          <h3>Science</h3>
          <p>বিজ্ঞানের মৌলিক ধারণা বুঝে শেখা এবং নিয়মিত অনুশীলন।</p>
        </article>
        <article class="card">
          <div class="icon">📐</div>
          <h3>Mathematics</h3>
          <p>গাণিতিক ধারণা, সমস্যা সমাধান ও ধাপে ধাপে অনুশীলন।</p>
        </article>
        <article class="card">
          <div class="icon">💻</div>
          <h3>ICT</h3>
          <p>তথ্য ও যোগাযোগ প্রযুক্তির বিষয়গুলো সহজভাবে শেখা।</p>
        </article>
      </div>
      <p style="text-align:center;margin-top:22px;color:#637187">
        শ্রেণি, ব্যাচ ও ক্লাসের সময় জানতে আমাদের সঙ্গে যোগাযোগ করুন।
      </p>
    </section>

    <section class="admission" id="admission">
      <div class="section-title">
        <h2>ভর্তি সম্পর্কে জানতে চান?</h2>
        <p>কোর্স, ব্যাচ ও ভর্তি সংক্রান্ত তথ্যের জন্য যোগাযোগ করুন।</p>
      </div>
      <a class="btn" href="https://wa.me/8801572524444?text=Assalamu%20Alaikum%2C%20ETHICA%20Learning%20Hub%20e%20vorti%20somproke%20jante%20chai.">
        WhatsApp-এ যোগাযোগ
      </a>
      <a class="btn" href="tel:+8801572524444">এখনই কল করুন</a>
    </section>

    <section id="contact">
      <div class="section-title">
        <h2>যোগাযোগ</h2>
        <p>আমাদের সঙ্গে যোগাযোগ করতে নিচের তথ্য ব্যবহার করুন</p>
      </div>
      <div class="contact-grid">
        <div class="contact-item">
          <h3>📍 আমাদের ঠিকানা</h3>
          <p>E-55/A, Opposite Janata Bank,<br>
          Ambagan, Khulshi, Chattogram</p>
          <a class="phone"
             href="https://www.google.com/maps/search/?api=1&query=E-55%2FA%2C+Opposite+Janata+Bank%2C+Ambagan%2C+Khulshi%2C+Chattogram"
             target="_blank" rel="noopener">Google Maps-এ দেখুন</a>
        </div>
        <div class="contact-item">
          <h3>📞 মোবাইল নম্বর</h3>
          <a class="phone" href="tel:+8801572524444">01572524444</a>
          <a class="phone" href="tel:+8801627043406">01627043406</a>
        </div>
        <div class="contact-item">
          <h3>📚 আমাদের লক্ষ্য</h3>
          <p>গুণগত শিক্ষা | যত্নশীল গাইডলাইন | নিয়মিত অনুশীলন</p>
          <p><strong>Learn • Practice • Improve</strong></p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p><strong>ETHICA Learning Hub</strong></p>
    <p>Science • Math • ICT</p>
    <p>Learn • Practice • Improve</p>
    <p>© <span id="year"></span> ETHICA Learning Hub. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>
