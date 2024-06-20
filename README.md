# Run script 

##ouvrir un noeud 
#qrsh

##exécuter un script 
#sh nomscript

##modifier un script
#vi nomscript
#puis pour enregistrer CTRL+c :wq! [enter]

##lire un script 
#cat nomscript


##soumettre un job 
#SGE_Batch -c "./nomscript -parameters" -P 1 -q bpp -r nomjob


# Mon Projet

## Introduction

Bienvenue dans mon projet. Ce projet démontre comment afficher des blocs de code dans un document sur GitHub.

## Exemple de Code

Voici un exemple de fonction en Python :

```python
def hello_world():
    print("Hello, world!")

hello_world()
