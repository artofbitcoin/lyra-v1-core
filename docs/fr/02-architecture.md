# 2. Architecture d’un marché d’options

Le cœur de Lyra sépare OptionMarket, LiquidityPool, OptionGreekCache et les adaptateurs d’échange. OptionMarket reçoit les paramètres de transaction et coordonne l’ouverture, la fermeture, la réclamation et le règlement des positions.

LiquidityPool fournit le collatéral et la liquidité nécessaires aux positions. Les composants de couverture relient le risque du pool à des venues externes, tandis que les adaptateurs isolent les différences entre Synthetix, GMX et les environnements de test.

OptionGreekCache maintient les valeurs nécessaires à la tarification : volatilité, delta, vega et autres expositions. Le dépôt contient aussi des bibliothèques BlackScholes et GWAV qui matérialisent les calculs et les moyennes pondérées dans le temps.

Suite : [ouvrir et fermer une position](03-positions.md).
