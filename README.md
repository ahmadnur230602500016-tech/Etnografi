# Etnografi<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analisis Struktur Sosial & Arsitektur Sulawesi Selatan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            scroll-behavior: smooth;
        }
        .serif {
            font-family: 'Playfair Display', serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .sticky-nav {
            position: sticky;
            top: 0;
            z-index: 50;
            backdrop-filter: blur(8px);
            background-color: rgba(255, 255, 255, 0.9);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header / Hero Section -->
    <header class="gradient-bg text-white py-20 px-6 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="serif text-4xl md:text-6xl mb-4">Kebudayaan Sulawesi Selatan</h1>
            <p class="text-xl text-gray-300 font-light tracking-wide">Analisis Struktur Sosial, Organisasi, dan Arsitektur Tradisional</p>
            <div class="mt-8 flex justify-center gap-4">
                <a href="#struktur-sosial" class="bg-amber-600 hover:bg-amber-700 text-white px-6 py-2 rounded-full transition shadow-lg">Struktur Sosial</a>
                <a href="#arsitektur" class="border border-white hover:bg-white hover:text-black px-6 py-2 rounded-full transition">Arsitektur</a>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="sticky-nav border-b border-gray-200">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="font-bold text-amber-800 tracking-tighter">SULSEL-KULTUR</span>
            <div class="hidden md:flex gap-8 text-sm font-semibold uppercase tracking-widest text-gray-600">
                <a href="#bugis" class="hover:text-amber-600">Bugis</a>
                <a href="#makassar" class="hover:text-amber-600">Makassar</a>
                <a href="#toraja" class="hover:text-amber-600">Toraja</a>
                <a href="#mandar" class="hover:text-amber-600">Mandar</a>
            </div>
        </div>
    </nav>

    <main class="max-w-6xl mx-auto px-6 py-12">
        
        <!-- SECTION I: STRUKTUR SOSIAL -->
        <section id="struktur-sosial" class="mb-20">
            <div class="flex items-center gap-4 mb-10">
                <div class="h-1 w-12 bg-amber-600"></div>
                <h2 class="serif text-3xl italic">I. Analisis Struktur Sosial</h2>
            </div>

            <!-- BUGIS -->
            <div id="bugis" class="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden mb-12">
                <div class="p-8">
                    <div class="flex items-center gap-2 text-amber-700 mb-4">
                        <i data-lucide="users"></i>
                        <span class="font-bold tracking-widest uppercase text-sm">Masyarakat Bugis</span>
                    </div>
                    <h3 class="text-2xl font-bold mb-6">Arung, Pangadereng, dan Asseajingeng</h3>
                    
                    <div class="grid md:grid-cols-2 gap-8">
                        <div class="bg-gray-50 p-6 rounded-xl border-l-4 border-amber-500 italic text-gray-700">
                            <h4 class="font-bold text-gray-900 not-italic mb-2">Teks Kuratorial</h4>
                            "Masyarakat Bugis secara historis mengenal susunan sosial yang bertaut dengan mitologi To Manurung, legitimasi kerajaan, kepemilikan kehormatan, dan kedudukan dalam adat..."
                        </div>
                        <div>
                            <h4 class="font-bold mb-4 flex items-center gap-2"><i data-lucide="layers" class="w-5"></i> Penjelasan Struktur</h4>
                            <ul class="space-y-4">
                                <li><strong class="text-amber-800">a. Arung / Anakarung:</strong> Golongan bangsawan, pusat tata nilai, dan penjaga martabat komunitas.</li>
                                <li><strong class="text-amber-800">b. To Maradeka / To Sama:</strong> Orang merdeka; petani, pedagang, dan tulang punggung ekonomi.</li>
                                <li><strong class="text-amber-800 text-sm opacity-60">c. Ata:</strong> Kategori historis (tawanan/ketergantungan). Disajikan sebagai catatan sejarah kritis.</li>
                            </ul>
                        </div>
                    </div>

                    <div class="mt-8 p-6 bg-amber-50 rounded-xl">
                        <h4 class="font-bold mb-2">Organisasi Sosial: Asseajingeng</h4>
                        <p class="text-gray-700">Hubungan keluarga yang luas. Kerabat (<em>seajing</em>) wajib menjaga <strong>siri’</strong>; penghinaan pada satu anggota adalah luka bagi seluruh keluarga.</p>
                    </div>
                </div>
            </div>

            <!-- MAKASSAR -->
            <div id="makassar" class="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden mb-12">
                <div class="p-8">
                    <div class="flex items-center gap-2 text-blue-700 mb-4">
                        <i data-lucide="anchor"></i>
                        <span class="font-bold tracking-widest uppercase text-sm">Masyarakat Makassar</span>
                    </div>
                    <h3 class="text-2xl font-bold mb-6">Karaeng, Tu Maradeka, dan Politik Kehormatan</h3>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <div class="p-4 border border-gray-100 rounded-lg bg-gray-50">
                            <h5 class="font-bold text-blue-800 mb-2">Anaq Karaeng</h5>
                            <p class="text-sm">Keturunan bangsawan. Gelar menjadi penanda legitimasi sosial dan representasi sejarah kerajaan.</p>
                        </div>
                        <div class="p-4 border border-gray-100 rounded-lg bg-gray-50">
                            <h5 class="font-bold text-blue-800 mb-2">Tu Maradeka</h5>
                            <p class="text-sm">Basis sosial masyarakat: nelayan, prajurit, dan pemuka kampung.</p>
                        </div>
                        <div class="p-4 border border-gray-100 rounded-lg bg-gray-50 opacity-60">
                            <h5 class="font-bold text-blue-800 mb-2">Ata</h5>
                            <p class="text-sm">Kategori historis ketergantungan masa lalu, kini telah melebur ke kelompok merdeka.</p>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h4 class="font-bold mb-4">Organisasi Sosial</h4>
                        <p class="text-gray-700 leading-relaxed">Kuasa tidak hanya ditentukan oleh garis darah, tetapi juga oleh kemampuan menjaga harmoni, keberanian, dan kehormatan publik dalam hubungan dengan dewan adat.</p>
                    </div>
                </div>
            </div>

            <!-- TORAJA -->
            <div id="toraja" class="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden mb-12">
                <div class="p-8">
                    <div class="flex items-center gap-2 text-red-700 mb-4">
                        <i data-lucide="home"></i>
                        <span class="font-bold tracking-widest uppercase text-sm">Masyarakat Toraja</span>
                    </div>
                    <h3 class="text-2xl font-bold mb-6">Tana’, Tongkonan, dan Martabat Leluhur</h3>
                    
                    <div class="grid md:grid-cols-2 gap-8 mb-8">
                        <div class="space-y-4">
                            <div class="flex gap-4">
                                <div class="bg-red-100 text-red-800 h-8 w-8 rounded-full flex items-center justify-center shrink-0 font-bold italic">B</div>
                                <div><strong>Tana’ Bulaan:</strong> Bangsawan tinggi, terkait otoritas adat dan ritus besar.</div>
                            </div>
                            <div class="flex gap-4">
                                <div class="bg-gray-200 text-gray-800 h-8 w-8 rounded-full flex items-center justify-center shrink-0 font-bold italic">S</div>
                                <div><strong>Tana’ Bassi:</strong> Bangsawan menengah dengan kedudukan sosial penting.</div>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div class="flex gap-4">
                                <div class="bg-green-100 text-green-800 h-8 w-8 rounded-full flex items-center justify-center shrink-0 font-bold italic">K</div>
                                <div><strong>Tana’ Karurung:</strong> Masyarakat umum, petani, dan warga adat.</div>
                            </div>
                            <div class="flex gap-4 opacity-50">
                                <div class="bg-black text-white h-8 w-8 rounded-full flex items-center justify-center shrink-0 font-bold italic">Q</div>
                                <div><strong>Tana’ Kua-kua:</strong> Kategori historis terendah sistem lama.</div>
                            </div>
                        </div>
                    </div>

                    <div class="border-t pt-6">
                        <h4 class="font-bold text-red-900 mb-2">Kekuatan Tongkonan</h4>
                        <p class="text-gray-700 italic">"Tongkonan mana?" adalah pertanyaan tentang asal-usul, jaringan kekerabatan, dan hak adat. Ia adalah titik temu pemeliharaan memori keluarga.</p>
                    </div>
                </div>
            </div>

            <!-- MANDAR -->
            <div id="mandar" class="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden">
                <div class="p-8">
                    <div class="flex items-center gap-2 text-teal-700 mb-4">
                        <i data-lucide="waves"></i>
                        <span class="font-bold tracking-widest uppercase text-sm">Masyarakat Mandar</span>
                    </div>
                    <h3 class="text-2xl font-bold mb-6">Malaqbi, Hadat, dan Etika Pesisir</h3>
                    
                    <div class="grid md:grid-cols-2 gap-8">
                        <div>
                            <h4 class="font-bold mb-4">Struktur Historis</h4>
                            <ul class="list-disc list-inside space-y-2 text-gray-700">
                                <li><strong>Todiang Laiyana:</strong> Bangsawan/Mara’dia.</li>
                                <li><strong>To Maradeka:</strong> Warga produktif (pelaut, petani).</li>
                                <li><strong>Batua:</strong> Lapisan terendah masa lalu.</li>
                            </ul>
                        </div>
                        <div class="bg-teal-50 p-6 rounded-xl">
                            <h4 class="font-bold text-teal-900 mb-2">Nilai Malaqbi</h4>
                            <p class="text-sm leading-relaxed">Menekankan keluhuran perilaku, kesantunan bicara, dan rasa hormat. <strong>Siri’</strong> dalam Mandar adalah konsekuensi hilangnya nilai Malaqbi.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <hr class="mb-20">

        <!-- SECTION II: ARSITEKTUR -->
        <section id="arsitektur" class="mb-20">
            <div class="flex items-center gap-4 mb-10">
                <div class="h-1 w-12 bg-amber-600"></div>
                <h2 class="serif text-3xl italic">II. Arsitektur Tradisional</h2>
            </div>

            <div class="grid md:grid-cols-2 gap-12">
                <!-- TONGKONAN -->
                <div class="card-hover">
                    <div class="aspect-video bg-gray-200 rounded-2xl mb-6 flex items-center justify-center overflow-hidden">
                        <!-- Placeholder for Tongkonan Image -->
                        <div class="text-center p-8">
                            <i data-lucide="image" class="w-12 h-12 mx-auto text-gray-400 mb-2"></i>
                            <span class="text-gray-500 font-medium">[Ilustrasi Tongkonan Toraja]</span>
                        </div>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Tongkonan: Rumah Leluhur & Kosmos</h3>
                    <p class="text-gray-600 mb-6 italic">"Tubuh sosial masyarakat Toraja, panggung ingatan yang menonjol dalam daftar tentatif UNESCO."</p>
                    
                    <div class="space-y-4 text-sm">
                        <div class="p-4 bg-white shadow-sm rounded-lg border border-gray-100">
                            <h5 class="font-bold text-amber-700">Filosofi Atap</h5>
                            Lengkung yang menyerupai perahu atau tanduk kerbau; simbol perjalanan dan ikatan dunia leluhur.
                        </div>
                        <div class="p-4 bg-white shadow-sm rounded-lg border border-gray-100">
                            <h5 class="font-bold text-amber-700">Struktur & Tektonika</h5>
                            Sistem tiang dan balok yang unik, memisahkan bagian bawah, badan, dan atap.
                        </div>
                        <div class="p-4 bg-amber-900 text-white rounded-lg">
                            <span class="uppercase text-xs font-bold block mb-1 opacity-70">Label Objek: Miniatur</span>
                            "Lihatlah atapnya: ia seperti perahu yang berhenti di gunung."
                        </div>
                    </div>
                </div>

                <!-- BALLA LOMPOA -->
                <div class="card-hover">
                    <div class="aspect-video bg-gray-200 rounded-2xl mb-6 flex items-center justify-center overflow-hidden">
                        <!-- Placeholder for Balla Lompoa Image -->
                        <div class="text-center p-8">
                            <i data-lucide="image" class="w-12 h-12 mx-auto text-gray-400 mb-2"></i>
                            <span class="text-gray-500 font-medium">[Ilustrasi Balla Lompoa Gowa]</span>
                        </div>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Balla Lompoa: Istana & Ingatan</h3>
                    <p class="text-gray-600 mb-6 italic">"Representasi rumah kebesaran Kerajaan Gowa, dibangun ulang pada 1936 menggunakan kayu ulin."</p>
                    
                    <div class="space-y-4 text-sm">
                        <div class="p-4 bg-white shadow-sm rounded-lg border border-gray-100">
                            <h5 class="font-bold text-blue-700">Sulapa Appa</h5>
                            Falsafah segi empat sebagai simbol kesempurnaan hidup yang direfleksikan pada struktur bangunan.
                        </div>
                        <div class="p-4 bg-white shadow-sm rounded-lg border border-gray-100">
                            <h5 class="font-bold text-blue-700">Tiga Bagian Kosmos</h5>
                            Pammakang (loteng), Kale Balla (badan rumah), dan Passiringan (kolong).
                        </div>
                        <div class="p-4 bg-blue-900 text-white rounded-lg">
                            <span class="uppercase text-xs font-bold block mb-1 opacity-70">Label Objek: Replika Tiang</span>
                            "Tiang bukan hanya penyangga kayu. Ia adalah garis tegak antara bumi, manusia, dan martabat."
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-900 text-white py-12 px-6">
        <div class="max-w-6xl mx-auto text-center">
            <p class="text-gray-400 text-sm mb-4">Disusun berdasarkan naskah analisis kebudayaan Sulawesi Selatan</p>
            <div class="flex justify-center gap-6 opacity-50">
                <span>Bugis</span>
                <span>Makassar</span>
                <span>Toraja</span>
                <span>Mandar</span>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();
    </script>
</body>
</html>
