# Primitives du rollup Miden

Miden Crypto regroupe les primitives partagées par le rollup et sa machine virtuelle.
Les fonctions de hachage algébriques réduisent le coût d’arithmétisation dans les preuves STARK.
RPO, RPX et Poseidon2 produisent des digests de 256 bits avec des compromis différents.
BLAKE3 et Keccak256 restent utiles aux frontières avec des protocoles externes.
Les arbres de Merkle engagent de grands états tout en permettant des ouvertures locales.
Le transcript transforme les messages du protocole en challenges non interactifs.
Chaque primitive doit être domaine-séparée selon son rôle dans le protocole.

Suite : [02 — Hachages algébriques](02-hachages-algebriques.md).
