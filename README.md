# Application Gantt


## Objectifs

Développez une application pour mobile permettant de gérer un projet selon 
la méthode de gantt. Cette application devra bien évidemment être adaptée
aux périphériques mobiles et répondre aux règles d'accessibilité web.

Vous utiliserez pour cela le framework Cordova. Aucune technologie n'est 
proscrite cette fois-ci, choisissez en fonction de vos appétences, ou plus 
judicieusement selon des critères de compatibilité et d'adéquation avec 
le projet :  VueJS, React, Angular, Bootstrap CSS, Framework7...

## Version 1

La première version du programme n'inclut qu'un formulaire permettant 
d'enregistrer une tâche (nom, date de début, durée) sur le téléphone. Les 
données seront stockées dans [le système de base de données fournis par Cordova](https://cordova.apache.org/docs/fr/latest/cordova/storage/database/database.html)

Pour cela, vous devez impérativement créer un script SQL de création de la 
base de données.

## Version 2

La seconde version permet en plus d'afficher la liste des tâches enregistrées 
dans la base de données

## Version 3

La troisème évolution du programme prend en compte les spécificités du [réseau PERT](https://fr.wikipedia.org/wiki/PERT), notamment les dépendances des tâches entre-elles.

## Attendus

- le **code source en version 2** MINIMUM, **commenté** et versionné sur un **dépôt Github**,
  avec un fichier **README.md** expliquant l'installation et l'exécution du programme
- les **maquettes** du projet seront incluses au dépôt
- le dépôt nous sera **fournis via Slack**

## Grille d'évaluation

| Critère de succès                                            | Compétence | Succès (oui/non) |
|:------------------------------------------------------------:|:----------:|:----------------:|
|Le lien vers le dépôt est fourni via Slack                    |     0      |       [  ]       |
|Le code source est en version 2 minimum                       |     0      |       [  ]       |
|Le code source est versionné                                  |     0      |       [  ]       |
|Le fichier README décrit la procédure d'installation          |     0      |       [  ]       |
|Le fichier README décrit la procédure d'exécution             |     0      |       [  ]       |
|Les maquettes correspondent aux spécificités fonctionnelles   |     1      |       [  ]       |
|Les maquettes incluent un diagramme d'enchainement des écrans |     1      |       [  ]       |
|L'interface est conforme aux maquettes                        |     2      |       [  ]       |
|Les pages web s'adaptent à la taille de l'écran               |     2      |       [  ]       |
|Les pages web sont optimisées pour le mobile                  |     2      |       [  ]       |
|La documentation technique est présente                       |     2      |       [  ]       |
|Le programme est fonctionnel                                  |     3      |       [  ]       |
|Le code source est documenté ou auto-documenté                |     3,6    |       [  ]       |
|L'accès aux données utilise les mécanismes de sécurité du SGBD|     6      |       [  ]       |
|Connaissance du langage de requête de type SQL                |     6      |       [  ]       |


### Détail des compétences mises en oeuvre 

- 0 : prérequis. Sans ces points validés, les autres critères ne sont pas évalués
- 1 : Maquetter une application
- 2 : Réaliser une interface utilisateur web statique et adaptable
- 3 : Développer une interface utilisateur web dynamique
- 6 : Développer les composants d’accès aux données
