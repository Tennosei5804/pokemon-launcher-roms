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

Les anciens fichiers GB, GBC, GBA et NDS sont conservés. L'ajout des nouvelles archives à la release ne configure pas automatiquement leur présence dans le catalogue du launcher ni le téléchargement et la reconstitution des archives découpées. Les fichiers restaurés peuvent être importés dans un logiciel compatible.
