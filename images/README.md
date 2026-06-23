<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tiwari Tea Stall - Gallery</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#111;
    color:#fff;
}
.container{
    width:90%;
    margin:auto;
    padding:20px;
}
h2{
    color:#ffb347;
    border-bottom:2px solid #444;
    padding-bottom:10px;
}
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}
.card{
    background:#1e1e1e;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 5px 10px rgba(0,0,0,.5);
}
.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}
.card p{
    text-align:center;
    padding:10px;
}
</style>

</head>
<body>

<div class="container">

<h2>Logo</h2>

<div class="gallery">
<div class="card">
<img src="images/logo/logo.png" alt="Logo">
<p>Logo</p>
</div>
</div>

<h2>Banner</h2>

<div class="gallery">

<div class="card">
<img src="images/banner/hero-banner.jpg" alt="">
<p>Hero Banner</p>
</div>

<div class="card">
<img src="images/banner/welcome-banner.jpg" alt="">
<p>Welcome Banner</p>
</div>

<div class="card">
<img src="images/banner/offer-banner.jpg" alt="">
<p>Offer Banner</p>
</div>

</div>

<h2>Gallery</h2>

<div class="gallery">

<div class="card">
<img src="images/gallery/shop-front.jpg" alt="">
<p>Shop Front</p>
</div>

<div class="card">
<img src="images/gallery/tea-making.jpg" alt="">
<p>Tea Making</p>
</div>

<div class="card">
<img src="images/gallery/customers.jpg" alt="">
<p>Customers</p>
</div>

<div class="card">
<img src="images/gallery/evening-view.jpg" alt="">
<p>Evening View</p>
</div>

</div>

<h2>Menu</h2>

<div class="gallery">

<div class="card">
<img src="images/menu/masala-chai.jpg" alt="">
<p>Masala Chai</p>
</div>

<div class="card">
<img src="images/menu/adrak-chai.jpg" alt="">
<p>Adrak Chai</p>
</div>

<div class="card">
<img src="images/menu/elaichi-chai.jpg" alt="">
<p>Elaichi Chai</p>
</div>

<div class="card">
<img src="images/menu/lemon-tea.jpg" alt="">
<p>Lemon Tea</p>
</div>

<div class="card">
<img src="images/menu/coffee.jpg" alt="">
<p>Coffee</p>
</div>

<div class="card">
<img src="images/menu/samosa.jpg" alt="">
<p>Samosa</p>
</div>

<div class="card">
<img src="images/menu/pakora.jpg" alt="">
<p>Pakora</p>
</div>

<div class="card">
<img src="images/menu/bun-maska.jpg" alt="">
<p>Bun Maska</p>
</div>

</div>

</div>

</body>
</html>
