<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-euiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Itim&display=swap" rel="stylesheet">
        <script src="./script.js"></script>
        <title>Tic-Tac-TOE</title>
    </head>
    <body>
        <main class="background">
            <section class="title">
                <h1>Tic-Tac-Toe</h1>
            </section>
            <section class="display">
                Player <span class="display-player player">X</span>'s turn
            </section>
            <section class="container">
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
                <div class="title"></div>
            </section>
            {
                padding: 0;
                margin: 0;
                font-family: 'Itim', cursive;
            }
            .background {
                background-color: #283135;
                height: 100vh;
                padding-top: 1px;
            }
            .title {
                color: white;
                text-align: center;
                font-size: 40px;
                margin-bottom: 10%
            }
            .display {
                color: white;
                font-size: 25px;
                text-align: center;
                margin-top: 1em;
                margin-bottom: 1em;
            }
        </main>
    </body>
</html>
