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

