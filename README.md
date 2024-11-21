## Graph Neural Networks

Le jeu de données utilisé dans cette étude est un graphe représentant un réseau d'aéroports, enrichit avec des informations sur les villes correspondantes. Les données sont structurées au format
GraphML, un standard XML pour la représentation de graphes. Le graphe comprend 3363 nœuds, représentant chacun une ville avec un aéroport, et 13547 arêtes, symbolisant probablement les connexions aériennes directes entre ces villes. Chaque nœud du graphe est caractérisé par les attributs suivants :
- Coordonnées géographiques (longitude et latitude)
- Population de la ville
- Pays d'appartenance
- Nom de la ville

L'objectif principal est de développer un modèle de classification capable de prédire le pays d'un nœud en fonction de sa position géographique et de sa connectivité dans le graphe. Ce modèle permettra
d'évaluer dans quelle mesure les caractéristiques locales et les connexions contribuent à déterminer le pays.
