<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
    .instagram-button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
      color: white;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    .tiktok-button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: linear-gradient(45deg, #69c9d0, #ee1d52); /* TikTok's gradient colors */
      color: white;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    .email-button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #ff69b4;
      color: white;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
      margin-left: 10px;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 10px;
      max-width: 400px;
      margin: 0 auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background-color: #ff69b4;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff85c1;
    }
    .about-us {
      background-color: #fff;
      padding: 30px;
      margin-top: 30px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #ffb6c1;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
      color: white;
    }
    footer p {
      margin: 0;
      font-size: 1.2em;
    }
    .how-it-works {
      background-color: #fff;
      padding: 30px;
      margin-top: 30px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
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
        <img src="bracelet1.jpg" alt="Pink Bracelet">
        <h3>Pink Bracelet</h3>
        <p>€15 - A beautiful and elegant pink bracelet, perfect for any occasion. Made with high-quality materials.</p>
      </div>
      <div class="product">
        <img src="bracelet2.jpg" alt="Beaded Bracelet">
        <h3>Beaded Bracelet</h3>
        <p>€18 - A unique beaded design, combining style and comfort for everyday wear.</p>
      </div>
      <div class="product">
        <img src="bracelet3.jpg" alt="Gold Charm Bracelet">
        <h3>Gold Charm Bracelet</h3>
        <p>€20 - A luxurious gold bracelet with charms that make it a statement piece.</p>
      </div>
      <div class="product">
        <img src="bracelet4.jpg" alt="Silver Bracelet">
        <h3>Silver Bracelet</h3>
        <p>€25 - Classic and stylish, this silver bracelet can be worn alone or stacked with others.</p>
      </div>
      <div class="product">
        <img src="bracelet5.jpg" alt="Custom Bracelet">
        <h3>Custom Bracelet</h3>
        <p>€30 - Create your own bracelet with personalized colors and charms.</p>
      </div>
    </div>
    <a class="instagram-button" href="https://www.instagram.com/milenas_shop" target="_blank">Follow on Instagram</a>
    <a class="tiktok-button" href="https://www.tiktok.com/@milenas_shop" target="_blank">Follow on TikTok</a>
  </div>

  <!-- "Place an Order" Section moved to the center -->
  <div class="section" style="display: flex; justify-content: center; align-items: center;">
    <div>
      <h2>Place an Order</h2>
      <form action="https://formspree.io/f/xaneljap" method="POST">
        <input type="text" name="Name" placeholder="Your name" required>
        <input type="email" name="Email" placeholder="Your email" required>
        <input type="text" name="Address" placeholder="Your address" required> <!-- Added Address field -->
        <textarea name="Order Details" placeholder="Which bracelet would you like to order?" required></textarea>
        <input type="text" name="Instagram or TikTok" placeholder="Your Instagram or TikTok handle" required>
        <!-- New input field for color preferences -->
        <input type="text" name="Color Preferences" placeholder="Your preferred bracelet colors" required>
        <button type="submit">Send</button>
      </form>
    </div>
  </div>

  <!-- "About Us" moved to the bottom -->
  <div class="about-us">
    <h2>About Us</h2>
    <p>Milena_Shop is a small business dedicated to creating high-quality, beautiful bracelets for all occasions. Our goal is to provide unique and stylish accessories that will make you feel special. We value craftsmanship and attention to detail, ensuring that each piece is designed with care.</p>
  </div>

  <!-- "How it Works" Section -->
  <div class="how-it-works">
    <h2>How It Works</h2>
    <p>Once you submit your order, we will get back to you via email, Instagram, or TikTok with all the details. You can ask any questions, confirm your order, and finalize the design. For payment, we use Stripe, ensuring a secure and smooth transaction process.</p>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Milena_Shop | All rights reserved.</p>
  </footer>

</body>
</html>
