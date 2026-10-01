# Mattthew
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Landing Page</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f9;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            background-color: #202035;
            color: white;
            padding: 15px 25px;
        }

        .menu {
            display: flex;
            gap: 20px;
        }

        .menu a {
            color: white;
            text-decoration: none;
        }

        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            background-color: #fde3d3;
            padding: 40px;
        }

        .hero button {
            background-color: #ef6c2f;
            color: white;
            border: none;
            padding: 10px 30px;
            border-radius: 20px;
        }

        .content {
            padding: 25px;
        }

        .cards {
            display: flex;
            gap: 15px;
        }

        .card {
            flex: 1;
            border: 1px solid #ddd;
            padding: 10px;
        }

        .card-image {
            height: 70px;
        }

        .orange {
            background-color: #ef6c2f;
        }

        .navy {
            background-color: #202035;
        }

        .maroon {
            background-color: #7a294b;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            background-color: #202035;
            color: white;
            padding: 15px 25px;
        }
    </style>
</head>

<body>

    <!-- NAVBAR -->
    <nav class="navbar">
        <b>LogoKu</b>

        <div class="menu">
            <a href="#">Beranda</a>
            <a href="#">Produk</a>
            <a href="#">Kontak</a>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero">
        <h1>Selamat Datang di Situs Kami</h1>
        <p>Bangun website impian dengan HTML & CSS</p>
        <button>Mulai</button>
    </section>

    <!-- CONTENT -->
    <section class="content">
        <h2>Layanan Kami</h2>

        <div class="cards">

            <div class="card">
                <div class="card-image orange"></div>
                <h3>Layanan 1</h3>
                <p>Deskripsi singkat</p>
            </div>

            <div class="card">
                <div class="card-image navy"></div>
                <h3>Layanan 2</h3>
                <p>Deskripsi singkat</p>
            </div>

            <div class="card">
                <div class="card-image maroon"></div>
                <h3>Layanan 3</h3>
                <p>Deskripsi singkat</p>
            </div>

        </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
        <span>© 2026 Situs Kami</span>
        <span>Instagram | Twitter | Email</span>
    </footer>

</body>
</html>
