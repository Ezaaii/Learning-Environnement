# Learning-Environnement

## Mon code

+ HTML

  ```
  <DOCTYPE html>
  <html>
    <head>
      <title> Le markdown c'est bien </title>
      <meta charset="utf-8"/>
      <link rel="stylesheet" type="text/css" href="main.css">
    </head>
    <body>
      <div class="container">
        <div class="main">
          <ul>
            <li>
              <h1>Qu'est ce que le Markdown?</h1>
              <strong>le pain c'est bon.</strong>
            </li>
            <li><h1>Liste des syntaxes</h1>
              <ul>
                <li>
                  <h2>Les titres</h2>
                  <table border="0px" style="text-align:center" class="tabl" cellpadding="8">
                    <thead> <td style="background-color:#332B40"><h3 style="color: white">Markdown</h3></td>
                      <td style="background-color: #332B40"><h3 style="color: white">Apparence</h3></td> </thead>
                    <tbody style="background-color: lightgrey">
                      <tr>
                        <td>#</td>
                        <td><h1>H1</h1></td>
                      </tr>
                      <tr>
                        <td>##</td>
                        <td><h2>H2</h2></td>
                      </tr>
                      <tr>
                        <td>###</td>
                        <td><h3>H3</h3></td>
                      </tr>
                      <tr>
                        <td>####</td>
                        <td><h4>H4</h4></td>
                      </tr>
                      <tr>
                        <td>#####</td>
                        <td><h5>H5</h5></td>
                      </tr>
                      <tr>
                        <td>######</td>
                        <td><h6>H6</h6></td>
                      </tr>
                      <tr>
                        <td>Titre alternatif H1<br>===============<br></td>
                        <td><h1>Titre alternatif H1</h1></td>
                      </tr>
                      <tr>
                        <td>Titre alternatif H2<br>----------------------------<br></td>
                        <td><h2>Titre alternatif H2</h2></td>
                      </tr>
                    </tbody>
                  </table>
                </li>
                <li>
                  <h2>Altération de carractères</h2>
                  <table border="0px" class="tabl" cellpadding="8">
                    <tbody>
                      <tr>
                        <td style="background-color: #332B40; text-align:center">
                          <h3 style="color: white">Code<h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color: lightgrey">
                          *le texte est italique* ou _italique<br>
                          **Le texte est gras** ou __gras__<br>
                          *On peut aussi __combiner__ les deux*<br>
                          ~~Je n'ai pas écrit ça~~<br>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:#332B40; text-align:center">
                          <h3 style="color: white">Résultat</h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color: lightgrey">
                          <em>le texte est italique</em> ou <em>italique</em> <br>
                          <b>Le texte est gras</b> ou <b>gras</b> <br>
                          <em>On peut aussi <b>combiner</b> les deux</em> <br>
                          <strike>Je n'ai pas écrit ça</strike> <br>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </li>
                <li>
                  <h2>Les listes</h2>
                  <table border="0px" class="tabl" cellpadding="8">
                    <tr>
                      <td style="background-color:#332B40; text-align:center">
                        <h3 style="color: white">Code</h3>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color: lightgrey">
                          1. Liste ordonnée<br>
                          2. Liste ordonnée 2
                          <blockquote>1. Sous liste</blockquote><br>
                          * Liste non ordonnée<br>
                          + Avec des plus aussi<br>
                          - et des moins<br>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color: #332B40; text-align:center">
                        <h3 style="color: white">Résultat</h3>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color: lightgrey">
                        <ol>
                          <li>Liste ordonnée</li><br>
                          <li>Liste ordonnée 2</li>
                        </ol>
                        <ol>
                          <blockquote><li> Sous liste</li></blockquote><br>
                        </ol>
                        <ul style="list-style-type:circle">
                          <li>Liste non ordonnée</li><br>
                          <li>Avec des plus aussi</li><br>
                          <li>et des moins</li><br>
                      </td>
                    </tr>
                  </table>
                </li>
                <li>
                  <h2>Les liens</h2>
                  <table class="tabl" cellpadding="8">
                    <thead style="background-color:#332B40">
                      <td style="background-color:lightgray"><em>(Passez la souris sur le lien pour voir le titre)</em></td>
                    </thead>
                    <tbody>
                      <tr>
                        <td style="background-color:#332B40; text-align:center">
                          <h3 style="color: white">Code</h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:lightgray">
                          [je suis un lien](http://lelien)<br>
                          [je suis un lien avec un titre](http://google.com "Google")<br>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:#332B40; text-align:center">
                          <h3 style="color: white">Résultat</h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:lightgray">
                          [je suis un lien](http://lelien) <br>
                          [je suis un lien avec un titre](http://google.com "Google") <br>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </li>
                <li>
                  <h2>Les images</h2>
                  <table class="tabl" cellpadding="8">
                    <thead>
                      <td style="background-color:lightgray"><em>(Passez la souris sur les images pour voir le titre)</em></td>
                    </thead>
                    <tbody>
                      <tr>
                        <td style="background-color:#332B40; text-align:center">
                          <h3 style="color: white">Code</h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:lightgray">
                          ![alttext](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 1")<br>
                          ou<br>
                          ![alt text][logo]<br>
                          [logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 2"<br>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:#332B40; text-align:center">
                          <h3 style="color: white">Résultat</h3>
                        </td>
                      </tr>
                      <tr>
                        <td style="background-color:lightgray">
                          ![alttext](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 1")<br>
                          ou<br>
                          ![alt text][logo]<br>
                          [logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo 2"<br>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </li>
                <li>
                  <h2>Code et syntaxe intégrée</h2>
                  <table class="tabl" cellpadding="8">
                    <tr>
                      <td style="background-color:#332B40; text-align:center">
                        <h3 style="color: white">Code</h3>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color:lightgray">
                        <HTML><br>
                          <h1>titre</h1><br>
                          <ul style="color: black; list-style-type:none"><br>
                            <li>j'aime</li><br>
                            <li>le</li><br>
                            <li>pain</li><br>
                          </ul><br>
                          <a href="http://google.com">text</a>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color:#332B40; text-align:center">
                        <h3 style="color: white">Résultat</h3>
                      </td>
                    </tr>
                    <tr>
                      <td style="background-color:lightgray">
                        <HTML><br>
                          <h1>titre</h1><br>
                          <ul style="color: black; list-style-type:none"><br>
                            <li>j'aime</li><br>
                            <li>le</li><br>
                            <li>pain</li><br>
                          </ul><br>
                          <a href="http://google.com">text</a><br>
                      </td>
                    </tr>
                  </table>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </body>
  </html>
  ```

+ CSS

  ```
  html, body {
    font-family: arial;
    height: 100%;
    width: 100%;
    background-color: #66567F;
  }

  div {
    padding-right: 30px;
    width: 100%;
  }

  .container {
    display: flex;
  }

  .main {
    display: block;
    width: 700px;
    margin: 0 auto;
    background-color: #9981BF;
  }

  .tabl {
    width: 600px;
    line-height: 25px;
    tab-size: 40px;
  }

  H1 {
    font-weight: 600;
  }
  H2 {
    font-weight: 600;
  }
  H3 {
    font-weight: 600;
  }
  H4 {
    font-weight: 600;
  }

  ```

## Problèmes rencontrés

+ La conversion Markdown > HTML était longue mais pas trop compliquée.
+ Le plus dur était de refaire les tableaux... C'est tellement plus simple à faire en MD.
