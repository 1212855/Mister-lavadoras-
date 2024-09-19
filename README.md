# Mister-lavadoras-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MisterLavadoras - Tu servicio de lavandería</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo MisterLavadoras">
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h1>Bienvenido a MisterLavadoras</h1>
        <p>Tu servicio confiable y rápido de lavandería.</p>
    </section>

    <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <ul>
            <li>Lavado y secado</li>
            <li>Lavado en seco</li>
            <li>Planchado de ropa</li>
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 MisterLavadoras. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header .logo img {
    max-width: 150px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    text-align: center;
}

h1, h2 {
    margin-bottom: 10px;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin: 5px 0;
}

form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 0 auto;
}

form input, form textarea, form button {
    margin: 10px 0;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
<img src="logo.png" alt="Logo MisterLavadoras">

