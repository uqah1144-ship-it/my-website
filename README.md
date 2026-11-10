<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jainu Restaurant</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

html{
  scroll-behavior:smooth;
}

body{
  font-family:Arial,sans-serif;
  background:#fff8f0;
  color:#222;
}

header{
  background:#111;
  color:white;
  padding:18px 20px;
  text-align:center;
}

header h1{
  color:#ffb000;
  font-size:30px;
}

header p{
  margin-top:6px;
  color:#ddd;
}

nav{
  background:#222;
  padding:12px;
  text-align:center;
  position:sticky;
  top:0;
  z-index:10;
}

nav a{
  color:white;
  text-decoration:none;
  margin:0 10px;
  font-weight:bold;
}

.hero{
  padding:60px 20px;
  text-align:center;
  background:linear-gradient(135deg,#ffb000,#ff6b00);
  color:white;
}

.hero h2{
  font-size:38px;
  margin-bottom:12px;
}

.hero p{
  font-size:18px;
  margin-bottom:25px;
}

.btn{
  display:inline-block;
  background:#111;
  color:white;
  padding:14px 25px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
}

section{
  padding:45px 20px;
  max-width:1100px;
  margin:auto;
}

section h2{
  text-align:center;
  margin-bottom:30px;
  font-size:30px;
}

.menu{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
}

.card{
  background:white;
  border-radius:15px;
  padding:25px;
  text-align:center;
  box-shadow:0 4px 15px rgba(0,0,0,.12);
}

.card .emoji{
  font-size:55px;
}

.card h3{
  margin:12px 0 8px;
}

.price{
  color:#e85d00;
  font-size:20px;
  font-weight:bold;
  margin:10px;
}

.order{
  text-align:center;
  background:#111;
  color:white;
  border-radius:20px;
}

.order h2{
  color:#ffb000;
}

.whatsapp{
  display:inline-block;
  background:#25D366;
  color:white;
  padding:15px 25px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
  margin-top:10px;
}

footer{
  background:#111;
  color:#aaa;
  text-align:center;
  padding:25px;
  margin-top:20px;
}
</style>
</head>

<body>

<header>
  <h1>🍽️ Jainu Restaurant</h1>
  <p>स्वादिष्ट खाना • अच्छी क्वालिटी • बेहतरीन सर्विस</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#menu">Menu</a>
  <a href="#order">Order</a>
</nav>

<div class="hero" id="home">
  <h2>Welcome to Jainu Restaurant</h2>
  <p>गरमा-गरम और स्वादिष्ट खाना आपके लिए ❤️</p>
  <a class="btn" href="#menu">Menu देखें</a>
</div>

<section id="menu">
  <h2>🍔 Our Menu</h2>

  <div class="menu">

    <div class="card">
      <div class="emoji">🍔</div>
      <h3>Cheese Burger</h3>
      <p>Fresh & tasty burger</p>
      <div class="price">₹99</div>
    </div>

    <div class="card">
      <div class="emoji">🍕</div>
      <h3>Veg Pizza</h3>
      <p>Cheesy & delicious pizza</p>
      <div class="price">₹149</div>
    </div>

    <div class="card">
      <div class="emoji">🍟</div>
      <h3>French Fries</h3>
      <p>Crispy golden fries</p>
      <div class="price">₹69</div>
    </div>

    <div class="card">
      <div class="emoji">🥤</div>
      <h3>Cold Drink</h3>
      <p>Chilled refreshing drink</p>
      <div class="price">₹49</div>
    </div>

    <div class="card">
      <div class="emoji">🍜</div>
      <h3>Veg Noodles</h3>
      <p>Hot & spicy noodles</p>
      <div class="price">₹99</div>
    </div>

    <div class="card">
      <div class="emoji">🥪</div>
      <h3>Veg Sandwich</h3>
      <p>Fresh & crispy sandwich</p>
      <div class="price">₹79</div>
    </div>

  </div>
</section>

<section id="order" class="order">
  <h2>📱 Order Now</h2>
  <p>WhatsApp पर अपना ऑर्डर भेजें</p>

  <a class="whatsapp"
     href="https://wa.me/917869609096?text=Hello%20Jainu%20Restaurant,%20mujhe%20order%20karna%20hai."
     target="_blank">
     WhatsApp पर Order करें
  </a>
</section>

<section>
  <h2>📍 Contact</h2>
  <p style="text-align:center;">
    Jainu Restaurant<br>
    Chhattisgarh, India<br><br>
    📞 7869609096
  </p>
</section>

<footer>
  © 2026 Jainu Restaurant. All Rights Reserved.
</footer>

</body>
</html>
