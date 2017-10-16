# vcard

## Mon code

+ HTML

  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="main.css">
    <title>Vcard Nicolas Van Roost</title>
  </head>
  <body>
    <div class="menu">
      <div class="profilepic">
        <img src="https://raw.githubusercontent.com/Ezaaii/moncv/master/profile.png" alt="profile picture">
        <h1>Nicolas<br>Van Roost</h1>
        <div class="links">
          <div>profile</div>
          <div>CV</div>
          <div>Portfolio</div>
          <div>Contact</div>
        </div>
        <div class="infos">
          <h2>Infos</h2>
          <span> Age : </span>
            <ul><li>23 ans</li></ul>
          <span> Adresse : </span>
            <ul><li>Rue, n°, ville</li></ul>
          <span> Tel : </span>
            <ul><li>(+32)0474/|||||||</li></ul>
          <span> Mail :</span>
            <ul><li> n.vanroost@gmail.com</li></ul>
            <span> permis :</span>
              <ul><li> voiture (B) provisoire</li></ul>
        </div>
      </div>
    </div>
    <main>
      <section class="bloc">
        <h2>CV</h2>
      </section>
      <section class="bloc">
        <h2>Portfolio</h2>
      </section>
      <section class="bloc">
        <h2>Vidéos</h2>
      </section>
      <section class="bloc">
        <h2>Projets</h2>
      </section>
      <section class="bloc">
        <h2>Compétences</h2>
      </section>
      <section class="bloc">
        <h2>Contact</h2>
      </section>
    </main>
  </body>
  </html>
  ```

+ CSS

  ```
  html, body {
    background-color: #308794;
    background-image: url(https://pre00.deviantart.net/d31a/th/pre/f/2016/154/e/e/ee7b3477cd693629672dd3bdb0fb1b93-d9j7xyq.jpg);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    padding: 0;
    margin: 0;
    font-family: Arial;
  }
  .menu {
    display: block;
    position: fixed;
    height: 100%;
    width: 300px;
    background-color: #308794;
    box-shadow: 8px 0px 0px rgba(42, 121, 127, 0.5);
    top: 0;
    left: 0;
  }
  .menu img {
    display: block;
    margin: 0 auto;
    margin-top: 15px;
    height: 250px;
    width: 250px;
    border-radius: 150px;
    box-shadow: 8px 8px 1px #DB4A7E;
  }
  .menu h1 {
    display: block;
    margin: 0 auto;
    margin-top: 15px;
    width: 250px;
    color: #fff;
    text-transform: capitalize;
    font-size: 50px;
  }
  .menu .links{
    display: block;
    margin: 0 auto;
    margin-top: 30px;
    width: 300px;
    height: 200px;
    color: #DB4A7E;
  }
  .menu .links div {
    display: block;
    background-color: #379AA8;
    margin-bottom: 3px;
    padding-top: 15px;
    height: 35px;
    text-align: center;
    font-size:22px;
    font-weight: bold;
  }
  .menu .links div:nth-child(1){
    background-color: #DB4A7E;
    color: #fff;
    width: 310px;
    font-size: 25px;
  }
  .menu .links div:hover {
    background-color: #DB4A7E;
    color: #fff;
    width: 310px;
    font-size: 25px;
  }
  .menu .infos {
    display: block;
    margin: 0 auto;
    margin-top: 30px;
    width: 250px;
    height: 300px;
    box-shadow: 8px 8px 1px #DB4A7E;
    background-color: #fff;
    border-radius: 15px;
  }
  .menu .infos h2 {
    display: block;
    margin: 0 auto;
    padding-top: 15px;
    width: 200px;
    color : #DB4A7E;
    font-size: 30px;
  }
  .menu .infos ul {
    display: block;
    margin: 0 auto;
    width: 200px;
    color: #DB4A7E;
    font-size: 18px;
    list-style-type: none;
  }
  .menu .infos span {
    display: block;
    margin: 0 auto;
    width: 200px;
    color: #DB4A7E;
    font-weight: bold;
    font-size: 20px;
  }
  main {
    width: 64%;
    display: block;
    margin: 0 auto;
    margin-top: 10px;
    margin-bottom: 30px;
    height: inherit;
  }
  main h2 {
    margin-left: 30px;
    padding-top: 15px;
    font-size: 36px;
  }
  main p {
    margin-left: 30px;
    padding-top: 5px;
    font-size: 26px;
  }
  main a {
    margin-left: 30px;
    padding-top: 5px;
    font-size: 26px;
    text-decoration: none;
    color: #DB4A7E;
  }
  main a:hover {
    color: #308794;
    font-size: 28px;
  }
  .bloc {
    display: block;
    margin: 0 auto;
    float: left;
    width: 300px;
    height: 300px;
    padding-bottom: 30px;
    margin-top: 15px;
    color: #DB4A7E;
    background-color: #fff;
    box-shadow: 8px 8px 0px rgba(42, 121, 127, 0.5);
  }
  .bloc:nth-child(n+1){
    float:left;
    margin-right: 30px;
    margin-bottom: 30px;
  }
  .bloc:hover {
    background-color: #F6A5B0;
  }
  ```

## Difficultés rencontrées

+ Pas vraiment de difficultés, j'ai conservé le layout de l'excercice précédent pour garder une cohérence graphique et éventuellement lier le CV à la VCard.
