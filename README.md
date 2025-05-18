# Shop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Zapsta | Online Shop</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
    }

    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .product {
      background: white;
      border-radius: 10px;
      padding: 15px;
      margin: 20px 0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .product img {
      width: 150px;
      border-radius: 8px;
    }

    .info {
      flex: 1;
      margin-left: 20px;
    }

    .info h2 {
      margin-top: 0;
    }

    .price {
      font-size: 1.2em;
      color: #28a745;
    }

    button {
      padding: 10px 20px;
      background: #28a745;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #218838;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>Zapsta</h1>
  <p>Scroll It. Want It. Zapsta Got It.</p>
</header>

<div class="container">
  <div class="product">
    <img src="https://via.placeholder.com/150" alt="Product 1" />
    <div class="info">
      <h2>Wireless Earbuds</h2>
      <p>High quality, noise cancelling earbuds for your everyday needs.</p>
      <p class="price">$19.99</p>
      <button onclick="order('Wireless Earbuds')">Buy Now</button>
    </div>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150" alt="Product 2" />
    <div class="info">
      <h2>Smart Watch</h2>
      <p>Track your health, stay connected, and look stylish at the same time.</p>
      <p class="price">$29.99</p>
      <button onclick="order('Smart Watch')">Buy Now</button>
    </div>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150" alt="Product 3" />
    <div class="info">
      <h2>LED Desk Lamp</h2>
      <p>Adjustable brightness, touch control, and perfect for your workspace.</p>
      <p class="price">$14.99</p>
      <button onclick="order('LED Desk Lamp')">Buy Now</button>
    </div>
  </div>
</div>

<footer>
  &copy; 2025 Zapsta. All rights reserved.
</footer>

<script>
  function order(productName) {
    alert(`Thank you for your interest in "${productName}"!\nPlease DM us on Instagram @zapsta.store to order.`);
  }
</script>

</body>
</html>
