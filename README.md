# NLP_tweets_vaccins

# Objectif et méthodologie

- L'objectif de notre étude est d'analyser les débats et discussions autour du vaccin contre la Covid-19 en France pour en faire ressortir des tendances. 
- Dans ce cadre nous intéressons au réseau social Twitter. À partir des données de tweets, notre but est de mettre en avant les principaux sujets exprimés en segmentant notre dataset en diffférents grands thèmes. Pour ce faire nous procédons d'abord à une extraction et à un nettoyage de la base de données. Puis nous implémentons une méthode LDA afin de mettre en exergue des groupes de sujets. Enfin nous interprétons les résultats du LDA pour mettre en lumière des conclusions. 

Le plan est donc le suivant : 
#### I) Extraction de données
#### II) Nettoyage des données
#### III) Première analyse et segmentation par LDA
#### IV) Exploration des groupes obtenus via la LDA
#### V) Conclusion et limites

# Organisation

- Le notebook Final_Extraction correspond au code permettant d'extraire des tweets via l'API Twitter. 
- Le notebook NLP_Tweets_Vaccins correspond à l'analyse des tweets
