<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Branding - siswi smk</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        softPink: {
                            50: '#fef7f9',
                            100: '#fef2f5',
                            200: '#fce7ed',
                            300: '#fad1de',
                            400: '#f8b9cb',
                            500: '#f4a3b8',
                            600: '#e08ba3',
                            700: '#c76e87',
                            800: '#a7586d',
                            900: '#8a4a59'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-bg {
            background: linear-gradient(135deg, #fce7ed 0%, #fad1de 100%);
        }
        .skill-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body class="bg-softPink-50 text-gray-800">

    <!-- Navbar -->
    <nav class="bg-softPink-500 text-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <h1 class="text-xl font-bold">Personal Branding - siswi smk</h1>
            <ul class="flex space-x-6 text-sm">
                <li><a href="#hero" class="hover:text-softPink-100 transition">Home</a></li>
                <li><a href="#about" class="hover:text-softPink-100 transition">Tentang Saya</a></li>
                <li><a href="#skills" class="hover:text-softPink-100 transition"> htmk,desain canva</a></li>
                <li><a href="#contact" class="hover:text-softPink-100 transition">085194335008</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="hero-bg text-gray-800 py-20">
        <div class="max-w-7xl mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-8 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4 text-softPink-700">Halo, saya april leanitha tsagrin!</h1>
                <p class="text-lg md:text-xl mb-6">
                    Siswi Sekolah Menengah Kejuruan yang sedang belajar dan berkembang di bidang teknologi dan desain. Walaupun belum punya pengalaman profesional, saya penuh semangat untuk belajar bahasa pemograman, desain di Canva, dan keterampilan komunikasi.
                </p>
                <a href="#about" class="bg-softPink-300 hover:bg-softPink-400 text-softPink-800 px-6 py-3 rounded-full font-semibold transition transform hover:scale-105">Pelajari Lebih Lanjut</a>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <img src="https://placehold.co/400x500" alt="Foto profil siswi SMK dengan latar belakang soft pink lembut, memakai seragam sekolah, tersenyum dengan sikap percaya diri dan lembut, gaya portrait close-up dengan pencahayaan alami dari depan, menunjukkan keceriaan remaja namun tenang dan profesional awal karier" class="rounded-full shadow-xl w-80 h-auto border-4 border-softPink-300" onerror="this.style.display='none'">
                    <div class="absolute inset-0 rounded-full bg-gradient-to-br from-softPink-200/30 to-transparent"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10 text-softPink-600">tentang saya</h2>
            <div class="text-center">
                <p class="text-lg mb-4">
                    Saya adalah siswi SMK yang antusias belajar hal-hal baru, khususnya di dunia teknologi dan kreatif. Meskipun belum memiliki pengalaman yang formal, saya sedang membangun dasar-dasar saya melalui pendidikan dan proyek pribadi.
                </p>
                <p class="text-lg mb-4">
                    Saya fokus belajar bahasa pemograman untuk membangun aplikasi sederhana, desain grafis menggunakan Canva untuk membuat konten visual menarik, dan keterampilan komunikasi untuk berinteraksi efektif dengan orang lain.
                </p>
                <p class="text-lg">
                    Mimpinya adalah menjadi profesional di bidang desain, membantu orang lain melalui teknologi dan seni digital.
                </p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-16 bg-softPink-100">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10 text-softPink-700">Keterampilan Saya</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="skill-card bg-white p-6 rounded-lg shadow-md text-center">
                    <div class="w-32 h-32 mx-auto mb-4 bg-softPink-200 rounded-full flex items-center justify-center text-softPink-600 font-bold text-2xl">💻</div>
                    <h3 class="text-xl font-semibold mb-2 text-softPink-600">Bahasa Pemograman</h3>
                    <p class="text-gray-700">
                        Sedang belajar JavaScript, Python, dan HTML/CSS untuk membuat situs web 
                    </p>
                </div>
                <div class="skill-card bg-white p-6 rounded-lg shadow-md text-center">
                    <div class="w-32 h-32 mx-auto mb-4 bg-softPink-200 rounded-full flex items-center justify-center text-softPink-600 font-bold text-2xl">🎨</div>
                    <h3 class="text-xl font-semibold mb-2 text-softPink-600">Desain di Canva</h3>
                    <p class="text-gray-700">
                        Menguasai Canva untuk membuat poster, infografik, dan desain media sosial yang menarik. Belajar layout, tipografi, dan kreativitas visual.
                    </p>
                </div>
                <div class="skill-card bg-white p-6 rounded-lg shadow-md text-center">
                    <div class="w-32 h-32 mx-auto mb-4 bg-softPink-200 rounded-full flex items-center justify-center text-softPink-600 font-bold text-2xl">💬</div>
                    <h3 class="text-xl font-semibold mb-2 text-softPink-600">Komunikasi</h3>
                    <p class="text-gray-700">
                        Belajar presentasi efektif, networking, dan komunikasi tim. Mengikuti workshop untuk meningkatkan soft skills di dunia kerja.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8 text-softPink-600">Hubungi Saya</h2>
            <p class="text-lg mb-6">Mari ☎️:085194335008
            📸:aprilsgrin
            📩:aprilsagrinn@gmail.com</p>
            <form id="contactForm" class="max-w-md mx-auto mb-6">
                <input type="text" id="name" placeholder="Nama Anda" class="w-full mb-4 p-3 border border-gray-300 rounded-md" required>
                <input type="email" id="email" placeholder="Email Anda" class="w-full mb-4 p-3 border border-gray-300 rounded-md" required>
                <textarea id="message" placeholder="Pesan Anda" class="w-full mb-4 p-3 border border-gray-300 rounded-md" rows="5" required></textarea>
                <button type="submit" class="bg-softPink-500 hover:bg-softPink-600 text-white px-6 py-3 rounded-md font-semibold transition">Kirim Pesan</button>
            </form>
            <p class="text-gray-600">Atau follow saya di social media untuk update terkini!</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-softPink-600 text-white py-6">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p>© 2025 Personal Branding Siswi SMK. Dibuat dengan cinta menggunakan HTML, CSS, dan JavaScript.</p>
        </div>
    </footer>

    <script>
        // Simple form submission handler
        const contactForm = document.getElementById('contactForm');
        contactForm.addEventListener('submit', function(event) {
            event.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;

            // Simple alert for demo; in real app, send to server
            alert(`Terima kasih, ${name}! Pesan Anda sudah diterima. Email: ${email}\nPesan: ${message}`);

            // Reset form
            contactForm.reset();
        });
    </script>
</body>
</html>
