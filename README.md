<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Palmitas Web.com</title>
    <link rel="stylesheet" href="SD.css">
</head>
<body>
    <!-- Encabezado principal -->
    <header>
        <h1>Palmitas site web</h1>
    </header>

    <!-- Menú superior -->
    <nav class="menu-superior">
        <ul>
            <li><a href="producto.html">Inicio</a></li>
            <li><a href="#video">Video</a></li>
            <li><a href="Productos.html">Productos</a></li>
            <li><a href="Contactos (1).html">Contacto</a></li>
        </ul>
    </nav>

    <!-- Menú lateral -->
    <aside class="menu-lateral">
        <ul>
            <li><a href="#valores">Valores</a></li>
            <li><a href="#respeto">Respeto</a></li>
            <li><a href="#igualdad">Igualdad</a></li>
            <li><a href="#honestidad">Honestidad</a></li>
        </ul>
    </aside>

    <!-- Contenido principal -->
    <main class="contenido">
        <h2>Bienvenido a Nuestra Página🌴🍸🌴🥥🏝️</h2>
        <img src="Logo.jpg" alt="Un toque de coco, un mundo de sabor y olor" width="150" height="150" />
        <p>Un toque de coco, un mundo de sabor</p>

        <!-- Video -->
        <div class="video-container">
            <video id="miVideo" width="140" height="140" controls>
                <source src="video.mp4" type="video/mp4" />
            </video>
            <div class="menu-video">
                <button onclick="document.getElementById('miVideo').play()">Reproducir</button>
                <button onclick="document.getElementById('miVideo').pause()">Pausar</button>
                <button onclick="document.getElementById('miVideo').currentTime = 0">Volver al Inicio</button>
            </div>
        </div>
    </main>

    <!-- Menú de pie de página -->
    <footer class="menu-footer">
        <ul>
            <li><a href="#privacidad">Política de Privacidad</a></li>
            <li><a href="#terminos">Términos y Condiciones</a></li>
            <li><a href="#ayuda">Ayuda</a></li>
        </ul>
    </footer>
</body>
</html>
