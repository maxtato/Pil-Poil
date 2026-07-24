# Pil Poil 🟡

**Tape pile poil.** Un jeu de timing : un chrono démarre, à toi de taper exactement à la cible — à la seconde, au dixième, puis au centième près.

Le jeu tient dans un seul fichier : ouvre `index.html` dans un navigateur, sur mobile ou sur ordinateur (Espace/Entrée fonctionnent aussi).

## Modes de jeu

| Mode | Principe |
|---|---|
| **Campagne** | 16 niveaux à difficulté croissante : plusieurs taps enchaînés, chrono qui s'efface, cibles révélées au dernier moment… 4 défis de départ (Facile, Normal, Difficile, Wanda). |
| **Survie** | 3 vies, la difficulté grimpe à chaque manche réussie, sans plafond : au-delà du niveau 16, la fenêtre de tolérance continue de fondre. Record sauvegardé. |
| **Entraînement** | Une cible au choix (1 à 10 s), répétée sans fin, avec suivi de ta moyenne et de ton meilleur écart. |
| **Duel** | 2 à 4 joueurs sur le même appareil, chacun son tour, mêmes règles pour tous. |

## Nouveautés de la v12

- **Mode Survie** : 3 vies, difficulté sans plafond, record de score et de manche sauvegardé.
- **Séries** : en campagne et en survie, les excellents (≤ 100 ms) enchaînés gonflent le gain de +5 % par étage, jusqu'à +50 %. Le multiplicateur s'affiche sur le gain (« +1 234 ×3 »).
- **Succès** : 10 badges à débloquer (Pile Poil, Millimétré, En Fusion, Survivant…), avec notification en jeu et écran dédié dans Paramètres → Succès.

## Logo

Le logo officiel vit dans `assets/` en ultra haute définition (5628×4624, fond transparent) :
`logo-hd.png` (lettres noires, fonds clairs) et `logo-hd-nuit.png` (lettres blanches, fonds sombres).
Le jeu embarque des versions WebP allégées et choisit automatiquement la bonne selon le thème.

## Historique

- **v12.5** — refonte complète des 10 thèmes d'après la seconde planche : dix identités réellement distinctes (Blanc, Lilas, Menthe, Azur, Soleil, Rose, Corail bicolore, Encre, Abysse, Marine), bâties sur de grandes formes pleines qui débordent du cadre (cercles massifs, vagues, capsules, quarts de cercle) et des signes discrets (grilles de points, cercles creux, traits fins).

- **v12.4** — logo bitmap officiel : détouré précisément du fond blanc, upscalé en très haute définition, variante nuit générée (lettres blanches, contre-formes transparentes), intégré au jeu avec bascule automatique selon le thème.
- **v12.3** — règle de texte unifiée (noir sur fond clair ou pastel, blanc sur couleur franche) ; les étoiles de résultats et emblèmes or restent d'un jaune vif fixe.
- **v12.2** — chaque thème a sa mise en scène propre, inspirée des maquettes : gerbes d'éclats autour de l'objectif, double anneau et tirets autour du bouton, trames de points en coin, halos, vagues, lune et étoiles.
- **v12.1** — contrastes retravaillés et mesurés (accents, or adaptatif, pastilles de bilan).
- **v12** — mode Survie, séries (combo), succès.
- **v11** — campagne par paliers de score (10 essais par niveau), duel, entraînement, 10 thèmes, sauvegarde de la progression.
