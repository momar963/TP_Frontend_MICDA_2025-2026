# Découverte du Sénégal

**TP Bootstrap — Master MICDA 2025–2026**
**Module : Librairies et Frameworks Frontend**

**Auteur : Momar Gaye**

---

## Présentation

Ce projet est une page d'accueil touristique sur le Sénégal, réalisée à partir d'une capture d'écran fournie dans le cadre du TP. J'ai reproduit la maquette avec **Bootstrap 5.3** (chargé par CDN) et un peu de CSS personnalisé pour les couleurs et l'image de bannière.

La page présente trois destinations (Dakar, le Lac Rose et la Casamance) et s'adapte aux écrans d'ordinateur, de tablette et de téléphone.

## Contenu de la page

- **Barre de navigation** : collée en haut de la page (`sticky-top`), avec un menu qui se transforme en bouton hamburger sur mobile.
- **Bannière d'accueil** : image de paysage en arrière-plan, titre, phrase d'accroche et bouton « Explorer maintenant ».
- **Destinations** : trois cartes colorées (vert, bleu, jaune), chacune avec une photo, un texte et un bouton « En savoir plus ».
- **Atouts du Sénégal** : trois blocs avec icônes — paysages uniques, culture riche, tourisme durable.
- **Pied de page** : mention de copyright et liens vers Facebook, Instagram et YouTube.

## Technologies utilisées

| Technologie | Rôle |
|---|---|
| HTML5 | Structure de la page |
| CSS3 (`css/style.css`) | Couleurs, bannière, cartes, hauteur des images |
| Bootstrap 5.3 (CDN) | Grille, navbar, cartes, boutons, classes utilitaires |
| Bootstrap Icons (CDN) | Icônes de la navbar et des atouts |

## Structure du projet

```
tp-bootstrap-senegal-momar-gaye/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── paysage.jpg
│   ├── dakar.jpg
│   ├── lac-rose.jpg
│   └── casamance.jpg
└── README.md
```

## Lancer le projet

1. Cloner ou télécharger le dépôt.
2. Ouvrir le dossier `tp-bootstrap-senegal-momar-gaye`.
3. Vérifier que le dossier `images/` contient bien les quatre photos.
4. Ouvrir `index.html` dans un navigateur.

Une connexion internet est nécessaire, car Bootstrap et Bootstrap Icons sont chargés depuis un CDN. Aucune installation (Node, npm) n'est requise.

## Ce que j'ai utilisé de Bootstrap

- **Grille** : `container`, `row`, `col-12 col-md-6 col-lg-4` pour passer de 1 à 2 puis 3 colonnes selon la largeur de l'écran.
- **Navbar** : `navbar-expand-lg`, `navbar-toggler` et `collapse` pour le menu mobile.
- **Cartes** : `card`, `card-body` et `h-100` pour des cartes de même hauteur.
- **Boutons** : `btn-primary`, `btn-success`, `btn-warning`.
- **Utilitaires** : espacements (`py-5`, `p-4`, `mb-4`), flexbox (`d-flex`, `gap-3`), texte (`fw-bold`, `text-center`).

## Personnalisation

Le fichier `css/style.css` complète Bootstrap pour :

- définir le bleu foncé de la navbar et du footer ;
- mettre l'image `paysage.jpg` en fond de la bannière ;
- colorer les cartes en vert, bleu et jaune clair ;
- fixer la hauteur des photos avec `object-fit: cover` pour qu'elles restent bien cadrées.

## Remarques

- L'image de bannière a été remplacée par une photo de paysage de mon choix (`paysage.jpg`).
- J'ai été accompagné par Claude (assistant IA d'Anthropic) pour comprendre la structure Bootstrap et organiser le projet.

---

*Projet réalisé par Momar Gaye — Master MICDA, année universitaire 2025–2026.*
