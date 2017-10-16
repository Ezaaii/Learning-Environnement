# Star-Wars-Crawl

## Mon Code

+ HTML

  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="main.css">
    <title>Star Wars</title>
  </head>
  <body>
    <audio src="https://ia801703.us.archive.org/15/items/StarWarsThemeSongByJohnWilliams/Star%20Wars%20Theme%20Song%20By%20John%20Williams.mp3" autoplay></audio>
    <div class="fade"></div>
    <section class="starwars">
      <div class="crawl">
        <div class="titre">
          <img src="http://www.becode.org/img/logo_footer.png" alt="becode logo">
          <p>Episode II</p>
          <h1>Le retour du Roi</h1>
        </div>
        <p>Après son passage, plutôt court, il faut bien l'avouer; Le Roi revient pour enfin passer 5 minutes avec les Lovelaciens.</p>
        <p>Perdu dans l'espace, dérivant dans le néant, parviendra-t-il à donner de l'intérêt à cette classe exploitée pour leur capacité à porter des frigos et autre meubles sans se plaindre.</p>
        <p>Les lovelaciens, désepérés, auront besoin de plus qu'une machine à café sur utilisée pour vaincre le coté obscure du code.</p>
      </div>
    </section>
  </body>
  </html>
  ```

+ CSS

  ```
  main, html {
    background-image: url(http://www.spaceops2018.org/upload/fond/space.jpeg);
    background-size: cover;
    margin: 0;
    padding:0;
    width: 100%;
    height: 100%;
    overflow: hidden;

  }
  .fade {
    position: relative;
    width: 100%;
    min-height: 60vh;
    top: -25px;
    background-image: linear-gradient(0deg, transparent, black 75%);
    z-index: 1;
  }
  .starwars{
    display: flex;
    justify-content: center;
    height: 800px;
    perspective: 400px;
    color: yellow;
    font-size: 500%;
    font-weight: bold;
    font-family: arial;
    text-align: center;
  }
  .crawl{
    transform-origin: 50% 100%;
    position: relative;
    top: -100px;
    animation: crawl 60s linear;
  }
  @keyframes crawl {
    0% {
      top: 0;
      transform: rotateX(15deg) translateZ(0);
    }
    100% {
      top: -6000px;
      transform: rotateX(20deg) translateZ(-2500px);
    }
  }
  ```

### Problèmes rencontrés

+ Petite difficulté à comprendre la rotation 3D avec la perspective.
