<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#090711">
  <title>BROOQ — Beyond Ordinary</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background: #090711;
      color: #f5f1fa;
      font-family: Arial, Helvetica, sans-serif;
    }

    header {
      min-height: 82px;
      padding: 0 7%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid #ffffff16;
    }

    .logo {
      font-size: 29px;
      font-weight: 800;
      letter-spacing: 5px;
    }

    nav { display: flex; gap: 30px; }

    nav a, .footer a {
      color: #c9c1d3;
      text-decoration: none;
      font-size: 12px;
      letter-spacing: 2px;
    }

    nav a:hover, .footer a:hover { color: white; }

    .hero {
      min-height: 690px;
      padding: 110px 8%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background:
        radial-gradient(ellipse at 75% 40%, #51247c55, transparent 48%),
        linear-gradient(120deg, #0b0913, #171020 65%, #090711);
    }

    .eyebrow {
      color: #b99bdc;
      font-size: 11px;
      letter-spacing: 5px;
      margin-bottom: 28px;
    }

    h1 {
      font-size: clamp(64px, 12vw, 150px);
      line-height: .9;
      letter-spacing: -7px;
      max-width: 950px;
    }

    .hero p {
      color: #bcb4c7;
      font-size: 15px;
      line-height: 1.8;
      max-width: 420px;
      margin-top: 32px;
    }

    .explore {
      display: inline-block;
      width: fit-content;
      margin-top: 38px;
      padding: 16px 28px;
      border: 1px solid #a98bc7;
      color: white;
      text-decoration: none;
      font-size: 11px;
      letter-spacing: 3px;
      transition: .3s;
    }

    .explore:hover {
      background: #a98bc7;
      color: #090711;
    }

    .collection {
      padding: 100px 8%;
      background: #100d19;
    }

    .collection h2 {
      font-size: clamp(32px, 5vw, 58px);
      letter-spacing: -2px;
      margin-bottom: 18px;
    }

    .collection p {
      color: #aaa1b7;
      line-height: 1.8;
      max-width: 500px;
    }

    .coming {
      margin-top: 48px;
      padding: 55px 25px;
      border: 1px solid #ffffff20;
      text-align: center;
      color: #c4b1dc;
      letter-spacing: 4px;
      font-size: 12px;
    }

    footer {
      padding: 35px 8%;
      display: flex;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
      color: #81798e;
      font-size: 11px;
    }

    @media (max-width: 600px) {
      header { padding: 0 5%; }
      nav { gap: 13px; }
      nav a { font-size: 9px; letter-spacing: 1px; }
      .hero { min-height: 570px; padding: 90px 7%; }
      h1 { letter-spacing: -4px; }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">BROOQ</div>
    <nav>
      <a href="#home">HOME</a>
      <a href="#collection">COLLECTION</a>
      <a href="#about">ABOUT</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="eyebrow">A NEW STANDARD OF STYLE</div>
      <h1>BEYOND<br>ORDINARY.</h1>
      <p>
        Designed with purpose. Defined by detail.
        Discover a different expression of modern fashion.
      </p>
      <a class="explore" href="#collection">EXPLORE BROOQ</a>
    </section>

    <section class="collection" id="collection">
      <div class="eyebrow">THE BROOQ EXPERIENCE</div>
      <h2>Made to stand apart.</h2>
      <p>
        A modern clothing label built around distinctive design,
        thoughtful details and timeless expression.
      </p>
      <div class="coming">FIRST COLLECTION — COMING SOON</div>
    </section>

    <section class="collection" id="about">
      <div class="eyebrow">OUR PHILOSOPHY</div>
      <h2>Identity in every detail.</h2>
      <p>
        BROOQ represents individuality, creativity and a fresh
        perspective on everyday fashion.
      </p>
    </section>
  </main>

  <footer>
    <span>© 2026 BROOQ. ALL RIGHTS RESERVED.</span>
    <a href="#home">BACK TO TOP ↑</a>
  </footer>

</body>
</html># brooq-website
BROOQ - Premium Luxury Fashion Website
