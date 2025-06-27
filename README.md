# Ollo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ollo - General Store</title>
  <style>
    :root {
      --matcha: #a8c8a0;
      --mocha: #6b4f3b;
      --bg-light: #f9f9f9;
      --text-dark: #333;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg-light);
      color: var(--text-dark);
    }

    header {
      background-color: var(--mocha);
      padding: 10px 20px;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      width: 40px;
      height: 40px;
      margin-right: 10px;
    }

    .logo h1 {
      margin: 0;
      font-size: 1.8em;
    }

    nav {
      display: flex;
      align-items: center;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    .search-bar {
      margin-left: 20px;
    }

    .search-bar input {
      padding: 6px 10px;
      border: none;
      border-radius: 4px;
      outline: none;
    }

    .hero {
      background-color: var(--matcha);
      padding: 60px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px 20px;
    }

    .product {
      background: white;
      border-radius: 8px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .product img {
      max-width: 100%;
      height: 180px;
      object-fit: contain;
    }

    .product h3 {
      margin: 15px 0 10px;
    }

    .product p {
      color: var(--mocha);
      font-weight: bold;
    }

    footer {
      background-color: var(--mocha);
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav {
        margin-top: 10px;
        flex-wrap: wrap;
        gap: 10px;
      }

      .search-bar {
        margin-top: 10px;
        margin-left: 0;
      }

      .hero h2 {
        font-size: 2em;
      }

      .logo h1 {
        font-size: 1.5em;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="https://via.placeholder.com/40x40?text=O" alt="Ollo Logo" />
      <h1>Ollo</h1>
    </div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Contact</a>
      <div class="search-bar">
        <input type="text" placeholder="Search products..." />
      </div>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Ollo</h2>
    <p>Your one-stop shop for daily essentials and more!</p>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x180?text=Item+1" alt="Product 1">
      <h3>Item One</h3>
      <p>Rs. 999</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x180?text=Item+2" alt="Product 2">
      <h3>Item Two</h3>
      <p>Rs. 749</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x180?text=Item+3" alt="Product 3">
      <h3>Item Three</h3>
      <p>Rs. 499</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Ollo Store. All rights reserved.
  </footer>

</body>
</html>

