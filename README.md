<!DOCTYPE html>
<html lang="pt-BR">
<head>
 <meta charset="UTF-8">
  <link rel="stylesheet" href="styles.css">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>MARIO</title>
</head>
<body>
   <div class="game">
    <img class="mario" src="img/mario.gif" alt="mario">
    <img class="pipe" src="img/pipe.png" alt="cano">
    <img class="clouds" src="img/clouds.png" alt="nuvem">
    <button class="start" onclick="startGame()">Iniciar</button>
   </div>

    <div class="game-over"><h1>Game Over :(</h1><button onclick="restartGame()">Reiniciar</button></div>
    <div class="pontuacao">pontuação:</div>
</body>
<script src="script.js"></script>
</html>
