# Installer Apache Superset :

1- Allez sur https://www.gitpod.io/

2- Essayez de se connecter avec vos comptes Github :

![image](https://user-images.githubusercontent.com/123749462/235998291-8785258a-8679-4ef1-a647-6fc585d701a0.png)

3- Créez un nouveau Workspace :

![image](https://user-images.githubusercontent.com/123749462/236002255-a1b8238e-aa81-4476-87c4-eae7eb05f11f.png)

4- Dans Context URL ; copier et coller cet URL : ```https://github.com/zineb-kplr/Empty-template``` :

![image](https://user-images.githubusercontent.com/123749462/236002642-c7bc8ccc-4abf-4fed-9293-a4671a838d9a.png)

5- Allez dans Extensions et installez Docker si vous ne l'avez pas déjà installé:

![image](https://user-images.githubusercontent.com/123749462/236003043-6ad4d4fb-1f51-47ee-8110-18eb42c0108a.png)

6- Passez au terminal :

![image](https://user-images.githubusercontent.com/123749462/236003884-a0d1f66a-1d34-4b82-8c06-142e93d1d356.png)

7- Clonez le répo de Superset dans votre terminal avec la commande suivante :

 ```
 git clone https://github.com/apache/superset.git
 ```
8- Accédez au dossier que vous avez créé :

 ```
cd superset
 ```
 
 9-  Superset via Docker :
 
 ```
 docker-compose -f docker-compose-non-dev.yml pull
 ```
 
10- Savoir l'URL où vous allez avoir votre UI Apache Superset dans votre Browser :
(Après l'exécution de cette commande copier et coller l'URL que vous allez avoir comme output dans un éditeur de texte)
```
gp url 8088  
```

11- Lancez Superset via Docker :
 
 ```
 docker-compose -f docker-compose-non-dev.yml up
 ```
 
 12- Dans votre Browser coller L'URL que vous avez obtenu dans l'étape 10 : 
 
 ![image](https://user-images.githubusercontent.com/123749462/236005756-f9b5145c-b420-496d-9e00-1ded3da21a45.png)
 
 13- Connectez-vous avec le nom d'utilisateur et le mot de passe par défaut :

```
username: admin
password: admin
```

Et Voilààààààà !!!!!

![image](https://user-images.githubusercontent.com/123749462/236006031-feb600eb-9322-47b6-a0b7-9c4ebeb2fc16.png)
