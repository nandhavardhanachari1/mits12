
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

    <title>Flappy Bird Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div id="game-container">
        <canvas id="gameCanvas"></canvas>
        <div id="game-over">
            <h1>Game Over</h1>
            <button onclick="restartGame()">Restart</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
