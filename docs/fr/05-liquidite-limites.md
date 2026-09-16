# 5. Liquidité, couverture et limites

LiquidityPool gère les dépôts et retraits des fournisseurs de liquidité, les frais et la capacité du pool à absorber les paiements. PoolHedger et les adaptateurs de marché servent à réduire l’exposition directionnelle créée par les options vendues.

Les paramètres de taille, de delta, de volatilité et de marge limitent les positions acceptables. Une modification de ces valeurs change directement le profil de risque et doit être lue avec les contrats de configuration et les scripts de déploiement.

Le parcours couvre l’architecture et les flux visibles dans contracts/, test/ et examples/. Il ne déclare aucune installation, compilation ou exécution de test. Les avertissements d’audit présents dans le README restent applicables à la version documentée.

Fin du parcours.
