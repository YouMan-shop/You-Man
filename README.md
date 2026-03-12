<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>متجري الإلكتروني</title>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
}
header {
    background-color: #0078d4;
    color: white;
    padding: 15px;
    text-align: center;
}
h1 { margin: 0; }
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}
.product {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    margin: 10px;
    width: 200px;
    text-align: center;
    padding: 15px;
}
.product img {
    width: 100%;
    border-radius: 8px;
}
.product h2 {
    font-size: 18px;
    margin: 10px 0 5px;
}
.product p {
    color: #555;
    margin: 5px 0;
}
button {
    background-color: #0078d4;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background-color: #005a9e;
}
footer {
    text-align: center;
    padding: 15px;
    background-color: #333;
    color: white;
    margin-top: 20px;
}
</style>
</head>
<body>

<header>
<h1>متجري الإلكتروني</h1>
</header>

<div class="container">
  <div class="product">
    <img src="https://via.placeholder.com/200x200.png?text=منتج+1" alt="منتج 1">
    <h2>منتج 1</h2>
    <p>سعر: 50 دينار</p>
    <button>اشترِ الآن</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200x200.png?text=منتج+2" alt="منتج 2">
    <h2>منتج 2</h2>
    <p>سعر: 75 دينار</p>
    <button>اشترِ الآن</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200x200.png?text=منتج+3" alt="منتج 3">
    <h2>منتج 3</h2>
    <p>سعر: 100 دينار</p>
    <button>اشترِ الآن</button>
  </div>
</div>

<footer>
&copy; 2026 متجري الإلكتروني
</footer>

</body>
</html>
