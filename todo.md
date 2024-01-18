essayer workflow_dispatch lancemet a la main
essayer crontab

exo : 
on : pull request vers main
lire fichier src/version.txt
mettre valeur dans variable
si valeur == autre chose que tata alors :
 mergesuccess
sinon fail

Action : javascript, parse json output un random
parsing json avec une action javascript
output d'un spot en random version yaml 
step suivant fait un livrable téléchargeable ?

Action : meme que précédente mais en python depuis entrypoint.sh d'un dockerfile

Action : Ajout d'un spot via issue, et/ou modif d'un spot
A la création d'une issue, si elle a le tag qui faut
template create_spot
construire le json, ajouter commiter et faire une PR

Action : validation du spot.json avant merge + test U plus tard + push ftp via secrets
action en GO qui parse spot.json et qui valide que c'est cohérent
chaque element a les variables qu'il faut au format qu'il faut
si oui, pousse le fichier sur ftp

