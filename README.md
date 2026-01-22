<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ARMAX Gayrimenkul</title>

  <style>
    * {
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    body {
      margin: 0;
      background: #f5f7fa;
      color: #1f2937;
    }

    /* ===== HEADER ===== */
    .header {
      background: #3b6ccf;
      height: 220px;
      position: relative;
    }

    .header-title {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: #ffffff;
      font-size: 32px;
      font-weight: 700;
      letter-spacing: 2px;
      text-align: center;
      width: 100%;
    }

    /* ===== LOGO ===== */
    .logo-wrap {
      position: absolute;
      left: 50%;
      bottom: -45px;
      transform: translateX(-50%);
      background: #ffffff;
      padding: 22px 38px;
      border-radius: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .logo {
      background: #0a33ff;
      color: #ffffff;
      padding: 22px 38px;
      border-radius: 26px;
      font-weight: 700;
      font-size: 20px;
      letter-spacing: 1px;
    }

    /* ===== CONTENT ===== */
    .container {
      max-width: 420px;
      margin: 90px auto 40px;
      padding: 0 16px;
    }

    h1 {
      text-align: center;
      font-size: 26px;
      margin-bottom: 4px;
    }

    h2 {
      text-align: center;
      font-size: 16px;
      font-weight: 400;
      color: #6b7280;
      margin-top: 0;
    }

    .divider {
      height: 1px;
      background: #e5e7eb;
      margin: 24px 0;
    }

    /* ===== LINKS ===== */
    .link {
      background: #ffffff;
      border-radius: 16px;
      padding: 16px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      text-decoration: none;
      color: inherit;
      margin-bottom: 14px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      transition: transform .15s ease;
    }

    .link:hover {
      transform: scale(1.02);
    }

    .link-left {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .icon {
      width: 44px;
      height: 44px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #ffffff;
    }

    .icon img {
      width: 26px;
      height: 26px;
      object-fit: contain;
    }

    .sahibinden { background: #ffe600; }
    .hepsi { background: #ffffff; }
    .emlakjet { background: #e6f7ec; }
    .instagram {
      background: linear-gradient(45deg,#f58529,#dd2a7b,#8134af,#515bd4);
    }

    .arrow {
      font-size: 20px;
      color: #9ca3af;
    }

    .section-title {
      margin: 26px 0 12px;
      font-size: 18px;
    }
  </style>
</head>

<body>

  <div class="header">
    <div class="header-title">ARMAX GAYRİMENKUL</div>

    <div class="logo-wrap">
      <div class="logo">ARMAX</div>
    </div>
  </div>

  <div class="container">
    <h1>ARMAX GAYRİMENKUL</h1>
    <h2>İNŞAAT DANIŞMANLIĞI</h2>

    <div class="divider"></div>

    <!-- Sahibinden -->
    <a class="link" href="https://armaxgayrimenkul.sahibinden.com/" target="_blank">
      <div class="link-left">
        <div class="icon sahibinden">
          <img src="images/sahibinden.png" alt="Sahibinden">
        </div>
        <strong>Sahibinden</strong>
      </div>
      <div class="arrow">→</div>
    </a>

    <!-- Hepsi Emlak -->
    <a class="link" href="https://www.hepsiemlak.com/emlak-ofisi/armax-gayrimenkul-45672" target="_blank">
      <div class="link-left">
        <div class="icon hepsi">
          <img src="images/hepsiemlak.png" alt="Hepsi Emlak">
        </div>
        <strong>Hepsi Emlak</strong>
      </div>
      <div class="arrow">→</div>
    </a>

    <!-- Emlakjet -->
    <a class="link" href="https://www.emlakjet.com/emlak-ofisleri-detay/armax-gayrimenkul-183377" target="_blank">
      <div class="link-left">
        <div class="icon emlakjet">
          <img src="images/emlakjet.png" alt="Emlakjet">
        </div>
        <strong>Emlak Jet</strong>
      </div>
      <div class="arrow">→</div>
    </a>

    <div class="section-title">Beni takip edin</div>

    <!-- Instagram -->
    <a class="link" href="https://www.instagram.com/armaxgayrimenkul.gop/" target="_blank">
      <div class="link-left">
        <div class="icon instagram">
          <img src="images/instagram.png" alt="Instagram">
        </div>
        <div>
          <strong>Instagram</strong><br>
          <small>Bizi Takip Edin</small>
        </div>
      </div>
      <div class="arrow">→</div>
    </a>

  </div>

</body>
</html>
