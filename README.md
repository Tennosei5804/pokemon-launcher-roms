# pokemon-launcher-roms

Dépôt privé des ROMs pour Pokémon Launcher, sur le compte **Tennosei5804**.

## Où sont les fichiers ?

Les ROMs sont jointes à la **[release `roms`](https://github.com/Tennosei5804/pokemon-launcher-roms/releases/tag/roms)**. Elles ne sont pas stockées dans l'arborescence du code. Ouvrez la release et développez la section **Assets** pour les retrouver.

Il faut être connecté au compte Tennosei5804 ou à un compte autorisé sur ce dépôt privé.

## Archives 3DS et Switch

Les fichiers du dossier `Rom` sont conservés dans des archives ZIP, découpées en parties de 1 900 Mio maximum. Le nom d'origine et le contenu exact des fichiers sont conservés. Une archive composée d'une seule partie porte également le suffixe `.zip.001`.

- Téléchargez **toutes les parties d'un même jeu**, puis ouvrez sa première partie `.zip.001` avec 7-Zip pour extraire le fichier d'origine.
- Pour vérifier et restaurer les fichiers avec Python, téléchargez aussi le [manifeste](https://github.com/Tennosei5804/pokemon-launcher-roms/releases/download/roms/roms-3ds-switch-manifest.json) et le [script de restauration](https://github.com/Tennosei5804/pokemon-launcher-roms/releases/download/roms/restaurer-roms.py).
- Les [instructions détaillées](https://github.com/Tennosei5804/pokemon-launcher-roms/releases/download/roms/LIRE-MOI-roms-3ds-switch.md) expliquent les deux méthodes.

Le manifeste recense les fichiers d'origine, leurs tailles et leurs empreintes SHA-256, ainsi que les parties nécessaires à leur restauration. Chaque partie envoyée est vérifiée avec l'empreinte fournie par GitHub.

## Utilisation dans le launcher

Le catalogue du launcher comprend les 31 jeux et la mise à jour de Z-A. Les archives 3DS/Switch sont téléchargées, vérifiées et extraites automatiquement. Pour Z-A, le menu propose le téléchargement simultané du jeu et de sa mise à jour 2.0.2.

## Mods 60 FPS

Les sept packs sélectionnés sont dans la [release `mods-60fps`](https://github.com/Tennosei5804/pokemon-launcher-roms/releases/tag/mods-60fps), accompagnés de leur manifeste et des crédits de Fl4sh9174. Les fichiers des jeux restent dans la release `roms`.

Dans le launcher 0.9.2, ouvrir **⋯ → Mods 60 FPS**, puis **Télécharger le mod** ou **Télécharger et activer J1/J2**. La désactivation conserve les autres mods et les sauvegardes. Les téléchargements utilisent la session GitHub CLI autorisée sur ce dépôt.

Les versions ciblées et l'identifiant de compilation doivent correspondre au jeu lancé. Épée/Bouclier sont proposés comme expérimentaux ; leur pack est distinct du patch complet KM-Editor. Les performances à 60 FPS restent dépendantes du jeu et du PC.
