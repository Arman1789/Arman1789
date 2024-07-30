<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unsere Restaurants</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            width: 100%;
            text-align: center;
        }
        .container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 2em;
        }
        .restaurant {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            width: 300px;
            text-align: center;
            margin: 1em;
            padding: 1em;
        }
        .restaurant img {
            max-width: 100%;
            border-radius: 8px;
        }
        .restaurant h2 {
            margin-top: 0.5em;
        }
        .restaurant a {
            display: inline-block;
            margin-top: 1em;
            padding: 0.5em 1em;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .restaurant a:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Unsere Restaurants</h1>
    </header>
    <div class="container">
        <div class="restaurant">
            <img src="http://shakyshake.de/logo.png" alt="Shaky Shake Logo">
            <h2>Shaky Shake</h2>
            <p><a href="http://shakyshake.de">Zum Menü</a></p>
        </div>
        <div class="restaurant">
            <img src="http://help-pizza.de/logo.png" alt="Help Pizza Logo">
            <h2>Help Pizza</h2>
            <p><a href="http://help-pizza.de">Zum Menü</a></p>
        </div>
    </div>
</body>
</html>
