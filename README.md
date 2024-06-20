# Run script 

## Ouvrir un noeud 
```bash
qrsh

## Exécuter un script 
```bash
sh nomscript

## Modifier un script
```bash
vi nomscript
puis pour enregistrer CTRL+c :wq! [enter]

Lire un script 
```cat nomscript


Soumettre un job sur le cluster CQLS-OSU
```bash
SGE_Batch -c "./nomscript -parameters" -P 1 -q bpp -r nomjob


# Mon Projet

## Introduction

Bienvenue dans mon projet. Ce projet démontre comment afficher des blocs de code dans un document sur GitHub.

## Exemple de Code

Voici un exemple de fonction en Python :

```python
def hello_world():
    print("Hello, world!")

hello_world()
