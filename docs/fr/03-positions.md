# 3. Ouverture, fermeture et réclamation

Une position est décrite par un strike, une échéance, un type d’option et une quantité. L’appelant choisit notamment une option long call, long put ou une jambe courte, puis fournit les bornes de coût et de collatéral acceptables.

OptionMarket vérifie les paramètres, calcule le coût et met à jour les soldes du compte. La fermeture suit le chemin inverse et applique les règles de frais, de prix et de collatéral propres au marché.

Après une opération, l’utilisateur peut réclamer les actifs dus. Les tests du dépôt séparent les ouvertures réussies, les ouvertures rejetées, les fermetures et les réclamations, ce qui rend visibles les transitions attendues sans exécuter ces tests dans ce parcours.

Suite : [prix, grecs et expiration](04-prix-expiration.md).
