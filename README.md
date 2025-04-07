# MULTIVENTAS<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda iPhones Usados</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f4f4f4; margin: 0; padding: 0; }
    header { background-color: #000; color: #fff; padding: 1rem; text-align: center; }
    .container { padding: 2rem; max-width: 1200px; margin: auto; }
    .grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 1.5rem; }
    .card { background: #fff; padding: 1rem; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .card img { width: 100%; height: 200px; object-fit: cover; border-radius: 10px; }
    .card h3 { margin: 0.5rem 0; }
    .card p { font-size: 14px; color: #555; }
    .card button { background: #000; color: #fff; border: none; padding: 0.5rem 1rem; border-radius: 5px; cursor: pointer; }
    footer { text-align: center; padding: 2rem 1rem; color: #888; }
  </style>
</head>
<body>
  <header>
    <h1>Tienda iPhones Usados</h1>
    <p>Modelos del 11 al 16 Pro Max | Envío en 3 a 5 días | Incluye cargador, lámina de vidrio y carcasa a elección</p>
  </header>
  <div class="container">
    <div class="grid">
      <!-- iPhones del 11 al 16 Pro Max -->
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+11" alt="iPhone 11">
        <h3>iPhone 11</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 11')">Me interesa</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+12" alt="iPhone 12">
        <h3>iPhone 12</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 12')">Me interesa</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+13" alt="iPhone 13">
        <h3>iPhone 13</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 13')">Me interesa</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+14+Pro+Max" alt="iPhone 14 Pro Max">
        <h3>iPhone 14 Pro Max</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 14 Pro Max')">Me interesa</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+15+Pro+Max" alt="iPhone 15 Pro Max">
        <h3>iPhone 15 Pro Max</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 15 Pro Max')">Me interesa</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/250x200?text=iPhone+16+Pro+Max" alt="iPhone 16 Pro Max">
        <h3>iPhone 16 Pro Max</h3>
        <p>Usado, excelente estado. Incluye cargador, lámina de vidrio y carcasa.</p>
        <button onclick="contactar('iPhone 16 Pro Max')">Me interesa</button>
      </div>
    </div>
  </div>
  <footer>
    <p>© 2025 Tienda iPhones Usados - Contacto vía WhatsApp</p>
  </footer>

  <script>
    function contactar(modelo) {
      const mensaje = `Hola, estoy interesado(a) en el ${modelo}. ¿Está disponible?`;
      window.open(`https://wa.me/56988582065?text=${encodeURIComponent(mensaje)}`, '_blank');
    }
  </script>
</body>
</html>
