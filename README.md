# HTML-Lecture-8

    <html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title></title>

    </head>
    <body>
        <h1>The map and area elements</h1>
        <p>Click on the roses and trees to read more about the topic:</p>
        <img src="file:///C:/Users/Carmella%20Rei%20Van/Downloads/Keukenhof-Gardens-Lisse-Netherlands.jpg" alt="Garden" usemap="#garden"
             width="400" height="379">
        <map name="garden">
            <area shape="rect" coords="300,300,250,250" alt="Grass"
                  href="https://www.biologyonline.com/dictionary/grass">
            <area shape="circle" coords="50,220,100" alt="Rose"
                  href="https://en.wikipedia.org/wiki/Rose">
        </map>
    </body>
    </html>


------------------------------------------------

    <html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title></title>

    </head>
    <body>
        <h1>The map and area elements</h1>
        <p>Click on the roses and trees to read more about the topic:</p>
        <center>
            <img src="file:///C:/Users/Carmella%20Rei%20Van/Downloads/Keukenhof-Gardens-Lisse-Netherlands.jpg" alt="Garden" usemap="#garden"
                 width="400" height="379">
        </center>
        <map name="garden">
            <area shape="rect" coords="300,300,250,250" alt="Grass"
                  href="grass.html">
            <area shape="circle" coords="50,220,100" alt="Rose"
                  href="roses.html">
        </map>

        <style>
            body{
                background-color: #ebcdc3;
            }
            h1, p {
                font-family: Georgia, 'Times New Roman', Times, serif;
                text-align: center;

            }
        </style>
    </body>
    </html>

------------------------------------------------

roses.html

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body>
        <center>
            <img src="file:///C:/Users/Carmella%20Rei%20Van/Downloads/Romantic-Garden-Love-Nature-Rose-Plants-Flowers-4666689.jpg" alt="roses" usemap="#workmap"
                 width="400" height="379">
        </center>
        <p>
            Roses are considered as one of the most beautiful and appeling flower
            <a href="https://en.wikipedia.org/wiki/Rose">
                click here to learn more
            </a>
        </p>

        <style>
            body {
                background-color: #ebcdc3;

            }

            p {
                font-family: Georgia, 'Times New Roman', Times, serif;
                text-align: center;
            }
        </style>
    </body>
    </html>

------------------------------------------------

grass.html

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body>
        <center>
            <img src="file:///C:/Users/Carmella%20Rei%20Van/Downloads/thumb_720_450_dreamstime_xl_13444388-custom.jpg" alt="Grass" width="400" height="379">
            </center>
            <p>
                Grass is a plant with narrow leaves growing from the base.
                A common kind of grass is used to cover the ground in a
                lawn and other places.
                Grass gets water from the roots in the ground. Grasses are
                monocotyledon, herbaceous plants.
                <a href="https://simple.wikipedia.org/wiki/Grass">
                    click here to learn more
                </a>
            </p>

            <style>
                body {
                    background-color: #ebcdc3;
                }

                p {
                    font-family: Georgia, 'Times New Roman', Times, serif;
                    text-align: center;
                }
            </style>
    </body>
    </html>

------------------------------------------------













