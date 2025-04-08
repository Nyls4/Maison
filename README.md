<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Location de Maison</title>
  <style>
    /* Styles de base */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }
    header {
      background: #2c3e50;
      color: #ecf0f1;
      padding: 20px;
      text-align: center;
    }
    .logo {
      width: 80px;
      height: 80px;
      margin: 0 auto 10px;
    }
    nav a {
      color: #ecf0f1;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 30px 20px;
      max-width: 800px;
      margin: auto;
      background-color: #fff;
      margin-bottom: 20px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    footer {
      background: #2c3e50;
      color: #ecf0f1;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <!-- Logo personnalisé en SVG avec une icône de maison -->
    <div class="logo">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
        <!-- Toit -->
        <polygon points="32,5 5,28 11,28 11,55 25,55 25,40 39,40 39,55 53,55 53,28 59,28" fill="#ecf0f1"/>
        <!-- Corps de la maison -->
        <rect x="18" y="35" width="28" height="20" fill="#3498db"/>
      </svg>
    </div>
    <h1>Maison à Louer</h1>
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#maison">La Maison</a>
      <a href="#tarifs">Tarifs</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Section Accueil -->
  <section id="accueil">
    <h2>Bienvenue</h2>
    <p>Découvrez notre charmante maison à louer pour vos séjours. Profitez d’un cadre paisible et d’un confort optimal pour vos vacances ou votre résidence temporaire.</p>
  </section>

  <!-- Section La Maison -->
  <section id="maison">
    <h2>La Maison</h2>
    <p>Située dans un environnement agréable, cette maison offre :</p>
    <ul>
      <li>3 chambres spacieuses</li>
      <li>Un grand salon lumineux</li>
      <li>Une cuisine entièrement équipée</li>
      <li>Un jardin privatif</li>
      <li>Un emplacement calme et sécurisé</li>
    </ul>
    <p>Les espaces ont été pensés pour garantir confort et convivialité.</p>
  </section>

  <!-- Section Tarifs -->
  <section id="tarifs">
    <h2>Tarifs</h2>
    <p>Pour connaître nos tarifs et les disponibilités, n’hésitez pas à nous contacter. Nous proposons des offres adaptées à toutes les durées de location.</p>
  </section>

  <!-- Section Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Pour plus d’informations ou pour réserver, contactez-nous :</p>
    <ul>
      <li>Email : <a href="mailto:contact@maisonalouer.fr">contact@maisonalouer.fr</a></li>
      <li>Téléphone : 01 23 45 67 89</li>
      <li>Adresse : 123 Rue de l'Exemple, 75000 Paris</li>
    </ul>
  </section>
  <footer>
    <p>&copy; 2025 Maison à Louer. Tous droits réservés.</p>
  </footer>
</body>
</html>
