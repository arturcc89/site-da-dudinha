<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Poemas para Bonny</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=UnifrakturCook&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'UnifrakturCook', cursive;
      background: url('fundo.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    .menu {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: rgba(10, 10, 10, 0.9);
      padding: 15px;
      text-align: center;
      z-index: 1000;
    }

    .menu a {
      color: crimson;
      margin: 0 20px;
      text-decoration: none;
      font-size: 18px;
    }

    .poema {
      background-color: rgba(0, 0, 0, 0.7);
      margin: 100px auto 60px;
      padding: 30px;
      border-radius: 10px;
      width: 80%;
      font-size: 20px;
      line-height: 1.6;
      box-shadow: 0 0 10px black;
    }

    hr {
      border: none;
      border-top: 2px dashed crimson;
      margin: 60px 0;
    }

    footer {
      text-align: center;
      font-style: italic;
      color: gray;
      margin: 60px 20px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <div class="menu">
    <a href="#poema1">Poema 1</a>
    <a href="#poema2">Poema 2</a>
    <a href="#poema3">Poema 3</a>
  </div>

  <div id="poema1" class="poema">
    <h2>Poema 1</h2>
    <p>Teus olhos, Bonny, são noites sem fim<br>
    onde estrelas nascem só pra me guiar.<br>
    Cada riso teu é tempestade mansa,<br>
    e eu me deixo naufragar.</p>
  </div>

  <hr>

  <div id="poema2" class="poema">
    <h2>Poema 2</h2>
    <p>Entre ruínas e rosas negras<br>
    tua presença acende o mundo.<br>
    Um caos doce, alma selvagem,<br>
    onde até o silêncio é profundo.</p>
  </div>

  <hr>

  <div id="poema3" class="poema">
    <h2>Poema 3</h2>
    <p>Se eu pudesse moldar o tempo,<br>
    guardava teus gestos num relicário.<br>
    Pois cada instante contigo, Bonny,<br>
    é eternidade num altar diário.</p>
  </div>

  <footer>
    Eu sei que você acha bonito... e isso é tudo que eu queria te dar.<br>
    Porque eu sempre vou lembrar do que você me deu e das nossas aventuras.
  </footer>

</body>
</html>
