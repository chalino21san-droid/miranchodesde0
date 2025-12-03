<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Rancho Desde Cero</title>

    <style>
        /* Estilos globales */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        h1, h2 {
            font-family: 'Georgia', serif;
            color: #2C6E49;
        }

        a {
            text-decoration: none;
            color: #2C6E49;
        }

        /* Cabecera */
        header {
            background-image: url('https://via.placeholder.com/1600x500/7b9a65/ffffff?text=Mi+Rancho+Desde+Cero');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
            margin: 10px 0;
        }

        /* Navegación */
        nav {
            background-color: #2C6E49;
            padding: 10px;
            text-align: center;
        }

        nav a {
            margin: 0 20px;
            color: white;
            font-size: 1.1em;
        }

        /* Sección Principal */
        .section {
            padding: 40px 20px;
            text-align: center;
            background-color: #ffffff;
        }

        .section:nth-child(odd) {
            background-color: #f9f9f9;
        }

        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .section p {
            font-size: 1.1em;
            margin-bottom: 20px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Botón de suscripción */
        .subscribe {
            background-color: #7b9a65;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }

        .subscribe:hover {
            background-color: #6a8752;
        }

        /* Pie de página */
        footer {
            background-color: #2C6E49;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Responsividad */
        @media screen and (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            .section h2 {
                font-size: 2em;
            }

            .section p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <!-- Cabecera -->
    <header>
        <h1>Mi Rancho Desde Cero</h1>
        <p>Guía para construir tu propio rancho desde lo básico, paso a paso.</p>
         <img src="Verde naturaleza 💚.jfif" height="200" width="500">

    </header>

    <!-- Navegación -->
    <nav>
        <a href="#planificacion">Planificación</a>
        <a href="#construccion">Construcción</a>
        <a href="#animales">Animales</a>
        <a href="#cultivos">Cultivos</a>
        <a href="#finanzas">Finanzas</a>
    </nav>

    <!-- Sección Planificación -->
    <section id="planificacion" class="section">
        <h2>Planificación del Rancho</h2>
        <p>Definir tus objetivos es el primer paso: ¿Quieres criar animales, cultivar alimentos o ambas cosas? ¡Aquí te damos las claves!</p>
        <button class="subscribe">¡Suscríbete para más tips!</button>
    </section>

    <!-- Sección Construcción -->
    <section id="construccion" class="section">
        <h2>Construcción del Rancho</h2>
        <p>Te guiamos para construir las instalaciones básicas de tu rancho, como cercados, bodegas, y huertos, de manera económica.</p>
    </section>

    <!-- Sección Animales -->
    <section id="animales" class="section">
        <h2>Animales para tu Rancho</h2>
        <p>Desde gallinas hasta vacas, aprende cómo comenzar con animales adecuados para tu rancho, dependiendo del tamaño y tu presupuesto.</p>
    </section>

    <!-- Sección Cultivos -->
    <section id="cultivos" class="section">
        <h2>Cultivos para Principiantes</h2>
        <p>Si eres nuevo en el mundo agrícola, te mostramos los cultivos más sencillos y rentables para empezar tu rancho.</p>
    </section>

    <!-- Sección Finanzas -->
    <section id="finanzas" class="section">
        <h2>Finanzas y Crecimiento</h2>
        <p>Aprende cómo manejar los ingresos de tu rancho y cómo invertir para expandirlo poco a poco. ¡Te damos consejos prácticos!</p>
    </section>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2025 Mi Rancho Desde Cero. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
