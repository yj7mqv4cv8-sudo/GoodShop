<!DOCTYPE html>
<html lang="bs">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Moderni Online Shop</title>

<!-- SEO -->
<meta name="description" content="Elegantni i moderan online shop sa minimalističkim dizajnom i brzim iskustvom kupovine.">
<meta name="keywords" content="online shop, prodavnica, web shop, kupovina, moderna web stranica">

<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #f3f3f3;
  color: #111;
}

/* HERO */
.hero {
  background: linear-gradient(135deg, #111, #444);
  color: #fff;
  text-align: center;
  padding: 80px 30px;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 10px;
}

.hero p {
  opacity: 0.9;
}

.btn-main {
  margin-top: 20px;
  padding: 14px 28px;
  border: none;
  border-radius: 30px;
  background: #fff;
  color: #111;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}
.btn-main:hover { transform: scale(1.05); }

/* PRODUCTS */
.shop {
  max-width: 1100px;
  margin: 50px auto;
  padding: 0 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 25px;
}

.card {
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  padding: 18px;
  text-align: center;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

.price {
  font-size: 18px;
  font-weight: bold;
  margin: 8px 0;
}

.btn-buy {
  padding: 10px 22px;
  border: none;
  border-radius: 25px;
  background: #111;
  color: #fff;
  cursor: pointer;
  transition: 0.3s;
}
.btn-buy:hover { opacity: 0.85; }

/* FOOTER */
footer {
  text-align: center;
  padding: 25px;
  opacity: 0.7;
}
</style>
</head>

<body>

<section class="hero">
  <h1>Kupovina koja inspiriše</h1>
  <p>Kvaliteta na jedan klik — moderan i elegantan online shop.</p>
  <button class="btn-main">Pogledaj ponudu</button>
</section>

<section class="shop">
  <div class="grid">

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="Proizvod">
      <h3>Premium Proizvod 1</h3>
      <p class="price">49 KM</p>
      <button class="btn-buy">Dodaj u korpu</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="Proizvod">
      <h3>Premium Proizvod 2</h3>
      <p class="price">69 KM</p>
      <button class="btn-buy">Dodaj u korpu</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="Proizvod">
      <h3>Premium Proizvod 3</h3>
      <p class="price">89 KM</p>
      <button class="btn-buy">Dodaj u korpu</button>
    </div>

  </div>
</section>

<footer>
  © 2025 — Moderni Online Shop
</footer>

</body>
</html>
