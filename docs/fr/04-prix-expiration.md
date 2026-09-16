# 4. Prix, grecs et expiration

La tarification des options dépend de la volatilité, du prix du sous-jacent, du strike, de l’échéance et des paramètres de risque. BlackScholes fournit les formules de base, tandis que OptionGreekCache évite de recalculer inutilement l’exposition de chaque board.

GWAVOracle représente une moyenne géométrique pondérée par le temps. Elle atténue l’effet d’un prix ponctuel dans les calculs qui déterminent la marge et les règlements, mais elle doit rester synchronisée avec les mises à jour de marché.

Lorsqu’un board expire, il doit être réglé avant que les positions individuelles puissent être soldées. Le dépôt décrit aussi la mise à jour des grecs cachés et les contrôles de fraîcheur nécessaires aux dépôts et retraits de liquidité.

Suite : [liquidité, couverture et limites](05-liquidite-limites.md).
