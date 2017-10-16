# Exercice_OP_Caritative

## Mon Code

+ HTML

  ```
  <DOCTYPE html>
  <html>
    <head>
      <title> WWF </title>
      <meta charset="utf-8"/>
      <link rel="stylesheet" type="text/css" href="main.css">
    </head>
    <body>
      <div class="main">
        <div class="logo">
          <img src="https://vignette.wikia.nocookie.net/logopedia/images/0/0d/2000px-WWF_logo.svg.png/revision/latest?cb=20120906084534" class="logo"/>
        </div>
        <header>
          <div class="right">
            <h1>J'aime les pandas</h1>
            <p>
              Sauvez les pandas, plantez un bamboo.
            </p>
          </div>
        </header>
      </div>
      <div class="quote">
        <span>
          <span class="surtext">
            "Les pandas sont tout doux! J'aime les pandas!"
          </span>
          <br>
          <span class="soustext">
            Ceci était un message de l'association de protection des pandas qui aimeraient<br> que les gens aiment plus les pandas mais qui aimeraient aussi que les pandas<br> soient moins câlins parce qu'il faut pas déconner y a des gens qui essaient de bosser ici.
          </span>
          <br>  <br>  <br>  <br>  <br>
          <span class="surtext">
            <a href="https://thatsthespir.it/of/ayn-rand" target="blank">"The question isn't who is going to let me; it's who is going to stop me."</a>
          </span>
          <br>
          <span class="soustext">
            <a href="https://thatsthespir.it/of/ayn-rand" target="blank">Ayn Rand</a>
          </span>
        </span>
      </div>
      <div class="jaguar">
      </div>
      <div class="text">
        <div class="colone">
          <div>
            <h2>
              Titre 1
            </h2>
            Lorem ipsum dolor sit amet, <span>consectetur</span> adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </div>
          <div>
            <h2>
              Titre 2
            </h2>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor <span>incididunt</span> ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </div>
          <div>
            <h2>
              Titre 3
            </h2>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea <span>commodo</span> consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </div>
      </div>
    </div>
    <div class="photos">
      <h2>D'autres associations</h2>
      <img src="https://rangerclub.be/themes/wwf-be/dist/images/vector/logo.svg">
      <img src="https://wwf.be/assets/Uploads/_resampled/ResizedImageWzE0MCwxNDBd-logo-vef-new2.png">
      <img src="https://pbs.twimg.com/profile_images/779289835848818688/yifTHAJE.jpg">
    </div>
    </body>
  </html>
  ```

+ CSS

  ```
  html,body {
    margin: 0;
    padding: 0;
    font-family: Arial;
  }
  div {

  }
  .main {
    display: flex;
  }
  header {
    display: block;
    float: left;
    background-image: url(/home/user/becode/Exercice_OP_Caritative/panda.jpg);
    background-size: cover;
    background-position: center;
    height: 720px;
    width: 100%;
    background-color: black;
    margin-left: 0px
  }
  .logo {
    float: left;
    padding-left: 15px;
    padding-top: 15px;
    position: absolute;
    height: 150px;
  }
  .right {
    float: right;
    position: relative;
    background-color: rgba(0,0,0,.75);
    width: 400px;
    height: 720px;
  }
  .right h1 {
    color: white;
    text-align: center;
    padding-top: 30px;
  }
  .right p {
    color: white;
    text-align: center;
  }
  .quote {
    display: flex;
    margin: 0;
    padding: 0;
    background-color:black;
    height: 400px;
  }
  .quote span {
    border: 1px dashed red
    display: block;
    text-align: center;
    vertical-align: top;
    height: 400px;
    width: 100%;
    margin: 75px auto;
  }
  .quote span .surtext{
    font-family:  sans-serif;
    font-style: italic;
    font-size: 40px;
    color: white;
  }
  .quote span .soustext {
    font-size: 16px;
    font-style: italic;
    color: white;
    margin-bottom: 100px;
  }
  .quote .surtext a {
    color: white;
    text-decoration: none;
  }
  .quote .soustext a {
    color: white;
    text-decoration: none;
  }
  .text {
    margin: 0;
    padding: 0;
    height: 400px;
  }
  .text .colone {
    display: block;
    width: 100%;
  }
  .text .colone div {
    display: block;
    font-size: 18px;
    float: left;
    width: 400px;
    height: 100px;
    margin-left: 150px;
    margin-top: 50px;
    line-height: 20px;
    text-align: justify;
  }
  .text .colone div h2 {
    text-transform: uppercase;
  }
  .text .colone span {
    font-weight: bold;
  }
  .jaguar {
    display: block;
    height: 720px;
    width: 100%;
    background-color: white;
    background-image: url(/home/user/becode/Exercice_OP_Caritative/jaguar.jpg);
    background-size: cover;
  }
  .photos {
    height: 400px;
    width: 1000px;
    margin: 0 auto;
  }
  .photos h2{
    text-transform: uppercase;
    widows: 100%;
    text-align: center;
    margin-top: 50px;
    font-size: 28px;
  }
  .photos img {
    display: block;
    height: 250px;
    width: 250px;
    margin-left: 65px;
    margin-top: 10px;
    float: left;
    border-radius: 150px;
  }
  ```

## Problèmes rencontrés

+ Un petit souci pour comprendre le display absolute pour le header.
+ Un peu de mal à placer mes div en colonnes
