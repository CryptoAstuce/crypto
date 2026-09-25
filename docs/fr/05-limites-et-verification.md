# Limites et vérification

Le dépôt indique que le développement a migré vers miden-vm ; la branche next reste la référence du fork.
Les changements de domaine ou de Poseidon2 peuvent casser la compatibilité des racines persistées.
Les primitives cryptographiques ne garantissent pas seules la correction du protocole qui les compose.
Les conversions, étiquettes de domaine et formats sérialisés font partie de la surface de sécurité.
Ce parcours repose sur les modules hash, merkle, transcript, rand et aead du code source.
Aucune installation, compilation, fuzzing ou exécution nouvelle n’a été effectuée.
Aucune affirmation de performance mesurée n’est faite ici.
Pour vérifier, consulter les tests, fuzz targets et guides de migration du dépôt Miden VM.
