<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beauty Glam</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: Arial, sans-serif; background: #f9f9f9; }
    header {
      background: #ff69b4;
      color: white;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
    }
    .section h2 {
      margin-bottom: 20px;
      color: #ff69b4;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }
    .card button {
      background: #ff69b4;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      margin-top: 10px;
      cursor: pointer;
    }
    .cart {
      font-size: 1rem;
      background: white;
      color: #ff69b4;
      padding: 5px 15px;
      border-radius: 15px;
      box-shadow: 0 1px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>Beauty Glam</h1>
    <nav>
      <a href="#bases">Bases</a>
      <a href="#labiales">Labiales</a>
      <a href="#sombras">Sombras</a>
      <a href="#rubores">Rubores</a>
      <a href="#mascaras">Máscaras</a>
      <a href="#brochas">Brochas</a>
    </nav>
    <div class="cart">🛒 Carrito</div>
  </header>

  <section id="bases" class="section">
    <h2>Bases</h2>
    <div class="products">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_607746-MLA78655415110_092024-O.webp" alt="Base 1">
        <p>Base Maybelline Fit Me Matte + Poreless 220 Natural Beige x 30ml</p>
        <p>$48.000</p>
<button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_618541-MLA83131106425_032025-O.webp" alt="Base 2">
        <p>Base Super Stay Lumi Matte 120 Maybelline 35ml 72000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_748070-MLU77834099809_072024-O.webp" alt="Base 3">
        <p>Polvo Compacto Fit Me Matte Porcelain Maybelline 12gr 32000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_865062-MCO77568225883_072024-O.webp" alt="Base 4">
        <p>Base Profesional Trendy Mousse - g a $27900</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>

  <section id="labiales" class="section">
    <h2>Labiales</h2>
    <div class="products">
      <!-- Labiales Cards -->
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_833621-MLU77964581048_082024-O.webp" alt="Labial 1">
        <p>Labial Liquido Super Stay Vinyl Ink Witty Maybelline 4.2ml </p>
<p>$47.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_855623-MLU77784638367_072024-O.webp" alt="Labial 2">
        <p>Brillo labial Maybelline Lifter Gloss Shade Petal 5.4mL </p>
<p>$50.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_981589-MLU75111618251_032024-O.webp" alt="Labial 3">
        <p>Lápiz Labial Max Factor Colour Elixir Moisture Lipstick Simply Nude</p>
 <p>$58.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_944913-CBT82292077828_022025-O.webp" alt="Labial 4">
        <p>Tinte De Labios Rhode Shortcake</p>
<p>$35.000</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>

  <section id="sombras" class="section">
    <h2>Sombras</h2>
    <div class="products">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_864965-MCO53002710983_122022-O.webp" alt="Sombra 1">
        <p>Paleta De Sombras Be You Tiful - g a $357</p>
   <p>$25.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_888370-MCO76782224807_062024-O.webp" alt="Sombra 2">
        <p>Paleta De Sombras De Ojos De 24 Tonos - Colores Vibrantes</p>
<p>$100.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_873080-MLA80962278529_112024-O.webp" alt="Sombra 3">
        <p>Sombras Huda Nude - G Color Rosa</p>
<p>$18.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_877020-MCO76349192815_052024-O.webp" alt="Sombra 4">
        <p>PSombras, Glitter, Iluminador - g a $1056 25000</p>
<p>$25.000</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>

  <section id="rubores" class="section">
    <h2>Rubores</h2>
    <div class="products">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_670508-MLA79786164407_102024-O.webp" alt="Rubor 1">
        <p>RColorete Intenso Peach Stick de O Boticário, 5,5 g 50000</p>
 <p>$50.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_670162-MLU78280629655_082024-O.webp" alt="Rubor 2">
        <p>Rubor Liquido X2 Trendy Safari - Ml Tono Del Maquillaje X2 Tonos Universales</p>
<p>$24.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_666709-MLU71339764996_082023-O.webp" alt="Rubor 3">
        <p>Rubor Vogue Champagne X4g</p>
 <p>$15.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_715625-MCO79657050249_092024-O.webp" alt="Rubor 4">
        <p>Rubor Cremoso Play Blush Melu - g a $2838</p>
        <p>$20000</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>

  <section id="mascaras" class="section">
    <h2>Máscaras</h2>
    <div class="products">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_870754-MCO28057195007_082018-O.webp" alt="Máscara 1">
        <p>VMascara Pestañina Extra Volumen + Deli - mL a $2490</p>
   <p>$25.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_762663-MLA81783614432_012025-O.webp" alt="Máscara 2">
        <p>Maybelline Colossal Máscara De Pestañas Waterproof Black</p>
  <p>27.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_908752-MLU77983066421_072024-O.webp" alt="Máscara 3">
        <p>Pestañina Panorama Voluminizadora A Prueba de Agua L'oréal Paris x 9,4ml 54000</p>
  <p>$54.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_988059-MCO77200298020_072024-O.webp" alt="Máscara 4">
        <p>Tratamiento En Mascara Crystal Gel Pestañas 4 En 1 Prosa</p>
  <p>$28.000</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>

  <section id="brochas" class="section">
    <h2>Brochas</h2>
    <div class="products">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_657246-MLU70816047891_082023-O.webp" alt="Brocha 1">
        <p>Brocha Base Brocha Mágica Plana - Unidad Color Negro</p>
<p>$9.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_615436-MLU73211173173_122023-O.webp" alt="Brocha 2">
        <p>uego de 18 brochas de maquillaje Bs-mall color champagne gold</p>
<p>80.00</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_798817-MCO71038107962_082023-O.webp" alt="Brocha 3">
        <p>Brocha Profesional Para Rubor Tre - Unidad a $13000</p>
<p>$13.000</p>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_787559-MCO46870523749_072021-O.webp" alt="Brocha 4">
        <p>Brocha Para Sombras Profesional Tr</p>
<p>$7.500</p>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </section>
</body>
</html>
