# 3. Stockage et loyers

Le StorageRegistry attribue une capacité de stockage à un fid et encaisse le loyer correspondant. Ce découplage permet au protocole de faire respecter les limites de stockage sans mélanger la logique d’identité et la logique économique. Les clients peuvent ainsi distinguer la possession d’un fid de la capacité de données qui lui est accordée.

Les contrats utilisent des réserves et des contrôles d’accès pour limiter les changements sensibles. Les interfaces indiquent les opérations de renouvellement, d’allocation et de retrait à observer dans une intégration.

[Chapitre suivant : récupération et bundling](04-recovery.md).
