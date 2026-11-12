# Wiki Moulinette

Site statique autonome : ouvrir `index.html` directement, ou publier ce dossier tel quel sur GitHub Pages. Aucune dépendance nécessaire pour consulter le site.

## Publication GitHub Pages

1. Pousser la branche `main` vers `git@github.com:ImMiza/moulinette-wiki.github.io.git` (déjà configuré comme `origin`).
2. Dans **Settings → Pages → Build and deployment**, choisir **Deploy from a branch**, puis `main` et `/ (root)`.
3. Le site sera accessible à `https://immiza.github.io/moulinette-wiki.github.io/`.

Garder `.nojekyll` : GitHub Pages doit servir le dossier `_astro/` contenant les styles et scripts. Conserver tous les fichiers et dossiers, pas seulement `index.html`.

Pour actualiser le site, regénérer `game/wiki/static/` dans le dépôt du jeu, puis recopier son contenu ici avant de pousser les mises à jour. Ce dépôt ne contient que l'export, pas les sources du générateur.
