<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tienda Online</title>
  <link rel="stylesheet" href="estilos.css" />
</head>
<body>
  <header>
    <div class="logo">Tienda Online</div>
    <nav>
      <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#sobre">Sobre Nosotros</a></li>
        <li><a href="#productos">Productos</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <section id="inicio" class="hero">
    <h1>Productos de Belleza</h1>
    <p>Descubre lo mejor en cosméticos y cuidado personal</p>
    <a href="#productos" class="boton">VER PRODUCTOS</a>
  </section>

  <section id="sobre" class="seccion">
    <h2>Sobre Nosotros</h2>
    <p>Somos una tienda dedicada a ofrecer los mejores productos de belleza con atención al detalle y al cliente.</p>
  </section>

  <section id="productos" class="seccion">
    <h2>Productos Destacados</h2>
    <div class="grid-productos">
      <div class="producto">
        <img src="https://via.placeholder.com/150" alt="Producto 1">
        <h3>Producto 1</h3>
        <p>$10.00</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/150" alt="Producto 2">
        <h3>Producto 2</h3>
        <p>$12.00</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/150" alt="Producto 3">
        <h3>Producto 3</h3>
        <p>$15.00</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/150" alt="Producto 4">
        <h3>Producto 4</h3>
        <p>$18.00</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="seccion">
    <h2>Contacto</h2>
    <form>
      <input type="text" placeholder="Nombre" required>
      <input type="email" placeholder="Correo electrónico" required>
      <textarea placeholder="Mensaje" required></textarea>
      <button type="submit">ENVIAR MENSAJE</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Tienda Online. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
