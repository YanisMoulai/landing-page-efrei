<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Votre Produit — Landing Page</title>
  <meta name="description" content="Découvrez votre solution idéale pour gagner du temps et obtenir des résultats." />
  <style>
    :root {
      --primary: #4f46e5;
      --dark: #0f172a;
      --light: #f8fafc;
      --gray: #64748b;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Inter, sans-serif;
      color: var(--dark);
      background: var(--light);
      line-height: 1.6;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 2rem 1.5rem;
    }
    header {
      background: linear-gradient(135deg, var(--primary), #6366f1);
      color: white;
    }
    header .container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: center;
      min-height: 90vh;
    }
    h1 { font-size: 3rem; line-height: 1.2; margin-bottom: 1rem; }
    p.lead { font-size: 1.2rem; margin-bottom: 2rem; }
    .btn {
      display: inline-block;
      background: white;
      color: var(--primary);
      padding: 0.9rem 1.5rem;
      border-radius: 999px;
      font-weight: 600;
      text-decoration: none;
    }
    .hero-card {
      background: white;
      border-radius: 1.5rem;
      padding: 2rem;
      box-shadow: 0 20px 40px rgba(0,0,0,.15);
      color: var(--dark);
    }
    section {
      padding: 4rem 0;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .feature {
      background: white;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 10px 25px rgba(0,0,0,.08);
    }
    .feature h3 { margin-bottom: .5rem; }
    .cta {
      background: var(--dark);
      color: white;
      text-align: center;
    }
    .cta .btn { margin-top: 1.5rem; }
    footer {
      text-align: center;
      color: var(--gray);
      padding: 2rem 1rem;
      font-size: .9rem;
    }
    @media (max-width: 800px) {
      header .container { grid-template-columns: 1fr; text-align: center; }
      h1 { font-size: 2.2rem; }
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <div class="container">
      <div>
        <h1>Boostez votre activité dès aujourd'hui</h1>
        <p class="lead">Une solution simple, rapide et efficace pour atteindre vos objectifs sans complexité.</p>
        <a href="#cta" class="btn">Commencer maintenant</a>
      </div>
      <div class="hero-card">
        <h2>Pourquoi nous choisir ?</h2>
        <p>✔️ Mise en place rapide<br>✔️ Résultats mesurables<br>✔️ Support réactif</p>
      </div>
    </div>
  </header>

  <!-- FEATURES -->
  <section>
    <div class="container">
      <h2 style="text-align:center; margin-bottom:3rem;">Fonctionnalités clés</h2>
      <div class="features">
        <div class="feature">
          <h3>Simplicité</h3>
          <p>Une interface intuitive pensée pour aller droit à l'essentiel.</p>
        </div>
        <div class="feature">
          <h3>Performance</h3>
          <p>Optimisée pour offrir rapidité et fiabilité à chaque utilisation.</p>
        </div>
        <div class="feature">
          <h3>Accompagnement</h3>
          <p>Une équipe disponible pour vous aider à chaque étape.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta" id="cta">
    <div class="container">
      <h2>Prêt à passer au niveau supérieur ?</h2>
      <p>Rejoignez des centaines d'utilisateurs satisfaits dès maintenant.</p>
      <a href="#" class="btn">S'inscrire gratuitement</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2025 Votre Marque — Tous droits réservés
  </footer>

</body>
</html>
