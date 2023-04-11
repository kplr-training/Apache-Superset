# Analyse et visualisation de Flight Data :

## Visualisation 7 : Retard moyen des vols par aéroport
Cette visualisation montre le retard moyen des vols pour chaque aéroport.

- Sélectionner le type de visualisation Bar Chart.
- Pour le champ Axe X, sélectionnez la colonne ORIGIN_AIRPORT.
- Pour le champ Axe Y, sélectionnez la fonction d'agrégation AVG(DEPARTURE_DELAY).
- Fixez la limite à une valeur appropriée.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/231020750-d51ada53-19ba-4bbd-bea0-a227f6ce550f.png)

## Visualisation 8 : Principales destinations en fonction du nombre de vols
Cette visualisation montre les principales destinations en fonction du nombre de vols.

- Sélectionnez le type de visualisation Table.
- Pour le champ Groupe par, sélectionnez la colonne DESTINATION_AIRPORT.
- Pour le champ Métriques, sélectionnez la fonction d'agrégation COUNT(*).
- Triez les résultats par ordre décroissant .
- Fixez la limite à une valeur appropriée.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/231021336-14579275-6855-45a6-b61c-fa7fc3e56466.png)

## Visualisation 9 : Heat Map du nombre de vols par origine et destination
Cette visualisation montre le nombre de vols entre chaque aéroport d'origine et de destination sous forme de carte thermique.

- Sélectionnez le type de visualisation Heatmap.
- Pour le champ Axe X, sélectionnez la colonne  ORIGIN_AIRPORT.
- Pour le champ Axe Y, sélectionnez la colonne DESTINATION_AIRPORT.
- Pour le champ Métriques, sélectionnez la fonction d'agrégation COUNT(*).
- Configure Row Limit à 10
- En option, vous pouvez ajuster le schéma de couleurs et les paramètres de la légende à votre convenance.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/231126102-6b9d3b55-96b9-4162-9c47-64db39a1af53.png)

## Visualisation 10 :  Bubble chart des retards de vols par compagnie aérienne et par distance
Cette visualisation montre la relation entre le retard des vols et la distance, groupés par compagnie aérienne, sous la forme d'un graphique à bulles.

- Sélectionner le type de visualisation  Bubble chart.
- Pour le champ Entité, sélectionnez la colonne AIRLINE.
- Pour le champ de l'axe X, sélectionnez la colonne DISTANCE et choisissez la fonction d'agrégation AVG.
- Pour le champ de l'axe des Y, sélectionnez la colonne AIR_TIME et choisissez la fonction d'agrégation AVG.
- Pour la zone Bubble Size, sélectionnez la colonne DEPARTURE_DELAY et choisissez la fonction d'agrégation AVG.
- En option, vous pouvez ajouter un filtre pour limiter les données à un intervalle de temps spécifique, ajuster le schéma de couleurs et les paramètres de la légende, et modifier la taille des bulles.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.
![image](https://user-images.githubusercontent.com/123749462/231129990-da6a5dff-7bbb-43b7-b1ff-bcf5319ec136.png)

## Visualisation 11 :  Destinations de vol sur Mapbox : Localisations basées sur des données de longitude et de latitude 

- Dans l'onglet "Query", sélectionnez la colonne "Longitude" pour le champ "Longitude" et la colonne "Latitude" pour le champ "Latitude".
- Personnalisez le style et la couleur des marqueurs comme vous le souhaitez.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/231133649-b275655c-3980-4140-8881-1c11277aeb0b.png)

