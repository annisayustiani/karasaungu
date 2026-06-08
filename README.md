<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KARASA UNGU - Karakter Rasa Ubi Ungu</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f8f2fb;
color:#4b2e5e;
}

header{
background:white;
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:100;
box-shadow:0 2px 10px rgba(0,0,0,0.05);
}

.logo{
font-size:28px;
font-weight:bold;
color:#6a1b9a;
}

nav a{
text-decoration:none;
margin-left:25px;
color:#4b2e5e;
font-weight:600;
}

.hero{
display:flex;
align-items:center;
justify-content:space-between;
padding:80px 8%;
gap:50px;
flex-wrap:wrap;
}

.hero-text{
flex:1;
}

.hero-text h1{
font-size:70px;
line-height:1;
color:#6a1b9a;
}

.hero-text h2{
font-size:35px;
margin:15px 0;
font-weight:400;
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:#7b1fa2;
color:white;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

.hero img{
width:450px;
max-width:100%;
border-radius:20px;
}

.section{
padding:80px 8%;
}

.section-title{
text-align:center;
font-size:38px;
margin-bottom:40px;
color:#6a1b9a;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.card-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:18px;
box-shadow:0 3px 15px rgba(0,0,0,0.08);
}

.card h3{
margin-bottom:15px;
color:#6a1b9a;
}

.menu{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.menu-item{
background:white;
border-radius:20px;
overflow:hidden;
box-shadow:0 3px 15px rgba(0,0,0,0.08);
}

.menu-item img{
width:100%;
height:250px;
object-fit:cover;
}

.menu-item h3{
padding:15px;
text-align:center;
color:#6a1b9a;
}

.menu-item p{
padding:0 15px 20px;
text-align:center;
}

.contact{
background:#6a1b9a;
color:white;
text-align:center;
padding:70px 8%;
}

.contact h2{
margin-bottom:20px;
}

footer{
background:#4b2e5e;
color:white;
text-align:center;
padding:20px;
}

@media(max-width:768px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-text h1{
font-size:50px;
}

.about{
grid-template-columns:1fr;
}

nav{
display:none;
}
}
</style>
</head>

<body>

<header>
<div class="logo">KARASA UNGU</div>

<nav>
<a href="#tentang">Tentang</a>
<a href="#visi">Visi & Misi</a>
<a href="#manfaat">Manfaat</a>
<a href="#menu">Menu</a>
<a href="#kontak">Kontak</a>
</nav>
</header>

<section class="hero">

<div class="hero-text">
<h1>KARASA<br>UNGU</h1>

<h2>Karakter Rasa Ubi Ungu</h2>

<p>
Segarnya Ubi Ungu, Karakternya Selalu Baru.
Minuman berbahan dasar ubi ungu pilihan yang
kaya nutrisi dan cita rasa khas.
</p>

<a href="#kontak" class="btn">Pesan Sekarang</a>

<br><br>

<p>
📞 089656387208<br>
📍 Sayang, Jatinangor<br>
📸 @berkarakterr.id
</p>

</div>

<img src="hero.jpg" alt="Karasa Ungu">

</section>

<section class="section" id="tentang">

<h2 class="section-title">Tentang Kami</h2>

<div class="about">

<img src="logo.png" alt="Karasa Ungu">

<div>

<p>
KARASA UNGU merupakan usaha minuman berbasis agribisnis
yang mengolah ubi ungu menjadi minuman kekinian dengan
cita rasa khas dan kandungan nutrisi yang baik bagi tubuh.
</p>

<br>

<p>
Nama "Karasa" merupakan singkatan dari Karakter Rasa Ubi Ungu.
Kata "Karakter" terinspirasi dari usaha fashion Berkarakter.id
yang mengedepankan kualitas, keunikan, dan identitas yang kuat.
</p>

</div>

</div>

</section>

<section class="section" id="visi">

<h2 class="section-title">Visi & Misi</h2>

<div class="card-container">

<div class="card">
<h3>Visi</h3>
<p>
Menjadi usaha minuman berbasis agribisnis yang inovatif
dalam mengolah ubi ungu lokal menjadi produk bernilai tambah.
</p>
</div>

<div class="card">
<h3>Misi</h3>
<p>
Mengolah ubi ungu menjadi produk berkualitas, mendukung
petani lokal, dan menghadirkan minuman sehat untuk semua.
</p>
</div>

</div>

</section>

<section class="section" id="manfaat">

<h2 class="section-title">Manfaat Ubi Ungu</h2>

<div class="card-container">

<div class="card">
<h3>Kaya Antioksidan</h3>
<p>Mengandung antosianin yang baik untuk tubuh.</p>
</div>

<div class="card">
<h3>Tinggi Serat</h3>
<p>Membantu menjaga kesehatan pencernaan.</p>
</div>

<div class="card">
<h3>Sumber Energi</h3>
<p>Karbohidrat alami untuk aktivitas harian.</p>
</div>

<div class="card">
<h3>Bahan Alami</h3>
<p>Memiliki warna ungu alami tanpa pewarna sintetis.</p>
</div>

</div>

</section>

<section class="section" id="menu">

<h2 class="section-title">Menu Favorit Kami</h2>

<div class="menu">

<div class="menu-item">
<img src="original.jpg">
<h3>Original Purple</h3>
<p>Perpaduan ubi ungu dan susu yang creamy.</p>
</div>

<div class="menu-item">
<img src="cheese.jpg">
<h3>Purple Cheese</h3>
<p>Kombinasi ubi ungu dengan topping keju.</p>
</div>

<div class="menu-item">
<img src="choco.jpg">
<h3>Purple Choco</h3>
<p>Perpaduan ubi ungu dan cokelat manis.</p>
</div>

<div class="menu-item">
<img src="fresh.jpg">
<h3>Purple Fresh</h3>
<p>Minuman ringan yang segar dan menyegarkan.</p>
</div>

</div>

</section>

<section class="contact" id="kontak">

<h2>Hubungi Kami</h2>

<p>📞 089656387208</p>
<p>📍 Sayang, Jatinangor</p>
<p>📸 Instagram: @berkarakterr.id</p>

</section>

<footer>
© 2026 KARASA UNGU - Karakter Rasa Ubi Ungu
</footer>

</body>
</html>
