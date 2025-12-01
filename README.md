<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Orbit Watch — Flat 20% Off</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700;900&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent:#ffb84d;
      --dark:#111827;
      --muted:#6b7280;
      --card:#f3f4f6;
      --primary:#2b2f6b;
    }
    *{box-sizing:border-box}
    body{font-family:Montserrat,system-ui,Arial,sans-serif;margin:0;background:linear-gradient(180deg,#111827 0%, #0f1724 60%);color:var(--dark);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:32px}
    .container{width:100%;max-width:1100px;background:linear-gradient(180deg,#ffffff 0%, #f7f7fb 100%);border-radius:14px;overflow:hidden;box-shadow:0 30px 60px rgba(2,6,23,0.45);display:grid;grid-template-columns:1fr 420px;gap:0}
    @media(max-width:900px){.container{grid-template-columns:1fr;max-width:720px}}
    .left{padding:36px 44px;display:flex;flex-direction:column;gap:20px}
    .brand{display:flex;align-items:center;gap:14px}
    .logo{width:54px;height:54px;border-radius:10px;background:var(--primary);display:flex;align-items:center;justify-content:center;color:white;font-weight:800;font-family:'Playfair Display',serif;font-size:20px}
    .brand h1{margin:0;font-size:20px}
    .tag{font-size:13px;color:var(--muted);margin-top:-4px}
    .headline{font-family:'Playfair Display',serif;font-size:44px;line-height:1; color:var(--primary);margin:6px 0}
    .sub{color:var(--muted);font-size:15px;max-width:56ch}
    .features{display:flex;gap:12px;flex-wrap:wrap}
    .pill{background:linear-gradient(90deg,#fff 0%, #fffde7 100%);padding:10px 14px;border-radius:12px;font-weight:600;box-shadow:0 8px 18px rgba(9,30,66,0.06)}
    .cta{margin-top:10px;display:flex;gap:12px;align-items:center}
    .btn{background:var(--accent);padding:14px 20px;border-radius:10px;border:0;font-weight:700;cursor:pointer;box-shadow:0 10px 30px rgba(255,184,77,0.18)}
    .btn.secondary{background:transparent;border:2px solid rgba(43,47,107,0.08);padding:12px 16px}
    .coupon{margin-left:8px;padding:8px 12px;border-radius:8px;background:#fff8ea;color:var(--primary);font-weight:700}
    .left .list{display:grid;grid-template-columns:repeat(2, minmax(0,1fr));gap:12px;margin-top:6px}
    .spec{background:linear-gradient(180deg,#ffffff,#fbfbfe);padding:14px;border-radius:10px;border:1px solid rgba(16,24,40,0.04);display:flex;flex-direction:column;gap:6px}
    .spec h4{margin:0;font-size:13px;color:var(--muted)}
    .spec p{margin:0;font-weight:700}

    /* right column */
    .right{background:linear-gradient(180deg,#e6f0ff,#f6f9ff);padding:28px;display:flex;flex-direction:column;align-items:center;justify-content:space-between}
    .promo{align-self:stretch;background:linear-gradient(180deg,#fff,#fff8f2);border-radius:12px;padding:16px;border:1px solid rgba(16,24,40,0.04);display:flex;flex-direction:column;gap:12px}
    .promo h2{margin:0;color:#b03b3b;font-size:28px;text-align:right}
    .promo .percent{font-size:40px;font-weight:900;color:#c33a3a;text-align:right}
    .watch-img{width:100%;height:320px;border-radius:10px;overflow:hidden;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#f6f6f8,#ffffff)}
    .watch-img img{width:100%;height:100%;object-fit:cover}
    .order{display:flex;flex-direction:column;gap:10px;align-items:center}
    .order small{color:var(--muted)}
    .order .code{background:var(--primary);color:white;padding:10px 16px;border-radius:10px;font-weight:800}
    .order .buy{display:flex;gap:8px}

    footer{padding:18px 28px;display:flex;justify-content:space-between;align-items:center;border-top:1px solid rgba(15,23,42,0.04);background:transparent}

  </style>
</head>
<body>
  <div class="container">
    <div class="left">
      <div class="brand">
        <div class="logo">O</div>
        <div>
          <h1>Orbit Watch</h1>
          <div class="tag">Durable • Scratch Resistant • Water Resistant</div>
        </div>
      </div>

      <h2 class="headline">Build a great website — get <span style="color:var(--accent)">20% off</span> on premium watches</h2>
      <p class="sub">Limited-time launch offer. Create your stunning online store with our quick setup and theme templates — and save 20% on every watch while the promotion lasts. Perfect for creators, boutiques, and gift shoppers.</p>

      <div class="features">
        <div class="pill">Free shipping over ₹999</div>
        <div class="pill">2-year warranty</div>
        <div class="pill">30-day returns</div>
      </div>

      <div class="cta">
        <button class="btn" id="orderBtn">Order Now</button>
        <button class="btn secondary" id="learnBtn">Build a Website</button>
        <div class="coupon">Code: ORBIT20</div>
      </div>

      <div class="list">
        <div class="spec">
          <h4>Material</h4>
          <p>Durable Stainless Steel</p>
        </div>
        <div class="spec">
          <h4>Finish</h4>
          <p>Luxury Finish</p>
        </div>
        <div class="spec">
          <h4>Resistance</h4>
          <p>Scratch & Water Resistant</p>
        </div>
        <div class="spec">
          <h4>Support</h4>
          <p>24/7 Customer Care</p>
        </div>
      </div>

      <footer>
        <div style="font-size:14px;color:var(--muted)">© Orbit Watch</div>
        <div style="font-size:13px;color:var(--muted)">Offer valid while stocks last</div>
      </footer>
    </div>

    <aside class="right">
      <div class="promo">
        <div style="display:flex;justify-content:space-between;align-items:center">
          <div style="text-align:left">
            <div style="font-size:12px;color:var(--muted);font-weight:600">Flat</div>
            <div class="percent">20% Off</div>
          </div>
          <div style="width:120px;height:120px;border-radius:10px;overflow:hidden;background:white;box-shadow:0 10px 30px rgba(15,23,42,0.06)">
            <img src="/mnt/data/45.jpg" alt="Orbit watch" style="width:100%;height:100%;object-fit:cover">
          </div>
        </div>

        <div class="watch-img">
          <img src="/mnt/data/45.jpg" alt="Watch showcase">
        </div>

        <div style="display:flex;justify-content:space-between;align-items:center">
          <div>
            <div style="font-size:13px;color:var(--muted)">Classic Automatic</div>
            <div style="font-weight:800;font-size:18px">Heritage Series</div>
          </div>
          <div style="text-align:right">
            <div style="font-size:13px;color:var(--muted);text-decoration:line-through">₹7,999</div>
            <div style="font-weight:900;font-size:20px">₹6,399</div>
          </div>
        </div>
      </div>

      <div class="order">
        <small>Use coupon <strong>ORBIT20</strong> at checkout to apply discount</small>
        <div class="buy">
          <button class="btn" id="buyBtn">Buy Now</button>
          <button class="btn secondary" id="cartBtn">Add to Cart</button>
        </div>
      </div>
    </aside>
  </div>

  <script>
    document.getElementById('orderBtn').addEventListener('click', function(){
      alert('Great choice! Coupon ORBIT20 will be applied at checkout.');
    });
    document.getElementById('buyBtn').addEventListener('click', function(){
      // simple demo behaviour
      alert('Redirecting to secure checkout... (demo)');
    });
    document.getElementById('learnBtn').addEventListener('click', function(){
      alert('We can build your website. Tell me what platform you prefer (Shopify, WordPress, custom) and I\'ll give a plan.');
    });
  </script>
</body>
</html>
