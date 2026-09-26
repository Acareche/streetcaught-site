# StreetCaught — site web

Site vitrine du jeu **StreetCaught** : repérer de vraies voitures, les scanner en cartes, les faire courir.

Tout tient dans un seul fichier, `index.html` (CSS, JS, silhouettes et textures holo inclus). Aucune étape de build.

## Voir le site en local

Ouvrir `index.html` dans un navigateur.

## Mettre en ligne avec GitHub Pages

Settings → Pages → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)`.
Le site sera à `https://<ton-utilisateur>.github.io/streetcaught-site/`.

## Contenu

- Vitrine et fonctionnement (repérer, scanner, courir)
- Rareté (7 paliers, classiques en bois)
- Finitions de carte (8 effets, motifs holo/carbone/forgé numérotés, alt art), démo interactive
- Courses (stats, pondérations d'épreuves, surfaces, démo de drag)
- Atelier (axes, fusion, pièces, emplacements)
- Jauges, fair-play, FAQ

Les cartes reproduisent `CarCard.tsx` de l'appli. Les noms de voitures servent à identifier des modèles réels ; StreetCaught n'est affilié à aucun constructeur.
