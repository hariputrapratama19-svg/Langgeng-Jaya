# Langgeng-Jaya
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Saya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Hari Putra Pratama</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">Tentang</a>
            <a href="#contact">Kontak</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Selamat Datang di Website Saya</h2>
        <p>Website sederhana menggunakan HTML & CSS.</p>
        <button onclick="scrollToAbout()">Pelajari Lebih Lanjut</button>
    </section>

    <section id="about" class="about">
        <h2>Tentang Saya</h2>
        <p>Saya sedang belajar membuat website dari nol dan ingin menjadi web developer.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Kontak</h2>
        <p>Email: hariputrapratama19@gmail.com</p>
        <p>WhatsApp: 081977447037</p>
    </section>

    <footer>
        <p>© 2026 Hari Putra Pratama. All Rights Reserved.</p>
    </footer>

    <script>
        function scrollToAbout() {
            document.getElementById("about").scrollIntoView({ behavior: "smooth" });
        }
    </script>

</body>
</html>
