# Chiffrement authentifie

Le module AEAD fournit confidentialite et authenticite pour des donnees hors preuve.
XChaCha20Poly1305 privilegie les performances generales et les nonces etendus.
AEAD-Poseidon2 privilegie une execution efficace a l interieur des SNARK et STARK.
Les sealed boxes combinent K256 ou X25519 avec l un de ces schemas AEAD.
Les messages bytes et les elements de corps utilisent des interfaces distinctes et non interchangeables.
La cle, le nonce et les donnees associees doivent suivre une politique explicite de protocole.
L efficacite arithmetique ne dispense jamais de verifier authenticite et reutilisation des nonces.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
