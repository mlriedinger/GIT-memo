# memo-git

* Créer un dossier : mkdir
* Activer Git pour un répertoire : git init

# Visualiser les modifications avant de faire un commit

* Visualiser l'état des fichiers avant le commit : git status
* Afficher les modifications qui ont été apportées à un fichier : git diff

# Faire un commit

* Sélectionner les fichiers que l'on veut intégrer au prochain commit : git add <FILENAME> ou git add .
* Soumettre les modifications avec un court message : git commit -m "le contenu du msg"

# Bonne pratique pour faire un commit

* git status
* git add <FILENAME>
* git commit -m "message"

# Historique des commit
* git log
* git log --oneline : affiche l'historique avec un ID court des commits

# Revenir à un commit
* git checkout <IDduCommit> : revenir à un commit
* git HEAD~2 : revenir au deuxième commit avant le HEAD

# Pousser du code sur GitHub
* git remote add origin https://github.com/mlriedinger/CV-exo.git
* git push -u origin master

# Résolution de conflits
Si modification sur la même ligne sur GitHub et en local, Git affiche un message d'erreur au moment de push le local. 
Résolution : 
* faire un git pull pour récupérer les modifications GitHub
* l'IDE affiche le conflit avec le sympbole <<<<<< >>>>>>> 
* choisir de ne conserver que l'un ou l'autre des changements, ou les deux
* faire un commit avec un message de résolution de conflit

# Créer une nouvelle branche
* git checkout -b nomDeLaBranche : pour créer la nouvelle branche et se placer directement dedans

# Fusionner des branches (merge)
Si on a une branche A et qu'on veut la fusionner avec des modifications apportées dans une branche B :
* on se place dans la branche A avec : git checkout A
* on fusionne la branche B avec A : git merge B
* on fait un git push origin A

# Issues
Pour fermer une issue, il faut indiquer "fixes #idIssue" dans le message du commit
