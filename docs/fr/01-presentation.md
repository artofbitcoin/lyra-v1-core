# 1. Le rôle de Lyra V1

Lyra V1 est un protocole de dérivés et d’options sur chaîne. Le dépôt v1-core regroupe les contrats Solidity, les scripts de déploiement et les suites d’intégration nécessaires pour représenter un marché d’options complet.

Le protocole organise des marchés par actif sous-jacent et actif de cotation. Les utilisateurs peuvent ouvrir des positions longues ou courtes, déposer du collatéral et régler leurs positions lorsque les échéances sont atteintes.

Le dépôt avertit que le SDK est en alpha ouverte et que certains composants, dont GWAVOracle et LyraAdapter, n’étaient pas encore audités dans la version étudiée. Ces limites font partie du périmètre documentaire.

Suite : [l’architecture d’un marché](02-architecture.md).
