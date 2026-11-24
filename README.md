# GSIA Crypto Academy — version 1

Application éducative PWA autonome. Elle peut être hébergée sur GitHub Pages et installée sur Android depuis le navigateur.

## Fonctions de cette version
- Mini-cours éducatifs et progression locale.
- Suivi indicatif de Bitcoin, Ethereum et Solana via l'API publique CoinGecko.
- Portefeuille de simulation en dollars fictifs, enregistré uniquement sur l'appareil.
- Partage du lien vers Telegram.
- Installation PWA et cache hors connexion de l'interface.

## Limites et sécurité
- Aucune crypto réelle n'est achetée, vendue, conservée ou transférée.
- Aucun dépôt, retrait, paiement, portefeuille blockchain ou rendement n'est proposé.
- Les données de simulation sont locales au navigateur et peuvent être effacées.
- Les cours de démonstration peuvent être indisponibles ou retardés.
- Ne pas ajouter de clés privées, phrases de récupération, mots de passe ou jetons secrets dans le dépôt GitHub.
- Avant toute monétisation, vérifier les obligations légales, fiscales, de protection des consommateurs et de traitement des paiements au Togo et dans les pays ciblés.
- Vérifier les conditions de licence et d'attribution de CoinGecko avant usage commercial. La version de démonstration ne doit pas être considérée comme une licence commerciale.

## Déploiement GitHub Pages
1. Créer un nouveau dépôt public nommé `gsia-crypto-academy`.
2. Importer `index.html`, `manifest.webmanifest`, `sw.js` et `icon.svg` à la racine.
3. Ouvrir Settings → Pages.
4. Dans Build and deployment, choisir Deploy from a branch.
5. Sélectionner `main` et `/ (root)`, puis Save.
6. Attendre l'adresse publiée par GitHub Pages. Le service worker et l'installation PWA nécessitent HTTPS.
7. Tester le lien sur Android avec Chrome ou un navigateur compatible, puis utiliser le menu du navigateur → Installer l'application / Ajouter à l'écran d'accueil.

## Telegram
- Créer un canal Telegram GSIA Crypto Academy pour les cours et annonces.
- Publier le lien GitHub Pages dans le canal.
- Le bouton Partager de l'application ouvre le partage Telegram.
- Pour un bot automatisé, voir `telegram-bot/README.md`. Le bot nécessite un hébergement serveur séparé. Ne jamais mettre le token du bot dans `index.html` ou GitHub.

## Personnalisation
Remplacer les textes de marque dans `index.html`. Remplacer `APP_URL` automatiquement après publication (il utilise déjà l'adresse courante).
