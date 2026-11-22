# WebStudio — boutique de sites web

Site e-commerce statique en HTML, CSS et JavaScript, prêt pour GitHub Pages.

## 1. Personnaliser PayPal

1. Crée ton lien PayPal.Me depuis https://www.paypal.com/paypalme/
2. Ouvre `config.js`.
3. Remplace `TON_IDENTIFIANT_PAYPAL` par ton identifiant PayPal.Me.
   - Exemple : pour `https://paypal.me/MarieStudio`, indique `MarieStudio`.
4. Modifie aussi `contactEmail` avec ton adresse e-mail professionnelle.
5. Enregistre le fichier.

Le bouton de paiement ouvre PayPal.Me avec le total du panier. Après paiement, le client doit contacter l'adresse e-mail configurée pour organiser la livraison.

**Important :** cette version est une boutique front-end statique. Elle ne vérifie pas automatiquement les paiements, ne crée pas de commande côté serveur et ne livre pas automatiquement les fichiers. Vérifie chaque paiement dans ton compte PayPal avant de livrer. Pour des paiements avec panier détaillé, confirmation automatique et livraison numérique, il faudra connecter une solution de paiement avec backend ou une plateforme de vente numérique.

## 2. Publier gratuitement sur GitHub Pages

1. Connecte-toi à https://github.com/
2. Clique sur **New repository**.
3. Nomme le dépôt `webstudio` et choisis **Public**.
4. Clique sur **Create repository**.
5. Clique sur **Add file → Upload files**.
6. Envoie les quatre fichiers : `index.html`, `style.css`, `script.js`, `config.js` (tu peux aussi envoyer ce README).
7. Clique sur **Commit changes**.
8. Ouvre **Settings → Pages**.
9. Dans **Build and deployment**, choisis **Deploy from a branch**.
10. Choisis la branche **main**, le dossier **/(root)**, puis **Save**.

GitHub affichera l'adresse publique de ton site dans la section Pages après quelques instants, généralement sous la forme `https://TON-PSEUDO.github.io/webstudio/`.

## 3. Modifier les produits et les prix

Les produits sont définis au début de `script.js`, dans le tableau `products`. Chaque objet contient un nom, une catégorie, un prix en euros et une description. Modifie ces valeurs pour gérer ton catalogue.

## 4. À prévoir avant une vraie mise en vente

- Remplacer l'adresse e-mail de démonstration.
- Ajouter tes véritables aperçus et fichiers livrables.
- Rédiger tes conditions générales de vente, politique de confidentialité et politique de remboursement.
- Vérifier les obligations légales applicables à ton activité.
- Tester le parcours de paiement avec ton propre compte avant l'ouverture.
