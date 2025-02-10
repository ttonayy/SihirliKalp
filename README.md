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
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f8f1f1;
    color: #3e3e3e;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    border: 2px solid #d1a1b7;
    width: 60%;
    text-align: center;
}

header .header-content {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2rem;
    font-weight: bold;
    color: #8b4e55;
}

header .heart {
    font-size: 2.5rem;
    margin-left: 10px;
}

h2 {
    color: #8b4e55;
    margin: 20px 0;
}

input {
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #8b4e55;
    width: 70%;
    margin-bottom: 20px;
}

button {
    background-color: #8b4e55;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #b76a73;
}

#result {
    margin-top: 20px;
    font-size: 1.2rem;
    color: #4caf50;
}

.hint {
    font-size: 1rem;
    color: #d16c77;
    font-style: italic;
    margin-top: 20px;
}
