---
name: Ajoutez un spot
about: En remplissant le JSON pour le nouveau spot, il sera automatiquement ajouté
title: Ajout d'un spot
labels: addSpot
assignees: ''

---

Modifiez le JSON ci dessous pour que les informations correspondent au nouveau spot a ajouter.

type : plaine OU treuil OU bord-de-mer

si type = bord-de-mer : 
- "tideTableUrl": "Zuydcoote/"

Veillez a retirer les informations non requises, par exemple si le spot n'a pas de période d'interdiction.
excludeDays : 0 = dimanche, 1=lundi ...

# Spot Template a remplir

```
name: La Creche
type: bord-de-mer
localisation: nord
url: https://www.meteoblue.com/fr/meteo/semaine/terlincthun_france_3295326
goodDirection: OSO ONO O
minSpeed: 13
maxSpeed: 23
distance: 132km 1h50mn
geoloc: 50.75035246960507 1.594958234383776
tideTableUrl: https://www.horaire-maree.fr/maree/Wimereux/
excludeDays: 0 1
monthsToExcludes: 8 9 10
description: Fermeture de janvier a fin aout
balise: 
ffvl: https://federation.ffvl.fr/terrain/740
youtube: https://www.youtube.com/watch?v=L3AfTOjkCpU
``` 

# Fin spot template
