# Dropshipping
Real
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FitVibe – Dein Fitness-Shop</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
      color: #111;
    }
    header {
      background: #00C28A;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      background: #111;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1571019613914-85f342c55f57') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 3rem;
      text-shadow: 2px 2px 10px #000;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .product-card {
      border: 1px solid #ccc;
      padding: 20px;
      width: 250px;
      border-radius: 10px;
      transition: box-shadow 0.3s;
    }
    .product-card:hover {
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    .product-card img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    footer {
      background: #f0f0f0;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>FitVibe</h1>
    <p>Dein Onlineshop für effektives Training</p>
  </header>

  <nav>
    <a href="#">Start</a>
    <a href="#">Shop</a>
    <a href="#">Über uns</a>
    <a href="#">Kontakt</a>
  </nav>

  <div class="hero">
    Starte dein Training heute!
  </div>

  <div class="section">
    <h2>Bestseller-Produkte</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1" alt="Widerstandsband">
        <h3>Widerstandsband Pro</h3>
        <p>Perfekt für Home-Workouts</p>
        <p><strong>19,99 €</strong></p>
        <button>Jetzt kaufen</button>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1599058917211-9f1b6c924b86" alt="Shaker">
        <h3>Shaker Bottle</h3>
        <p>Stylisch & auslaufsicher</p>
        <p><strong>12,99 €</strong></p>
        <button>Jetzt kaufen</button>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1598972435752-6f63c4f02a04" alt="Handschuhe">
        <h3>Trainingshandschuhe</h3>
        <p>Grip & Schutz beim Workout</p>
        <p><strong>14,99 €</strong></p>
        <button>Jetzt kaufen</button>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 FitVibe | Impressum | Datenschutz
  </footer>

</body>
</html>