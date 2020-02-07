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



