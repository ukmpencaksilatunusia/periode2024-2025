<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="https://lh3.googleusercontent.com/d/1hG-F2JiaPbsMC48ILGQ5CdqjjnhNYn47=w1000">
    <title>Beranda</title>
    <!-- Import Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>      
    <link rel="stylesheet" href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css">
    <link rel="stylesheet" href="style.css">
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
      <div id="mobile-menu" class="hidden md:hidden absolute top-56 left-0 w-full bg-black/80 backdrop-blur-lg shadow-lg">
        <a href="../beranda/index.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Beranda</a>
        <a href="../tentang/tentang.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Tentang</a>
        <a href="../galeri/galeri.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Galeri</a>
        <a href="../prestasi/prestasi.html" class="block px-6 py-3 border-b text-white hover:bg-gray-800 transition duration-300">Prestasi</a>
        <button class="w-full px-6 py-3 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition duration-300">Daftar</button>
        <a href="../hubungi/hubungi.html" target="_blank"><button class="w-full px-6 py-3 bg-gray-700 text-white rounded-lg hover:bg-gray-600 transition duration-300 mt-2">Hubungi</button></a> 
      </div>
    </header>
    <!-- End header -->

    <!-- Hero -->
    <section class="relative w-full h-screen bg-gray-900 text-white">
      <!-- Background Image -->
      <div class="absolute inset-0">
        <img src="https://lh3.googleusercontent.com/d/1Wvd1BgoEQ37W3lPRe00aCt0XpS83VqnT=w1000" 
          class="w-full h-full object-cover brightness-50" 
          alt="Hero Image">
      </div>

      <!-- Text Overlay -->
      <div class="absolute inset-0 flex flex-col items-center justify-center text-center px-6">
        <h1 class="text-4xl md:text-6xl font-bold hero-text">Unit Kegiatan Mahasiswa Pencak Silat Unusia</h1>
        <p class="text-lg md:text-2xl mt-4 hero-text" style="animation-delay: 0.2s;">Bergabunglah dengan kami dan raihlah prestasi!</p>
        <div class="flex items-center mt-6 space-x-3 hero-text" style="animation-delay: 0.4s;">
          <p class="text-base md:text-lg">Mari berkenalan dengan kami</p>
          <span class="text-white-500">
            <i class='bx bx-right-top-arrow-circle' style="font-size: 20px;"></i>
          </span>
        </div>
      </div>
    </section>
    <!-- End Hero -->

    <!-- Why -->
    <section id="why-section" class="h-screen flex items-center justify-center bg-[#1B3E1B]">
      <div class="container mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold text-white animate-slide-up">Kenapa Bergabung dengan Kami?</h2>
        <p class="text-white mt-2 animate-slide-up">Alasan kenapa UKM Pencak Silat Unusia cocok buat lo!</p>

        <div class="mt-12 grid md:grid-cols-3 gap-8">
          <!-- Item 1 -->
          <div class="flex flex-col items-center p-6 bg-white rounded-xl border-4 border-[#FF0000] shadow-lg h-60 animate-slide-up transition-transform duration-300 hover:scale-105">
            <div class="text-6xl text-[#1B3E1B]">🥋</div>
            <h3 class="text-xl font-semibold mt-4 text-[#1B3E1B]">Latihan Profesional</h3>
            <p class="text-gray-700 mt-2 text-center">Dibimbing oleh pelatih berpengalaman dengan teknik terbaik.</p>
          </div>

          <!-- Item 2 -->
          <div class="flex flex-col items-center p-6 bg-white rounded-xl border-4 border-[#FF0000] shadow-lg h-60 animate-slide-up transition-transform duration-300 hover:scale-105">
            <div class="text-6xl text-[#1B3E1B]">🏆</div>
            <h3 class="text-xl font-semibold mt-4 text-[#1B3E1B]">Berprestasi</h3>
            <p class="text-gray-700 mt-2 text-center">Kesempatan ikut kejuaraan dan membawa nama kampus.</p>
          </div>

          <!-- Item 3 -->
          <div class="flex flex-col items-center p-6 bg-white rounded-xl border-4 border-[#FF0000] shadow-lg h-60 animate-slide-up transition-transform duration-300 hover:scale-105">
            <div class="text-6xl text-[#1B3E1B]">🤝</div>
            <h3 class="text-xl font-semibold mt-4 text-[#1B3E1B]">Kebersamaan</h3>
            <p class="text-gray-700 mt-2 text-center">Gabung komunitas yang solid dan selalu support satu sama lain.</p>
          </div>
        </div>
      </div>
    </section>
    <!-- End Why -->

    <!-- Jadwal -->
    <section class="w-full h-[90vh] bg-gray-900 text-white flex flex-col items-center justify-center px-6 relative overflow-hidden">
      <!-- Motif Background -->
      <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/hexellence.png')] opacity-20"></div>

      <h2 class="inline-block text-4xl font-extrabold mb-6 relative z-10 text-yellow-400 uppercase tracking-wide leading-none max-h-12">
        Jadwal Latihan
    </h2>

    <div class="grid md:grid-cols-2 gap-12 w-4/5 max-w-9xl relative z-10 p-3 h-auto">
      <div class="bg-gradient-to-br from-gray-800 to-gray-700 p-5 rounded-md shadow-md border border-yellow-500 cursor-pointer min-h-[80px]">
          <h3 class="text-3xl font-semibold text-yellow-400 mb-1">Pagar Nusa</h3>
          <ul class="text-gray-300 text-2xl">
              <li>🕘 Kamis: 20.00 - 23.00 WIB</li>
              <li>🕒 Minggu: 15.00 - 17.00 WIB</li>
          </ul>
      </div>
      <div class="bg-gradient-to-br from-gray-800 to-gray-700 p-5 rounded-md shadow-md border border-yellow-500 cursor-pointer min-h-[80px]">
          <h3 class="text-3xl font-semibold text-yellow-400 mb-1">PSHT</h3>
          <ul class="text-gray-300 text-2xl">
              <li>🕑 Kamis: 14.00 - 18.00 WIB</li>
              <li>🕑 Minggu: 14.00 - 18.00 WIB</li>
          </ul>
      </div>
      <div class="bg-gradient-to-br from-gray-800 to-gray-700 p-5 rounded-md shadow-md border border-yellow-500 cursor-pointer min-h-[80px]">
          <h3 class="text-3xl font-semibold text-yellow-400 mb-1">IKSPI</h3>
          <ul class="text-gray-300 text-2xl">
              <li>🕑 Kamis: 14.00 - 18.00 WIB</li>
              <li>🕑 Minggu: 14.00 - 18.00 WIB</li>
          </ul>
      </div>
      <div class="bg-gradient-to-br from-gray-800 to-gray-700 p-5 rounded-md shadow-md border border-yellow-500 cursor-pointer min-h-[80px]">
          <h3 class="text-3xl font-semibold text-yellow-400 mb-1">Cimande</h3>
          <ul class="text-gray-300 text-2xl">
              <li>🕑 Kamis: 14.00 - 18.00 WIB</li>
              <li>🕑 Minggu: 14.00 - 18.00 WIB</li>
          </ul>
      </div>
    </div>

    </section>
    <!-- End Jadwal -->

    <!-- Manfaat -->
