# Analyse et visualisation de Flight Data :

- Aller sur Datasets : 

![image](https://user-images.githubusercontent.com/123749462/230634813-2cd6920b-2cd1-4719-867b-2450f4c51466.png)

- Cliquer sur la base de donées flights :

![image](https://user-images.githubusercontent.com/123749462/230635653-6784e4a5-86fa-47d9-b3d5-8faf31767e6d.png)

- Voilà à quoi ressemble l'interface où vous pouvez créer vos visualisations de la data flight :

![image](https://user-images.githubusercontent.com/123749462/230751632-05f0a951-c25f-4115-a26e-52c1bd5ecf1b.png)

## Visualisation 1 : Nombre de vols par compagnie aérienne
Cette visualisation montre le nombre de vols pour chaque compagnie aérienne.

- Sélectionner le type de visualisation Bar Chart.
- Pour le champ Axe X(Dimensions), sélectionnez la colonne AIRLINE.
- Pour le champ de l'axe Y(Metrics), sélectionnez la fonction d'agrégation COUNT(*).
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/230803352-d8cf650c-148f-46d0-b57e-54e795777d46.png)

## Visualisation 2 : Retard moyen à l'arrivée par compagnie aérienne
Cette visualisation montre le retard moyen à l'arrivée pour chaque compagnie aérienne.

- Sélectionnez le type de visualisation Bar Chart.
- Remplir les champs obligatoires, y compris le titre du graphique et la source des données.
- Pour le champ Axe X(Dimensions), sélectionnez la colonne AIRLINE.
- Pour le champ de l'axe Y(Metrics), sélectionnez la fonction d'agrégation AVG(ARRIVAL_DELAY).
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/230936017-70dc86d6-e3c3-4f66-92a5-da95c536d388.png)

## Visualisation 3 : Nombre de vols par jour de la semaine

Cette visualisation montre le nombre de vols pour chaque jour de la semaine.

- Sélectionnez le type de visualisation Bar Chart.
- Pour le champ Axe X, sélectionnez la colonne DAY_OF_WEEK.
- Pour le champ Axe Y, sélectionnez la fonction d'agrégation COUNT(*).
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.


![image](https://user-images.githubusercontent.com/123749462/230937035-d37cc995-9df7-4e5e-b19d-d043380a56d9.png)

## Visualisation 4 : Pourcentage de vols annulés par compagnie aérienne
Cette visualisation montre le pourcentage de vols annulés pour chaque compagnie aérienne.


- Sélectionner le type de visualisation Pie Chart.
- Remplir les champs obligatoires, y compris le titre du graphique et la source de données.
- Pour le champ Dimensions, sélectionnez la colonne AIRLINE.
- Pour le champ Metrics, sélectionnez l'expression SUM(CANCELLED).
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.

![image](https://user-images.githubusercontent.com/123749462/230939429-61daeff3-399e-4006-a0c0-08e5a4458a18.png)

## Visualisation 5 : Distribution des retards au départ
Cette visualisation montre la distribution des retards au départ.

- Sélectionner le type de visualisation Histogramme.
- Dans le champ Colonnes, sélectionnez la colonne DEPARTURE_DELAY.
- Cliquez sur le bouton Exécuter la requête pour générer la visualisation.
![image](https://user-images.githubusercontent.com/123749462/231005320-a417f766-d837-444a-a1ac-dcfadb8aee17.png)

