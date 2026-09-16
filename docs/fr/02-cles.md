# 2. Clés de signature et KeyRegistry

Le KeyRegistry associe à chaque fid des clés publiques et un type de clé. Les clés peuvent être ajoutées, retirées ou migrées selon les règles d’administration. Les événements rendent ces changements indexables et permettent aux clients de reconstruire l’état sans faire confiance à une base centralisée.

Le KeyGateway regroupe les contrôles nécessaires à l’ajout de clés, tandis que le SignedKeyRequestValidator vérifie les métadonnées signées. La séparation entre gestionnaire, registre et passerelle réduit la surface de chaque contrat.

[Chapitre suivant : stockage et loyers](03-stockage.md).
