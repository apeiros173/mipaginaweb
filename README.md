<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Aleatoria</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        :root {
            --color-fondo: #ff0000;
            --color-principal: #3498db;
            --color-secundario: #ff0000;
            --fuente: 'Arial', sans-serif;
        }

        body {
            background-image: url('https://play-lh.googleusercontent.com/bkilPawVNMG14p6Zm0qjqfNbv3xb69CcvnTE-A0cSzTnxgvWjzd0X9i2YGrhpq5NRw=w900');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            margin: 0;
            padding: 0;
            font-family: var(--fuente);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .contenedor {
            text-align: center;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: rgba(255, 255, 255, 0.8);
            width: 80%;
            max-width: 600px;
        }

        h1 {
            color: var(--color-principal);
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        h2 {
            color: var(--color-secundario);
            font-size: 2rem;
            margin-top: 30px;
        }

        p {
            color: #333;
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        button {
            background-color: var(--color-secundario);
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #cc0000;
        }

        a {
            display: inline-block;
            margin-top: 15px;
            text-decoration: none;
            color: var(--color-principal);
            font-weight: bold;
            font-size: 1.2rem;
        }

        a i {
            margin-right: 8px;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="contenedor">
        <h1>Bienvenido a tu página aleatoria</h1>
        <p>Este es un ejemplo de código HTML con estilos CSS generados aleatoriamente.</p>
        <button onclick="window.location.href='https://www.youtube.com/@APEIROS173'">Mi canal de YouTube</button>
        
        <h2>Redes Sociales</h2>
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-facebook-square"></i> Facebook
        </a>
    </div>
</body>
</html>
