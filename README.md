
Commande pour reinitialiser le repertoir distant github a la creation d'un nouveau projet

# Initialiser depo 
 - Aller sur la racine du projet dans terminal
 - S'assurer d'ajouter les exception pour les fichier .env et /node_modules sur le fichier  .gitignore

# Commandes
 - rmdir /s .git             (vide le depo acctuel)
 - git init                  (crée un nouveau depo)
 - git add .
 - git commit -m "Initial commit"
 - git remote add origin https://github.com/rachid-adf/My-seed.git
 - git push origin master
