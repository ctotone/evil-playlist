# JDR Audio Library

Module personnel Foundry VTT pour stocker et réutiliser des playlists audio entre plusieurs mondes.

## Installation locale

1. Fermer Foundry.
2. Copier le dossier `jdr-audio-library` dans :
   - Windows : `%localappdata%/FoundryVTT/Data/modules/`
   - Linux/macOS : dossier User Data Foundry, puis `Data/modules/`
3. Relancer Foundry.
4. Activer le module dans le monde voulu : `Manage Modules`.

## Organisation audio conseillée

Place les fichiers audio dans :

```text
assets/audio/music/
assets/audio/ambience/
assets/audio/sfx/
```

Exemple de chemin utilisable dans Foundry :

```text
modules/jdr-audio-library/assets/audio/ambience/western/saloon-01.ogg
```

## Utilisation des compendiums

Le module déclare cinq compendiums de type Playlist :

- Audio - Western / Deadlands
- Audio - Pirate
- Audio - Horreur / Lovecraft
- Audio - Cyberpunk / Interface
- Soundboard - Bruitages et transitions

Dans Foundry :

1. Crée ou importe tes playlists dans l'onglet Playlists.
2. Va dans l'onglet Compendiums.
3. Déverrouille le compendium cible si nécessaire.
4. Glisse-dépose une playlist dans le compendium.
5. Dans un autre monde, active le module et importe la playlist depuis le compendium.

## Important

Ne partage pas publiquement ce module avec des fichiers audio sous licence si tu n'as pas les droits de redistribution.
Pour GitHub, privilégie un dépôt privé si tu inclus ta bibliothèque audio personnelle.
