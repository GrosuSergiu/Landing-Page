# Landing-Page

<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magazin Miere Naturală</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <a href="#home">Acasă</a>
            <a href="#produse">Produse</a>
            <a href="#contact">Contacte</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Miere de Albine</h1>
        <p>Bucură-te de gustul naturii cu mierea noastră 100% Sănătoasă! Naturală!</p>
        <a href="#produse" class="btn">Vezi Produsele</a>
    </section>

    <section id="produse" class="produse">
        <h2>Produsele Noastre</h2>
        <div class="card poliflora">
            <img src="https://www.mierepenet.ro/poze-produse/17/mari/miere-poliflora.jpg" alt="Miere Polifloră">
            <h3>Miere Polifloră</h3>
            <p>Preț: 60 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
        <div class="card">
            <img src="https://www.mierepenet.ro/poze-produse/1/mici/miere-salcam.webp" alt="Miere de Salcâm">
            <h3>Miere de Salcâm</h3>
            <p>Preț: 100 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
        <div class="card">
            <img src="https://tse3.mm.bing.net/th?id=OIP.TUQCrpPsOPbCIDP-Dj5mLQHaFj&pid=Api&P=0&h=180" alt="Miere cu Propolis">
            <h3>Miere cu Propolis</h3>
            <p>Preț: 80 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
        <div class="card">
            <img src="https://www.mierepenet.ro/poze-produse/2/mici/miere-floarea-soarelui.jpg" alt="Miere de Floarea-Soarelui">
            <h3>Miere de Floarea-Soarelui</h3>
            <p>Preț: 70 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
        <div class="card">
            <img src="https://www.mierepenet.ro/poze-produse/3/mici/miere-de-rapita.jpg" alt="Miere de Rapiță">
            <h3>Miere de Rapiță</h3>
            <p>Preț: 65 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
        <div class="card">
            <img src="https://tse2.mm.bing.net/th?id=OIP.Z8OodvxG3Bfo5YBvYRk1kAHaF8&pid=Api&P=0&h=180" alt="Miere de Tei">
            <h3>Miere de Tei</h3>
            <p>Preț: 90 lei/kg</p>
            <a href="#contact" class="btn-buy">Cumpără</a>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contactează-ne</h2>
        <p><strong>Telefon:</strong> 068882119</p>
        <p><strong>Email:</strong> <a href="mailto:grosusergiu56@gmail.com">grosusergiu56@gmail.com</a></p>
        <p><strong>Adresă:</strong> str. Bucuriei 10, mun. Chișinău</p>
        <p><strong>Producător:</strong> Dragos Grosu</p>
    </section>
</body>
</html>








<style.css>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

.navbar {
    background-color: lightyellow;
    padding: 1em;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar a {
    margin: 0 15px;
    text-decoration: none;
    color: black;
    font-weight: bold;
    transition: color 0.5s;
}

.navbar a:hover {
    color: darkorange;
}

.hero {
    background-color: lightgoldenrodyellow;
    text-align: center;
    padding: 50px 20px;
}

.hero h1 {
    font-size: 2.5em;
    color: black;
    overflow: hidden;
    white-space: nowrap;
    border-right: 3px solid black;
    animation: typing 3s steps(30) 1s forwards;
}

.hero p {
    font-size: 1.2em;
    padding: 0 20px;
    color: black;
}

.hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background-color: gold;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s, transform 0.3s, box-shadow 0.3s;
    animation: colorChange 4s infinite;
}

.hero .btn:hover {
    background-color: goldenrod;
    transform: translateY(-5px);
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
}

@keyframes colorChange {
    0% { background-color: gold; }
    25% { background-color: yellow; }
    50% { background-color: blue; }
    75% { background-color: green; }
    100% { background-color: gold; }
}

.produse {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
    text-align: center;
}

.produse h2 {
    width: 100%;
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
    color: black;
}

.card {
    width: 280px;
    height: auto;
    margin: 20px;
    background-color: wheat;
    border-radius: 0;
    transition: transform 0.3s ease-in-out;
    text-align: center;
}

.card img {
    display: block;
    margin: 0 auto 15px;
    width: 100%;
    height: 200px;
    object-fit: contain;
    object-position: center;
    background-color: white;
    transition: transform 0.3s ease-in-out;
}

.card:hover {
    transform: translateY(-5px);
}

.card img:hover {
    transform: scale(1.05);
}

.card h3 {
    color: black;
    font-size: 1.2em;
    margin: 10px 0;
}

.card p {
    color: dimgray;
    font-size: 1em;
    margin: 5px 0;
}

.card .price {
    font-weight: bold;
    color: darkgreen;
    font-size: 1.1em;
    margin-top: 10px;
}

.card .btn-buy {
    display: inline-block;
    margin-top: 15px;
    padding: 8px 15px;
    background-color: gold;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.card .btn-buy:hover {
    background-color: goldenrod;
}

.contact {
    background-color: moccasin;
    padding: 20px;
    text-align: center;
}

.contact h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.contact p {
    font-size: 1.1em;
    color: black;
    margin: 5px 0;
}

.contact a {
    color: darkorange;
    text-decoration: none;
    font-weight: bold;
}

.contact a:hover {
    text-decoration: underline;
}

@media (max-width: 777px) {
    .card {
        width: 100%;
        margin-bottom: 15px;
    }

    .produse {
        display: block;
        padding: 10px;
    }

    .hero h1 {
        font-size: 2em;
    }

    .hero p {
        font-size: 1em;
        padding: 0 10px;
    }

    .hero .btn {
        font-size: 1em;
        padding: 10px 20px;
    }

    .navbar {
        padding: 0.8em;
    }

    .navbar a {
        font-size: 1em;
        margin: 0 10px;
    }

    .contact p {
        font-size: 1em;
        padding: 0 10px;
    }
}

@keyframes typing {
    0% {
        width: 0;
    }
    100% {
        width: 100%;
    }
}
