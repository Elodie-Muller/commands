# Run script 

Ouvrir un noeud 
```bash
qrsh
```
Exécuter un script 
```bash
sh nomscript
```
Modifier un script
```bash
vi nomscript
puis pour enregistrer CTRL+c :wq! [enter]
```
Lire un script 
```bash
cat nomscript
```
Soumettre un job sur le cluster CQLS-OSU (sans ouvrir de noeud)
```bash
SGE_Batch -c "./nomscript -parameters" -P 1 -q bpp -r nomjob
```

# 
