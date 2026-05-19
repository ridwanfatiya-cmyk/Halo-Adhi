<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Some Message For You ❤️</title>
    <style>
        /* Mengatur suasana warna latar belakang yang hangat dan menenangkan */
        body {
            margin: 0;
            padding: 0;
            background-color: #4a121a; /* Merah marun gelap yang teduh */
            color: #fff5f5; /* Putih gading agar tidak kontras menusuk mata */
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            line-height: 1.6;
        }

        .container {
            max-width: 600px;
            width: 90%;
            text-align: center;
            padding: 40px 20px;
        }

        /* Animasi hati pink pastel lembut */
        .heart-icon {
            font-size: 50px;
            color: #ffb3c6; /* Pink pastel */
            display: inline-block;
            animation: pulse 2s infinite;
            margin-bottom: 20px;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); filter: drop-shadow(0 0 10px #ffb3c6); }
            100% { transform: scale(1); }
        }

        h1 {
            font-size: 2rem;
            color: #ffc2d1;
            margin-bottom: 10px;
        }

        .opening-text {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-bottom: 40px;
        }

        /* Bagian Tombol Interaktif */
        .box-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 40px;
        }

        .secret-box {
            background-color: #5c1d24;
            border: 1px solid #7a2a33;
            border-radius: 12px;
            padding: 15px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }

        .secret-box:hover {
            background-color: #6e252d;
            transform: translateY(-2px);
        }

        .box-title {
            margin: 0;
            font-size: 1rem;
            color: #ffb3c6;
            font-weight: 600;
        }

        /* Menyembunyikan pesan sebelum diklik */
        .box-content {
            display: none;
            margin-top: 10px;
            font-size: 1rem;
            color: #ffffff;
            border-top: 1px dashed #7a2a33;
            padding-top: 10px;
            text-align: left;
        }

        /* Bagian Penutup & Tombol WA */
        .closing {
            margin-top: 50px;
            border-top: 1px solid #5c1d24;
            padding-top: 30px;
        }

        .wa-button {
            display: inline-block;
            background-color: #ff75a0; /* Tombol pink cerah */
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: bold;
            margin-top: 15px;
            transition: background 0.3s;
            box-shadow: 0 4px 15px rgba(255, 117, 160, 0.4);
        }

        .wa-button:hover {
            background-color: #ff5285;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Ikon Hati -->
        <div class="heart-icon">💖</div>

        <!-- 1. Pembuka & Validasi -->
        <h1>Hai, ini pesan singkat yang aku siapin buat lu...</h1>
        <p class="opening-text">
            Aku tahu beberapa hari ini rasanya berat banget buat kamu. Menunggu pengumuman itu melelahkan, dan isi kepala lu mungkin lagi berisik banget karena ekspektasi orang lain. Bingung, cemas, takut... itu semua wajar, kok. Kamu gak salah kalau merasa begitu saat ini.
        </p>

        <!-- 2. Konten Bukti Nyata (Interaktif) -->
        <p style="color: #ffc2d1; font-weight: bold;">Klik kotak-kotak di bawah ini:</p>
        
        <div class="box-container">
            <!-- Kotak 1 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">🎁 Tentang Hasil Ujianmu Nanti...</p>
                <div class="box-content">
                    Apapun warna yang muncul di layarmu nanti—mau itu hijau ataupun warna lain—itu <strong>sama sekali tidak mengurangi nilai dirimu</strong>. Hasil ujian itu cuma layar penunjuk jalan, bukan penentu mutlak masa depanmu. Kamu tetap manusia yang hebat dengan proses yang luar biasa.
                </div>
            </div>

            <!-- Kotak 2 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">🎁 Tentang Krisis Kepercayaan dari Orang Lain...</p>
                <div class="box-content">
                    Dunia mungkin gak lihat seberapa keras kamu berjuang sendirian, tapi aku bisa rasain itu kok. Jangan biarkan keraguan orang lain bikin kamu lupa kalau kamu adalah orang yang tangguh, baik, dan punya banyak potensi yang belum mereka tahu. Aku bangga banget sama prosesmu sampai titik ini.
                </div>
            </div>

            <!-- Kotak 3 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">🎁 Yang Perlu Kamu Ingat...</p>
                <div class="box-content">
                    Kuliah itu cuma salah satu dari ribuan jalan menuju sukses. Tempatmu bersinar tidak ditentukan oleh nama besar kampus, tapi oleh besarnya semangat yang kamu punya. Kamu akan tetap sampai di tempat terbaikmu, dengan caramu sendiri.
                </div>
            </div>
        </div>

        <!-- 3. Penutup & Akses Kontak -->
        <div class="closing">
            <p>Apapun hasilnya nanti, gw bakal tetap jadi temen lu, anjay... agak geli jujur <em>I'm always in your corner.</em></p>
            <!-- Ganti nomor di bawah ini dengan nomor WA-mu (Gunakan format 62 di depan) -->
            <a href="https://wa.me/62895402920321?text=Hai,%20makasih%20ya%20web-nya.%20Aku%20butuh%20temen%20ngobrol%20sekarang..." class="wa-button" target="_blank">
                Klik di sini kalau kamu butuh temen ngobrol sekarang ❤️
            </a>
        </div>
    </div>

    <!-- JavaScript Sederhana untuk Efek Klik -->
    <script>
        function toggleBox(element) {
            // Mengambil elemen konten di dalam kotak yang diklik
            var content = element.querySelector('.box-content');
            
            // Mengubah status tampilannya (buka/tutup)
            if (content.style.display === "block") {
                content.style.display = "none";
                element.style.backgroundColor = "#5c1d24";
            } else {
                content.style.display = "block";
                element.style.backgroundColor = "#6e252d";
            }
        }
    </script>

</body>
</html>
