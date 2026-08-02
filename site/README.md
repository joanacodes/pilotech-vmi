# Pilotech-VMI — Site Web

Site vitrine statique (HTML + Tailwind CSS via CDN) pour Pilotech-VMI, installateur de VMC/VMI en Île-de-France.

## Structure du projet

```
.
├── index.html          Accueil
├── a-propos.html        À propos
├── gammes.html           Catalogue des 7 gammes VMI
├── pro-1000.html         Fiche produit Pro 1000
├── cube.html             Fiche produit Cube
├── urban-2.html          Fiche produit Urban 2
├── purevent.html         Fiche produit Purevent
├── cave.html             Fiche produit Cave
├── wally.html            Fiche produit Wally
├── lofty.html            Fiche produit Lofty
├── blog.html             Blog
├── blog-article.html     Exemple d'article de blog
└── images/               Photos produits réelles (7 fichiers)
```

Chaque page partage le même **header/menu** et **footer**, avec surlignage du lien actif dans la navigation.

## Déploiement sur GitHub Pages

1. Poussez ce dossier tel quel sur un dépôt GitHub (à la racine, ou dans un dossier `docs/`).
2. Dans les paramètres du dépôt → **Pages**, choisissez la branche et le dossier racine (`/` ou `/docs`).
3. Le site sera servi automatiquement sur `https://<votre-compte>.github.io/<nom-du-repo>/`.

Aucune étape de build n'est nécessaire : les pages sont du HTML statique, Tailwind CSS et Font Awesome sont chargés depuis un CDN.

## Notes de reconstruction

- Le contenu (copywriting) de chaque page provient tel quel des maquettes HTML fournies.
- Les 7 vraies photos produits fournies (`images/`) ont été intégrées automatiquement sur : leur page produit dédiée, les carrousels "gammes" présents sur chaque page produit, le catalogue `gammes.html`, et en partie sur la page d'accueil (galerie réalisations + grille "Nos VMC").
- Les autres visuels (à propos, blog, sections génériques de l'accueil) n'avaient pas d'équivalent réel fourni : ils utilisent des photos de secours fiables (Unsplash) à la place des liens d'aperçu temporaires de l'outil de maquettage d'origine, qui ne fonctionnaient plus.
- La page `wally.html` avait une section "Témoignages" tronquée dans le fichier source fourni ; elle a été complétée avec le bloc de témoignages identique utilisé sur les autres pages produits (même gabarit, même texte).
- Quelques témoignages clients mentionnent encore "Toshiba" (résidu du copywriting d'origine) : conservé tel quel conformément à la consigne de ne pas modifier le texte fourni.
