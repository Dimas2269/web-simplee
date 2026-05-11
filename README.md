# web-simplee
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan Single Page Website</title>
    
            <style>
      /* Mengatur agar efek scroll / gulir menjadi halus */
      html {
        scroll-behavior: smooth;
      }

      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }

      /* Membuat header menempel di atas layar */
      header {
        background-color: #333;
        color: white;
        padding: 15px;
        position: fixed;
        top: 0;
        width: 100%;
      }

      nav a {
        color: white;
        margin-right: 15px;
        text-decoration: none;
        font-weight: bold;
      }

      nav a:hover {
        color: #4caf50;
      }

      /* Memberikan ruang agar konten tidak tertutup oleh header */
      main {
        padding: 20px;
      }

      /* Mengatur setiap section agar memiliki tinggi minimal setinggi layar */
      section {
        min-height: 100vh;
        padding-top: 70px; /* Jarak ekstra agar judul tidak tertutup menu */
        border-bottom: 2px dashed #ccc;
      }
    </style>

</head>
<body>
    
<header>
    <nav>
        <a href="#Beranda">Beranda</a>
        <a href="#Profil">Profil</a>
        <a href="#Informasi">Informasi</a>
        <a href="#Kontak">Kontak</a>
        <a href="#Alamat">Alamat</a>
    </nav>
</header>

<main>
    <section id="Beranda"> <h1>
        Selamat Datang di Beranda Website
    </h1>
    <p>Ini Adalah Halaman Beranda</p></section>

    <section id="Profil"> <h1>
        Selamat Datang di Profil Website
    </h1>
    <p>Ini Adalah Halaman Profil</p></section> 
    <section id="Informasi"> <h1>
        Selamat Datang di Informasi Website
    </h1>
    <p>Ini Adalah Halaman Informasi</p></section> 
    <section id="Kontak"> <h1>
        Selamat Datang di Kontak Website
    </h1>
    <p>Ini Adalah Halaman Kontak</p></section>
    <section id="Alamat"> <h1>
        Selamat Datang di Alamat Website
    </h1>
    <p>Ini Adalah Halaman Alamat</p></section>
</main>
</body>
</html>
