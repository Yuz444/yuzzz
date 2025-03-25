YUZ
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Web Stylée</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: url('https://preview.redd.it/4bqhih6hof7a1.jpg?auto=webp&s=8b064ac1ec03dbc6b63c4319e4178b39b5128e7c') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-family: Arial, sans-serif;
            color: white;
        }

        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1.2rem;
            color: white;
            background: #ff5722;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn:hover {
            background: #e64a19;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenue sur mon site</h1>
        <p>Une belle page avec une image de Berserk en fond.</p>
        <a href="page2.html" class="btn">Découvrir</a>
    </div>
</body>
</html>






























<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 2 - Berserk</title>
    <style>
        body {
            background: url('https://i.imgur.com/6K9dBpc.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        a {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 20px;
            color: white;
            background: #ff5722;
            text-decoration: none;
            border-radius: 5px;
        }
        a:hover {
            background: #e64a19;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenue sur la deuxième page</h1>
        <p>Encore plus d'images et d'infos sur Berserk !</p>
        <a href="index.html">Retour</a>
    </div>
</body>
</html>

