
Commande pour reinitialiser le repertoir distant github a la creation d'un nouveau projet



# Initialiser depo 
 - aller sur la racine du projet dans terminal
 - s'assurer d'ajouter les exception pour les fichier .env et /node_modules sur le fichier  .gitignore

# Commandes
# Annuler un git init
rmdir /s .git
# Créer un nouveau depo
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/rachid-adf/My-seed.git
git push origin master
