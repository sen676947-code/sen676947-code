<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Web Saya</title>

    <style>
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #080B16;
        }
        header {
            background-color: #0D1220;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #111827;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            padding: 8px 15px;
            border-radius: 8px;
            transition: 0.3s;
        }
        nav a:hover {
            background-color: #3B71D9;
            text-decoration: underline;
        }
        .konten {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #151B2B;
            border: 1px solid #2A3652;
            border-radius: 12px;
        }
        .hobi {
            color: white;
        }
        #hobi,
        #game-favorite,
        #tentang-saya,
        #deskripsi {
            scroll-margin-top: 80px;
        }
        .fade-section {
            opacity: 0;
            transform: translateY(40px);
            transition:
                opacity 0.8s ease,
                transform 0.8s ease;
        }
        .fade-section.show {
            opacity: 1;
            transform: translateY(0);
        }
        .top-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #5487D8;
            color: white;
            padding: 12px 15px;
            border-radius: 50%;
            text-decoration: none;
            font-size: 20px;
            z-index: 2000;
            transition: 0.3s;
        }
        .top-btn:hover {
            background-color: #3B71D9;
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.4);
        }
        img {
            max-width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img
            src="ea-sports@logotyp.us.svg"
            alt="EA Sports Logo"
            width="200"
            height="100"
            style="position: absolute; top: -10px; left: -50px;">
        <img
            src="sw_logo_stacked_2x-52b4f6d33087_7ef430af.png"
            alt="Star Wars Logo"
            width="100"
            height="50"
            style="position: absolute; top: 10px; right: 10px;">
        <h1 style="color: #F8FAFC; text-align: center;">
            Web Portofolio
        </h1>
    </header>
    <div class="konten fade-section"
        style="
            background-color: #2A3652;
            width: 700px;
            border-radius: 10px;
            margin: 5px auto;
            padding: 2px;">
        <h2 style="color: white; text-align: center;">
            Ini adalah website tentang hobi saya
        </h2>
    </div>
    <hr width="100%" color="#3B82F6" size="5">
    <nav>
        <a href="#hobi">Hobi</a>
        <a href="#game-favorite">Game Favorite</a>
        <a href="#tentang-saya">Tentang Saya</a> 
        <a href="#deskripsi">Deskripsi</a>
    </nav>
    <div
        class="konten fade-section"
        style="
            background-color: #2A3652;
            width: 700px;
            border-radius: 10px;
            margin: 20px auto;
            padding: 20px;">
        <h1
            id="tentang-saya"
            style="color: white;">Tentang Saya:</h1>
            <h2 style="color: #CBD5E1;">Nama: Husen Al-Amrie</h2>
            <h2 style="color: #CBD5E1;">Kelas: XI RPL B</h2>
            <h2 style="color: #CBD5E1;">Jurusan: RPL (Rekaya Perangkat Lunak)</h2>
        <h4 style="color: #CBD5E1;">
            Saya adalah salah satu siswa SMK Negeri 3 Palu jurusan
            Rekayasa Perangkat Lunak (RPL).

            Saya memiliki ketertarikan pada dunia teknologi,
            terutama dalam membuat website dan belajar pemrograman.

            Di waktu luang, saya suka bermain game dan mencoba
            berbagai game seperti Star Wars Jedi: Fallen Order
            dan EA Sports FC 26.

            Selain bermain game, saya juga senang mempelajari
            hal-hal baru yang berhubungan dengan komputer dan teknologi.</h4>
    </div>
    <div
        class="konten fade-section"
        style="
            background-color: #2A3652;
            width: 700px;
            border-radius: 10px;
            margin: 20px auto;
            padding: 20px;">
        <h1
            id="hobi"
            style="color: white;">Hobi:</h1>
        <hr width="100%" color="#3B82F6" size="5">
        <h3 style="color: #ffffff;">Berikut adalah beberapa hobi saya:</h3>
        <h2 style="color: #F8FAFC;">1. Bermain Game</h2>
        <p style="color: #CBD5E1;">
            Bermain game adalah salah satu hobi favorit saya.
            Saya menikmati berbagai jenis game, mulai dari game aksi,
            petualangan, hingga simulasi olahraga.

            Bermain game tidak hanya menghibur, tetapi juga membantu
            saya mengasah keterampilan strategi dan refleks.</p>
        <hr width="100%" color="#3B82F6" size="5">
        <h2 style="color: #F8FAFC;">2. Belajar Frontend Development</h2>
        <p style="color: #CBD5E1;">
            Saya juga memiliki ketertarikan pada frontend development
            dan UI design.

            Saya senang mempelajari cara membuat tampilan website agar
            terlihat menarik, modern, rapi, dan mudah digunakan.

            Saya tertarik mencoba berbagai kombinasi warna, layout,
            font, serta elemen desain untuk membuat tampilan website
            menjadi lebih nyaman dilihat.

            Selain itu, saya juga ingin terus mengembangkan kemampuan
            HTML dan CSS agar dapat membuat website dengan desain
            yang sesuai dengan ide dan kreativitas saya.</p>
    </div>
    <div
        class="konten fade-section"
        style="
            background-color: #2A3652;
            width: 700px;
            border-radius: 10px;
            margin: 20px auto;
            padding: 20px;">
        <h2 style="color: #F8FAFC;">Beberapa web & Form yang pernah saya buat:</h2>
        <ul style="color: #CBD5E1; text-align: left;">
            <li>
                <a href="Tugas Form Pendaftaran.html"style="color: #CBD5E1; text-decoration: underline;">&rarr; Tes 1 form: Form Pendaftaran Siswa Baru</a>
            </li>

            <li><a href="tes buat web liverpool 1.html"style="color: #CBD5E1; text-decoration: underline;">&rarr; Tes 1 web : sejarah Liverpool</a></li>
            <li><a href="tes buat web liverpool 2.html"style="color: #CBD5E1; text-decoration: underline;">&rarr; Tes 2 web : biodata pemain Liverpool</a></li>
            <li><a href="tes buat web liverpool 3.html"style="color: #CBD5E1; text-decoration: underline;">&rarr; Tes 3 web : jadwal pertandingan Liverpool</a></li>
        </ul>
    </div>
    <div
        class="konten fade-section"
        style="
            background-color: #2A3652;
            width: 700px;
            border-radius: 10px;
            margin: 20px auto;
            padding: 20px;">
        <h1 id="game-favorite"style="color: white;">Game Favorite:</h1>
        <hr width="100%" color="#3B82F6" size="5">

        <p style="color: white;">Berikut adalah beberapa game favorit saya:</p>
        <h1 style="color: white;">1. Star Wars Jedi: Fallen Order</h1>
        <img
            src="1007429.jpg.jpg"
            alt="Gambar Star Wars"
            width="700"
            height="400"
            style="border-radius: 10px;">
        <p style="color: white;">
            Star Wars Jedi: Fallen Order adalah permainan video
            aksi-petualangan pemain tunggal buatan Respawn Entertainment
            dan terbitan Electronic Arts.

            Ceritanya berlatar lima tahun setelah Revenge of the Sith,
            mengikuti Cal Kestis, seorang mantan Padawan yang diburu
            oleh Kekaisaran Galaksi saat ia berusaha membangkitkan
            kembali Ordo Jedi.</p>
        <p style="color: white;">Alur Cerita Utama:</p>
        <p style="color: white;">Cal Kestis menyembunyikan identitasnya sebagai mantan Jedi di planet pembuangan kapal Bracca.</p>
        <p style="color: white;">Kekuatannya terungkap secara tidak sengaja, lalu ia dikejar oleh pasukan Inkuisitor Kekaisaran.</p>
        <p style="color: white;">Ia bergabung dengan mantan Jedi bernama Cere Junda dan pilot Grzicc (Greez Dritus) di kapal Stinger Mantis.</p>
        <p style="color: white;">Misi mereka adalah mencari holocron peninggalan Eno Cordova yang berisi daftar anak-anak sensitif Force agar tidak jatuh ke tangan musuh.</p>
        <hr width="100%" color="#3B82F6" size="5">
        <h1 style="color: white;">2. EA Sports FC 26</h1>
        <img
            src="22537619.jpg"
            alt="Gambar EA Sports FC 26"
            width="700"
            height="400"
            style="border-radius: 10px;">
        <p style="color: white;">
            EA Sports FC 26 adalah game simulasi sepak bola yang
            dikembangkan dan diterbitkan oleh Electronic Arts.

            Game ini merupakan bagian dari seri EA Sports FC dan
            menjadi penerus EA Sports FC 25.

            FC 26 menghadirkan berbagai pembaruan pada gameplay,
            mode Career, Ultimate Team, serta pengalaman bermain
            sepak bola yang lebih realistis.</p>
        <p style="color: white;">
            Saya menyukai EA Sports FC 26 karena game ini memungkinkan
            saya memainkan pertandingan sepak bola dengan berbagai klub
            dan pemain favorit.

            Selain bermain pertandingan biasa, saya juga menikmati
            mode Career dan Rush karena memberikan pengalaman bermain
            yang berbeda.

            Game ini juga menarik bagi saya karena sepak bola merupakan
            salah satu olahraga yang saya sukai.</p>
    </div>
    <div
        class="konten fade-section"
        style="
            display: flex;
            align-items: center;
            background-color: #c9d6f0;
            border-radius: 10px;
            margin: 20px auto;
            padding: 15px;
            gap: 20px;
            width: 750px;">
        <div>
            <h2 id="deskripsi"style="color: rgb(17, 10, 102);">Deskripsi:</h2>
            <h3 style="font-family: 'Times New Roman', Times, serif; text-align: left;">Ini adalah website yang dibuat oleh (Husen Alamrie) sebagai tugas pembelajaran HTML dan CSS. Jadi, kalo jelek atau ada yang kurang, mohon maaf. 😹🥀</h3>
            <h2 style="color: rgb(6, 3, 61);">Hubungi Saya:</h2>
            <h3>0812-4588-4610</h3>
            <a href="https://www.instagram.com/husenalamrie"style="color: rgb(15, 12, 75); text-align: right; text-decoration: underline;">&rarr; Instagram saya</a>
           <hr width="100%" color="#3B82F6" size="5">
           <h1>Saran Dan Masukkan Dari Kalian:</h1>
            <textarea placeholder="Saran/Masukkan:" cols="90" rows="5"></textarea>
        </div>

    </div>
    <a href="#" class="top-btn">⬆</a>
    <script>
        const sections =
            document.querySelectorAll('.fade-section');
        const observer =
            new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('show');
                    }
                });
            }, {
                threshold: 0.15
            });
        sections.forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
</html>
>>
