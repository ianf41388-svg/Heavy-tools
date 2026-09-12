# Heavy-tools
Menjual 
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heavy Tools - Sparepart Alat Berat</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f4f4;
      color: #222;
    }

    header {
      background: #1f2937;
      color: white;
      text-align: center;
      padding: 35px 20px;
    }

    header h1 {
      color: #fbbf24;
      font-size: 36px;
      margin-bottom: 8px;
    }

    header p {
      font-size: 16px;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }

    .title {
      text-align: center;
      margin-bottom: 25px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .product {
      background: white;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }

    .product-image {
      height: 150px;
      background: #e5e7eb;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #777;
      margin-bottom: 15px;
    }

    .product h3 {
      margin-bottom: 10px;
    }

    .price {
      color: #dc2626;
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 15px;
    }

    .whatsapp {
      display: inline-block;
      background: #25D366;
      color: white;
      text-decoration: none;
      padding: 12px 18px;
      border-radius: 8px;
      font-weight: bold;
    }

    .whatsapp:hover {
      background: #1ebe5d;
    }

    footer {
      margin-top: 40px;
      background: #1f2937;
      color: white;
      text-align: center;
      padding: 25px;
    }
  </style>
</head>

<body>

  <header>
    <h1>HEAVY TOOLS</h1>
    <p>Sparepart & kebutuhan alat berat</p>
  </header>

  <div class="container">

    <div class="title">
      <h2>Produk Kami</h2>
      <p>Silakan pilih produk yang ingin dipesan.</p>
    </div>

    <div class="products">

      <div class="product">
        <div class="product-image">
          Foto Produk
        </div>

        <h3>Filter Perkins</h3>

        <div class="price">
          Rp2.000
        </div>

        <a
          class="whatsapp"
          href="https://wa.me/6281574855715?text=Halo%20Heavy%20Tools,%20saya%20ingin%20memesan%20Filter%20Perkins."
          target="_blank">
          Pesan via WhatsApp
        </a>
      </div>


      <div class="product">
        <div class="product-image">
          Foto Produk
        </div>

        <h3>Field Guard</h3>

        <div class="price">
          Rp2.000
        </div>

        <a
          class="whatsapp"
          href="https://wa.me/6281574855715?text=Halo%20Heavy%20Tools,%20saya%20ingin%20memesan%20Field%20Guard."
          target="_blank">
          Pesan via WhatsApp
        </a>
      </div>


      <div class="product">
        <div class="product-image">
          Foto Produk
        </div>

        <h3>Produk Lainnya</h3>

        <div class="price">
          Rp2.000
        </div>

        <a
          class="whatsapp"
          href="https://wa.me/6281574855715?text=Halo%20Heavy%20Tools,%20saya%20ingin%20memesan%20produk."
          target="_blank">
          Pesan via WhatsApp
        </a>
      </div>

    </div>
  </div>

  <footer>
    <p>© 2026 Heavy Tools</p>
    <p>Hubungi kami melalui WhatsApp: 0815-7485-5715</p>
  </footer>

</body>
</html>