<section id="manfaat-section" class="w-full min-h-screen h-auto bg-gradient-to-b from-gray-900 to-black text-white flex flex-col items-center px-6 py-12 pt-24 transition-all duration-300">
  <h2 class="text-4xl font-extrabold text-center mb-10 tracking-wide">
      Mengapa Bergabung dengan Kami?
  </h2>

  <div class="w-full max-w-5xl space-y-8">
      <!-- Baris 1 -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform " onclick="toggleAccordion(1, 'row1')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Pembinaan Fisik & Mental
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform " onclick="toggleAccordion(2, 'row1')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Prospek Karir
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
      </div>
      <div id="accordion-row1" class="hidden backdrop-blur-md bg-white/10 p-6 rounded-lg shadow-lg">
          <p id="accordion-text-row1" class="text-lg text-gray-300"></p>
      </div>

      <!-- Baris 2 -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform " onclick="toggleAccordion(3, 'row2')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Kompetisi & Prestasi
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform " onclick="toggleAccordion(4, 'row2')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Persaudaraan
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
      </div>
      <div id="accordion-row2" class="hidden backdrop-blur-md bg-white/10 p-6 rounded-lg shadow-lg">
          <p id="accordion-text-row2" class="text-lg text-gray-300"></p>
      </div>

      <!-- Baris 3 -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform " onclick="toggleAccordion(5, 'row3')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Kedisiplinan & Kepercayaan Diri
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
          <div class="group backdrop-blur-lg bg-white/10 p-6 rounded-2xl shadow-xl cursor-pointer hover:bg-white/20 transition-all duration-300 transform" onclick="toggleAccordion(6, 'row3')">
              <h3 class="text-2xl font-semibold flex justify-between items-center">
                  Spiritualitas & Nilai Budaya
                  <span class="text-2xl transition-transform ">
                      <i class='bx bx-chevron-down'></i>
                  </span>
              </h3>
          </div>
      </div>
      <div id="accordion-row3" class="hidden backdrop-blur-md bg-white/10 p-6 rounded-lg shadow-lg">
          <p id="accordion-text-row3" class="text-lg text-gray-300"></p>
      </div>
  </div>
