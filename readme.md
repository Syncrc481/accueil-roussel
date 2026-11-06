# Fleurs Roussel

Site vitrine responsive pour Fleurs Roussel, une artisane fleuriste à Vendôme. Il présente les bouquets de la semaine, les engagements de la boutique, les ateliers et les coordonnées de contact.

## Technologies

- HTML5
- Tailwind CSS 4 et son outil en ligne de commande
- Illustrations SVG
- Polices Inter et Playfair Display via Google Fonts

## Prérequis

Installez Node.js et npm sur votre ordinateur.

## Installation et lancement

À la racine du projet, installez les dépendances :

```bash
npm install
```

Lancez la compilation du CSS en mode surveillance :

```bash
npm run dev
```

Ouvrez ensuite `index.html` dans votre navigateur. Laissez la commande active pendant vos modifications : le fichier `dist/output.css` sera mis à jour automatiquement.

## Générer le CSS pour la production

```bash
npm run build
```

Cette commande génère une version minifiée de `dist/output.css`, utilisée par `index.html`.

## Structure du projet

```text
├── index.html        # Contenu de la page
├── src/
│   └── input.css     # Import Tailwind et thème personnalisé
├── dist/
│   └── output.css    # Feuille de style générée
├── img/              # Illustrations et icônes SVG
└── package.json      # Dépendances et commandes npm
```

Les liens « Commander » et « Réserver une place » dirigent vers les coordonnées en bas de page. Le site ne comporte pas de système de commande ou de réservation en ligne.
