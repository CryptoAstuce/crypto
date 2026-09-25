# Hachages algébriques

Un hachage adapté au corps minimise le nombre de contraintes imposées au prouveur.
RPO est construit pour la récursion STARK et travaille naturellement sur des éléments du corps.
RPX vise une évaluation plus rapide tout en conservant une interface de digest comparable.
Poseidon2 fournit une permutation récente réutilisée par le transcript et le générateur aléatoire.
Les variantes tronquées de BLAKE3 changent la taille de sortie mais pas l’algorithme source.
Une conversion bytes vers éléments de corps doit fixer ordre, longueur et encodage canonique.
Mélanger digests ou domaines sans étiquette explicite fragilise la liaison au contexte.

Suite : [03 — Arbres authentifiés](03-arbres-authentifies.md).
