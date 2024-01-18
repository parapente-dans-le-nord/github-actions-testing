essayer workflow_dispatch lancemet a la main
essayer crontab

exo : 
on : pull request vers main
lire fichier src/version.txt
mettre valeur dans variable
si valeur == autre chose que tata alors :
 mergesuccess
sinon fail

parsing json avec une action javascript
output d'un spot en random version yaml 
step suivant fait un livrable téléchargeable ?

A la création d'une issue, si elle a le tag qui faut
template create_spot
construire le json, ajouter commiter et faire une PR


final : 
action en GO qui parse spot.json et qui valide que c'est cohérent
chaque element a les variables qu'il faut au format qu'il faut

si oui, pousse le fichier sur ftp

