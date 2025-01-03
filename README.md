<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Besar Jaringan Komputer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Add a fade-in effect */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* Apply fadeIn animation to elements */
        .fade-in {
            animation: fadeIn 1s ease-out;
        }

        /* Optional: Add hover animation for interactive elements */
        .hover-animate:hover {
            transform: scale(1.05);
            transition: transform 0.3s ease;
        }
    </style>
    <script>
        // Optional: Delay the animation for a smooth opening effect
        window.onload = () => {
            setTimeout(() => {
                document.body.classList.add("fade-in");
            }, 100);
        };
    </script>
</head>
<body class="bg-gsradient-to-r from-pink-200 via-pink-300 to-pink-400 font-sans text-white fade-in">
    <!-- Wrapper -->
    <div class="max-w-6xl mx-auto my-16 p-8 bg-white text-gray-900 shadow-2xl rounded-3xl fade-in">
        <!-- Biodata Section -->
        <section class="text-center border-b pb-8">
            <div class="relative inline-block">
                <img src="vionadeva.jpeg" alt="Foto Saya" class="w-40 h-40 rounded-full shadow-lg border-4 border-pink-300 fade-in">
                <span class="absolute -bottom-2 right-0 bg-pink-400 text-white text-sm px-4 py-1 rounded-full">Mahasiswa</span>
            </div>
            <h1 class="mt-6 text-4xl font-extrabold fade-in">Viona Deva Qaulika</h1>
            <p class="text-lg fade-in">NIM: 607012400110</p>
            <p class="text-lg fade-in">Kelas: D3SI 48-02</p>
            <p class="text-lg fade-in">Mata Kuliah: Jaringan Komputer</p>
        </section>

        <!-- Materi Section -->
        <section class="mt-8 fade-in">
            <h2 class="text-3xl font-bold text-center mb-6 fade-in">Materi: Switch</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-pink-100 p-6 rounded-lg shadow-inner fade-in">
                    <h3 class="text-2xl font-bold mb-4">Pengertian Switch</h3>
                    <p class="text-gray-700">Switch adalah perangkat jaringan yang digunakan untuk menghubungkan perangkat-perangkat dalam suatu jaringan lokal (LAN). Fungsi switch adalah meneruskan paket data antara perangkat-perangkat yang terhubung ke switch tersebut. Switch bekerja pada lapisan data link (layer 2) dalam OSI Layer. Dan mampu melakukan pengiriman data berdasarkan alamat MAC (Media Access Control).</p>
                </div>
                <div class="bg-pink-100 p-6 rounded-lg shadow-inner fade-in">
                    <h3 class="text-2xl font-bold mb-4">Fungsi Switch</h3>
                    <p class="text-gray-700">Switch menghubungkan perangkat dalam jaringan lokal (LAN) dan meneruskan paket data dengan efisien. Beberapa fungsi utama switch adalah:</p>
                    <ul class="list-disc list-inside text-gray-700">
                        <li>Meneruskan paket data berdasarkan alamat MAC tujuan.</li>
                        <li>Segmentasi jaringan dengan VLAN.</li>
                        <li>Meningkatkan kinerja jaringan dengan mengurangi tabrakan data.</li>
                        <li>Memfilter dan mengontrol lalu lintas broadcast.</li>
                        <li>Penyampaian paket data dengan cepat.</li>
                    </ul>
                </div>
            </div>
            <div class="mt-6 bg-pink-100 p-6 rounded-lg shadow-inner fade-in">
                <h3 class="text-2xl font-bold mb-4">Jenis Switch</h3>
                <ul class="list-disc list-inside text-gray-700">
                    <li>Unmanaged Switch</li>
                    <li>Managed Switch</li>
                    <li>Layer 2 Switch</li>
                    <li>Layer 3 Switch</li>
                    <li>PoE Switch</li>
                    <li>Stackable Switch</li>
                </ul>
            </div>
            <div class="mt-6 text-center fade-in">
                <img src="https://www.dlink.com/en/-/media/product-pages/dms/108/dms-108-a1-right-side.png" alt="Gambar Switch" class="w-80 mx-auto rounded-lg shadow-lg hover-animate">
                <p class="text-sm text-gray-600 mt-2">Contoh gambar perangkat Switch.</p>
            </div>
            <p class="mt-6 text-gray-700 fade-in">Sumber materi: <a href="https://it.telkomuniversity.ac.id" class="text-pink-500 underline" target="_blank">https://it.telkomuniversity.ac.id</a></p>
        </section>

        <!-- Link Section -->
        <section class="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-pink-100 p-6 rounded-lg shadow-inner text-center fade-in">
                <h3 class="text-xl font-bold mb-4">Tutorial Hosting web</h3>
                <a href="https://drive.google.com/file/d/1cuoRLCE1gFlzMI9YV2jOpu5p1LdpUBB2/view?usp=drive_link" class="text-pink-500 underline hover-animate">Klik di sini</a>
            </div>
            <div class="bg-pink-100 p-6 rounded-lg shadow-inner text-center fade-in">
                <h3 class="text-xl font-bold mb-4">Isi website</h3>
                <a href="https://drive.google.com/file/d/1hpcMj6CpNydHXMCpy_8r50v7LR3aNFwp/view?usp=drive_link" class="text-pink-500 underline hover-animate">Klik di sini</a>
            </div>
        </section>

        <!-- Footer Section -->
        <footer class="mt-12 text-center text-sm text-gray-600">
            &copy; 2024 Viona Deva. All Right Reserved. 
        </footer>
    </div>
</body>
</html>
