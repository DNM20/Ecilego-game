# Ecilego-game
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juego de Producción ECILEGO</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Juego de Producción ECILEGO</h1>
    <div id="game-container">
        <div class="station" id="station1">
            <h2>Estación 1</h2>
            <button onclick="processStation(1)">Insertar Brick en Vaso</button>
        </div>
        <div class="station" id="station2">
            <h2>Estación 2</h2>
            <button onclick="processStation(2)">Ensamblar Segundo Brick</button>
        </div>
        <div class="station" id="station3">
            <h2>Estación 3</h2>
            <button onclick="processStation(3)">Agregar Tercer Brick y Colocar Tapa</button>
        </div>
        <div class="station" id="station4">
            <h2>Estación 4</h2>
            <button onclick="processStation(4)">Control de Calidad y Etiquetar</button>
        </div>
    </div>
    <div id="results">
        <h2>Resultados</h2>
        <ul id="result-list"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
