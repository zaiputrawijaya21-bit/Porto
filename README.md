[porto.html](https://github.com/user-attachments/files/23677178/porto.html)
<!DOCTYPE html>![profil3](https://github.com/user-attachments/assets/f38739e4-e6ff-4960-9aae-7a69aafcf18d)

<html lang="id" class="scroll-sm![profil3](https://github.com/user-attachments/assets/74d91afc-c5a9-4564-8921-b93a5ee334dc)
o![profil](https://github.com/user-attachments/assets/001a91c8-f948-4f0d-98b7-4b51021e50a1)
oth">![profil2](https://github.com/user-attachments/assets/ecbc2e11-6151-4b59-93f2-088e5e1f025f)

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Profesional - Putra Wijaya Zai</title>
    <img width="1536" height="1024" alt="foto2" src="https://github.com/user-attachments/assets/5285a7a1-946a-452c-9145-fab9b6f69281" />

    <script<img width="1536" height="1024" alt="foto1" src="https://github.com/user-attachments/assets/80a3e0f1-0432-49a4-8c6f-e1dec6f68601" />
 src="https://cdn.tailwind![profil2](https://github.com/user-attachments/assets/33fe4940-8507-4914-83b1-5446e6214c72)
![profil](https://github.com/user-attachments/assets/6c94b385-024f-4be3-9769-1605b76f9c35)
[porto.html](https://github.com/user-attachments/files/23677210/porto.html)
<img width="1024" height="1536" alt="foto3" src="https://github.com/user-attachments/assets/7aa3f8b4-3611-48b6-b568-882fc2d14332" />
<img width="1024" height="1536" alt="foto3" src="https://github.com/user-attachments/assets/d0958bef-e0aa-4e87-9dd4-11b1b8352a2e" />
css.com"></script>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqc<img width="1536" height="1024" alt="foto2" src="https://github.com/user-attachments/assets/d91db7e0-a62e-4737-9947-e32dfbc7a67d" />
<img width="1536" height="1024" alt="foto1" src="https://github.com/user-attachments/assets/0165410e-48b2-44f9-adbc-e5f277f9b5f2" />
WaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        /* Menggunakan font Inter sebagai font utama */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #020617; /* Warna dasar diubah menjadi lebih gelap (slate-950) */
            color: #cbd5e1;
        }

        /* Latar Belakang Gradien Animasi yang lebih gelap */
        .animated-gradient-bg {
            background: linear-gradient(-45deg, #020617, #0f172a, #0c4a6e, #1e3a8a);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        /* Container untuk partikel animasi */
        #tsparticles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1; /* Diletakkan di belakang konten */
        }

        /* Gaya untuk judul bagian */
        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background-color: #38bdf8;
            margin: 8px auto 0;
            border-radius: 2px;
            transition: width 0.3s ease-in-out;
        }
        .section-title:hover::after {
            width: 100px;
        }

        /* Tombol Kembali ke Atas */
        #to-top-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: none; /* Tersembunyi secara default */
            z-index: 100;
        }
    </style>
</head>
<body class="antialiased">

    <div class="fixed top-0 left-0 w-full h-full animated-gradient-bg -z-20"></div>
    <div id="tsparticles"></div>

    <nav id="navbar" class="bg-slate-950/80 backdrop-blur-sm p-4 sticky top-0 z-50 transition-shadow duration-300">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-white text-2xl font-extrabold tracking-tight">PUTRA WIJAYA ZAI</a>
            
            <div class="hidden md:flex items-center space-x-8">
                <a href="#tentang" class="text-slate-300 hover:text-sky-400 transition-colors">Tentang Saya</a>
                <a href="#pendidikan" class="text-slate-300 hover:text-sky-400 transition-colors">Pendidikan</a>
                <a href="#hobi" class="text-slate-300 hover:text-sky-400 transition-colors">Hobi</a>
                <a href="#projek" class="text-slate-300 hover:text-sky-400 transition-colors">Projek</a>
                <a href="#keahlian" class="text-slate-300 hover:text-sky-400 transition-colors">Keahlian</a>
                <a href="#kontak" class="bg-sky-500 hover:bg-sky-600 text-white font-bold py-2 px-4 rounded-full transition-all duration-300 transform hover:scale-105">Kontak</a>
            </div>

            <button id="mobile-menu-button" class="md:hidden text-white text-2xl">
                <i class="fas fa-bars"></i>
            </button>
        </div>
        
        <div id="mobile-menu" class="hidden md:hidden mt-4">
            <a href="#tentang" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Tentang Saya</a>
            <a href="#pendidikan" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Pendidikan</a>
            <a href="#hobi" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Hobi</a>
            <a href="#projek" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Projek</a>
            <a href="#keahlian" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Keahlian</a>
            <a href="#kontak" class="block py-2 px-4 text-slate-300 hover:bg-slate-800 rounded">Kontak</a>
        </div>
    </nav>

    <header class="container mx-auto px-6 py-20 md:py-32 text-center overflow-hidden">
        <img data-aos="zoom-in" data-aos-duration="700" src="profil.jpg" alt="Foto Putra Wijaya Zai" class="w-60 h-50 mx-auto rounded-full mb-6 border-4 border-slate-700 shadow-lg">
        <h1 data-aos="fade-up" data-aos-duration="800" class="text-4xl md:text-6xl font-extrabold text-white leading-tight">PUTRA WIJAYA ZAI</h1>
        <p data-aos="fade-up" data-aos-duration="900" data-aos-delay="200" class="mt-4 text-lg md:text-xl text-sky-300">
            <span id="typed-text"></span>
        </p>
    </header>

    <main class="container mx-auto px-6">

        <section id="tentang" class="py-20">
            <h2 data-aos="fade-up" class="text-3xl sm:text-4xl font-bold text-center mb-10 text-slate-100 section-title">Tentang Saya</h2>
            <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center gap-10">
                <div data-aos="fade-right" class="md:w-1/3">
                    <img src="profil3.jpg" alt="Foto Putra" class="rounded-lg shadow-lg w-full">
                </div>
                <div data-aos="fade-left" class="md:w-2/3 bg-slate-900/70 backdrop-blur-sm p-8 rounded-lg shadow-md border border-slate-700">
                    <p class="text-lg text-left leading-relaxed">
                        Saya adalah mahasiswa semester 2 Program Studi Informatika yang akan segera memasuki semester 3, dengan ketertarikan dalam bidang <span class="font-semibold text-sky-400">Web Development</span>. Saat ini sedang aktif mengembangkan keterampilan di HTML, CSS, dan JavaScript. Memiliki komitmen tinggi untuk terus belajar dan berkembang, serta antusias mencari pengalaman nyata melalui program magang di bidang teknologi.
                    </p>
                </div>
            </div>
        </section>

        <section id="pendidikan" class="py-20">
            <h2 data-aos="fade-up" class="text-3xl sm:text-4xl font-bold text-center mb-12 text-slate-100 section-title">Riwayat Pendidikan</h2>
            <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center gap-10">
                <div data-aos="fade-right" data-aos-duration="800" class="md:w-1/2">
                    <div class="relative border-l-2 border-sky-800 pl-10">
                        <div data-aos="fade-left" data-aos-delay="200" class="mb-10">
                            <h3 class="text-xl font-semibold text-white">Universitas Battuta</h3>
                            <p class="text-sky-400 text-sm mb-1">2024 - Sekarang</p>
                            <p class="text-slate-400">S1 Informatika</p>
                        </div>
                        <div data-aos="fade-left" data-aos-delay="400">
                            <h3 class="text-xl font-semibold text-white">SMA Negeri 1 Pangkalan Susu</h3>
                            <p class="text-sky-400 text-sm mb-1">2021 - 2024</p>
                            <p class="text-slate-400">Jurusan IPA</p>
                        </div>
                    </div>
                </div>
                <div data-aos="fade-left" class="md:w-1/3">
                    <img src="profil2.jpg" alt="Foto Pendidikan" class="rounded-lg shadow-lg w-full">
                </div>
            </div>
        </section>

        <section id="hobi" class="py-20">
            <h2 data-aos="fade-up" class="text-3xl sm:text-4xl font-bold text-center mb-12 text-slate-100 section-title">Hobi Saya</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <div data-aos="fade-up" data-aos-delay="100" class="bg-slate-900 rounded-xl shadow-lg p-8 text-center flex flex-col items-center transition-all duration-300 hover:transform hover:-translate-y-2 hover:shadow-sky-500/20">
                    <i class="fas fa-futbol fa-5x text-sky-400 mb-4"></i>
                    <h3 class="text-2xl font-bold text-white mb-2">Main Voly</h3>
                    <p class="text-slate-400">Menjaga kebugaran dan melatih kekompakan tim di atas lapangan.</p>
                </div>
                <div data-aos="fade-up" data-aos-delay="200" class="bg-slate-900 rounded-xl shadow-lg p-8 text-center flex flex-col items-center transition-all duration-300 hover:transform hover:-translate-y-2 hover:shadow-sky-500/20">
                    <i class="fas fa-guitar fa-5x text-sky-400 mb-4"></i>
                    <h3 class="text-2xl font-bold text-white mb-2">Main Gitar</h3>
                    <p class="text-slate-400">Mengekspresikan diri dan melepas penat melalui alunan musik.</p>
                </div>
                <div data-aos="fade-up" data-aos-delay="300" class="bg-slate-900 rounded-xl shadow-lg p-8 text-center flex flex-col items-center transition-all duration-300 hover:transform hover:-translate-y-2 hover:shadow-sky-500/20">
                    <i class="fas fa-gamepad fa-5x text-sky-400 mb-4"></i>
                    <h3 class="text-2xl font-bold text-white mb-2">Main Game</h3>
                    <p class="text-slate-400">Mengasah kemampuan berpikir strategis, kritis dan penyelesaian masalah.</p>
                </div>
            </div>
        </section>
        
        <section id="projek" class="py-20">
            <h2 data-aos="fade-up" class="text-3xl sm:text-4xl font-bold text-center mb-16 text-slate-100 section-title">Projek Saya</h2>
            <div class="max-w-5xl mx-auto flex flex-col gap-16">
                <div data-aos="fade-up" class="bg-slate-900 rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-2xl flex flex-col md:flex-row group">
                    <div class="md:w-1/2">
                        <img src="foto1.png" alt="Situs Web Booking Minisoccer" class="w-full h-full object-cover">
                    </div>
                    <div class="md:w-1/2 p-8 flex flex-col justify-center">
                        <h3 class="text-2xl font-bold text-white mb-3">Website Booking Minisoccer</h3>
                        <p class="text-slate-400 mb-6">Membuat situs web untuk pemesanan lapangan minisoccer dengan fitur admin dan booking real-time.</p>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">CSS</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">JavaScript</span>
                        </div>
                    </div>
                </div>
                <div data-aos="fade-up" class="bg-slate-900 rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-2xl flex flex-col md:flex-row-reverse group">
                    <div class="md:w-1/2">
                        <img src="foto2.png" alt="Situs Web Booking Meja Billiard" class="w-full h-full object-cover">
                    </div>
                    <div class="md:w-1/2 p-8 flex flex-col justify-center">
                        <h3 class="text-2xl font-bold text-white mb-3">Website Booking Meja Billiard</h3>
                        <p class="text-slate-400 mb-6">Situs web ramah pengguna untuk memesan meja billiard standar dan VIP.</p>
                         <div class="flex flex-wrap gap-2">
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">Tailwind CSS</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">PHP</span>
                        </div>
                    </div>
                </div>
                <div data-aos="fade-up" class="bg-slate-900 rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-2xl flex flex-col md:flex-row group">
                    <div class="md:w-1/2">
                        <img src="foto3.png" alt="Situs Web Coffee Shop" class="w-full h-full object-cover">
                    </div>
                    <div class="md:w-1/2 p-8 flex flex-col justify-center">
                        <h3 class="text-2xl font-bold text-white mb-3">Website Coffee Shop (Tim)</h3>
                        <p class="text-slate-400 mb-6">Projek tim yang menampilkan katalog produk, keranjang belanja, dan sistem pemesanan.</p>
                         <div class="flex flex-wrap gap-2">
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">JavaScript</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">CSS</span>
                            <span class="bg-sky-900 text-sky-300 text-xs font-semibold px-2.5 py-0.5 rounded-full">PHP</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="keahlian" class="py-20">
            <h2 data-aos="fade-up" class="text-3xl sm:text-4xl font-bold text-center mb-12 text-slate-100 section-title">Keahlian Saya</h2>
            <div class="flex flex-col md:flex-row justify-center items-start gap-16">
                <div data-aos="fade-right" class="w-full md:w-auto text-center">
                    <h3 class="text-2xl font-semibold text-white mb-6">Keahlian Teknis</h3>
                    <div class="flex flex-wrap justify-center gap-6">
                        <div class="flex flex-col items-center gap-2 p-4 bg-slate-900 rounded-lg w-28 transition-transform transform hover:-translate-y-2"><i class="fab fa-html5 fa-3x text-orange-500"></i><span class="font-medium">HTML5</span></div>
                        <div class="flex flex-col items-center gap-2 p-4 bg-slate-900 rounded-lg w-28 transition-transform transform hover:-translate-y-2"><i class="fab fa-css3-alt fa-3x text-blue-500"></i><span class="font-medium">CSS3</span></div>
                        <div class="flex flex-col items-center gap-2 p-4 bg-slate-900 rounded-lg w-28 transition-transform transform hover:-translate-y-2"><i class="fab fa-js-square fa-3x text-yellow-400"></i><span class="font-medium">JavaScript</span></div>
                        <div class="flex flex-col items-center gap-2 p-4 bg-slate-900 rounded-lg w-28 transition-transform transform hover:-translate-y-2"><i class="fab fa-github fa-3x text-white"></i><span class="font-medium">GitHub</span></div>
                    </div>
                </div>
                <div data-aos="fade-left" class="w-full md:w-1/3 text-center">
                    <h3 class="text-2xl font-semibold text-white mb-6">Keahlian Non-Teknis</h3>
                    <div class="space-y-4">
                        <p class="bg-slate-900 p-3 rounded-lg text-lg transition-all duration-300 hover:bg-sky-500 hover:shadow-lg hover:shadow-sky-500/30">Manajemen Waktu</p>
                        <p class="bg-slate-900 p-3 rounded-lg text-lg transition-all duration-300 hover:bg-sky-500 hover:shadow-lg hover:shadow-sky-500/30">Penyelesaian Masalah</p>
                        <p class="bg-slate-900 p-3 rounded-lg text-lg transition-all duration-300 hover:bg-sky-500 hover:shadow-lg hover:shadow-sky-500/30">Kerjasama Tim</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="kontak" class="bg-slate-950/80 pt-16 pb-8 mt-20">
        <div class="container mx-auto px-6 text-center" data-aos="fade-in">
            <h2 class="text-3xl font-bold text-white mb-4">Hubungi Saya</h2>
             <div class="flex justify-center space-x-6 mb-10">
                <a href="mailto:putrazaiwijaya21@gmail.com" class="text-slate-400 hover:text-sky-400 transition-transform transform hover:-translate-y-1"><i class="fas fa-envelope fa-2x"></i></a>
                <a href="http://www.linkedin.com/in/bobby-agung-berkat-hulu-ba77a0362" target="_blank" rel="noopener noreferrer" class="text-slate-400 hover:text-sky-400 transition-transform transform hover:-translate-y-1"><i class="fab fa-linkedin fa-2x"></i></a>
                <a href="https://www.instagram.com/putra_zaii" target="_blank" rel="noopener noreferrer" class="text-slate-400 hover:text-sky-400 transition-transform transform hover:-translate-y-1"><i class="fab fa-instagram fa-2x"></i></a>
                <a href="https://github.com/Bobby-hulu9" target="_blank" rel="noopener noreferrer" class="text-slate-400 hover:text-sky-400 transition-transform transform hover:-translate-y-1"><i class="fab fa-github fa-2x"></i></a>
            </div>
            <p class="text-slate-500">&copy; 2025 Putra Wijaya Zai. </p>
        </div>
    </footer>

    <button id="to-top-button" class="bg-sky-500 hover:bg-sky-600 text-white w-12 h-12 rounded-full transition-all duration-300 transform hover:scale-110">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/tsparticles@3.3.0/tsparticles.bundle.min.js"></script>
    <script>
        // Inisialisasi AOS
        AOS.init({ once: true, offset: 50, duration: 800 });

        // Inisialisasi Typed.js
        new Typed('#typed-text', {
            strings: ['Mahasiswa Informatika', 'Calon Pengembang Web', 'Pecinta Teknologi'],
            typeSpeed: 50,
            backSpeed: 25,
            backDelay: 1500,
            loop: true
        });

        // Skrip untuk menu seluler
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));
        const navLinks = mobileMenu.getElementsByTagName('a');
        for (let link of navLinks) {
            link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
        }
        
        // Skrip untuk tombol kembali ke atas dan bayangan navbar
        const toTopButton = document.getElementById('to-top-button');
        const navbar = document.getElementById('navbar');
        window.onscroll = function() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                toTopButton.style.display = "block";
            } else {
                toTopButton.style.display = "none";
            }
            navbar.classList.toggle("shadow-lg", window.pageYOffset > 50);
        };
        toTopButton.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });

        // Konfigurasi animasi partikel tsParticles (DIPERBARUI)
        window.addEventListener('load', () => {
            tsParticles.load({
                id: "tsparticles",
                options: {
                    background: {
                        color: { value: "transparent" }
                    },
                    fpsLimit: 60,
                    particles: {
                        number: {
                            value: 30, // Jumlah partikel ditambah
                            density: { enable: true }
                        },
                        shape: {
                            type: "image",
                            image: [
                                { // Ikon Bola
                                    src: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath fill='%2338bdf8' d='M256 512A256 256 0 1 0 256 0a256 256 0 1 0 0 512zM164.2 99.9c-3.3-1.2-6.9 .1-8.9 2.9s-2.5 6.6-.9 9.4l45.2 78.3c3.3 5.7 10.3 8.3 16.9 6.3s11.5-8.4 11.5-15.3V112c0-8.8-7.2-16-16-16H184c-5.8 0-11.2 3.1-14.1 8.2L164.2 99.9zM256 128a16 16 0 1 1 0-32 16 16 0 1 1 0 32zm-16 64a16 16 0 1 1-32 0 16 16 0 1 1 32 0zm-16 96a16 16 0 1 1 0-32 16 16 0 1 1 0 32zM331.8 412.1c3.3 1.2 6.9-.1 8.9-2.9s2.5-6.6 .9-9.4l-45.2-78.3c-3.3-5.7-10.3-8.3-16.9-6.3s-11.5 8.4-11.5 15.3V400c0 8.8 7.2 16 16 16h28c5.8 0 11.2-3.1 14.1-8.2l5.7-9.9zM304 352a16 16 0 1 1-32 0 16 16 0 1 1 32 0zm-16 96a16 16 0 1 1 0-32 16 16 0 1 1 0 32zM112 256a16 16 0 1 1-32 0 16 16 0 1 1 32 0zm96 16a16 16 0 1 1 0-32 16 16 0 1 1 0 32zm96-16a16 16 0 1 1-32 0 16 16 0 1 1 32 0zm96 48a16 16 0 1 1 0-32 16 16 0 1 1 0 32zM160 352a16 16 0 1 1-32 0 16 16 0 1 1 32 0zm112 16a16 16 0 1 1 0-32 16 16 0 1 1 0 32z'/%3E%3C/svg%3E",
                                    width: 100, height: 100
                                },
                                { // Ikon Musik
                                    src: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 384 512'%3E%3Cpath fill='%2338bdf8' d='M384 192h-28.8c-4.9 0-9.6 2.1-12.8 5.7L256 288l0-144c0-44.2-35.8-80-80-80s-80 35.8-80 80l0 176c0 79.5 64.5 144 144 144s144-64.5 144-144l0-32c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 32c0 44.2-35.8 80-80 80s-80-35.8-80-80l0-176c0-17.7 14.3-32 32-32s32 14.3 32 32l0 128c0 17.7 14.3 32 32 32s32-14.3 32-32l0-128c0-17.7 14.3-32 32-32s32 14.3 32 32l0 112.4L337.5 167c2.4-2.7 5.7-4.2 9.2-4.2H384c17.7 0 32 14.3 32 32s-14.3 32-32 32z'/%3E%3C/svg%3E",
                                    width: 100, height: 100
                                },
                                { // Ikon Gamepad
                                    src: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 640 512'%3E%3Cpath fill='%2338bdf8' d='M112 160c-26.5 0-48 21.5-48 48s21.5 48 48 48 48-21.5 48-48-21.5-48-48-48zm32 144H80c-44.2 0-80 35.8-80 80v32c0 8.8 7.2 16 16 16h160c8.8 0 16-7.2 16-16v-32c0-44.2-35.8-80-80-80zm32-144c26.5 0 48-21.5 48-48s-21.5-48-48-48-48 21.5-48 48 21.5 48 48 48zm112 96c0-26.5-21.5-48-48-48H240c-26.5 0-48 21.5-48 48s21.5 48 48 48h48c26.5 0 48-21.5 48-48zm-48-176H240c-26.5 0-48 21.5-48 48s21.5 48 48 48h48c26.5 0 48-21.5 48-48s-21.5-48-48-48zM528 160c-26.5 0-48 21.5-48 48s21.5 48 48 48 48-21.5 48-48-21.5-48-48-48zm32 144H560c-44.2 0-80 35.8-80 80v32c0 8.8 7.2 16 16 16h160c8.8 0 16-7.2 16-16v-32c0-44.2-35.8-80-80-80zm32-144c26.5 0 48-21.5 48-48s-21.5-48-48-48-48 21.5-48 48 21.5 48 48 48z'/%3E%3C/svg%3E",
                                    width: 100, height: 100
                                },
                                { // Ikon Kode (DIPERBAIKI)
                                    src: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 640 512'%3E%3Cpath fill='%2338bdf8' d='M278.9 511.5l-61-17.7c-6.4-1.8-10-8.5-8.2-14.9L346.2 8.7c1.8-6.4 8.5-10 14.9-8.2l61 17.7c6.4 1.8 10 8.5 8.2 14.9L293.8 503.3c-1.9 6.4-8.5 10.1-14.9 8.2zm-114-112.2l43.5-46.4c4.6-4.9 4.3-12.7-.8-17.2L117 256l89.8-79.4c5.1-4.5 5.5-12.3.8-17.2l-43.5-46.4c-4.5-4.8-12.1-5.1-17-.5L3.8 247.2c-5.1 4.7-5.1 12.8 0 17.5l144.1 138.5c4.9 4.6 12.5 4.4 17-.5zm327.2.6l144.1-138.5c5.1-4.7 5.1-12.8 0-17.5L492.1 112.5c-4.9-4.6-12.5-4.4-17 .5L431.6 159.4c-4.6 4.9-4.3 12.7.8 17.2L523 256l-89.8 79.4c-5.1 4.5-5.5 12.3-.8 17.2l43.5 46.4c4.5 4.9 12.1 5.1 17 .6z'/%3E%3C/svg%3E",
                                    width: 120, height: 100
                                },
                                { // Ikon Terminal (DITAMBAHKAN)
                                    src: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 576 512'%3E%3Cpath fill='%2338bdf8' d='M9.4 86.6C-3.1 74.1-3.1 53.9 9.4 41.4s32.8-12.5 45.3 0L181 167.7c6.2 6.2 9.4 14.4 9.4 22.6s-3.1 16.4-9.4 22.6L54.7 339.3c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L110.7 256 9.4 150.6zM211.3 42.6c12.5-12.5 32.8-12.5 45.3 0l192 192c12.5 12.5 12.5 32.8 0 45.3l-192 192c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L378.7 256 211.3 87.9c-12.5-12.5-12.5-32.8 0-45.3z'/%3E%3C/svg%3E",
                                    width: 100, height: 100
                                }
                            ]
                        },
                        opacity: {
                            value: 0.4, // Opasitas partikel sedikit dinaikkan
                            animation: {
                                enable: true,
                                minimumValue: 0.1,
                                speed: 0.5
                            }
                        },
                        size: {
                            value: { min: 15, max: 25 }
                        },
                        move: {
                            enable: true,
                            speed: 1.2, // Kecepatan gerak sedikit ditambah
                            direction: "none",
                            outModes: "out"
                        }
                    },
                    detectRetina: true,
                }
            });
        });
    </script>


</body>
</html>
