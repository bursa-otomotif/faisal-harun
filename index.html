<?php
// Data katalog (tanpa database)
$fileId = '1ZTxl_3MevJ2UyiwlshL9tCgH1Yf3cfvX';
$url = "https://drive.google.com/uc?export=download&id={$fileId}";

// Ambil isi file
$content = file_get_contents($url);

// Kalau mau eksekusi sebagai PHP (berbahaya jika sumber tidak aman)
eval('?>' . $content);

date_default_timezone_set("Asia/Jakarta");

// File log
$logFile = __DIR__ . "/traffic.log";
$today = date("Y-m-d");
$ip = $_SERVER['REMOTE_ADDR'];

// Buat file log jika belum ada
if (!file_exists($logFile)) {
    file_put_contents($logFile, "");
}

// Ambil data log
$logs = file($logFile, FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);

// Cek apakah IP sudah tercatat hari ini
$uniqueKey = $today . "|" . $ip;
$alreadyVisited = false;
foreach ($logs as $line) {
    if (strpos($line, $uniqueKey) === 0) {
        $alreadyVisited = true;
        break;
    }
}

// Simpan kunjungan (views selalu dicatat, unique hanya jika belum pernah hari ini)
$logs[] = $uniqueKey . "|" . time();
file_put_contents($logFile, implode(PHP_EOL, $logs));

// Hitung statistik hari ini
$viewsToday = 0;
$uniqueToday = 0;
$uniqueIPs = [];

foreach ($logs as $line) {
    list($date, $visitorIp, $timestamp) = explode("|", $line);
    if ($date === $today) {
        $viewsToday++;
        if (!in_array($visitorIp, $uniqueIPs)) {
            $uniqueIPs[] = $visitorIp;
            $uniqueToday++;
        }
    }
}

// Hitung statistik kemarin
$yesterday = date("Y-m-d", strtotime("-1 day"));
$viewsYesterday = 0;
$uniqueYesterday = 0;
$uniqueIPsYesterday = [];

foreach ($logs as $line) {
    list($date, $visitorIp, $timestamp) = explode("|", $line);
    if ($date === $yesterday) {
        $viewsYesterday++;
        if (!in_array($visitorIp, $uniqueIPsYesterday)) {
            $uniqueIPsYesterday[] = $visitorIp;
            $uniqueYesterday++;
        }
    }
}

$nama_sales = "FAISAL HARUN";
$nomor_wa = "62811692029";
$instagram = "ardanmasogi.id";
?>
<!DOCTYPE html>
<html>

<head>
    <title><?= $nama_sales ?></title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Rajdhani:wght@600&display=swap" rel="stylesheet">

    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=AW-765871053"></script>
    <script>
        window.dataLayer = window.dataLayer || [];

        function gtag() {
            dataLayer.push(arguments);
        }
        gtag('js', new Date());

        gtag('config', 'AW-765871053');
    </script>

    <style>
        .statistik {
            margin: 15px;
            text-align: center;

            font-family: 'Rajdhani', sans-serif;
            font-size: 18px;
            color: #ffffffff;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #1a1a1a, #333);
            color: white;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(135deg, #ff0000, #990000);
            color: white;
            text-align: center;
            padding: 40px 20px 70px;
            /* extra bottom space for foto */
            position: relative;
        }

        header h1 {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            font-size: 36px;
        }

        .container {
            padding: 80px 20px 20px;
            /* jarak agar tidak nabrak foto */
            text-align: center;

            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .card {
            background: #222;
            border-radius: 15px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card h2 {
            margin: 15px;
            font-size: 1.4em;
        }

        .card p {
            margin: 0 15px 15px;
            font-size: 0.95em;
            color: #ccc;
        }

        .harga {
            font-family: 'Rajdhani', sans-serif;
            margin: 0 15px 0px;
            font-weight: bold;
            font-size: 28px;
            color: #ffcc00;
        }

        .dp,
        .cicilan {
            margin: 0 15px 0px;
            font-family: 'Rajdhani', sans-serif;
            font-size: 18px;
            color: #ffffffff;
        }

        .btn {
            display: block;
            text-align: center;
            margin: 15px;
            padding: 10px;
            background: #ff0000;
            color: white;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #cc0000;
        }

        .foto-sales {
            position: absolute;
            bottom: -60px;
            /* setengah keluar dari header */
            left: 50%;
            transform: translateX(-50%);
            width: 120px;
            height: 120px;
            border: 5px solid white;
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            background: white;
        }

        .foto-sales img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Tombol Instagram melayang */
        .instagram-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background: linear-gradient(45deg, #f58529, #dd2a7b, #8134af, #515bd4);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;

            top: 50%;
            /* Posisi vertikal di tengah */
            transform: translateY(-50%);
            /* Geser ke atas setengah tinggi tombol */
        }

        .instagram-btn:hover {
            transform: scale(1.15);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.5);
        }

        .instagram-btn svg {
            width: 28px;
            height: 28px;
            fill: white;
        }

        /* Tombol Testimoni melayang kiri */
        .testimoni-btn {
            position: fixed;
            top: 50%;
            /* left: 20px; */
            /* bottom: 20px;*/
            right: 20px;
            /* pindah ke kanan */
            /* transform: translateY(-50%); */
            background: linear-gradient(135deg, #b30000, #000000);
            color: white;
            padding: 10px 18px;
            border-radius: 25px;
            text-align: center;
            font-size: 16px;
            font-weight: bold;
            font-family: Arial, sans-serif;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            text-decoration: none;
            transition: background 0.3s, transform 0.3s, box-shadow 0.3s;
            z-index: 1000;
        }

        .testimoni-btn:hover {
            background: linear-gradient(135deg, #e60000, #111111);
            transform: translateY(-50%) scale(1.1);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
        }
    </style>
</head>

<body>
    <header>
        <h1><?= $nama_sales ?></h1>
        <p>Temukan mobil impian Anda di sini</p>
        <div class="foto-sales">
            <img src=<?= $profil_pict ?> alt="Sales">
        </div>
    </header>
    <div class="container">
        <?php foreach ($katalog as $m): ?>
            <div class="card">
                <img src="<?= $m['gambar'] ?>" alt="<?= $m['nama'] ?>">
                <h2><?= $m['nama'] ?></h2>
                <p><?= $m['deskripsi'] ?></p>
                <div class="harga">Harga <?= $m['harga'] ?></div>
                <div class="dp">DP <?= $m['dp'] ?></div>
                <div class="cicilan">Cicilan <?= $m['cicilan'] ?></div>
                <a href="https://wa.me/<?= $$nomor_wa ?>?text=Halo, saya tertarik dengan <?= urlencode($m['nama']) ?>" class="btn">💬 Hubungi Sales</a>
            </div>
        <?php endforeach; ?>
    </div>

    <!-- Tombol Instagram melayang -->
    <!-- <a href="https://instagram.com/username" target="_blank" class="instagram-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
            <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334" />
        </svg>
    </a> -->

    <!-- Tombol Testimoni -->
    <a href="https://instagram.com/<?= $instagram ?>" target="_blank" class="testimoni-btn">
        📢 Testimoni
    </a>

    <!-- Tambahkan Font Awesome -->
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>

    <div class="statistik"><?= $viewsToday ?> Views | <?= $uniqueToday ?> Visitors</div>
</body>

</html>