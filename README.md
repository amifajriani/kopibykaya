# kopibykay #
<style>
body {
  background-color: #fef7ee;
  font-family: 'Georgia', serif;
  color: #3e2723;
}

a {
  color: #6d4c41;
  text-decoration: none;
}

a:hover {
  color: #4e342e;
  text-decoration: underline;
}

.button-kopi {
  background-color: #6d4c41;
  color: white;
  padding: 12px 20px;
  text-decoration: none;
  border-radius: 6px;
  display: inline-block;
  font-size: 16px;
  margin-top: 10px;
}

.button-kopi:hover {
  background-color: #4e342e;
}
</style>
<style>
  body {
    background-color: #fef7ee;
    font-family: 'Georgia', serif;
    color: #3e2723;
    margin: 0;
    padding: 0;
  }

  .container {
    max-width: 1000px;
    margin: auto;
    padding: 30px;
  }

  .header {
    text-align: center;
    margin-bottom: 30px;
  }

  .header h1 {
    font-size: 36px;
    margin-bottom: 10px;
  }

  .header p {
    font-style: italic;
    color: #795548;
  }

  .hero-image {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 30px;
  }

  .section {
    margin-bottom: 40px;
  }

  .section h2 {
    font-size: 24px;
    border-bottom: 2px solid #d7ccc8;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }

  .gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    justify-content: center;
  }

  .gallery img {
    width: 30%;
    border-radius: 8px;
  }

  .menu {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  .menu-item {
    background-color: #fff3e0;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  }

  .menu-item h3 {
    margin-top: 0;
    color: #5d4037;
  }

  .button-kopi {
    background-color: #6d4c41;
    color: white;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 6px;
    display: inline-block;
    margin-top: 20px;
    text-align: center;
  }

  .button-kopi:hover {
    background-color: #4e342e;
  }

  @media screen and (max-width: 768px) {
    .gallery img {
      width: 48%;
    }

    .menu {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="container">
  <div class="header">
    <h1>☕ Kopi Pilihan Kami</h1>
    <p>Rasa hangat dari biji kopi terbaik Nusantara</p>
  </div>

  <img alt="Kopi Hero" class="hero-image" src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" />

  <div class="section">
    <h2>📖 Cerita Kami</h2>
    <p>Kami memulai perjalanan dari kecintaan pada aroma dan rasa kopi lokal. Misi kami sederhana: menghadirkan pengalaman kopi terbaik langsung ke cangkirmu, dengan rasa yang jujur dan cerita dari petani Indonesia.</p>
  </div>

  <div class="section">
    
    <h2>📸 Galeri Kopi</h2>
<style>
  .auto-scroll-gallery {
    display: flex;
    gap: 15px;
    overflow: hidden;
    white-space: nowrap;
    animation: scrollGallery 30s linear infinite;
  }

  .auto-scroll-gallery img {
    width: 250px;
    height: auto;
    border-radius: 8px;
    display: inline-block;
  }

  @keyframes scrollGallery {
    0% {
      transform: translateX(0%);
    }
    100% {
      transform: translateX(-100%);
    }
  }

  .gallery-container {
    overflow: hidden;
    width: 100%;
  }
</style>

<h2 style="text-align:center; color:#5d4037;">📸 Galeri Kopi</h2>
<div class="gallery-container">
  <div class="auto-scroll-gallery">
    <img src="https://images.unsplash.com/photo-1552250575-dc69ff5e0a48" alt="Biji Kopi">
    <img src="https://images.unsplash.com/photo-1572441710534-1f0efb007a1f" alt="Espresso Machine">
    <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" alt="Kopi Hitam">
    <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Manual Brew">
    <img src="https://images.unsplash.com/photo-1527515637462-cff94eecc1ac" alt="Latte Art">
    <!-- Ulangi gambar agar tidak habis saat scroll -->
    <img src="https://images.unsplash.com/photo-1552250575-dc69ff5e0a48" alt="Biji Kopi">
    <img src="https://images.unsplash.com/photo-1572441710534-1f0efb007a1f" alt="Espresso Machine">
    <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" alt="Kopi Hitam">
  </div>
</div>

    
  </div>

  <div class="section">
    <h2>☕ Menu Kopi</h2>
    <div class="menu">
      <div class="menu-item">
        <h3>Arabika Gayo</h3>
        <p>Aroma floral, asam segar, rasa elegan.</p>
        <p><strong>Rp 35.000</strong></p>
      </div>
      <div class="menu-item">
        <h3>Robusta Lampung</h3>
        <p>Rasa kuat dan pekat, cocok untuk pecinta kopi pahit.</p>
        <p><strong>Rp 28.000</strong></p>
      </div>
      <div class="menu-item">
        <h3>Toraja Kalosi</h3>
        <p>Aftertaste rempah-rempah yang khas dan lembut.</p>
        <p><strong>Rp 40.000</strong></p>
      </div>
      <div class="menu-item">
        <h3>Kopi Susu Gula Aren</h3>
        <p>Manis alami dari gula aren dengan campuran kopi spesial.</p>
        <p><strong>Rp 25.000</strong></p>
      </div>
    </div>
  </div>

  <div style="text-align: center;">
    <a class="button-kopi" href="https://wa.me/628xxxxxxxxxx" target="_blank">☕ Pesan Sekarang via WhatsApp</a>
  </div>
</div>

<p>&nbsp;</p>
<!--Kaya Kopi - Kekayaan Kopi Nusantara-->
<div style="background-color: #fef7ee; border-radius: 10px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 10px; color: #3e2723; font-family: Georgia, serif; margin: auto; max-width: 800px; padding: 30px;">

  <h1 style="text-align: center;">☕ Kopi Pilihan Kami</h1>
  <p style="font-style: italic; text-align: center;">Menjelajahi rasa khas dari biji kopi terbaik Nusantara.</p>

  <hr style="border-bottom: none; border-image: initial; border-left: none; border-right: none; border-top: 2px dashed rgb(161, 136, 127); border: none; margin: 20px 0px;" />

  <h2>📍 Arabika Gayo</h2>
  <p>Ditanam di dataran tinggi Aceh, kopi ini memiliki aroma floral dan rasa asam segar yang seimbang.</p>

  <h2>📍 Robusta Lampung</h2>
  <p>Kopi kuat dengan rasa pahit khas, cocok untuk penyuka kopi pekat dan kaya kafein.</p>

  <h2>📍 Toraja Kalosi</h2>
  <p>Rasa earthy dengan aftertaste rempah-rempah. Salah satu kopi premium Indonesia.</p>

  <div style="margin-top: 30px; text-align: center;">
    <a href="https://wa.me/628xxxxxxxxxx" style="background-color: #6d4c41; border-radius: 6px; color: white; font-size: 16px; padding: 12px 25px; text-decoration: none;" target="_blank">
      ☕ Pesan Kopi Sekarang
    </a>
  </div>

  <p style="color: grey; font-size: 13px; margin-top: 20px; text-align: center;">Hubungi kami untuk info reseller &amp; grosir.</p>
</div>
<!--Galeri Kopi-->
<div style="margin: auto; max-width: 1000px; padding: 30px;">
  <h2 style="color: #3e2723; margin-bottom: 30px; text-align: center;">📸 Galeri Kopi Kami</h2>

  <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
    
    <img alt="Latte Art" src="https://images.unsplash.com/photo-1527515637462-cff94eecc1ac" style="border-radius: 8px; width: 30%;" />
    <img alt="Manual Brew" src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" style="border-radius: 8px; width: 30%;" />
    <img alt="Biji Kopi" src="https://images.unsplash.com/photo-1552250575-dc69ff5e0a48" style="border-radius: 8px; width: 30%;" />

    <img alt="Espresso Machine" src="https://images.unsplash.com/photo-1572441710534-1f0efb007a1f" style="border-radius: 8px; width: 30%;" />
    <img alt="Cold Brew" src="https://images.unsplash.com/photo-1507914372368-bb6e43d53a36" style="border-radius: 8px; width: 30%;" />
    <img alt="Kopi Hitam" src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" style="border-radius: 8px; width: 30%;" />

  </div>
</div>
