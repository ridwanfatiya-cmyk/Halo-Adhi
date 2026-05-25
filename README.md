<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Satu Atap Tenang ☕</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #3d141a; /* Marun gelap teduh, nyaman di mata */
            color: #f7ebeb; 
            font-family: 'Segoe UI', -apple-system, BlinkMacSystemFont, Roboto, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            line-height: 1.6;
        }
        .container {
            max-width: 550px;
            width: 88%;
            padding: 30px 20px;
        }
        /* Foto Profil Bulat */
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid #ffb3c6;
            margin: 0 auto 20px auto;
            display: block;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }
        h1 {
            font-size: 1.6rem;
            color: #ffc2d1;
            text-align: center;
            margin-bottom: 15px;
        }
        p {
            font-size: 1rem;
            opacity: 0.9;
        }
        .opening-text {
            text-align: justify;
            margin-bottom: 30px;
        }
        /* Kotak Quotes Tokoh */
        .quote-box {
            background-color: #4f1b22;
            border-left: 4px solid #ff75a0;
            padding: 15px;
            border-radius: 4px;
            margin: 25px 0;
            font-style: italic;
        }
        .quote-author {
            display: block;
            text-align: right;
            font-style: normal;
            font-size: 0.85rem;
            color: #ffb3c6;
            margin-top: 5px;
        }
        /* Bagian Akordion/Tombol */
        .box-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 20px;
        }
        .secret-box {
            background-color: #521c23;
            border: 1px solid #6b252e;
            border-radius: 8px;
            padding: 15px;
            cursor: pointer;
            transition: background 0.2s;
        }
        .secret-box:hover {
            background-color: #5f2129;
        }
        .box-title {
            margin: 0;
            font-size: 0.95rem;
            color: #ffb3c6;
            font-weight: 600;
        }
        .box-content {
            display: none;
            margin-top: 10px;
            font-size: 0.95rem;
            color: #ffffff;
            border-top: 1px dashed #6b252e;
            padding-top: 10px;
            text-align: left;
        }
        /* Penutup */
        .closing {
            margin-top: 40px;
            text-align: center;
            border-top: 1px solid #4f1b22;
            padding-top: 20px;
        }
        .wa-button {
            display: inline-block;
            background-color: #ff75a0;
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: bold;
            margin-top: 10px;
            box-shadow: 0 4px 10px rgba(255, 117, 160, 0.3);
        }
    </style>
</head>
<body>
    <!-- Ganti dengan file musikmu jika ada -->
    <div class="container">
        <!-- Ganti dengan nama file fotomu -->
        <img src="Phoyonya.JPEG" alt="Teman" class="profile-img">
        <h1>Good Morning... ✨</h1>
        <p class="opening-text">
            Hari ini hari H pengumuman ya? Wajar banget kalau lu lagi deg-degan atau overthinking sekarang. Lu udah ngambil langkah yang berani buat memperjuangkan masa depan lu, dan lu udah berhasil ngelewatin itu sampai titik ini. Lu keren, beneran.
        </p>
        <!-- Quotes Tokoh Dunia (Henry Ford cocok untuk Teknik Industri / Bisnis) -->
        <div class="quote-box">
            "Failure is simply the opportunity to begin again, this time more intelligently."
            <span class="quote-author">— Henry Ford</span>
        </div>
        <p style="color: #ffc2d1; font-size: 0.9rem; text-align: center; margin-bottom: 15px;">
            (Klik kotak di bawah buat buka pesan + nyalain musik 🎵)
        </p>
        <div class="box-container">
            <!-- Kotak 1 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">🎯 Soal TI UI & Sekolah Bisnis...</p>
                <div class="box-content">
                    Lu milih Teknik Industri atau Sekolah Bisnis karena lu emang punya minat di sana. Pilihan kampus lu emang tinggi dan kompetitif, tapi itu bukti kalau lu punya ambisi yang bagus. Apapun hasilnya nanti jam 3 sore, ambisi dan isi kepala lu gak bakal hilang cuma karena hasil satu ujian. 
                </div>
            </div>
            <!-- Kotak 2 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">👥 Kalau lu merasa ragu karena orang lain...</p>
                <div class="box-content">
                    Orang lain cuma bisa ngomong atau berkomentar, tapi mereka gak tahu gimana perjuangan lu bagi waktu setahun ini. Gak usah dengerin yang bikin lu drop. Standar sukses lu, lu sendiri yang nentuin, bukan ekspektasi orang lain. temen-temen lu dan orang tua lu cuman berharap yang terbaik buat lu.
                </div>
            </div>
            <!-- Kotak 3 -->
            <div class="secret-box" onclick="toggleBox(this)">
                <p class="box-title">🚪 Apapun warnanya nanti...</p>
                <div class="box-content">
                    Kalau hijau, kita selebrasi bareng pake pecel lele itu. Kalau ternyata belum rezeki, lu harus ingat kalau ini bukan akhir dari segalanya. Masih banyak jalan lain (jalur mandiri, dll) dan mental lu udah kebentuk jadi lebih kuat lewat proses kemarin. Lu gak bakal mulai dari nol lagi.
                </div>
            </div>
        </div>
        <!-- Bagian Akhir -->
        <div class="closing">
            <p>Nanti sore setelah lihat pengumuman, Apapun hasilnya, <em>I've got your back.</em></p>
            <a href="https://wa.me/628123456789?text=Gue%20udah%20buka%20webnya,%20thanks%20ya..." class="wa-button" target="_blank">
                Pencet di sini kalau butuh temen ngobrol ☕
            </a>
        </div>
    </div>
    <script>
        function toggleBox(element) {
            var audio = document.getElementById("myAudio");
            audio.play().catch(function(e) { console.log("Audio play blocked"); });
            var content = element.querySelector('.box-content');
            if (content.style.display === "block") {
                content.style.display = "none";
            } else {
                content.style.display = "block";
            }
        }
    </script>

</body>
</html>
