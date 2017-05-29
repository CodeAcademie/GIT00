# Initiation à GIT


## Exercice 1: Git en ligne de commande
* Au sein d'un terminal
* Créer un répertoire **mon-depot**, puis se rendre dans ce repertoire
* Transformer le en dépot git avec la commande **git init**.
* Créer un fichier README dans votre repertoire contenant le contenu suivant :
"Version 1 du fichier README."
* Ajouter le fichier README à l’index de votre dépot git avec la commande **git
add README**.
* Les changements enregistrés à l’index à l’aide de la commande git add sont
mis en attente pour être enregistrés lors du prochain commit. Faire un premier
commit avec la commande **git commit**. La commande ouvre un éditeur de fichier pour obtenir un description brève du commit.
Entrer "Ajout d’un fichier README", puis quitter l'éditeur.
Si tout se passe bien, votre premier commit est enregistré dans votre dépot.
* Apporter une modification `a votre fichier README, par exemple, remplacer
”version 1” par ”version 2”.
* Ajouter de nouveau les changements apportés avec la commande git add
README et sauvegarder les changements en tappant de nouveau la commande
git commit.
* Visualisez l’état de votre dépot git avec la commande gitk

## Exercice 2: Synchroniser plusieurs dépots Git

* Revenir dans le repertoire parent (celui qui contient mon-depot) et créer une
copie du dépot précédent avec la commande **git clone mon-depot depot-de-bob**.
* Se rendre dans **depot-de-bob** et lancer gitk, que constatez vous ?
* Faire un changement dans le fichier README de depot-de-bob. Enregistrer le
changement avec git add README, et git commit. Relancer gitk. Quel est l’état
de depot-de-bob ? de mon-depot ?
* Ajouter un nouveau fichier Test.php quelconque dans mon-depot, l’ajouter à
l’index et le commiter. Retourner dans depot-bob et tapper la commande git
pull. Quitter l’éditeur sans modifier le message et tapper la commande gitk.
Que s’est-il passé ?

## Exercice 3 : Création d'un premier dépot sur GitHub

* Github offre des services de stoquage de dépots git publics.
* Inscrivez vous sur Github et créez votre premir dépot.
* Une fois que vous avez créé le nouveau dépôt, copiez son url et connectez-le à mon-depot en tappant les commandes suivantes **git remote add <nom> <url du depot>** et **git push <nom> master**
* Qu'avez-vous fait ? 

## Exercice 4 : Découverte de GIT et GitHub.
Définir ce que fait les fonctionnalités suivantes : 
* git init
* git log
* git status
* git push
* git remote -v
* git add 
* git rm
* git diff

## Exercice 5 : Lecture et compréhension 
Lire et suivre la documentation suivante : [Git Basics](http://people.irisa.fr/Anthony.Baire/git/git-for-beginners-handout.pdf)


