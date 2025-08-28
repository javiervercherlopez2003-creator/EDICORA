# MICONSTRUCTORA
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Constructora Ejemplo</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <div class="logo">Constructora</div>
      <ul class="nav-links">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#quienes-somos">Quiénes somos</a></li>
        <li><a href="#proyectos">Proyectos</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Sección de Inicio -->
    <section id="inicio" class="hero">
      <h1>Bienvenido a Constructora</h1>
      <p>Calidad. Diseño. Compromiso.</p>
    </section>

    <!-- Sección Quiénes somos -->
    <section id="quienes-somos" class="section">
      <h2>Quiénes somos</h2>
      <p>
        Somos una empresa constructora especializada en crear espacios únicos con los más altos estándares de calidad. 
        Ubicados en Torbay, Australia Occidental, trabajamos en estrecha colaboración con nuestros clientes para construir hogares que inspiran.
      </p>
    </section>

    <!-- Sección Proyectos -->
    <section id="proyectos" class="section">
      <h2>Proyectos</h2>
      <div class="proyectos-grid">
        <div class="proyecto">
          <h3>Proyecto A</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
        <div class="proyecto">
          <h3>Proyecto B</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
        <div class="proyecto">
          <h3>Proyecto C</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
        <div class="proyecto">
          <h3>Proyecto D</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
        <div class="proyecto">
          <h3>Proyecto E</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
        <div class="proyecto">
          <h3>Proyecto F</h3>
          <a href="#" class="btn">Ver Proyecto</a>
        </div>
      </div>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto" class="section contacto">
      <h2>Contacto</h2>
      <p>Teléfono: +61 432 851 406</p>
      <p>Email: contacto@constructora.com</p>
      <p>Ubicación: Torbay, Western Australia</p>
      <p>ABN: 47 161 390 414</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Constructora. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Tipografía */
body {
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  background-color: #ffffff;
  color: #222;
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
}

ul {
  list-style: none;
}

/* Header y navegación */
header {
  background-color: #000;
  color: #fff;
  padding: 20px 40px;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  letter-spacing: 1px;
}

.nav-links {
  display: flex;
  gap: 20px;
}

.nav-links li a {
  color: #fff;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-links li a:hover {
  color: #ccc;
}

/* Secciones */
.section {
  padding: 80px 40px;
  max-width: 1100px;
  margin: auto;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  border-bottom: 2px solid #eee;
  padding-bottom: 10px;
  color: #111;
}

/* Hero (Inicio) */
.hero {
  background-color: #f5f5f5;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.25rem;
  color: #555;
}

/* Proyectos */
.proyectos-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  margin-top: 40px;
}

.proyecto {
  background-color: #f0f0f0;
  padding: 30px;
  border-radius: 8px;
  text-align: center;
  transition: background-color 0.3s ease;
}

.proyecto:hover {
  background-color: #e0e0e0;
}

.proyecto h3 {
  font-size: 1.25rem;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #333;
}

/* Contacto */
.contacto p {
  margin-bottom: 10px;
  color: #444;
}

/* Footer */
footer {
  background-color: #111;
  color: #ccc;
  text-align: center;
  padding: 20px 0;
  font-size: 0.9rem;
}
