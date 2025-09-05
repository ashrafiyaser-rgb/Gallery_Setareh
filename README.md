<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>گالری ستاره</title>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Vazirmatn', sans-serif;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
      overflow: hidden;
    }

    /* افکت ستاره‌ها */
    .stars {
      width: 100%;
      height: 100%;
      background: transparent url("https://www.transparenttextures.com/patterns/stardust.png") repeat;
      position: absolute;
      top: 0;
      left: 0;
      z-index: 0;
      animation: twinkle 10s linear infinite;
    }

    @keyframes twinkle {
      from { background-position: 0 0; }
      to { background-position: 1000px 1000px; }
    }

    .card {
      position: relative;
      z-index: 1;
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.3);
      text-align: center;
      width: 360px;
      animation: fadeIn 1s ease-in-out;
    }

    .msg1 {
      font-weight: bold;
      margin-bottom: 16px;
      font-size: 20px;
      color: #2c3e50;
    }
    .msg2 {
      font-size: 14px;
      color: #27ae60;
      margin-bottom: 15px;
    }
    .msg3 {
      font-size: 14px;
      margin-bottom: 15px;
      color: #34495e;
    }
    .msg4 {
      font-size: 12px;
      color: red;
      margin-bottom: 20px;
    }

    .links-container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 10px;
    }
    .link-box {
      flex: 1 1 calc(50% - 10px);
      margin: 5px 0;
      padding: 12px;
      border-radius: 20px;
      background: #8e44ad;
      color: white;
      text-decoration: none;
      font-size: 16px;
      transition: 0.3s;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
      text-align: center;
    }
    .link-box:hover {
      transform: translateY(-3px);
      background: #f39c12;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="stars"></div>

  <div class="card">
    <div class="msg1">🌟 گالری ستاره 🌟</div>
    <div class="msg2">خاطرات شما با درخشش ستاره‌ها ماندگار می‌شود</div>
    <div class="msg3">انواع لوازم آرایشی-بهداشتی-لباس زیر مردانه-زنانه-بچه گانه-انواع پیراهن مردانه-عطر و ادکلن و...</div>
    <div class="msg4">شماره مجوز</div>

    <div class="links-container">
      <a class="link-box" href="XXXXXXXXXXXXXXXXXXXXXXX" target="_blank">نام کانال</a>
      <a class="link-box" href="https://wa.me/98XXXXXXXXXX" target="_blank">واتساپ</a>
      <a class="link-box" href="tel:+98XXXXXXXXXX">تماس تلفنی</a>
    </div>
  </div>
</body>
</html>
