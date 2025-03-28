<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kopi Juwara – Rasa Juara, Energi Maksimal!</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Kopi Juwara</h1>
        <p>Rasa Juara, Energi Maksimal!</p>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <img src="https://source.unsplash.com/600x400/?coffee" alt="Kopi Juwara">
        <div class="hero-text">
            <h2>Nikmati Kopi Premium dengan Diskon 20% Hari Ini!</h2>
            <p>Kopi sehat dengan ekstrak Ganoderma yang menjaga energi & kesehatan.</p>
            <a href="#form-pemesanan" class="btn">Pesan Sekarang</a>
            <a href="https://wa.me/6281234567890" class="btn wa-btn">Hubungi via WhatsApp</a>
        </div>
    </section>

    <!-- Manfaat Kopi -->
    <section class="benefits">
        <h2>Kenapa Pilih Kopi Juwara?</h2>
        <ul>
            <li>✅ Rasa Premium & Aroma Mewah</li>
            <li>✅ Mengandung Ekstrak Ganoderma</li>
            <li>✅ Tidak Menyebabkan Asam Lambung</li>
            <li>✅ Tingkatkan Fokus & Produktivitas</li>
        </ul>
    </section>

    <!-- Formulir Pemesanan -->
    <section id="form-pemesanan">
        <h2>Pesan Sekarang!</h2>
        <p>Diskon 20% hanya hari ini! Isi formulir di bawah ini:</p>
        <form action="https://formspree.io/f/yourformid" method="POST">
            <input type="text" name="nama" placeholder="Nama Anda" required>
            <input type="tel" name="telepon" placeholder="Nomor WhatsApp" required>
            <input type="text" name="alamat" placeholder="Alamat Pengiriman" required>
            <button type="submit" class="btn">Kirim Pesanan</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Kopi Juwara. Semua Hak Dilindungi.</p>
    </footer>

</body>
</html>body {
    font-family: Arial, sans-serif;
    background-color: #1a1a1a;
    color: #fff;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: #4d2600;
    padding: 20px;
}

h1 {
    color: #ffcc00;
    margin: 0;
}

.hero {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
}

.hero img {
    width: 80%;
    max-width: 400px;
    border-radius: 10px;
}

.hero-text {
    margin-top: 20px;
}

.btn {
    display: inline-block;
    background-color: #ffcc00;
    color: #4d2600;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    margin: 10px;
}

.wa-btn {
    background-color: #25d366;
    color: #fff;
}

.benefits {
    background-color: #4d2600;
    padding: 20px;
    margin-top: 20px;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin: 10px 0;
}

#form-pemesanan {
    padding: 20px;
}

input, button {
    display: block;
    width: 80%;
    max-width: 400px;
    margin: 10px auto;
    padding: 10px;
}

footer {
    background-color: #000;
    padding: 10px;
    margin-top: 20px;
}
