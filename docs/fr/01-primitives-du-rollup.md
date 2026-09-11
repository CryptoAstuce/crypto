# Primitives du rollup Miden

Miden Crypto regroupe les primitives partagees par le rollup et sa machine virtuelle.
Les fonctions de hachage algebriques reduisent le cout d arithmetisation dans les preuves STARK.
RPO, RPX et Poseidon2 produisent des digests de 256 bits avec des compromis differents.
BLAKE3 et Keccak256 restent utiles aux frontieres avec des protocoles externes.
Les arbres de Merkle engagent de grands etats tout en permettant des ouvertures locales.
Le transcript transforme les messages du protocole en challenges non interactifs.
Chaque primitive doit etre domaine-separee selon son role dans le protocole.

Suite : [02 — Hachages algebriques](02-hachages-algebriques.md).
