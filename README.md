<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa Vacanza a Santo Stefano di Magra</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Casa Vacanza a Santo Stefano di Magra</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">Chi Siamo</a></li>
                <li><a href="#gallery">Galleria</a></li>
                <li><a href="#contact">Contatti</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Benvenuti!</h2>
        <p>Scopri il nostro incantevole appartamento situato a Santo Stefano di Magra, perfetto per le tue vacanze!</p>
        <img src="home.jpg" alt="Casa Vacanza">
    </section>

    <section id="about">
        <h2>Chi Siamo</h2>
        <p>La nostra casa vacanza offre un'esperienza unica con tutti i comfort di cui hai bisogno. Situata in una posizione strategica, è l'ideale per esplorare la bellezza della Liguria e della Toscana.</p>
    </section>

    <section id="gallery">
        <h2>Galleria</h2>
        <div class="gallery">
            <img src="img1.jpg" alt="Immagine 1">
            <img src="img2.jpg" alt="Immagine 2">
            <img src="img3.jpg" alt="Immagine 3">
        </div>
    </section>

    <section id="contact">
        <h2>Contatti</h2>
        <p>Per maggiori informazioni e prenotazioni:</p>
        <ul>
            <li>Email: info@casavacanzasantostefano.it</li>
            <li>Telefono: +39 123 456 7890</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Casa Vacanza a Santo Stefano di Magra. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
Stili CSS
css
Copia codice
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    text-align: center;
}

section#home {
    background-color: #f4f4f4;
}

section#gallery .gallery {
    display: flex;
    justify-content: center;
    gap: 10px;
}

section#gallery .gallery img {
    width: 200px;
    height: 150px;
    object-fit: cover;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
