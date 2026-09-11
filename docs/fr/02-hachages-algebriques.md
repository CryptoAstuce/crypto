# Hachages algebriques

Un hachage adapte au corps minimise le nombre de contraintes imposees au prouveur.
RPO est construit pour la recursion STARK et travaille naturellement sur des elements du corps.
RPX vise une evaluation plus rapide tout en conservant une interface de digest comparable.
Poseidon2 fournit une permutation recente reutilisee par le transcript et le generateur aleatoire.
Les variantes tronquees de BLAKE3 changent la taille de sortie mais pas l algorithme source.
Une conversion bytes vers elements de corps doit fixer ordre, longueur et encodage canonique.
Melanger digests ou domaines sans etiquette explicite fragilise la liaison au contexte.

Suite : [03 — Arbres authentifies](03-arbres-authentifies.md).
