# Plugins OCEAN — mises à jour

Plugins VST3 perso pour FL Studio (Windows) : **VERBLIFT**, **OCEAN FX 1**, **OCEAN FX 2**, **OCEAN MIX**, **STUTTERVOX**, **OCEAN ASSIST**.

- `installer/` : l'installation de départ (à faire une seule fois, voir le LISEZ-MOI dans le zip).
- `manifest.json` : la dernière version de chaque plugin. Les plugins installés le lisent toutes les 6 h
  et s'installent tout seuls.
- `bin/` : les fichiers des mises à jour. Chacun est signé (Ed25519) : un plugin refuse tout fichier
  qui n'a pas la bonne signature.

Polices : Inter (SIL Open Font License). Cryptographie : Monocypher (BSD-2 / CC0).
