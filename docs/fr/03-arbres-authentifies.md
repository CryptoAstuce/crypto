# Arbres authentifiés

Les structures Merkle représentent notes, comptes et états par une racine compacte.
Une preuve d’ouverture reconstruit la racine depuis une feuille et son chemin d’authentification.
Les Sparse Merkle Trees adressent un espace de clefs vaste sans matérialiser chaque feuille vide.
Les mises à jour doivent recalculer tous les nœuds du chemin avec le domaine correct.
Les versions récentes séparent explicitement le hachage des feuilles de celui des nœuds internes.
Un changement de permutation ou de domaine invalide racines, caches et témoins historiques.
La racine n’authentifie la sémantique d’une feuille que si son encodage est non ambigu.

Suite : [04 — Chiffrement authentifié](04-chiffrement-authentifie.md).
