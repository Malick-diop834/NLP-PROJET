# 1. Initialiser le dépôt local
git init

# 2. Ajouter tous les fichiers du projet
git add .

# 3. Enregistrer les modifications locales
git commit -m "Initial commit"

# 4. Renommer la branche principale en main
git branch -M main

# 5. Lier le dossier local au dépôt GitHub (remplacez l'URL par la vôtre)
git remote add origin https://github.com/VOTRE_PSEUDO/NOM_DU_DEPOT.git

# 6. Envoyer les fichiers sur GitHub
git push -u origin main
