# moncv

## Mon code

+ HTML

  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="main.css">
    <title>Nicolas Van Roost</title>
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
        <h1>Expérience</h1>
        <ul>
          <li>Education</li>
            <ul>
              <li>Collège st-Etienne | Section Infographie</li>
              <li>Haute école Alber Jacquard | Illustration/animation</li>
            </ul>
          <li>expérience professionnelle</li>
            <ul>
              <li>freelance artist</li>
            </ul>
          <li>stages</li>
            <ul>
              <li>my zebrabook | Illustrateur</li>
              <li>Illustrateur indé Dominique Mertens | Aide illustrateur</li>
              <li>NoteCampus | Illustrateur/animateur/Graphiste</li>
            </ul>
        </ul>
      </section>
      <section class="bloc">
        <h1>Compétences</h1>
        <ul>
          <li>Graphiste</li>
            <ul>
              <li>Photoshop</li>
              <li>Illustrator</li>
              <li>InDesign</li>
              <li>Flash</li>
              <li>After Effect</li>
              <li>Sony Vegas pro</li>
              <li>TvPaint</li>
              <li>Corel Painter</li>
              <li>Cinema 4D</li>
            </ul>
          <li>Developper</li>
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>(PHP)</li>
              <li>(JavaScript)</li>
            </ul>
          <li>Autre</li>
            <ul>
              <li>Word</li>
              <li>Excel</li>
              <li>Powerpoint</li>
              <li>Outlook</li>
            </ul>
          <li>Langues</li>
            <ul>
              <li>Français</li>
              <li>Anglais</li>
            </ul>
        </ul>
      </section>
      <section class="bloc">
        <h1>Contact me</h1>
        <a href="https://behance.net/ezaaii">Behance</a><br>
        <a href="https://www.linkedin.com/in/nicolas-van-roost-a445a8133/">Linkedin</a><br>
        <a href="https://github.com/Ezaaii">Github</a><br>
        <a href="https://twitter.com/ezaaii">Twitter</a><br>
        <a href="https://facebook.com/ezouille">Facebook</a><br>
        <a href="http://youtube.com/user/ezaaii">Youtube</a><br>
        <a href="http://twitch/tv/ezaaii">Twitch</a><br>
      </<section>
    </main>
  </body>
  </html>
  ```

+CSS

  ```
  html, body {
    background-color: #308794;
    background-image: url(https://pre00.deviantart.net/d31a/th/pre/f/2016/154/e/e/ee7b3477cd693629672dd3bdb0fb1b93-d9j7xyq.jpg);
    background-size: cover;
    padding: 0;
    margin: 0;
    font-family: Arial;
  }
  .menu {
    position: fixed;
    float:left;
    height: 100%;
    width: 300px;
    background-color: #308794;
    box-shadow: 8px 0px 0px rgba(42, 121, 127, 0.5);
    float: left;
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
    width: 100%;
    display: block;
    margin: 0 auto;
    float: right;
    margin-top: 10px;
    margin-right: 75px;
    margin-bottom: 30px;
  }
  main h1 {
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
    width: 1000px;
    height: inherit;
    padding-bottom: 30px;
    color: #DB4A7E;
    background-color: #fff;
    box-shadow: 8px 8px 0px rgba(42, 121, 127, 0.5);
  }
  main .bloc ul {
    margin-left: 30px;
    font-size: 26px;
  }
  main .bloc li {
    margin-left: 30px;
    font-size: 22px;
  }
  ```

## Problèmes rencontrés

+ Pas vraiment de problèmes. J'ai compris comment mettre un menu fixe et des divs sur le coté. J'ai aussi compris à quoi servait le Inherit.
