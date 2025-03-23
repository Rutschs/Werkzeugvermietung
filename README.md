# Werkzeugvermietung<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Werkzeugvermietung</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        .item {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            display: inline-block;
            width: 200px;
        }
        .item img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Meine Werkzeugvermietung</h1>
    <div id="items">
        <div class="item">
            <img src="hammer.jpg" alt="Hammer">
            <h3>Hammer</h3>
            <p>5 CHF pro Tag</p>
            <button>Mieten</button>
        </div>
        <div class="item">
            <img src="bohrmaschine.jpg" alt="Bohrmaschine">
            <h3>Bohrmaschine</h3>
            <p>10 CHF pro Tag</p>
            <button>Mieten</button>
        </div>
    </div>
</body>
</html>
