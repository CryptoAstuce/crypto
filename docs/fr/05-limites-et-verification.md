# Limites et verification

Le depot indique que le developpement a migre vers miden-vm ; la branche next reste la reference du fork.
Les changements de domaine ou de Poseidon2 peuvent casser la compatibilite des racines persistees.
Les primitives cryptographiques ne garantissent pas seules la correction du protocole qui les compose.
Les conversions, etiquettes de domaine et formats serialises font partie de la surface de securite.
Ce parcours repose sur les modules hash, merkle, transcript, rand et aead du code source.
Aucune installation, compilation, fuzzing ou execution nouvelle n a ete effectuee.
Aucune affirmation de performance mesuree n est faite ici.
Pour verifier, consulter les tests, fuzz targets et guides de migration du depot Miden VM.
