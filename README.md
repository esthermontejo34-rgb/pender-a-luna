<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> BL STORM-SHOP </title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins', sans-serif;
}

body{
background:#111;
color:white;
}

header{
background:#000;
padding:30px;
text-align:center;
border-bottom:2px solid #d4af37;
}

.logo{
width:120px;
margin-bottom:15px;
}

header h1{
color:#d4af37;
font-size:35px;
}

header p{
color:#aaa;
margin-top:10px;
}

nav{
background:#000;
text-align:center;
padding:15px;
}

nav a{
color:#d4af37;
text-decoration:none;
margin:0 15px;
font-weight:500;
cursor:pointer;
transition:0.3s;
}

nav a:hover{
color:white;
}

.seccion{
display:none;
padding:60px 20px;
text-align:center;
animation:fade 0.4s ease-in-out;
}

.activa{
display:block;
}

@keyframes fade{
from{opacity:0;}
to{opacity:1;}
}

h2{
color:#d4af37;
margin-bottom:20px;
}

.sub{
color:#aaa;
margin-bottom:40px;
font-size:14px;
}

.productos{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
max-width:1200px;
margin:auto;
margin-bottom:60px;
}

.card{
background:linear-gradient(145deg,#1a1a1a,#111);
border-radius:18px;
overflow:hidden;
padding-bottom:20px;
border:1px solid #2a2a2a;
transition:0.35s;
}

.card:hover{
transform:translateY(-12px) scale(1.02);
box-shadow:0 15px 35px rgba(212,175,55,0.35);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
background:#222;
}

.card h3{
margin:18px 10px 5px;  
color:#d4af37;
font-size:18px;
}

.price{
color:white;
font-weight:600;
}

.review-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.review{
background:#000;
padding:20px;
border-radius:15px;
max-width:300px;
border:1px solid #d4af37;
}

.review span{
color:#d4af37;
}

.form-pago{
max-width:400px;
margin:auto;
display:flex;
flex-direction:column;
gap:15px;
}

.form-pago input{
padding:10px;
border-radius:5px;
border:none;
}

.form-pago button{
background:#d4af37;
border:none;
padding:10px;
font-weight:bold;
cursor:pointer;
}

footer{
background:#000;
text-align:center;
padding:20px;
color:#aaa;
border-top:1px solid #d4af37;
margin-top:60px;
}
</style>
</head>

<body>

<header>
<img src="logo lunita.jpeg" class="logo">
<h1> BL STORM-SHOP</h1>
<p> "Diseños únicos para fans que viven cada hitoria con intensidad"</p>
</header>

<nav>
<a onclick="mostrar('inicio')">Inicio</a>
<a onclick="mostrar('menu')">Menú</a>
<a onclick="mostrar('resenas')">Reseñas</a>
<a onclick="mostrar('pago')">Pago</a>
</nav>

<!-- INICIO -->
<section id="inicio" class="seccion activa">
<h2>Bienvenido a Panaderia Luna </h2>
<p class="sub"> Prueba nuestros dulces y deliciosos postres.</p>

<!-- ESPACIO PARA VIDEO -->
<div style="max-width:800px; margin:40px auto;">
<video width="100%" controls>
<source src="muñe.mp4" type="video/mp4">
Tu navegador no soporta el video.
</video>
</div>

</section>

<!-- MENÚ -->
<section id="menu" class="seccion">

<h2> postres de luna </h2>
<p class="sub"> Dulces y salados para cada antojo </p>

<div class="productos">

<div class="card"><img src="mini tartas.jpg"><h3>Mini Tartas </h3><p class="price">$25MX</p></div>

<div class="card"><img src="ENTREMET CHOCOLAT PRALINÉ NOISETTE.jpg"><h3>Entremet Chocolat Praline Noisette</h3><p class="price">$650MX</p></div>

<div class="card"><img src="Éclair de Fresa.jpg"><h3> Éclair de Fresa </h3><p class="price">$65MX</p></div>

<div class="card"><img src="Classic French Profiteroles.jpg"><h3>Profiteroles clasicos </h3><p class="price">$25MX</p></div>

<div class="card"><img src="roles.jpg"><h3>Roles Glaciados</h3><p class="price">$45MX</p></div>

<div class="card"><img src="galletas.jpg"><h3>Caja de 10 Galletas </h3><p class="price">$75MX</p></div>

<div class="card"><img src="gitano.jpg"><h3>Brazo Gitano</h3><p class="price">$35MX</p></div>

<div class="card"><img src="crosan.jpg"><h3>Croissant Rellenos</h3><p class="price">$40MX</p></div>

<div class="card"><img src="conchas.jpg"><h3>Conchas</h3><p class="price">$10MX</p></div>

<div class="card"><img src="bolillos.jpg"><h3>Bolillos</h3><p class="price">$5MX</p></div>

<div class="card"><img src="panecillos de queso crema.jpg"><h3>Panecillos de Queso philadelphia</h3><p class="price">$8MX</p></div>

<div class="card"><img src="Palitos de Pan.jpg"><h3>Palillos de Pan</h3><p class="price">$35MX</p></div>

<div class="card"><img src="pan con ajo.jpg"><h3>Pan con Ajo </h3><p class="price">$65MX</p></div>

<div class="card"><img src="baguette de mozzarella.jpg"><h3>Baguette de Mozzarella</h3><p class="price">$55MX</p></div>

<div class="card"><img src="🥐 Brioche Hot Dog Buns 🥐.jpg"><h3>Brioche Hot Dog Buns</h3><p class="price">$10MX</p></div>






</section>

<!-- RESEÑAS -->
<section id="resenas" class="seccion">
<h2>⭐ Reseñas</h2>

<div class="review-container">
<div class="review"><p>"Excelente calidad y muy buena presentación."</p><span>★★★★★</span></div>
<div class="review"><p>"Muy buen sabor y excelente atención."</p><span>★★★★★</span></div>
<div class="review"><p>"Los profiteroles son muy ricos."</p><span>★★★★☆</span></div>
<div class="review"><p>"Precios muy  accesibles y buena calidad."</p><span>★★★★★</span></div>
</div>

</section>

<!-- PAGO -->
<section id="pago" class="seccion">
<h2>💳 Pago con tarjeta</h2>

<form class="form-pago">
<input type="text" placeholder="Nombre en la tarjeta">
<input type="text" placeholder="Número de tarjeta">
<input type="text" placeholder="MM/AA">
<input type="text" placeholder="CVV">
<button type="submit">Pagar ahora</button>
</form>

</section>

<footer>
© 2026 panaderia Luna | Todos los derechos reservados
</footer>

<script>
function mostrar(id){
document.querySelectorAll('.seccion').forEach(sec=>{
sec.classList.remove('activa');
});
document.getElementById(id).classList.add('activa');
}

document.querySelector('.form-pago').addEventListener('submit', function(e){
e.preventDefault();
alert(" Pago realizado con éxito. ¡Gracias por comprar en Panaderia Luna!");
});
</script>

</body>
</html>
