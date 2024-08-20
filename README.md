<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web pro ženy - Citáty, Fotky a Výletní Tipy</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #ccc;
            padding: 20px;
            text-align: center;
            font-size: 2em;
            color: #555;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }
        .container {
            padding: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .quote-section {
            font-style: italic;
            font-size: 1.5em;
            margin: 20px 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            max-width: 300px;
            border-radius: 10px;
        }
        .blog-section {
            margin: 20px 0;
        }
        .blog-post {
            margin-bottom: 20px;
        }
        footer {
            background-color: #ccc;
            padding: 10px;
            text-align: center;
            font-size: 0.8em;
            color: #555;
        }
    </style>
</head>
<body>

    <header>
        Vítejte na stránce pro ženy - Inspirace, Citáty a Cestování
    </header>

    <nav>
        <a href="#citaty">Citáty a Motta</a>
        <a href="#galerie">Galerie</a>
        <a href="#vylety">Výletní Tipy</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <div class="container">
        <section id="citaty" class="quote-section">
            <h2>Citáty a Motta</h2>
            <p>"Život je příliš krátký na to, aby se braly vážně malé věci."</p>
            <!-- Můžeš přidat více citátů -->
        </section>

        <section id="galerie" class="gallery">
            <h2>Galerie z Výletů</h2>
            <img src="vase_foto1.jpg" alt="Foto 1">
            <img src="vase_foto2.jpg" alt="Foto 2">
            <img src="vase_foto3.jpg" alt="Foto 3">
            <!-- Přidej další fotky -->
        </section>

        <section id="vylety" class="blog-section">
            <h2>Výletní Tipy</h2>
            <div class="blog-post">
                <h3>Titul výletu</h3>
                <p>Popis výletu, zajímavá místa, co navštívit, co nevynechat...</p>
            </div>
            <!-- Přidej další příspěvky -->
        </section>

        <section id="kontakt">
            <h2>O mně & Kontakt</h2>
            <p>Ahoj, jsem (tvoje jméno), milovnice cestování a sběratelka citátů...</p>
            <p>Email: tvojemail@example.com</p>
        </section>
    </div>

    <footer>
        &copy; 2024 Tvoje Stránka pro Ženy
    </footer>

</body>
</html>
