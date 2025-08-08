#BrooklynFlix
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BrooklynFlix</title>
    <style>
        body {
            background-color: #0d1b2a;
            color: #ffffff;
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1b263b;
            padding: 20px 0;
            font-size: 2em;
            font-weight: bold;
            color: #ffd60a;
        }

        h1 {
            margin-top: 30px;
            font-size: 1.8em;
        }

        p {
            font-size: 1.2em;
            color: #adb5bd;
        }

        .video-container {
            margin: 30px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        iframe {
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>BrooklynFlix</header>

    <h1>Uma seleção de vídeos sobre a série Brooklyn Nine-Nine!</h1>
    <p>#comédia #policial #Brooklyn99 #NineNine</p>

    <div class="video-container">
        <!-- Trailer oficial Brooklyn Nine-Nine Temporada 1 -->
        <iframe width="360" height="215" src="https://www.youtube.com/embed/sEOuJ4z5aTc" 
        title="Brooklyn Nine-Nine Temporada 1 Trailer Oficial" allowfullscreen></iframe>

        <!-- Trailer Brooklyn Nine-Nine Temporada Final -->
        <iframe width="360" height="215" src="https://www.youtube.com/embed/QUi9S9gJ5oE" 
        title="Brooklyn Nine-Nine Temporada Final Trailer" allowfullscreen></iframe>

        <!-- Melhores momentos Brooklyn Nine-Nine -->
        <iframe width="360" height="215" src="https://www.youtube.com/embed/HP2Q72lkuL0" 
        title="Brooklyn Nine-Nine: Melhores Momentos" allowfullscreen></iframe>
    </div>

</body>
</html>
