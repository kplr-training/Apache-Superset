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
