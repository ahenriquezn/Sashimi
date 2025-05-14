<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushi Deluxe | Fresco y Delicioso</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Barra de navegación -->
    <header>
        <nav>
            <div class="logo">
                <h1>Sushi Deluxe</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
            <div class="carrito">
                <i class="fas fa-shopping-cart"></i>
                <span class="cart-count">0</span>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Sushi Fresco y Artesanal</h2>
            <p>Disfruta del auténtico sabor japonés</p>
            <a href="#menu" class="btn">Ver Menú</a>
        </div>
    </section>

    <!-- Menú -->
    <section id="menu" class="menu">
        <h2>Nuestro Menú</h2>
        <div class="menu-grid">
            <!-- Producto 1 -->
            <div class="menu-item">
                <img src="https://via.placeholder.com/200" alt="Sushi Roll">
                <h3>Roll Clásico</h3>
                <p>Salmón fresco, aguacate y arroz.</p>
                <span class="price">$8.99</span>
                <button class="add-to-cart">Añadir al carrito</button>
            </div>
            <!-- Producto 2 -->
            <div class="menu-item">
                <img src="https://via.placeholder.com/200" alt="Nigiri">
                <h3>Nigiri de Atún</h3>
                <p>Atún de alta calidad sobre arroz.</p>
                <span class="price">$10.99</span>
                <button class="add-to-cart">Añadir al carrito</button>
            </div>
            <!-- Más productos... -->
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="contact">
        <h2>Contacto</h2>
        <form>
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo electrónico" required>
            <textarea placeholder="Mensaje"></textarea>
            <button type="submit" class="btn">Enviar</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Sushi Deluxe. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
