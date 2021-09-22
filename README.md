# Vérifier que git est installé:
git -v
\
git version  

# Vérifier si un utilisateur est configuré:
git config --list
\
git config 
user.name

\
git config 
user.email


# Configurer utilisateur:
git config --global 
user.name
 "user"
\
git config --global 
user.email
 "
user@email.com
"

# Initialiser repository:
git init

# Commit:
git add .
\
git commit -m "commentaire"
\
git log --oneline                   //afficher liste des commits
\
git log --date=local
\
git checkout commitIdentifiant      //se replacer sur un commit

# Vérifier le statut des fichiers git:
git status 

# Création d'une branche:
git branch                          //indique la branche sur laquelle on se trouve
\
git branch nameOfBranch
\
git checkout nameOfBranch           //se déplacer de branche
\
git checkout -b nameOfBranch        //créer une branche et switcher dessus

# Fusionner (merge):
git checkout master                 //se placer sur la branche master en premier lieu
\
git merge nameOfBranch
\
git branch -d nameOfBranch          // !!!!!! puis SUPPRIMER la branche

# Push:
Ajouter le git remote dans le terminal après avoir créer et récupérer le lien sur le repo 
github.com

\
git push origin master
               
# Pull: 