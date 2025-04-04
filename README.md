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
  </style>
</head>
<body>
  <header>
    <h1>Milena_Shop</h1>
  </header>

  <div class="section">
    <h2>Our Bracelets</h2>
    <div class="products">
      <!-- Replace with real photos -->
      <div class="product">
        <img src="bracelet1.jpg" alt="Bracelet 1">
        <h3>Pink Bracelet</h3>
        <p>€15</p>
      </div>
      <div class="product">
        <img src="bracelet2.jpg" alt="Bracelet 2">
        <h3>Beaded Bracelet</h3>
        <p>€18</p>
      </div>
    </div>
    <a class="instagram-button" href="https://www.instagram.com/milenas_shop/?igsh=enhyZnljazhvYzRr#" target="_blank">Follow on Instagram</a>
    <a class="email-button" href="mailto:mimikataie@gmail.com,bichr0202@gmail.com" target="_blank">Contact Us via Gmail</a>
  </div>

  <div class="section">
    <h2>Place an Order</h2>
    <form action="#" method="POST">
      <input type="text" name="Name" placeholder="Your name" required>
      <input type="email" name="Email" placeholder="Your email" required>
      <textarea name="Order Details" placeholder="Which bracelet would you like to order?" required></textarea>
      <button type="submit">Send</button>
    </form>
  </div>
</body>
</html>
