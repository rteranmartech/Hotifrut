<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Frutas Frescas y Congeladas</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav {
            background-color: #388E3C;
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .social {
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 0.5rem 0;
            background-color: #81C784;
        }

        .section {
            padding: 2rem;
        }

        h2 {
            color: #4CAF50;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 0.5rem;
        }

        /* Grid para las cards */
        .cards {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1rem;
            margin-top: 1rem;
        }

        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .card img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            margin-bottom: 1rem;
        }

        .card-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .card-price {
            color: #E53935;
            font-size: 1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .card-stock {
            margin-bottom: 0.5rem;
        }

        .divider {
            background-color: #E0E0E0;
            text-align: center;
            font-weight: bold;
            padding: 1rem;
            margin: 2rem 0;
            color: #333;
        }

        .video-container {
            display: flex;
            justify-content: center;
            margin: 2rem 0;
        }

        footer {
            background-color: #f1f1f1;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
            color: #555;
        }

        /* Responsive */
        @media(max-width: 1024px) {
            .cards {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media(max-width: 600px) {
            .cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Frutas Frescas y Congeladas</h1>
    <p>Producto 100% natural - Sin aditivos - Alto en vitaminas</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Catálogo</a>
    <a href="#">Contacto</a>
</nav>

<div class="social">
    <a href="#">Instagram</a>
    <a href="#">Twitter</a>
    <a href="#">Facebook</a>
</div>

<section class="section">
    <h2>🍇 Productos destacados</h2>

    <div class="cards">
        <!-- Card 1 -->
        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Fresa+Albion" alt="Fresa Albion">
            <div class="card-title">Fresa Albion caja × 4 kg grande</div>
            <div class="card-price">$25</div>
            <div class="card-stock">Stock disponible: 25 unidades</div>
            <progress value="25" max="100">25%</progress>
        </div>

        <!-- Card 2 -->
        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Fresa+Capitola" alt="Fresa Capitola">
            <div class="card-title">Fresa Capitola caja surtida 4 kg</div>
            <div class="card-price">$22</div>
            <div class="card-stock">Stock disponible: 50 unidades</div>
            <progress value="50" max="100">50%</progress>
        </div>

        <!-- Card 3 -->
        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Fresa+Cesta" alt="Fresa Cesta">
            <div class="card-title">Fresa Capitola grande en cesta 13 kg</div>
            <div class="card-price">$55</div>
            <div class="card-stock">Stock disponible: 80 unidades</div>
            <progress value="80" max="100">80%</progress>
        </div>

        <!-- Card 4 -->
        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Guanabana" alt="Guanabana">
            <div class="card-title">Guanábana en moya sin semilla 1 kg</div>
            <div class="card-price">$2.8</div>
            <div class="card-stock">Stock disponible: 60 unidades</div>
            <progress value="60" max="100">60%</progress>
        </div>
    </div>
</section>

<!-- Separador -->
<div class="divider">🥶 Congelados y frescos los productos 🥶</div>

<!-- Video de proceso -->
<section class="section">
    <h2>🎬 Conoce cómo procesamos nuestros productos</h2>
    <div class="video-container">
        <video controls width="640" height="360">
            <source src="tu-video.mp4" type="video/mp4">
            Tu navegador no soporta la reproducción de video.
        </video>
    </div>
</section>

<!-- Más tarjetas de productos congelados -->
<section class="section">
    <h2>🍈 Ventas de productos congelados</h2>

    <div class="cards">
        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Mora" alt="Mora congelada">
            <div class="card-title">Mora congelada premium bolsa 1 kg</div>
            <div class="card-price">$3.0</div>
            <div class="card-stock">Stock disponible: 40 unidades</div>
            <progress value="40" max="100">40%</progress>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Piña" alt="Piña en cubos">
            <div class="card-title">Piña en cubos congelada 1 kg</div>
            <div class="card-price">$2.5</div>
            <div class="card-stock">Stock disponible: 70 unidades</div>
            <progress value="70" max="100">70%</progress>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Mango" alt="Pulpa de mango">
            <div class="card-title">Pulpa de mango lista para smoothies 1 kg</div>
            <div class="card-price">$3.2</div>
            <div class="card-stock">Stock disponible: 90 unidades</div>
            <progress value="90" max="100">90%</progress>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200x200?text=Mix+Berries" alt="Mix berries">
            <div class="card-title">Mix berries congelados 1 kg</div>
            <div class="card-price">$4.0</div>
            <div class="card-stock">Stock disponible: 50 unidades</div>
            <progress value="50" max="100">50%</progress>
        </div>
    </div>
</section>

<footer>
    <p>Contacto: 0424-1411022 | Correo: inversioneshortifrutca@gmail.com</p>
    <p>Ventas al mayor en toda Caracas</p>
</footer>

</body>
</html>
