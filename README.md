<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Negocio de Muebles</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .hero {
            background-image: url('tu-imagen-de-fondo.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 3em;
        }
        .section {
            padding: 60px 20px;
            text-align: center;
        }
        .section h2 {
            margin-bottom: 40px;
            font-size: 2em;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product {
            background-color: white;
            margin: 15px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Negocio de Muebles</h1>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#sobre-nosotros">Sobre Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="hero" id="inicio">
        <h1>Muebles de Calidad para tu Hogar</h1>
        <p>Diseños modernos y confortables</p>
    </div>

    <section class="section" id="productos">
        <h2>Productos Destacados</h2>
        <div class="products">
            <div class="product">
                <img src="producto1.jpg" alt="Producto 1">
                <h3>Sofá Moderno</h3>
                <p>Comodidad y estilo en un solo lugar.</p>
            </div>
            <div class="product">
                <img src="producto2.jpg" alt="Producto 2">
                <h3>Comedor Elegante</h3>
                <p>Perfecto para cenas en familia.</p>
            </div>
            <!-- Añadir más productos aquí -->
        </div>
    </section>

    <section class="section" id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Somos un negocio familiar dedicado a ofrecer muebles de alta calidad con diseños únicos. Nuestra misión es proporcionar a nuestros clientes productos que mejoren sus hogares.</p>
    </section>

    <section class="section" id="contacto">
        <h2>Contacto</h2>
        <form class="contact-form">
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo Electrónico" required>
            <textarea placeholder="Mensaje" rows="5" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Negocio de Muebles. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
