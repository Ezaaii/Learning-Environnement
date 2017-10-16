# starting-web-developpment

## Mon code

  + HTML

    ```
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <link rel="stylesheet" type="text/css" href="main.css">
      <link rel="stylesheet" href="/home/user/becode/starting-web-developpment/css/font-awesome.min.css">
      <link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Open+Sans:400,300,700|Montserrat:400,700">
      <title>Document</title>
    </head>
    <body>
    <main>
      <div class="bloc">
        <div class="text">
          <img class="profile" src="/home/user/becode/starting-web-developpment/Profile.jpeg" alt="Profile Tim Berners-Lee">
          <h1>Tim Berners-Lee</h1>
          <h2>Inventor of HTML</h2>
          <p>Tim Berners-Lee is the <span>inventor</span> of the web. In 1989, Tim was working in ,a computing services section of CERN when he came up with the concept; at the time he had no idea that it would be implemented on such an <span>enormous scale.</span></p>
          <a class="button" href="">See for yourself</a>
        </div>
      </div>
      <div class="bloc">
        <div class="text">
          <div class="links">
            <i class="fa fa-facebook-square fa-5x" aria-hidden="true"><p>Facebook</p></i>
            <i class="fa fa-linkedin-square fa-5x" aria-hidden="true"><p>Linkedin</p></i>
            <i class="fa fa-twitter-square fa-5x" aria-hidden="true"><p>Twitter</p></i>
          </div>
        </div>
      </div>
      <div class="bloc">
        <div class="text">
          <h2><span>His</span> favorite movies</h2>
          <div class="films">
            <img src="/home/user/becode/starting-web-developpment/SpaceOdyssey.jpeg" alt="Space Odyssey">
            <h3>2001 - Space Odyssey</h3>
            <p>Humanity finds a misterious, obviously artificial, object buried beneath the Lunar surface ans, with the intelligent computer H.A.L. 9000, sets off on a quest.</p>
          </div>
          <div class="films">
            <img src="/home/user/becode/starting-web-developpment/MrHulot.jpeg" alt="Les vacances de Monsieur Hulot">
            <h3>Monsieur Hulot</h3>
            <p>Monsieur Hulot comes to a beachside hotel for a vacation, where he accidentally (but good-naturedly) causes havoc.</p>
          </div>
          <div class="films">
            <img src="/home/user/becode/starting-web-developpment/Alien.jpeg" alt="Alien">
            <h3>Alien</h3>
            <p>The commercial vessel Nostromo receives a distress call from an unexplored planet. After searching for survivors, the crew heads home only to realize that a deadly bioform has joined them.</p>
          </div>
        </div>
      </div>
    </main>
    </body>
    </html>
    ```

  + CSS

    ```
    html, body {
      background-color: #E5E5E5;
    }
    .bloc {
      display: block;
      margin: 0 auto;
      width: 700px;
      background-color: white;
      box-shadow: 5px 5px 0px grey;
      border-radius: 3px;
      margin-bottom: 30px;
      padding-bottom: 30px;
      padding-top: 30px;
    }
    .bloc .text {
      display: block;
      margin: 0 auto;
      width: 90%;
      text-align: center;
      font-family: 'Open Sans', sans-serif;
      color: #666666;
    }
    .bloc .text .profile {
      display: block;
      margin: 0 auto;
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid #C4C4C4;
    }
    .bloc .text h1 {
      font-family: 'Open Sans', sans-serif;
      font-weight: 600;
      color: #FF4152;
    }
    .bloc .text p{
      text-align: justify;
      font-size: 18px;
    }
    .bloc .text p span{
      font-weight: bold;
    }
    .links {
      display: flex;
      color: #C4C4C4;
      flex-direction: row;
      font-size: 18px;
    }
    .links i{
      display: block;
      margin: 0 auto;
    }
    .links i:hover{
      color: #FF4152;
    }
    .button{
      display: block;
      margin: 0 auto;
      padding-top: 15px;
      width: 200px;
      height: 50px;
      font-size: 24px;
      font-weight: bold;
      text-decoration: none;
      color: #fff;
      background-color: #FF4152;
      border-radius: 5px;
      border: 3px solid #DB293B;
    }
    .button:hover{
      background-color: #F72E43;
    }
    .text h2 {
      font-weight: normal;
    }
    .text h2 span {
      background-color: #C4C4C4;
    }
    .text .films{
      height: 200px;
      margin-bottom: 30px;
      margin-left: 20px;
      display: block;
      width: 93%;
    }
    .text .films img {
      display: block;
      margin-bottom: 30px;
      margin-right: 30px;
      width: 23%;
      float: left;
    }
    ```

## Les problèmes rencontrés

+ j'ai eu un peu de mal à structurer les div pour la dernière section (films). J'avais mal positioné mes div dans l'HTML et mis un Flex sans raison. Une fois que je suis repassé en Block et que j'ai redimensionné mes divs tout s'est bien placé.

+ Juste une petite difficulté à comprendre comment importer les icones de la Font Awesome dans le HTML. Je n'avais pas vu qu'il fallait télécharger tout le dossier de font dans le dossier du projet.

+ Tout le reste à été j'ai compris comment séparer mes éléments en divs.
