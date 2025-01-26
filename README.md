# silver-sniffle/* Styles généraux */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

header .logo img {
    width: 150px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Style de la section principale */
main {
    padding: 20px;
}

.hero {
    background: #333;
    color: white;
    padding: 50px;
    text-align: center;
}

.promotion {
    text-align: center;
    margin-top: 30px;
}

.produits {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 20px;
}

.produit {
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 15px;
    width: 30%;
    text-align: center;
    margin-bottom: 20px;
}

.produit img {
    width: 100%;
    height: auto;
}

.produit button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    margin-top: 10px;
}

footer {
    background: #333;
    color: white;
    padding: 10px;
    text-align: center;
    margin-top: 20px;
}

/* Style du formulaire de contact */
form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

form label {
    margin-bottom: 5px;
    margin-top: 10px;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
}

form button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}