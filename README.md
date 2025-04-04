<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Commande</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFC0CB;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .logo {
            width: 100px;
            margin: 20px;
        }
        .photo-slot {
            width: 200px;
            height: 200px;
            background-color: white;
            margin: 10px auto;
            border-radius: 10px;
        }
        .btn-follow {
            display: block;
            margin: 20px auto;
            padding: 10px;
            background-color: #FF69B4;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .panier {
            background-color: white;
            padding: 10px;
            border-radius: 5px;
            width: 50%;
            margin: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="logo.png" alt="Logo" class="logo">
        <h1>Bienvenue sur notre boutique</h1>
        
        <div class="photo-slot"></div>
        <div class="photo-slot"></div>
        
        <button class="btn-follow" onclick="window.location.href='https://www.instagram.com/toncompte/'">Suivre sur Instagram</button>
        
        <h2>Panier</h2>
        <div class="panier">
            <p>Votre panier est vide.</p>
        </div>
    </div>
</body>
</html>
