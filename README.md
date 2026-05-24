<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Flex Time BD</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
background:#f5f5f7;
}

header{
background:#000;
color:#fff;
padding:20px;
text-align:center;
font-size:28px;
font-weight:bold;
}

.banner{
background:linear-gradient(135deg,#000,#444);
color:white;
text-align:center;
padding:60px 20px;
}

.banner h1{
font-size:40px;
margin:0;
}

.banner p{
opacity:0.8;
margin-top:10px;
}

.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:30px;
}

.card{
background:white;
width:280px;
padding:15px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
text-align:center;
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
border-radius:15px;
}

.price{
font-size:22px;
font-weight:bold;
color:green;
}

.btn{
display:inline-block;
margin-top:10px;
padding:12px 18px;
background:#25D366;
color:white;
text-decoration:none;
border-radius:10px;
}

footer{
background:#000;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}

</style>
</head>

<body>

<header>
Flex Time BD
</header>

<section class="banner">
<h1>Premium Gadgets Store</h1>
<p>Latest Smart Watch & Headphones</p>
</section>

<section class="products">

<div class="card">
<img src="watch.jpg" alt="Smart Watch">

<h2>Smart Watch</h2>

<p class="price">৳1299</p>

<a class="btn"
href="https://wa.me/8801980976522">
Order Now
</a>

</div>

<div class="card">
<img src="p9.jpg" alt="P9 Headphone">

<h2>P9 Headphone</h2>

<p class="price">৳850</p>

<a class="btn"
href="https://wa.me/8801980976522">
Order Now
</a>

</div>

</section>

<footer>
© 2026 Flex Time BD
</footer>

</body>
</html>
