<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Rincón del Bebé</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fffaf5;
            color: #333;
        }
        header {
            background-color: #f9c5d1;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 100px;
        }
        h1 {
            margin: 10px 0 0 0;
            font-size: 2rem;
            color: #b44b6e;
        }
        nav {
            background-color: #ffe5ec;
            padding: 10px;
            text-align: center;
        }
        nav a {
            text-decoration: none;
            color: #b44b6e;
            font-weight: bold;
            margin: 0 15px;
        }
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        .catalogo {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .producto {
            background-color: #fff;
            border-radius: 10px;
            padding: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .producto img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #ffe5ec;
            text-align: center;
            padding: 15px;
            font-size: 0.9rem;
        }
        iframe {
            width: 100%;
            height: 300px;
            border: none;
        }
    </style>
</head>
<body>

<header>
    <img src="https://i.ibb.co/gjYB1N5/logo-bebe.png" alt="Logo El Rincón del Bebé">
    <h1>El Rincón del Bebé</h1>
    <p>Todo para tu bebé, con amor ❤️</p>
</header>

<nav>
    <a href="#catalogo">Catálogo</a>
    <a href="#nosotros">Sobre Nosotros</a>
    <a href="#ubicacion">Ubicación</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="catalogo">
    <h2>Catálogo</h2>
    <div class="catalogo">
        <div class="producto">
            <img src="https://i.ibb.co/zsZjkGD/baby-clothes.jpg" alt="Ropa de bebé">
            <h3>Ropita para bebé</h3>
            <p>₡5,000</p>
        </div>
        <div class="producto">
            <img src="https://i.ibb.co/Q6BPKnW/baby-bottle.jpg" alt="Biberón">
            <h3>Biberón</h3>
            <p>₡3,500</p>
        </div>
        <div class="producto">
            <img src="https://i.ibb.co/mSgL8sS/baby-toy.jpg" alt="Juguete">
            <h3>Juguete suave</h3>
            <p>₡4,000</p>
        </div>
    </div>
</section>

<section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>En <strong>El Rincón del Bebé</strong> nos apasiona ofrecer productos de calidad para los más pequeños del hogar. Cada artículo es escogido con cariño y pensando en la comodidad y seguridad de tu bebé.</p>
</section>

<section id="ubicacion">
    <h2>Ubicación</h2>
    <p>Nos encontramos en San José, Costa Rica.</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3930.153463125387!2d-84.0907246845628!3d9.928069492895998!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8fa0e31b5b5fba51%3A0xb1d7339c70e9e8a0!2sSan%20Jos%C3%A9%2C%20Costa%20Rica!5e0!3m2!1ses!2scr!4v1682163130841!5m2!1ses!2scr"></iframe>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>📞 Teléfono: +506 8888 8888</p>
    <p>📱 WhatsApp: <a href="https://wa.me/50688888888" target="_blank">Escríbenos aquí</a></p>
    <p>📧 Email: contacto@elrincondelbebe.com</p>
</section>

<footer>
    &copy; 2025 El Rincón del Bebé | Diseñado con ❤️
</footer>

</body>
</html>
