# Apache JMeter

## 1. Installation
```
    $ brew install jmeter --with-plugins

```
## 2. Ouvrir Jmeter
```
 $ open /usr/local/bin/jmeter

```
### 3. Ajouter threeds
# 1
Clic droit sur le l’icone d’un ver qui s’apparu dans ,side bare gauche . Add  threads 
threeds groups.
Dans l’interface qui s’apparu remplir les informations obligatoires suivante :
Name :Nom du groupe.
Number of threads (users) : Nombre des utilisateurs
Loop count : nombre de répétition (forever pour une boucle infini) .
# 2 
préparer la requête Clic droit sur votre group créer AddSamplerhttp
Dans l’interface qui s’apparu remplir les information obligatoires suivante :
 Name : Nom de votre test
 Protocol : si vide http est par default
 Server Name or IP : l’adresse ip
 Port : le port
Path : end point du page a tester l’acces a elle
Advanced implémentation : HttpClient4
# 3 
Visualisation des résultat de test :
Click droit sur votre Test  Add  listner > puis vous choisissez 1 ou plusieurs format de
visualisation
# 4 
pour démarrer cliquer sur le bouton de démarrer , pour supprimer tous l’historique de test
cliquer sur clear resut ,pour arrêter un test en cour cliquer stop .

