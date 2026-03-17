<!DOCTYPE html>
<html>
<head>
<title>YOUR AK COLLECTION</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial;
  margin: 0;
  background: #f5f5f5;
}

header {
  background: #ff3f6c;
  color: white;
  padding: 15px;
  text-align: center;
  font-size: 22px;
}

.banner {
  background: url('https://via.placeholder.com/400x150') no-repeat center;
  background-size: cover;
  height: 150px;
}

.categories {
  display: flex;
  overflow-x: scroll;
  padding: 10px;
}

.cat {
  background: white;
  padding: 10px;
  margin: 5px;
  border-radius: 10px;
  min-width: 100px;
  text-align: center;
  font-size: 14px;
}

.products {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
  padding: 10px;
}

.product {
  background: white;
  padding: 10px;
  border-radius: 10px;
}

.product img {
  width: 100%;
  border-radius: 10px;
}

button {
  background: #25D366;
  color: white;
  border: none;
  padding: 8px;
  width: 100%;
  border-radius: 5px;
  margin-top: 5px;
}

.footer {
  text-align: center;
  padding: 10px;
  background: #222;
  color: white;
}
</style>
</head>

<body>

<header>
YOUR AK COLLECTION
</header>

<div class="banner"></div>

<h3 style="padding-left:10px;">Categories</h3>
<div class="categories">
  <div class="cat">T-Shirts</div>
  <div class="cat">Electronics</div>
  <div class="cat">Shoes</div>
  <div class="cat">Accessories</div>
</div>

<h3 style="padding-left:10px;">Trending Products</h3>
<div class="products">

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <p>T-Shirt</p>
    <p>₹299</p>
    <button onclick="order()">Order on WhatsApp</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/150">
    <p>Headphones</p>
    <p>₹599</p>
    <button onclick="order()">Order on WhatsApp</button>
  </div>

</div>

<div class="footer">
📞 Call: 8860293477 / 7827556760 <br>
🚚 Delivery Available
</div>

<script>
function order() {
  window.open("https://wa.me/918860293477");
}
</script>

</body>
</html>