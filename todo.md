essayer workflow_dispatch lancemet a la main
essayer crontab

exo : 
on : pull request vers main
lire fichier src/version.txt
mettre valeur dans variable
si valeur == autre chose que tata alors :
 mergesuccess
sinon fail

final : 
action en GO qui parse spot.json et qui valide que c'est cohérent
chaque element a les variables qu'il faut au format qu'il faut

si oui, pousse le fichier sur ftp

