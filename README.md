# Skyjo Score

Application web légère en **un seul `index.html`** pour compter les points pendant une partie de Skyjo.

## Fonctionnalités

- sélection de joueurs enregistrés localement ;
- ajout et suppression de joueurs ;
- lancement d'une partie avec les joueurs sélectionnés ;
- saisie des scores manche par manche ;
- prise en charge des scores négatifs ;
- classement automatique en temps réel ;
- historique des manches ;
- suppression d'une manche avec recalcul des totaux ;
- sauvegarde automatique dans le navigateur via `localStorage` ;
- reprise d'une partie en cours ;
- écran final avec classement et revanche.

## Structure du projet

```text
.
├── index.html
└── README.md
```

Aucune dépendance externe n'est nécessaire.

## Utilisation locale

Il suffit d'ouvrir `index.html` dans un navigateur moderne.

## Déploiement GitHub Pages

Le projet peut être publié très simplement avec GitHub Pages.

1. Aller dans `Settings` du dépôt.
2. Ouvrir `Pages`.
3. Choisir `Deploy from a branch`.
4. Sélectionner la branche `main` et le dossier `/ (root)`.
5. Enregistrer.

L'application sera alors servie directement depuis GitHub Pages.

## Direction artistique

L'interface adopte une **direction artistique originale inspirée d'un univers de cartes et de table de jeu**, afin d'évoquer l'ambiance de Skyjo tout en conservant une identité propre à l'application.

Par défaut, le dépôt **n'intègre pas d'assets officiels** du jeu. Si vous disposez de visuels que vous êtes autorisé à utiliser, vous pouvez les ajouter ensuite dans un dossier `assets/` et les intégrer au fond de l'interface.

## Stockage

Les données sont stockées localement dans le navigateur de l'utilisateur. Aucune base de données ni aucun serveur ne sont requis pour cette version.
