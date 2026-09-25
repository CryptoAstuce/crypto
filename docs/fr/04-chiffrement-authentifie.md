# Chiffrement authentifié

Le module AEAD fournit confidentialité et authenticité pour des données hors preuve.
XChaCha20Poly1305 privilégie les performances générales et les nonces étendus.
AEAD-Poseidon2 privilégie une exécution efficace à l’intérieur des SNARK et STARK.
Les sealed boxes combinent K256 ou X25519 avec l’un de ces schémas AEAD.
Les messages bytes et les éléments de corps utilisent des interfaces distinctes et non interchangeables.
La clé, le nonce et les données associées doivent suivre une politique explicite de protocole.
L’efficacité arithmétique ne dispense jamais de vérifier authenticité et réutilisation des nonces.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
