# Arbres authentifies

Les structures Merkle representent notes, comptes et etats par une racine compacte.
Une preuve d ouverture reconstruit la racine depuis une feuille et son chemin d authentification.
Les Sparse Merkle Trees adressent un espace de clefs vaste sans materialiser chaque feuille vide.
Les mises a jour doivent recalculer tous les noeuds du chemin avec le domaine correct.
Les versions recentes separent explicitement le hachage des feuilles de celui des noeuds internes.
Un changement de permutation ou de domaine invalide racines, caches et temoins historiques.
La racine n authentifie la semantique d une feuille que si son encodage est non ambigu.

Suite : [04 — Chiffrement authentifie](04-chiffrement-authentifie.md).
