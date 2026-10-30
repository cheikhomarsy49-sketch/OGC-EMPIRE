# OGC EMPIRE — boutique en ligne

Première version web responsive, sans dépendances ni frais de logiciel.

## Fonctionnalités
- Catalogue avec catégories et recherche
- Panier et calcul du total
- Formulaire de commande
- Création d'un message WhatsApp vers +221 78 526 62 63
- Interface responsive pour mobile et ordinateur
- Manifest/service worker de base pour installation sur appareils compatibles
## Prix de démonstration à valider avant publication
- Maillot : 5 000 FCFA (coût connu : 3 250 FCFA)
- Montre : 2 500 FCFA (coût à confirmer)
- Parfum : 2 000 FCFA (coût à confirmer)
- Accessoires hijab : 1 500 FCFA (coût à confirmer)
- Pantalon : 4 000 FCFA (coût à confirmer)

Les prix hors maillot sont provisoires. Les frais de livraison ne sont pas inclus. Le site ne traite pas les paiements et ne confirme pas automatiquement les stocks.

## Prévisualiser en local
Ouvrir `index.html` dans un navigateur. Pour tester le service worker/PWA, il faut un hébergement HTTP(S).

## Publication gratuite possible
1. Créer un compte GitHub.
2. Créer un dépôt public nommé `ogc-empire`.
3. Envoyer `index.html`, `manifest.json`, `sw.js` et `README.md` à la racine du dépôt.
4. Dans Settings > Pages, choisir Deploy from a branch, `main`, `/ (root)`, puis Save.
5. Après déploiement, GitHub Pages fournit une URL publique. La disponibilité et les conditions de l'offre gratuite peuvent évoluer.
6. Tester sur iPhone/Android. Sur iPhone, ouvrir le site dans Safari > Partager > Sur l’écran d’accueil. Sur Android, ouvrir le menu du navigateur > Installer/Ajouter à l'écran d'accueil si proposé.

## Personnaliser les produits
Dans `index.html`, chercher `const products=[...]` et modifier les noms, prix, catégories, emojis et descriptions. Les images sont ici des icônes provisoires; remplacer les blocs `.photo` par des photos réelles des produits pour une boutique professionnelle.

## Limites
- Pas de back-office ni de synchronisation de stock.
- Les commandes sont envoyées par WhatsApp; elles ne sont pas enregistrées dans une base de données.
- Pas de paiement en ligne intégré.
- Les prix, disponibilités, frais et délais de livraison doivent être confirmés avec le client.
