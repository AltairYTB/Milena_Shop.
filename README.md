<DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Milena_Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #ffe6f0;
      color: #333;
    }
    header {
      background-color: #ffb6c1;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: white;
    }
    .section {
      padding: 30px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .product {
      background: white;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }

    .social-button {
      display: inline-block;
      margin: 15px 10px 0;
      padding: 12px 22px;
      border-radius: 25px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .instagram-button {
      background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
    }

    .tiktok-button {
      background: linear-gradient(45deg, #69C9D0, #EE1D52, #010101);
    }

    .gmail-button {
      background-color: #D44638;
    }

    .info-section {
      background-color: white;
      margin: 40px auto 0;
      max-width: 800px;
      border-radius: 15px;
      padding: 30px;
      box-shadow: 0 0 20px rgba(0,0,0,0.05);
    }

    .info-section h2 {
      color: #ff69b4;
      margin-bottom: 10px;
    }

    .features {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .feature {
      background-color: #fff0f5;
      border-radius: 15px;
      padding: 20px;
      margin: 10px;
      width: 220px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    footer {
      background-color: #ffb6c1;
      text-align: center;
      padding: 20px;
      color: white;
      margin-top: 40px;
    }

    footer a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      margin: 0 10px;
    }

  </style>
</head>
<body>

  <header>
    <h1>Milena_Shop</h1>
  </header>

  <div class="section">
    <h2>Our Bracelets</h2>
    <div class="products">
      <div class="product">
        <img src="bracelet1.jpg" alt="Pink Dream" />
        <h3>Pink Dream</h3>
        <p>€15</p>
      </div>
      <div class="product">
        <img src="bracelet2.jpg" alt="Beaded Bliss" />
        <h3>Beaded Bliss</h3>
        <p>€18</p>
      </div>
      <div class="product">
        <img src="bracelet3.jpg" alt="Rainbow Joy" />
        <h3>Rainbow Joy</h3>
        <p>€17</p>
      </div>
      <div class="product">
        <img src="bracelet4.jpg" alt="Ocean Heart" />
        <h3>Ocean Heart</h3>
        <p>€16</p>
      </div>
      <div class="product">
        <img src="bracelet5.jpg" alt="Golden Touch" />
        <h3>Golden Touch</h3>
        <p>€20</p>
      </div>
      <div class="product">
        <img src="bracelet6.jpg" alt="Lavender Sparkle" />
        <h3>Lavender Sparkle</h3>
        <p>€19</p>
      </div>
    </div>

    <!-- Social Buttons -->
    <a class="social-button instagram-button" href="https://www.instagram.com/milenas_shop/?igsh=enhyZnljazhvYzRr#" target="_blank">Instagram</a>
    <a class="social-button tiktok-button" href="https://www.tiktok.com/@milenas_shop" target="_blank">TikTok</a>
    <a class="social-button gmail-button" href="https://gmail.google.com/mail/?view=cm&fs=1&to=milenashop115@gmail.com,bichr0202@gmail.com" target="_blank">Contact Us</a>
  </div>

  <!-- About Us -->
  <div class="info-section">
    <h2>About Milena_Shop</h2>
    <p>We are two passionate girls creating handmade bracelets with love 💕. Each piece is unique and crafted to elevate your everyday style ✨.</p>
  </div>

  <!-- Features -->
  <div class="info-section">
    <h2>Why Choose Us?</h2>
    <div class="features">
      <div class="feature">
        <h3>💌 Handmade with Love</h3>
        <p>Every bracelet is carefully designed and handmade in our studio.</p>
      </div>
      <div class="feature">
        <h3>🚚 Fast Delivery</h3>
        <p>We ship your order within 48h to get it to you quickly.</p>
      </div>
      <div class="feature">
        <h3>🎁 Perfect Gift</h3>
        <p>Our bracelets are the cutest gift for friends, sisters, or yourself!</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <p>Follow us on:
      <a href="https://www.instagram.com/milenas_shop/" target="_blank">Instagram</a> |
      <a href="https://www.tiktok.com/@milenas_shop" target="_blank">TikTok</a> |
      <a href="https://mail.google.com/mail/?view=cm&fs=1&to=milenashop115@gmail.com,bichr0202@gmail.com" target="_blank">Email Us</a>
    </p>
    <p>© 2025 Milena_Shop. All rights reserved.</p>
  </footer>

</body>
</html>
