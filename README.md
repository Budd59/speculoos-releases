# Speculoos — Binaires

Ce dépôt public héberge uniquement les fichiers `.jar` compilés des mods Speculoos (Minecraft 26.1.2, NeoForge 26.1.2.65-beta / Fabric loader 0.19.1). Le code source reste privé.

## Modules

| Module | Rôle |
|--------|------|
| `speculoos-core` | Bibliothèque partagée (requise par tous les autres) |
| `speculoos-rotation` | Dalles/escaliers avec placement vertical |
| `speculoos-plus` | Redstone chain / relay / lantern |
| `speculoos-offset` | Walls/fences/torches/lanternes/chaînes/relais avec footprint décalé (dépend de `core` et `plus`) |

## Installation

Téléchargez, pour votre modloader (Fabric **ou** NeoForge — ne pas mélanger), le jar de chaque module dont vous avez besoin depuis l'onglet [Releases](../../releases), et placez-les tous dans votre dossier `mods/`. `speculoos-offset` nécessite `speculoos-core` **et** `speculoos-plus` ; `speculoos-rotation` nécessite `speculoos-core`.
