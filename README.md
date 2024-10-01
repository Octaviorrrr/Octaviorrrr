<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique en ligne</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue dans notre boutique en ligne</h1>
        <nav>
            <a href="#">Accueil</a>
            <a href="#">Produits</a>
            <a href="#">Contact</a>
            <a href="#" id="cart-button">Panier (<span id="cart-count">0</span>)</a>
        </nav>
    </header>
    
    <main>
        <h2>Nos Produits</h2>
        <div class="product" data-name="Produit 1" data-price="20">
            <h3>Produit 1</h3>
            <p>Description du produit 1.</p>
            <p>Prix : 20€</p>
            <button onclick="addToCart(this)">Ajouter au panier</button>
        </div>
        <div class="product" data-name="Produit 2" data-price="30">
            <h3>Produit 2</h3>
            <p>Description du produit 2.</p>
            <p>Prix : 30€</p>
            <button onclick="addToCart(this)">Ajouter au panier</button>
        </div>
    </main>
    
    <footer>
        <p>&copy; 2024 Boutique en ligne</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

