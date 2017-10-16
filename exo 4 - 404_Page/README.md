# 404_Page

## Mon code

+ HTML

  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" type="text/css" href="main.css">
    <title>Error 404</title>
  </head>
  <body>
    <div class="space"></div>
    <div class="cadre">
      <img src="https://raw.githubusercontent.com/Ezaaii/404_Page/master/404.png"/>
        <div class="error">
          <h1>Oopsie doopsie!</h1>
          <span>On dirait que la page que vous demandez n'existe pas.</span>
          <a class="button" href="https://github.com/Ezaaii">Retour </a>
        </div>
    </div>
  </body>
  </html>
  ```

+ CSS

  ```
  body {
    background-size: cover;
    background-image: url(https://pre00.deviantart.net/d31a/th/pre/f/2016/154/e/e/ee7b3477cd693629672dd3bdb0fb1b93-d9j7xyq.jpg);
    background-color: #3DB5BF;
    margin: 0;
    padding: 0;
  }
  .space {
    height: 75px;
  }
  .cadre {
    display: block;
    margin: 0 auto;
    width: 1300px;
    height: 750px;
    background-color: rgba(246,162,229,75%);
    border-radius: 20px;
    box-shadow: 8px 8px 8px #308794;
  }
  .cadre img {
    position: absolute;
    float:left;
    padding-left: 80px;
    padding-top: 100px;
    width:650px;

  }
  .cadre .error {
    float: right;
    padding-top: 150px;
    padding-right: 120px;
    display: block;
    width: 45%;
    margin: 0 auto;
    text-align: center;
    font-family: arial;
  }
  .cadre .error h1 {
    text-transform: uppercase;
    font-size: 64px;
  }
  .cadre .error span {
    font-style: italic;
    font-size: 25px;
  }
  .cadre .error .button {
    display: block;
    margin: 0 auto;
    margin-top: 50px;
    height: 75px;
    width: 200px;
    background-color: #DB4A7E;
    font-size: 40px;
    text-align: center;
    cursor: pointer;
    outline: none;
    border: none;
    border-radius: 15px;
    box-shadow: 5px 5px 0px #B53D68;
    text-decoration: none;
    color: #fff;
    padding-top: 25px;
  }
  .cadre .error .button:hover {
    background-color: #DB3673;
  }
  .cadre .error .button:active {
    background-color: #DB3673;
    box-shadow: 1px 1px 0px #B53D68;
    transform: translateY(4px) translateX(4px);
  }
  ```

## Problèmes rencontrés

+ Petit souci pour placer l'image au bon endroit, j'ai du jouer avec les margin left au lieu de centrer pour un résultat plus beau graphiquement.
