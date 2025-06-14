<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<title>Phone Center - Rosny-sur-Seine</title>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<style>
body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-image: url('https://images.unsplash.com/photo-1603791440384-56cd371ee9a7?auto=format&fit=crop&w=1400&q=80');
background-size: cover;
background-position: center;
background-attachment: fixed;
color: #222;
}
header {
background-color: rgba(0,0,0,0.75);
color: white;
text-align: center;
padding: 30px 20px;
}
nav {
background-color: #333;
display: flex;
justify-content: center;
}
nav a {
color: white;
padding: 15px 20px;
text-decoration: none;
font-weight: bold;
transition: background-color 0.3s;
}
nav a:hover {
background-color: #555;
}
section {
background: rgba(255,255,255,0.95);
margin: 30px auto;
padding: 40px 20px;
max-width: 900px;
border-radius: 10px;
box-shadow: 0 0 15px rgba(0,0,0,0.1);
}
h2 {
margin-bottom: 25px;
}
.flex {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 20px;
}
.box {
background: white;
border-radius: 10px;
box-shadow: 0 0 7px rgba(0,0,0,0.1);
padding: 15px;
width: 280px;
text-align: center;
}
.box img {
max-width: 100%;
height: auto;
border-radius: 10px;
margin-bottom: 10px;
object-fit: cover;
}
form {
max-width: 600px;
margin: 0 auto;
display: flex;
flex-direction: column;
gap: 15px;
}
input, textarea {
padding: 10px;
font-size: 1rem;
border: 1px solid #ccc;
border-radius: 6px;
resize: vertical;
}
button {
background-color: #1e1e1e;
color: white;
border: none;
padding: 12px;
font-size: 1rem;
border-radius: 6px;
cursor: pointer;
transition: background-color 0.3s;
}
button:hover {
background-color: #444;
}
iframe {
width: 100%;
height: 300px;
border: none;
border-radius: 10px;
margin-top: 20px;
}
footer {
background-color: #1e1e1e;
color: white;
text-align: center;
padding: 20px;
margin-top: 40px;
}
</style>
</head>
<body>

<header>
<h1>Phone Center</h1>
<p>Vente & réparation de téléphones à Rosny-sur-Seine</p>
</header>

<nav>
<a href="#services">Services</a>
<a href="#gallery">Avant / Après</a>
<a href="#products">Produits</a>
<a href="#contact">Contact</a>
</nav>

<section id="services">
<h2>Nos Services</h2>
<div class="flex">
<div class="box">
<h3>Réparation Express</h3>
<p>Écrans, batteries, connecteurs</p>
<img src="https://cdn.pixabay.com/photo/2016/03/27/22/22/repair-1284305_600.jpg" alt="Réparation téléphone" />
</div>
<div class="box">
<h3>Accessoires</h3>
<p>Coques, câbles, écouteurs</p>
<img src="https://cdn.pixabay.com/photo/2020/02/04/18/42/cell-phone-4818425_600.jpg" alt="Accessoires téléphone" />
</div>
<div class="box">
<h3>Techniciens Experts</h3>
<p>Diagnostic rapide & pièces garanties</p>
<img src="https://cdn.pixabay.com/photo/2018/01/03/09/09/phone-3057973_600.jpg" alt="Atelier smartphone" />
</div>
</div>
</section>

<section id="gallery">
<h2>Avant / Après réparation</h2>
<div class="flex">
<div class="box">
<h4>Avant</h4>
<img src="https://cdn.pixabay.com/photo/2016/11/23/15/49/cracked-1853383_600.jpg" alt="Écran cassé" />
</div>
<div class="box">
<h4>Après</h4>
<img src="https://cdn.pixabay.com/photo/2017/03/29/12/09/smartphone-2188359_600.jpg" alt="Téléphone réparé" />
</div>
</div>
</section>

<section id="products">
<h2>Téléphones à vendre</h2>
<div class="flex">
<div class="box">
<h3>iPhone 11</h3>
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/IPhone_11_Black.svg" alt="iPhone 11" />
<p>Prix : 450 €</p>
</div>
<div class="box">
<h3>Samsung Galaxy S10</h3>
<img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Samsung_Galaxy_S10_plus.png" alt="Samsung Galaxy S10" />
<p>Prix : 399 €</p>
</div>
</div>
</section>

<section id="contact">
<h2>Contact & Localisation</h2>
<p><strong>Adresse :</strong> 75 rue Nationale, 78710 Rosny-sur-Seine</p>
<p><strong>Téléphone :</strong> <a href="tel:+33745633102">07 45 63 31 02</a></p>
<p><strong>Responsable :</strong> Nadir Ziouche</p>
<p><strong>Horaires :</strong> Mardi à Samedi : 9h30 - 12h / 14h30 - 19h</p>

<form>
<input type="text" placeholder="Votre nom" required />
<input type="email" placeholder="Votre email" required />
<textarea rows="5" placeholder="Votre message" required></textarea>
<button type="submit">Envoyer</button>
</form>

<iframe
src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2632.104999358839!2d1.6377454767764366!3d48.99457487134501!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e6b449de31f733%3A0xf66c95e15a9b7863!2s75%20Rue%20Nationale%2C%2078710%20Rosny-sur-Seine!5e0!3m2!1sfr!2sfr!4v1717230313144!5m2!1sfr!2sfr"
allowfullscreen=""
loading="lazy"
referrerpolicy="no-referrer-when-downgrade"
></iframe>
</section>

<footer>
<p>&copy; 2025 Phone Center - Tous droits réservés | Responsable : Nadir Ziouche</p>
</footer>

</body>
</html>
