# 4. Récupération et transactions groupées

Le RecoveryProxy permet à un opérateur autorisé d’engager une récupération de fid selon un processus distinct des opérations courantes. Le système conserve ainsi un chemin de secours sans donner à chaque clé de signature le pouvoir de remplacer le propriétaire.

Le Bundler regroupe des appels vers les gateways et le stockage dans une transaction unique. Cette composition améliore l’expérience d’onboarding et réduit le nombre d’allers-retours côté client, tout en concentrant les vérifications de permissions dans un point d’entrée explicite.

[Chapitre suivant : noms, abonnements et limites](05-limites.md).
