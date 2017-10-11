
Commande pour reinitialiser le repertoir distant github a la creation d'un nouveau projet

# annuler un git init
rmdir /s .git

# Initialiser depo 
 - aller sur la racine du projet dans terminal
 - s'assurer d'ajouter les exception sur le fichier  .gitignore

git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/rachid-adf/My-seed.git
git push origin master
