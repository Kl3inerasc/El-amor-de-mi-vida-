# El-amor-de-mi-vida-
Carta para el amor de mi vida 

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para el amor de mi vida</title>
    <style>
        /* General */
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #f8e4d9, #f4d2c1);
            color: #4a4a4a;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            min-height: 100vh;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        /* Header */
        header h1 {
            font-size: 3.5em;
            font-style: italic;
            color: #b56576;
            margin-top: 30px;
            animation: fadeInDown 2s ease-out;
        }

        /* Heart Container */
        .heart-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 20px 0;
            animation: scaleUp 2s ease-in-out;
        }

        .heart {
            width: 200px;
            height: 200px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="%23bde0fe"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>') no-repeat center;
            background-size: contain;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #4a4a4a;
            font-size: 2em;
            font-weight: bold;
            border-radius: 50%;
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .heart:hover {
            transform: scale(1.1);
        }

        /* Message */
        .message {
            background-color: rgba(255, 255, 255, 0.9);
            border: 2px solid #e8c4a5;
            border-radius: 15px;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            font-size: 1.2em;
            line-height: 1.6;
            animation: fadeIn 2.5s ease-in-out;
        }

        /* Footer */
        footer p {
            font-size: 1.5em;
            font-style: italic;
            color: #b56576;
            margin-bottom: 20px;
            animation: fadeInUp 2s ease-out;
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInDown {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes scaleUp {
            from {
                transform: scale(0.8);
                opacity: 0.5;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Para el amor de mi vida</h1>
    </header>
    <main>
        <div class="heart-container">
            <div class="heart">K y V</div>
        </div>
        <div class="message">
            Eres la mujer que se ganó mi amor y cariño, la única en el mundo que me ha hecho sentir lo que es el amor verdadero y las ganas de querer tanto a alguien sin poder decir el porqué.  
            Sentirme enamorado de ti es lo mejor que me ha pasado en la vida y sí, "en la vida", porque aunque no estemos juntos me has demostrado que en verdad todavía existe el amor y que puedo confiar totalmente en ti, mi princesa.
        </div>
    </main>
    <footer>
        <p>Siempre estarás en mi corazón, con amor eterno.</p>
    </footer>
    <script>
        // Script para una interacción adicional
        document.addEventListener("DOMContentLoaded", () => {
            const heart = document.querySelector(".heart");
            heart.addEventListener("click", () => {
                alert("¡Este corazón es solo para ti!");
            });
        });
    </script>
</body>
</html>
