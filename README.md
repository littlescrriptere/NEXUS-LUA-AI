
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brainrot Market</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  background: #10101b;
  color: white;
  font-family: Arial, sans-serif;
}
header {
  background: #1d1535;
  padding: 25px;
  text-align: center;
  border-bottom: 2px solid #9b4dff;
}
header h1 { color: #c084fc; font-size: 32px; }
header p { color: #ccc; }
.container {
  padding: 20px;
  max-width: 1000px;
  margin: auto;
}
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
  gap: 20px;
}
.product {
  background: #211d32;
  border: 1px solid #7041a5;
  border-radius: 15px;
  padding: 20px;
  text-align: center;
}
.product .emoji { font-size: 55px; }
.price { color: #a8ff60; font-size: 22px; }
button {
  background: #9333ea;
  color: white;
  border: none;
  padding: 12px 25px;
  border-radius: 9px;
  font-size: 16px;
  cursor: pointer;
}
button:hover { background: #b66aff; }
footer {
  text-align: center;
  padding: 30px;
  color: #aaa;
}
</style>
</head>
<body>

<header>
  <h1>🔥 BRAINROT MARKET 🔥</h1>
  <p>The ultimate Brainrot trading shop!</p>
</header>

<div class="container">
  <h2>🛒 Our Products</h2>

  <div class="products">

    <div class="product">
      <div class="emoji">🦈</div>
      <h3>Tralalero Tralala</h3>
      <p>Legendary Brainrot!</p>
      <p class="price">£5.00</p>
      <button onclick="buy('Tralalero Tralala')">Buy Now</button>
    </div>

    <div class="product">
      <div class="emoji">🐊</div>
      <h3>Bombardiro Crocodilo</h3>
      <p>Super rare Brainrot!</p>
      <p class="price">£7.00</p>
      <button onclick="buy('Bombardiro Crocodilo')">Buy Now</button>
    </div>

    <div class="product">
      <div class="emoji">🐒</div>
      <h3>Chimpanzini Bananini</h3>
      <p>Ultra Brainrot!</p>
      <p class="price">£3.00</p>
      <button onclick="buy('Chimpanzini Bananini')">Buy Now</button>
    </div>

  </div>
</div>

<footer>
  <p>🔥 Brainrot Market © 2026</p>
</footer>

<script>
function buy(product) {
  alert("You selected " + product +
  "! Contact us to complete your order.");
}
</script>

</body>
</html>