</section>
<!-- End Manfaat -->


    <!-- Cerita -->
    <section class="w-full h-[50vh] flex flex-col items-center justify-center bg-gray-900 text-white p-6">
        <h2 class="text-3xl font-bold mb-6">Cerita Anggota</h2>
        <div class="scroll-container">
            <div class="scroll-content" id="scrollText">
                <!-- Teks diisi JS -->
            </div>
        </div>
    </section>            
    <!-- End Cerita -->

    <!-- Berita -->
    <section class="bg-gray-100 py-12">
        <div class="container mx-auto px-6">
          <h2 class="text-3xl font-bold text-center text-gray-800 mb-8">Berita Kampus</h2>
          
          <div class="grid md:grid-cols-3 gap-6">
            <!-- Berita 1 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
              <img src="https://source.unsplash.com/400x250/?university" alt="Berita 1" class="w-full h-48 object-cover">
              <div class="p-4">
                <h3 class="text-xl font-semibold text-gray-800">Judul Berita 1</h3>
                <p class="text-gray-600 mt-2 text-sm">Deskripsi singkat berita ini untuk menarik pembaca.</p>
                <a href="#" class="inline-block mt-3 text-blue-600 font-semibold hover:underline">Baca Selengkapnya</a>
              </div>
            </div>
      
            <!-- Berita 2 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
              <img src="https://source.unsplash.com/400x250/?education" alt="Berita 2" class="w-full h-48 object-cover">
              <div class="p-4">
                <h3 class="text-xl font-semibold text-gray-800">Judul Berita 2</h3>
                <p class="text-gray-600 mt-2 text-sm">Deskripsi singkat berita ini untuk menarik pembaca.</p>
                <a href="#" class="inline-block mt-3 text-blue-600 font-semibold hover:underline">Baca Selengkapnya</a>
              </div>
            </div>
      
            <!-- Berita 3 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
              <img src="https://source.unsplash.com/400x250/?students" alt="Berita 3" class="w-full h-48 object-cover">
              <div class="p-4">
                <h3 class="text-xl font-semibold text-gray-800">Judul Berita 3</h3>
                <p class="text-gray-600 mt-2 text-sm">Deskripsi singkat berita ini untuk menarik pembaca.</p>
                <a href="#" class="inline-block mt-3 text-blue-600 font-semibold hover:underline">Baca Selengkapnya</a>
              </div>
            </div>
          </div>
        </div>
      </section>      
    <!-- End Berita -->

    <!-- FAQ -->
    <section class="bg-white py-12">
        <div class="container mx-auto px-6">
          <h2 class="text-3xl font-bold text-center text-gray-800 mb-8">FAQ Pencak Silat</h2>
          
          <div class="max-w-3xl mx-auto space-y-6">
            <!-- FAQ 1 -->
            <div class="border-b pb-4">
              <button class="w-full text-left flex justify-between items-center text-lg font-semibold text-gray-800 toggle-faq">
                Apa syarat untuk bergabung dengan UKM Pencak Silat?
                <span class="text-blue-600">+</span>
              </button>
              <p class="text-gray-600 mt-2 hidden">Cukup menjadi mahasiswa aktif kampus dan memiliki minat terhadap Pencak Silat. Tidak perlu pengalaman sebelumnya.</p>
            </div>
      
            <!-- FAQ 2 -->
            <div class="border-b pb-4">
              <button class="w-full text-left flex justify-between items-center text-lg font-semibold text-gray-800 toggle-faq">
                Apakah ada biaya pendaftaran?
                <span class="text-blue-600">+</span>
              </button>
              <p class="text-gray-600 mt-2 hidden">Tidak ada biaya pendaftaran, namun ada iuran bulanan untuk perlengkapan dan keperluan latihan.</p>
            </div>
      
            <!-- FAQ 3 -->
            <div class="border-b pb-4">
              <button class="w-full text-left flex justify-between items-center text-lg font-semibold text-gray-800 toggle-faq">
                Kapan dan di mana latihan diadakan?
                <span class="text-blue-600">+</span>
              </button>
              <p class="text-gray-600 mt-2 hidden">Latihan diadakan setiap Selasa & Kamis pukul 17.00 - 19.00 di lapangan utama kampus.</p>
            </div>
      
            <!-- FAQ 4 -->
            <div class="border-b pb-4">
              <button class="w-full text-left flex justify-between items-center text-lg font-semibold text-gray-800 toggle-faq">
                Apakah bisa ikut turnamen jika baru bergabung?
                <span class="text-blue-600">+</span>
              </button>
              <p class="text-gray-600 mt-2 hidden">Tentu, tapi perlu melewati beberapa sesi latihan dasar terlebih dahulu sebelum berkompetisi.</p>
            </div>
          </div>
        </div>
      </section>      
    <!-- End FAQ -->

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

    <script src="script.js"></script>
    <script src="../js/navbar.js"></script>
</body>
</html>
