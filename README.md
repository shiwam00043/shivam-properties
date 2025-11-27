# Shivam-properties
Best properties in sirmour
<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shivam Properties - Himachal Real Estate</title>
  <meta name="description" content="Himachal Pradesh land for sale — 100 bigha and 500 bigha available. Contact Shivam for details." />
  <meta name="keywords" content="Himachal property, land for sale Himachal, bigha, Shivam" />
  <meta name="author" content="Shivam" />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=" />
  <style>
    :root{--accent:#0b76ef;--bg:#f7f9fc;--card:#ffffff}
    *{box-sizing:border-box}
    body{font-family:system-ui,Segoe UI,Roboto,Arial;margin:0;background:var(--bg);color:#0b2540}
    .container{max-width:1100px;margin:24px auto;padding:16px}
    header{display:flex;align-items:center;gap:12px}
    .logo{background:var(--accent);color:white;padding:10px 14px;border-radius:8px;font-weight:700}
    nav{margin-left:auto}
    nav a{margin-left:12px;color:#0b2540;text-decoration:none;font-weight:600}
    .hero{background:url('https://images.unsplash.com/photo-1470770903676-69b98201ea1c') center/cover no-repeat;border-radius:12px;padding:48px;color:white;margin-top:16px}
    .hero h1{margin:0 0 8px;font-size:28px}
    .hero p{margin:0 0 16px}
    .btn{background:white;color:var(--accent);padding:10px 14px;border-radius:8px;font-weight:700;text-decoration:none}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-top:18px}
    .card{background:var(--card);padding:14px;border-radius:10px;box-shadow:0 4px 14px rgba(11,37,64,0.06)}
    .prop-img{height:160px;border-radius:8px;background:#ddd;background-size:cover;background-position:center}
    footer{margin-top:24px;padding:20px 0;color:#415162;font-size:14px;text-align:center}
    .contact-form input,.contact-form textarea{width:100%;padding:10px;margin-top:8px;border:1px solid #e3e6ea;border-radius:8px}
    .contact-form button{margin-top:8px;padding:10px 14px;border-radius:8px;border:0;background:var(--accent);color:white;font-weight:700}
    @media (max-width:600px){.hero{padding:24px}}
  </style>
</head>
<body>

  <div class="container">
    <header>
      <div class="logo">Shivam</div>
      <nav>
        <a href="#properties">Properties</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <h1>Shivam Properties</h1>
      <p>2 exclusive land parcels available in Himachal. Perfect for farming or investment.</p>
      <a href="#contact" class="btn">Contact Shivam</a>
    </section>

    <section id="properties">
      <h2 style="margin-top:18px">Available Properties (Himachal Pradesh)</h2>
      <div class="grid">
        <article class="card">
          <div class="prop-img" style="background-image:url('https://images.unsplash.com/photo-1470770903676-69b98201ea1c')"></div>
        </article>
      </div>
    </section>

    <section id="contact" style="margin-top:22px">
      <h2>Contact</h2>
      <div class="grid">
        <div class="card">
          <h3>Call / Message</h3>
          <p><strong>Phone:</strong> +91 8883300043</p>
          <p><strong>Email:</strong> contact.shivamproperties@gmail.com</p>
          <p><strong>Location:</strong> Himachal Pradesh, India</p>
        </div>

        <div class="card contact-form">
          <h3>Send a message</h3>
          <form action="https://formspree.io/f/your-form-id" method="POST">
            <label>Naam</label>
            <input type="text" name="name" required />
            <label>Phone</label>
            <input type="text" name="phone" required />
            <label>Message</label>
            <textarea name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
          </form>
        </div>

      </div>
    </section>

    <footer>
      <p>© Shivam — Himachal Property. All rights reserved.</p>
    </footer>
  </div>

</body>
</html>
