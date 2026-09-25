# Problemes Solutions

Prototype statique d'une bibliothèque de solutions pratiques aux problèmes du quotidien.

## Contenu

- `index.html` : structure sémantique, SEO de base et interface.
- `style.css` : design responsive, sans framework.
- `script.js` : catalogue des problèmes, recherche, filtres et fiches détaillées.

Le site ne nécessite ni serveur, ni base de données, ni API payante. La police d'interface est chargée depuis Google Fonts, avec des polices de secours si le réseau n'est pas disponible.

## Publier avec GitHub Pages

1. Pousser ces fichiers sur la branche `main` du dépôt GitHub.
2. Ouvrir **Settings > Pages**.
3. Choisir **Deploy from a branch**, puis `main` et `/ (root)`.
4. Enregistrer et attendre la génération de l'adresse publique.

Pour ajouter une fiche, ajouter un objet dans le tableau `problems` de `script.js` avec un identifiant unique, une catégorie, une description, des causes, des étapes et un conseil.