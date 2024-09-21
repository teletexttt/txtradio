<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teletext Radio Online</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('ff.png'); /* Cambia por el nombre de la imagen que subiste */
            background-size: cover;
            background-position: center;
            font-family: 'Courier New', Courier, monospace;
        }
        .content {
            text-align: center;
            color: white;
            padding-top: 20%;
        }
        .player {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Bienvenido a Teletext Radio Online</h1>
        <div class="player">
            <!-- Cambia la URL para que apunte al servidor de streaming (Icecast o Shoutcast) -->
            <audio controls>
                <source src="http://tu-dominio.com:8000/stream" type="audio/mpeg">
                Tu navegador no soporta el reproductor de audio.
            </audio>
        </div>
    </div>
</body>
</html>
