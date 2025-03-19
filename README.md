<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="https://lh3.googleusercontent.com/d/1hG-F2JiaPbsMC48ILGQ5CdqjjnhNYn47=w1000">
    <title>Tentang</title>
    <!-- Import Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>      
    <link rel="stylesheet" href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css">
    <link rel="stylesheet" href="tentang.css">
</head>
<body class="bg-gray-100">

<!-- Header -->
<header class="bg-black/50 backdrop-blur-lg shadow-md fixed top-0 left-0 w-full z-50">
  <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
    <!-- Logo + Brand -->
    <div class="flex items-center space-x-3">
      <img src="https://lh3.googleusercontent.com/d/1hG-F2JiaPbsMC48ILGQ5CdqjjnhNYn47=w1000" alt="Logo" class="h-8 w-8">
      <span class="text-xl font-semibold text-white">UKM Pencak Silat</span>
    </div>

    <!-- Navbar Tengah -->
    <div class="hidden md:flex space-x-6">
      <a href="../beranda/index.html" class="text-white hover:text-green-400 transition duration-300">Beranda</a>
      <a href="../tentang/tentang.html" class="text-white hover:text-green-400 transition duration-300">Tentang</a>
      <a href="../galeri/galeri.html" class="text-white hover:text-green-400 transition duration-300">Galeri</a>
      <a href="../prestasi/prestasi.html" class="text-white hover:text-green-400 transition duration-300">Prestasi</a>
    </div>

    <!-- Tombol Kanan -->
    <div class="hidden md:flex space-x-4">
      <button class=" text-white px-4 py-2 rounded-full transition duration-300 hover:bg-green-800">
        Daftar
    </button>
    <a href="../hubungi/hubungi.html" target="_blank"><button class=" text-white px-4 py-2 rounded-full transition duration-300 hover:bg-green-800">
        Hubungi
    </button></a> 
    </div>

    <!-- Tombol Hamburger (Mobile) -->
    <button id="menu-btn" class="md:hidden focus:outline-none">
      <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
      </svg>
    </button>
  </nav>

  <!-- Mobile Menu -->
  <div id="mobile-menu" class="hidden md:hidden absolute top-16 left-0 w-full bg-black/80 backdrop-blur-lg shadow-lg">
    <a href="../beranda/index.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Beranda</a>
    <a href="../tentang/tentang.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Tentang</a>
    <a href="../galeri/galeri.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Galeri</a>
    <a href="../prestasi/prestasi.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Prestasi</a>
    <button class="w-full px-6 py-3 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition duration-300">Daftar</button>
    <a href="../hubungi/hubungi.html" target="_blank"><button class="w-full px-6 py-3 bg-gray-700 text-white rounded-lg hover:bg-gray-600 transition duration-300 mt-2">Hubungi</button></a> 
  </div>
</header>
<!-- End header -->

    <!-- Hero Section -->
    <section class="relative bg-cover bg-center h-screen flex items-center justify-center text-white" style="background-image: url('URL_GAMBAR');">
        <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        <div class="relative z-10 text-center px-6">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">Tentang UKM Pencak Silat</h1>
            <p class="text-lg md:text-xl max-w-2xl mx-auto mb-6">
                UKM Pencak Silat adalah komunitas bagi mahasiswa yang ingin mengembangkan kemampuan bela diri serta menjunjung nilai budaya dan sportivitas.
            </p>
            <a href="#sejarah" class="px-6 py-3 bg-blue-500 hover:bg-blue-600 text-white text-lg rounded-lg shadow-md transition">Pelajari Lebih Lanjut</a>
        </div>
    </section>
    <!-- End Hero Section -->

    <!-- Sejarah -->
<section id="sejarah" class="min-h-screen flex items-center justify-center bg-gray-100 px-4">
  <div class="relative w-full max-w-5xl bg-white shadow-2xl rounded-2xl p-10 border-t-4 border-b-4 border-green-500">
      <h2 class="text-4xl font-bold text-gray-800 text-center relative inline-block after:block after:w-20 after:h-1 after:bg-green-500 after:mx-auto after:mt-2 hover:after:w-28 transition-all duration-300">
          Sejarah UKM Pencak Silat
      </h2>
      <div class="mt-8 space-y-6">
          <div class="w-16 h-1 bg-green-500 mx-auto"></div> <!-- Garis dekoratif -->
          <p class="text-base text-gray-600 invisible" id="paragraf1"></p>
          <p class="text-base text-gray-600 invisible" id="paragraf2"></p>
          <p class="text-base text-gray-600 invisible" id="paragraf3"></p>
      </div>
  </div>
