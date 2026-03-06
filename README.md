<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>PRINCE TRAVEL | Jasa Transportasi</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    :root {
      --primary: #002fff;
      --secondary: #05fc26;
      --light: #F5F9FF;
      --dark: #0B1320;
      --accent: #FFC107;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f2f4f7;
      font-family: system-ui, Arial, sans-serif;
    }


    header {
    /* Ganti 'banner.jpg' dengan nama file gambar Anda */
    background-image: url('https://i.ibb.co/JR7v3Lsv/sdfgdhghgsdvbfbdb.jpg');
    background-size: cover;    /* Agar gambar memenuhi kotak header */
    background-position: center; /* Agar gambar pas di tengah */
      color: #ffffff;
      padding: 40px 20px;
      text-align: center;
    }

    nav {
      background: #fff;
      padding: 10px 20px;
      position: sticky;
      top: 0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: var(--dark);
      font-weight: bold;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    footer {
      background: var(--dark);
      color: #b6a720;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    .btn {
      display: inline-block;
      background: var(--accent);
      color: #573838;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 15px;
      font-weight: bold;
    }.gallery-row {
      display: flex;
      gap: 16px;
      overflow-x: auto;
      padding-bottom: 10px;
    }

    .gallery-card {
      min-width: 220px;
      background: #44b8e6;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
      flex-shrink: 0;
    }

    .gallery-card h4 {
      margin: 10px;
      font-size: 16px;
      text-align: center;
    }

    .gallery-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px 10px 0 0;
    }

  </style>
</head>
<body>

  <header>
    <h1>PRINCE TRAVEL</h1>
    <p>Solusi Transportasi Aman, Cepat, dan Terpercaya</p>
    <a class="btn" href="https://wa.me/62895320654301" class="btn" target="_blank">
  Hubungi Admin
</a>

  </header>

  <nav>
    <a href="#tentang">Tentang</a>
    <a href="#layanan">Layanan</a>
    <a href="#armada">Armada</a>
    
    <head>
    <meta charset="UTF-8">
    <title>Gabung Grup</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        .wa-button {
            right: 17px;
            bottom: 17px;
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 10px 18px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
            transition: background 0.3s;
            z-index: 1000; /* supaya selalu di atas konten lain */
        }

        .wa-button:hover {
            background-color: #128C4A;
        }

        .wa-button img {
            width: 17px;  /* ukuran logo kecil */
            height: 17px;
        }
        @media (max-width: 600px) {
         .social-mini {
          bottom: 72px; /* naikkan sedikit */
  }
  .social-mini {
  position: fixed;
  right: 8px;      /* mepet kanan */
  bottom: 8px;     /* mepet bawah */
  display: flex;
  flex-direction: column; /* baris ke bawah */
  gap: 6px;
  z-index: 9999;
}

.social-mini a {
  width: 26px;
  height: 26px;
  background: #ffffff;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
}

.social-mini img {
  object-fit: contain;
}

.social-mini img.wa { width: 16px; height: 16px; }
.social-mini img.fb { width: 14px; height: 14px; }
.social-mini img.ig { width: 14px; height: 14px; }
.social-mini img.tt { width: 14px; height: 14px; }

}

    </style>
</head>
<body>

    <a href="https://whatsapp.com/channel/0029VbCC0QGEquiODUc45g3F" target="_blank" class="wa-button">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Logo">
        Gabung Chanel WhatsApp
    </a>
</body>
  </nav>

  <div class="container" id="tentang">
    <h2>Tentang Kami</h2>
    <p>
      PRINCE TRAVEL adalah perusahaan jasa transportasi yang melayani pengiriman barang, travel antar kota,
      dan layanan logistik dengan armada yang terawat dan sopir berpengalaman.
    </p>
  </div>

  <div class="container" id="layanan">
    <h2>Layanan Kami</h2>
    <div class="services">
      <div class="card">
        <h3>Travel Antar Kota</h3>
        <p>Layanan antar jemput penumpang antar kota dengan armada nyaman.</p>
      </div>
      <div class="card">
        <h3>Pengiriman Barang</h3>
        <p>Jasa kirim paket dan barang dengan aman dan cepat.</p>
      </div>
      <div class="card">
        <h3>Sewa Kendaraan</h3>
        <p>Sewa mobil untuk keperluan wisata atau bisnis.</p>
      </div>
    </div>
  </div>
<div class="container" id="armada">
  <h2>Armada Kami</h2>
  <p>Beberapa armada operasional kami:</p>
  
  <div class="gallery-row">
    <div class="gallery-card">
      <h4>Toyota Hi Ace</h4>
      <img src="https://i.ibb.co/dwHCmjnF/fz32bg1f253dg.jpg" alt="Toyota Hi Ace">
    </div>

    <div class="gallery-card">
      <h4>Toyota Inova Reborn</h4>
      <img src="https://i.ibb.co/F4Sr1Zky/sdgsdfg65.jpg" alt="Toyota Inova Reborn">
    </div>

    <div class="gallery-card">
      <h4>Toyota Avanza</h4>
      <img src="https://i.ibb.co/JjG28y2n/photo-2026-02-12-08-58-46.jpg" alt="Toyota Avanza">
    </div>

    <div class="gallery-card">
      <h4>Daihatsu Sigra</h4>
      <img src="https://i.ibb.co/bR1sy0X5/photo-2026-02-12-08-55-46.jpg" alt="Daihatsu Sigra">
    </div>
    
  </div>
</div>
</head>

<body>

    <div class="content">
        <h1>Suport Kami Selalu</h1>
        <p>Jangan pernah melupakan kami yaa ♥.</p>
        <p>Terimakasih.</p>
    </div>

    <footer>
        <p>© 2026 PRINCE TRAVEL. Semua hak cipta dilindungi.</p>
    </footer>
<div class="social-mini">
  <a href="https://wa.me/60172119192" target="_blank" aria-label="WhatsApp">
    <img class="wa" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
  <a href="https://www.facebook.com/usernamekamu" target="_blank" aria-label="Facebook">
    <img class="fb" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Facebook_Logo_%282019%29.png" alt="Facebook">
  </a>
  <a href="https://www.instagram.com/rikigunawan_10" target="_blank" aria-label="Instagram">
    <img class="ig" src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
  </a>
    <a href="https://www.tiktok.com/@rikigunawan_10" target="_blank" aria-label="TikTok">
    <img class="tt" src="https://i.ibb.co/PGQnPkY3/171342716-10691876.jpg" alt="TikTok">
</div>

