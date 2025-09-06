# My-store
I place to make an expression with cash 
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>FreshBite — Local Food Store</title>
  <meta name="description" content="FreshBite — delicious ready-to-eat meals, fresh produce, and friendly service." />
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fff8f3;
      --accent:#ff6b35;
      --muted:#6b6b6b;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.6);
      --radius:14px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      color-scheme: light;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#fff 0%,var(--bg) 100%);color:#222}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 20px;background:transparent}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:48px;height:48px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#ff9a66);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:18px;box-shadow:0 6px 20px rgba(255,107,53,0.18)}
    .brand h1{margin:0;font-size:18px}
    nav{display:flex;gap:12px;align-items:center}
    nav a{font-weight:600;color:var(--muted);text-decoration:none}/* HERO */
.hero{display:grid;grid-template-columns:1fr;gap:18px;padding:28px 20px 40px;align-items:center}
.hero-inner{background:linear-gradient(180deg, rgba(255,255,255,0.8), rgba(255,255,255,0.6));padding:22px;border-radius:20px;box-shadow:0 10px 30px rgba(15,15,15,0.06);display:flex;flex-direction:column;gap:14px}
.hero h2{margin:0;font-size:28px}
.hero p{margin:0;color:var(--muted)}
.cta{display:inline-block;background:var(--accent);color:#fff;padding:12px 18px;border-radius:12px;text-decoration:none;font-weight:700}

/* products grid */
.container{max-width:1100px;margin:18px auto;padding:0 18px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.card{background:var(--card);border-radius:14px;padding:12px;box-shadow:0 6px 18px rgba(12,12,12,0.05);display:flex;gap:12px;align-items:center}
.card img{width:110px;height:80px;border-radius:10px;object-fit:cover;flex-shrink:0}
.card h3{margin:0;font-size:16px}
.price{font-weight:700;color:var(--accent)}

/* feature row */
.features{display:flex;gap:12px;flex-wrap:wrap;margin:18px 0}
.feature{flex:1;min-width:160px;background:var(--glass);padding:12px;border-radius:12px;text-align:center}

footer{padding:26px 20px;color:var(--muted);font-size:14px}

/* responsive */
@media(min-width:720px){
  .hero{grid-template-columns:1fr 420px}
  .grid{grid-template-columns:repeat(3,1fr)}
  .hero h2{font-size:34px}
}

  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">FB</div>
      <div>
        <h1>FreshBite</h1>
        <div style="font-size:12px;color:var(--muted)">Local food • Fresh daily</div>
      </div>
    </div>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero container">
    <div class="hero-inner">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <div>
          <h2>Delicious meals. Honest prices. Made with love.</h2>
          <p>Ready-to-eat dishes, fresh produce, and weekly specials — delivered or picked up from our store.</p>
        </div>
      </div>
      <div style="display:flex;gap:12px;flex-wrap:wrap">
        <a class="cta" href="#menu">Shop the Menu</a>
        <a style="padding:12px 18px;border-radius:12px;background:transparent;border:1px solid #eee;text-decoration:none;font-weight:700;color:var(--muted)" href="#contact">Get in touch</a>
      </div>
    </div><div style="border-radius:18px;overflow:hidden;box-shadow:0 20px 60px rgba(0,0,0,0.06)">
  <img src="https://images.unsplash.com/photo-1604908177622-6d7d9fc5d7c8?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=8f4f0737e2d9f6465c2c2b3a2d78b8b5" alt="Assorted meals" style="width:100%;height:100%;object-fit:cover;display:block">
</div>

  </section>  <main class="container">
    <h2 id="menu" style="margin:8px 0 12px">Popular right now</h2>
    <div class="grid">
      <article class="card">
        <img src="https://images.unsplash.com/photo-1551218808-94e220e084d2?q=80&w=800&auto=format&fit=crop&s=0f6f2e1d2f7c9c1b9a0e7a5b1c9d3f6e" alt="Spicy jollof rice">
        <div>
          <h3>Spicy Jollof Rice</h3>
          <p style="margin:6px 0;color:var(--muted);font-size:14px">Classic, smoky, and perfectly spiced.</p>
          <div class="price">₦2,000</div>
        </div>
      </article><article class="card">
    <img src="https://images.unsplash.com/photo-1542831371-d531d36971e6?q=80&w=800&auto=format&fit=crop&s=5b5f7ad7f9b4b3f6e2b1c8d5a9e6f7c3" alt="Grilled chicken">
    <div>
      <h3>Grilled Chicken & Plantain</h3>
      <p style="margin:6px 0;color:var(--muted);font-size:14px">Smoky-sweet plantain with char-grilled chicken.</p>
      <div class="price">₦2,500</div>
    </div>
  </article>

  <article class="card">
    <img src="https://images.unsplash.com/photo-1569058249223-3d6e12b8f0b0?q=80&w=800&auto=format&fit=crop&s=7b1a0f8f5a3d4b2c6e1f3a9b8c7d6e5f" alt="Fresh salad">
    <div>
      <h3>Fresh Market Salad</h3>
      <p style="margin:6px 0;color:var(--muted);font-size:14px">Seasonal greens, citrus dressing.</p>
      <div class="price">₦1,200</div>
    </div>
  </article>
</div>

<section style="margin-top:18px">
  <h2 id="about">About FreshBite</h2>
  <p style="color:var(--muted);max-width:820px">We’re a small local business focused on fresh ingredients and friendly service. Everything is prepared daily with care — from traditional favorites to lighter, health-forward choices. Order for pickup or ask about our delivery.</p>

  <div class="features" style="margin-top:12px">
    <div class="feature">
      <strong>Fresh daily</strong>
      <div style="font-size:13px;color:var(--muted)">No preservatives</div>
    </div>
    <div class="feature">
      <strong>Pickup & Delivery</strong>
      <div style="font-size:13px;color:var(--muted)">Fast & reliable</div>
    </div>
    <div class="feature">
      <strong>Friendly prices</strong>
      <div style="font-size:13px;color:var(--muted)">Meals from ₦1,000</div>
    </div>
  </div>
</section>

<section id="contact" style="margin-top:22px;padding:18px;border-radius:12px;background:linear-gradient(180deg,#fff,#fffaf6);box-shadow:0 8px 30px rgba(0,0,0,0.04)">
  <h3>Contact & Orders</h3>
  <p style="color:var(--muted);margin-top:6px">Phone: <strong>+234 800 000 0000</strong> • Visit: <strong>10 Market Street, Lagos</strong></p>
  <p style="color:var(--muted);margin-top:6px">To change details: open this file and edit the text inside the &lt;main&gt; area. Replace the image URLs with your own or upload images to the repo and use relative paths like <code>images/meal1.jpg</code>.</p>
</section>

  </main>  <footer>
    <div class="container">© <strong>FreshBite</strong> — Made with care • Follow us on social media</div>
  </footer>
</body>
</html>