</section>
    <!-- End Sejarah -->

    <!-- Visi Misi -->
    <section id="visi-misi" class="min-h-screen flex flex-col items-center justify-center bg-gray-50 p-8">
        <div class="max-w-4xl text-center">
            <h2 class="text-4xl font-bold text-gray-800">Visi & Misi</h2>
    
            <!-- Visi -->
            <div class="mt-6">
                <h3 class="text-2xl font-semibold text-gray-700 opacity-0 transform translate-y-4 transition-all duration-500" id="visi">
                    "Terwujudnya Unit Kegiatan Mahasiswa Pencak Silat UNUSIA unggul sebagai pengembangan Pencak Silat yang berprestasi dalam bidang Keatlitan, Kaderisasi di Perguruan, dan membawa Pencak Silat UNUSIA kontribusi di Tingkat Nasional"
                </h3>
            </div>
    
            <!-- Misi -->
            <div class="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6 w-full">
                <div class="bg-white shadow-lg rounded-xl p-6 opacity-0 transform translate-y-4 transition-all duration-500" id="misi1">
                    <p class="text-gray-600">Mengembangkan Tradisi Pencak Silat asli Nusantara dengan mencetak atlet dalam lingkup Universitas.</p>
                </div>
                <div class="bg-white shadow-lg rounded-xl p-6 opacity-0 transform translate-y-4 transition-all duration-500" id="misi2">
                    <p class="text-gray-600">Melaksanakan proses berlatih yang efektif dan efisien, sesuai dengan pengembangan ilmu pengetahuan budaya pencak silat Nusantara.</p>
                </div>
                <div class="bg-white shadow-lg rounded-xl p-6 opacity-0 transform translate-y-4 transition-all duration-500" id="misi3">
                    <p class="text-gray-600">Membekali siswa didik dengan sikap Akhlaqul Karimah yang berlandaskan Ahlussunah Wal Jamaah Anahdliyah.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- End Visi Misi -->

    <!-- Struktur -->
    <section id="struktur-organisasi" class="py-20 bg-gray-100">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold text-gray-800">Struktur Organisasi</h2>
            <p class="text-gray-600 mt-2">Berikut adalah susunan kepengurusan organisasi kami.</p>
        </div>
    
        <div class="max-w-3xl mx-auto mt-10">
            <!-- Ketua -->
            <div id="ketua" class="bg-white p-6 rounded-lg shadow-md text-center cursor-pointer hover:scale-105 transition-transform">
                <h3 class="text-xl font-semibold">Ketua Organisasi</h3>
                <p class="text-gray-600">Nama Ketua</p>
            </div>
    
            <!-- Anggota (Hidden) -->
            <div id="anggota" class="grid grid-cols-2 gap-6 mt-6 opacity-0 transform translate-y-5 transition-all duration-700">
                <div class="bg-white p-4 rounded-lg shadow text-center">
                    <h4 class="font-semibold">Wakil Ketua</h4>
                    <p class="text-gray-600">Nama Wakil</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow text-center">
                    <h4 class="font-semibold">Sekretaris</h4>
                    <p class="text-gray-600">Nama Sekretaris</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow text-center">
                    <h4 class="font-semibold">Bendahara</h4>
                    <p class="text-gray-600">Nama Bendahara</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow text-center">
                    <h4 class="font-semibold">Koordinator</h4>
                    <p class="text-gray-600">Nama Koordinator</p>
                </div>
            </div>
        </div>
    </section>
    <!-- End Struktur -->

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-10">
      <div class="container mx-auto px-6 grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Kolom 1: Logo & Deskripsi -->
        <div>
          <h2 class="text-2xl font-bold">UKM Pencak Silat</h2>
          <p class="text-gray-400 mt-2">
            Wadah bagi mahasiswa yang ingin belajar dan mengembangkan diri dalam seni bela diri tradisional Indonesia.
          </p>
        </div>
    
        <!-- Kolom 2: Navigasi -->
        <div>
          <h3 class="text-xl font-semibold mb-3">Navigasi</h3>
          <ul class="space-y-2">
            <li><a href="../beranda/index.html" class="text-gray-400 hover:text-white">Beranda</a></li>
            <li><a href="../tentang/tentang.html" class="text-gray-400 hover:text-white">Tentang</a></li>
            <li><a href="../galeri/galeri.html" class="text-gray-400 hover:text-white">Galeri</a></li>
            <li><a href="../prestasi/prestasi.html" class="text-gray-400 hover:text-white">Prestasi</a></li>
          </ul>
        </div>
    
        <!-- Kolom 3: Kontak & Sosial Media -->
        <div>
          <h3 class="text-xl font-semibold mb-3">Kontak Kami</h3>
          <p class="text-gray-400">
            Email: 
            <a href="mailto:bangjaa@gmail.com?subject=Halo%20Bang%20Jaa&body=Isi%20pesan%20anda%20disini" 
               class="text-blue-400 hover:underline">
               ukmpencaksilat@gmail.com
            </a>
        </p>
        <p class="text-gray-400">
            Telp: 
            <a href="https://wa.me/6285715232441" target="_blank" class="text-blue-400 hover:underline">
                0857-1523-2441
            </a>
        </p>                
          
          <!-- Sosial Media -->
          <h3 class="text-xl font-semibold mt-4">Sosial Media</h3>
          <div class="flex space-x-4 mt-2">
            <a href="https://www.tiktok.com/@ukmpencaksilatunusia?_t=8qmxrhwy50a&_r=1" class="text-gray-400 hover:text-white text-2xl"><i class='bx bxl-tiktok'></i></a>
            <a href="https://www.instagram.com/ukm.pencaksilatunusia/" class="text-gray-400 hover:text-white text-2xl"><i class='bx bxl-instagram'></i></a>
            <a href="#" class="text-gray-400 hover:text-white text-2xl"><i class='bx bxl-telegram'></i></a>
          </div>
        </div>
      </div>
    
      <div class="text-center text-gray-500 text-sm mt-10">
        &copy; 2025 UKM Pencak Silat. All Rights Reserved.
      </div>
    </footer>
    <!-- End Footer -->

    <script src="tentang.js"></script>
    <script src="sejarah.js"></script>
    <script src="../js/navbar.js"></script>
</body>
</html>
