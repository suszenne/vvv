# vvv<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Where is Toto?</title>

  <style>
    html,
    body,
    #game-container {
      margin: 0;
      padding: 0;
    }
    #game-container {
      min-width: 100vw;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    #game-container>canvas {
      border-radius: 5px;
    }
  </style>
</head>

<body>
  <div id="game-container"></div>

  <script src="//cdn.jsdelivr.net/gh/photonstorm/phaser@3.12.0-beta2/dist/phaser.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/phaser-matter-collision-plugin"></script>
  <script src="./js/index.js" type="module"></script>
  <script src="https://github.com/liabru/matter-js/releases/download/0.10.0/matter.js"></script>
</body>

</html>
