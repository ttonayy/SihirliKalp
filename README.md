# SihirliKalp
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sevgililer Günü Hediye Kutusu</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="header-content">
                <h1>Ronya & Tonay</h1>
                <div class="heart">❤️</div>
            </div>
        </header>

        <main>
            <h2>Sevgililer Günü Sorusu</h2>
            <p>İstanbul'da Resmî kayıtlarda fazla geçmese de, özellikle Rum ve Ermeni topluluklarının kendi bağlarından elde ettikleri üzümlerle küçük çaplı ama kaliteli şaraplar ürettiği ve 'Makriköy' olarak da bilinen II. Abdülhamid döneminde önemli siyasi entrikalara ev sahipliği yapan ilçemiz nedir?</p>

            <input type="text" id="answer" placeholder="Cevabınızı buraya yazın">
            <button onclick="checkAnswer()">Cevabı Kontrol Et</button>
            <div id="result"></div>

            <p class="hint">İpucu: Kutunun içine işine yarayacak bir bilgi bırakmış olabilirim.</p>
        </main>
    </div>

    <script src="script.js"></script>
</body>
</html>
