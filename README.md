<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="buttonClicker.css">
</head>
<body>
        <div id="main_container">
            <div id="header">
                <h1>Dojonary</h1>
                <form>
                    <input type="text" placeholder="Search..">
                    <button type="button" onclick="log(this)">Login</button>
                </form>
            </div>
            <div class="definitions">
                <div class="two_definitions">
                    <div class="definition">
                        <div class="part_of_speech">
                            <h2>Ninja</h2>
                            <p>Noun</p>
                            <p>Plural:<span class="italics">ninjas</span></p>
                            <button class="likes"> 13 likes</button>
                        </div>
                            <p class="defined">A practioner skilled in <a href=#>Japanses</a> art of <a href=#>ninjutsu</a></p>
                    </div>
                    <div class="definition">
                        <div class="part_of_speach">
                            <h2>Ninja</h2>
                            <p>Noun</p>
                            <p>Plural:<span class="italics">ninjas</span></p>
                            <button class="likes">37 likes</button>
                        </div>
                            <p class="defined">A <a href=#>programmer</a> who breaks down problems with <a href=#>zen</a>-like focus. </p>
                            
                    </div>
                </div>
                <div class="definition_C">
                    <p>Dojonary is defined by <span id="bold">YOU</span></p>
                    <button id="add" onclick="add(this)">Add Definition</button>
                </div>
            </div>  
        </div>
    <script src="buttonClicker.js"></script>
</body>
</html>
