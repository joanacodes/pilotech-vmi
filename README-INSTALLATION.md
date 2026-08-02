# Pilotech-VMI — Blog Jekyll final

Ce package contient les 21 articles, leurs 21 images héro, le layout d’article,
l’index dynamique du blog, la configuration Jekyll et les dépendances Windows.

## Installation

Sur la branche `content/jekyll-21-vmc-articles`, copiez le contenu de ce ZIP
à la racine du dépôt en acceptant le remplacement des fichiers existants.

Puis exécutez :

```powershell
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

Prévisualisation : `http://127.0.0.1:4000/blog/`

Après validation :

```powershell
git add .
git commit -m "Complete Jekyll blog with 21 SEO articles and hero images"
git push

git switch main
git pull
git merge content/jekyll-21-vmc-articles
git push
```

Le blog sera publié à `https://pilotech-vmi.fr/blog/` après le déploiement GitHub Pages.
