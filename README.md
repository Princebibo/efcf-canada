# EFCF Canada — Festival du Film et du Cinéma Égyptien au Canada

Site vitrine trilingue (français par défaut, anglais, arabe avec mise en page RTL).

## Contenu

- `index.html` — le site complet : un seul fichier, sans dépendance ni build.
  Les traductions vivent dans l'objet `I18N` en bas du fichier.
- `assets/logo.png` — *(optionnel)* le logo officiel en image.

## Le logo

Le sceau EFCFC est intégré en SVG vectoriel dans `index.html` (symbole `#efcf-seal`) :
double anneau doré, texte circulaire bilingue, masque pharaonique, pellicules,
feuilles d'érable et lettrage EFCFC.

Pour utiliser le fichier image officiel à la place, déposez-le ici :

    assets/logo.png

Le site le détecte au chargement et remplace automatiquement le sceau vectoriel,
dans l'en-tête comme dans le hero. Aucune modification de code nécessaire.

## Lancer en local

    npx serve .

Puis ouvrir l'adresse affichée.

## Ajouter une langue

1. Ajouter une entrée dans `I18N` (avec `_dir` et `_title`).
2. Ajouter un bouton `<button data-lang="xx">` dans `.langs`.

## Direction

Nour Sobhy & Ahmed Bondok — co-fondateurs et co-présidents.
