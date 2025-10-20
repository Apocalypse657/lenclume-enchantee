<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>L’Enclume Enchantée</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=Crimson+Text:ital,wght@0,400;0,600;1,400&display=swap');

    body {
      background: radial-gradient(circle at top, #1b1b2f, #0d0d17);
      color: #f0e6d2;
      font-family: 'Crimson Text', serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 3rem 1rem;
      background: linear-gradient(to bottom, #2e2a3a, #1b1b2f);
      border-bottom: 2px solid #d4af37;
    }

    h1 {
      font-family: 'Cinzel', serif;
      font-size: 3rem;
      color: #d4af37;
      letter-spacing: 2px;
    }

    h2 {
      font-family: 'Cinzel', serif;
      color: #d4af37;
      border-bottom: 1px solid #d4af37;
      padding-bottom: 0.5rem;
      margin-top: 2.5rem;
    }

    p.quote {
      font-style: italic;
      color: #cfc6ac;
      text-align: center;
      margin-bottom: 2rem;
    }

    section {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
    }

    .item {
      display: flex;
      justify-content: space-between;
      margin: 0.4rem 0;
      border-bottom: 1px dashed rgba(212, 175, 55, 0.3);
      padding-bottom: 0.2rem;
    }

    .name {
      font-weight: 600;
    }

    .price {
      color: #d4af37;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      border-top: 1px solid #d4af37;
      margin-top: 3rem;
      color: #cfc6ac;
    }

    .page {
      border: 2px solid rgba(212, 175, 55, 0.3);
      border-radius: 10px;
      padding: 2rem;
      background: rgba(255, 255, 255, 0.03);
      margin-bottom: 3rem;
      box-shadow: 0 0 15px rgba(212, 175, 55, 0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>🪄 L’Enclume Enchantée</h1>
    <p>“Ici, le feu danse, le pain chante et la magie parfume l’air.”</p>
  </header>

  <section>

    <div class="page">
      <h2>✨ Entrées Enchantées</h2>
      <p class="quote">“Avant le festin, éveillons la magie des sens.”</p>

      <div class="item"><span class="name">Soupe de la Lune Rousse</span><span class="price">10,90 €</span></div>
      <div class="item"><span class="name">Croquant des Sous-Bois</span><span class="price">11,50 €</span></div>
      <div class="item"><span class="name">Œufs du Phénix Doré</span><span class="price">12,90 €</span></div>
      <div class="item"><span class="name">Brume des Falaises Nordiques</span><span class="price">13,90 €</span></div>
      <div class="item"><span class="name">Croustade des Alchimistes</span><span class="price">14,50 €</span></div>
    </div>

    <div class="page">
      <h2>🍔 Festins du Forgeron</h2>
      <p class="quote">“L’enclume chante, le feu danse, les saveurs s’élèvent.”</p>

      <div class="item"><span class="name">Burger du Dragon Noir</span><span class="price">22,90 €</span></div>
      <div class="item"><span class="name">Braise du Forgeron</span><span class="price">23,90 €</span></div>
      <div class="item"><span class="name">Pâtes du Soleil Déchu</span><span class="price">21,90 €</span></div>
      <div class="item"><span class="name">Risotto des Nymphes</span><span class="price">22,50 €</span></div>
      <div class="item"><span class="name">Tendre Sortilège (végane)</span><span class="price">19,90 €</span></div>
    </div>

    <div class="page">
      <h2>🍰 Douceurs & Délices</h2>
      <p class="quote">“Quand la magie devient sucrée.”</p>

      <div class="item"><span class="name">Mousse du Crépuscule</span><span class="price">9,50 €</span></div>
      <div class="item"><span class="name">Fruits des Fées</span><span class="price">8,90 €</span></div>
      <div class="item"><span class="name">Tarte Étoilée</span><span class="price">9,90 €</span></div>
      <div class="item"><span class="name">Crème des Songes</span><span class="price">9,50 €</span></div>
      <div class="item"><span class="name">Gâteau des Sorcières du Sud</span><span class="price">10,50 €</span></div>
    </div>

    <div class="page">
      <h2>🍹 Potions & Élixirs (sans alcool)</h2>
      <p class="quote">“Potions, élixirs et breuvages célestes.”</p>

      <div class="item"><span class="name">Potion du Lever d’Aube</span><span class="price">6,00 €</span></div>
      <div class="item"><span class="name">Larme de Licorne</span><span class="price">6,90 €</span></div>
      <div class="item"><span class="name">Éclat d’Émeraude</span><span class="price">7,50 €</span></div>
      <div class="item"><span class="name">Brume Céleste</span><span class="price">7,90 €</span></div>
      <div class="item"><span class="name">Infusion des Fées</span><span class="price">5,90 €</span></div>
    </div>

    <div class="page">
      <h2>🍷 Breuvages des Esprits (avec alcool)</h2>
      <p class="quote">“Les esprits du feu et de la lune se rencontrent ici.”</p>

      <div class="item"><span class="name">Vin du Crépuscule (rouge)</span><span class="price">6,90 €</span></div>
      <div class="item"><span class="name">Hydromel des Anciens</span><span class="price">9,90 €</span></div>
      <div class="item"><span class="name">Bière du Nain Forgeron</span><span class="price">8,50 €</span></div>
      <div class="item"><span class="name">Élixir de Lune Bleue</span><span class="price">11,50 €</span></div>
      <div class="item"><span class="name">Sang de Salamandre</span><span class="price">10,00 €</span></div>
    </div>

    <div class="page">
      <h2>🧒 Menu Enfant : Le Repas des Apprentis</h2>
      <p class="quote">“Pour les petits magiciens en herbe.”</p>
      <p>Plat au choix + Boisson enchantée + Dessert + Jouet magique — <strong>15,90 €</strong></p>
    </div>

    <div class="page">
      <h2>🌙 Menu du Jour</h2>
      <p>Formule midi (Entrée + Plat + Dessert + Café runique) — <strong>24,90 €</strong></p>
      <p class="quote">“Chaque jour, un sort culinaire différent.”</p>
    </div>

    <div class="page">
      <h2>🎁 Souvenirs & Produits Magiques</h2>
      <div class="item"><span class="name">Mini Grimoire à Colorier</span><span class="price">6,50 €</span></div>
      <div class="item"><span class="name">Potion Lumineuse Décorative</span><span class="price">9,90 €</span></div>
      <div class="item"><span class="name">Mug de la Forge Magique</span><span class="price">14,50 €</span></div>
      <div class="item"><span class="name">Grimoire des Recettes</span><span class="price">24,90 €</span></div>
    </div>

    <div class="page">
      <h2>🌌 Mot de la Fin</h2>
      <p class="quote">“Que la magie de ce festin reste dans ton cœur,<br>comme une étincelle douce et dorée.<br>Reviens quand l’enchantement t’appellera.”</p>
      <p style="text-align:center;">— L’équipe de L’Enclume Enchantée 🔮</p>
    </div>

  </section>

  <footer>
    © 2025 L’Enclume Enchantée — Site conçu avec amour et poussière d’étoiles ✨
  </footer>
</body>
</html>
