# Brin d'Aube

Site vitrine d'un fleuriste parisien **fictif**, réalisé comme projet d'entraînement. Aucune commande n'est réellement passée.

Une seule page, `index.html`, sans dépendance ni étape de build :

- catalogue filtrable par occasion et par couleur, avec tri par prix ;
- bouquets dessinés en SVG, générés à partir de chaque produit ;
- fiche produit (taille, options, date et créneau de livraison, message sur la carte) ;
- panier et commande simulée, conservés dans le `localStorage` du navigateur ;
- vérification du délai de livraison selon le code postal ;
- thème clair / sombre automatique, mise en page mobile.

## Lancer en local

Ouvrez `index.html` dans un navigateur.

## Publier avec GitHub Pages

Settings → Pages → *Deploy from a branch* → `main` / `(root)`. Le site sera servi à `https://<utilisateur>.github.io/brin-d-aube/`.
