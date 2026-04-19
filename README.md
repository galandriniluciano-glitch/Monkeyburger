# Monkeyburger
<!DOCTYPE html>

<html lang="es">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Monki Burger</title>

<style>

body {

    margin: 0;

    font-family: Arial, sans-serif;

    background: #fff;

}

/* HEADER */

header {

    background: #ff5a00;

    color: white;

    padding: 15px;

    display: flex;

    justify-content: space-between;

    align-items: center;

}

header h1 {

    margin: 0;

}

nav a {

    color: white;

    margin: 0 10px;

    text-decoration: none;

    font-weight: bold;

}

/* HERO */

.hero {

    background: url('https://images.unsplash.com/photo-1550547660-d9450f859349') center/cover;

    color: white;

    padding: 80px 20px;

    text-align: center;

}

.hero h2 {

    font-size: 40px;

}

.btn {

    background: #ff5a00;

    color: white;

    padding: 12px 20px;

    text-decoration: none;

    border-radius: 5px;

}

/* SECCIONES */

section {

    padding: 40px 20px;

    text-align: center;

}

/* MENU */

.menu {

    display: flex;

    flex-wrap: wrap;

    justify-content: center;

}

.card {

    border: 1px solid #ddd;

    border-radius: 10px;

    margin: 10px;

    width: 250px;

    padding: 15px;

}

.card img {

    width: 100%;

    border-radius: 10px;

}

/* MAPA */

iframe {

    width: 90%;

    height: 400px;

    border: none;

}

/* FOOTER */

footer {

    background: #222;

    color: white;

    padding: 20px;

}

/* WHATSAPP */

.whatsapp {

    position: fixed;

    bottom: 20px;

    right: 20px;

    background: #25D366;

    color: white;

    padding: 15px;

    border-radius: 50%;

    text-decoration: none;

    font-size: 20px;

}

</style>

</head>

<body>

<header>

    <h1>🍔 Monki Burger</h1>

    <nav>

        <a href="#menu">Menú</a>

        <a href="#ubicacion">Ubicación</a>

        <a href="#contacto">Contacto</a>

    </nav>

</header>

<div class="hero">

    <h2>Las mejores burgers de la zona 🔥</h2>

    <p>Pedí ahora y probá el sabor Monki</p>

    <a class="btn" href="#menu">Ver menú</a>

</div>

<section id="menu">

    <h2>🍔 Nuestro Menú</h2>

    <div class="menu">

        <div class="card">

            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd">

            <h3>Clásica</h3>

            <p>Carne, cheddar, lechuga y tomate</p>

            <strong>$2500</strong>

        </div>

        <div class="card">

            <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">

            <h3>Doble Monki</h3>

            <p>Doble carne, doble cheddar, bacon</p>

            <strong>$3500</strong>

        </div>

        <div class="card">

            <img src="https://images.unsplash.com/photo-1606755962773-d324e0a13086">

            <h3>Full Bacon</h3>

            <p>Carne, cheddar, mucho bacon 🔥</p>

            <strong>$3200</strong>

        </div>

    </div>

</section>

<section id="ubicacion">

    <h2>📍 Ubicación</h2>

    <iframe src="https://www.google.com/maps?q=&output=embed"></iframe>

</section>

<section id="contacto">

    <h2>📲 Contacto</h2>

    <p>Hacé tu pedido por WhatsApp</p>

    <a class="btn" href="https://wa.me/549XXXXXXXXXX">Pedir ahora</a>

</section>

<footer>

    <p>© 2026 Monki Burger</p>

</footer>

<a class="whatsapp" href="https://wa.me/549XXXXXXXXXX">💬</a>

</body>

</html>
