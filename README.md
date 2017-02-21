https://gist.github.com/aquelito/8596717

Pour créer un nouveau commit :

- Modifier un fichier en local dans le répertoir de travail où l'on a créer le dossier .git avec la commande
 git init
- Ajouter le fichier dans la staging area avec la commande
 git add [nom_fichier]
- Création d'un nouveau commit avec la commande 
 git commit -m "[description de la modification]"
- Envoie du commit sur le dépôt en ligne sur github
 git push -u [nom_dépot] [nom_branche] 

Dernier ajout : 
Connexion GitHub - Git par SSH ou HTTPS, création d'un dépot distant

HTTPS :
git remote add [nom_dépot] https://github.com/[login]/[nom_dépot].git

SSH :
git remote add [nom_dépot] git@github.com:[login]/[nom_dépot].git
