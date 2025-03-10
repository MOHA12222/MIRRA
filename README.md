# MIRRA
Spejl
<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mirra - Fremtidens Spejl</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background-color: #222;
            color: white;
            padding: 20px;
        }
        .hero {
            background: url('billede_af_spejl.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            font-weight: bold;
        }
        .produkter {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 40px;
            flex-wrap: wrap;
        }
        .produkt {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 250px;
        }
        .produkt img {
            width: 100%;
            border-radius: 10px;
        }
        .footer {
            background-color: #222;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mirra - Fremtidens Spejl</h1>
    </header>
    <div class="hero">Opdag den nyeste teknologi inden for spejle</div>
    <section class="produkter">
        <div class="produkt">
            <img src="spejl_2025.jpg" alt="Mirra AI-spejl 2025">
            <h2>Mirra AI-spejl</h2>
            <p>Udkommet i 2025 - Luksus smart-spejl med AI-assistent</p>
            <button>Køb nu</button>
        </div>
        <div class="produkt">
            <img src="spejl_2026.jpg" alt="Mirra AI-spejl 2026">
            <h2>Mirra Vision</h2>
            <p>Kommer i 2026 - Avanceret skønhedsanalyse og stemmestyring</p>
        </div>
        <div class="produkt">
            <img src="spejl_2027.jpg" alt="Mirra AI-spejl 2027">
            <h2>Mirra Ultra</h2>
            <p>Kommer i 2027 - Udvidet AI-integration og helseovervågning</p>
        </div>
    </section>
    <div class="footer">&copy; 2025 Mirra - Alle rettigheder forbeholdes</div>
</body>
</html>
