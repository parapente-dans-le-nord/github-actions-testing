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
- ajouter `needSeaCheck : true`
- "tideTableUrl": "Zuydcoote/"

Veillez a retirer les informations non requises, par exemple si le spot n'a pas de période d'interdiction.
excludeDays : 0 = dimanche, 1=lundi ...

# Spot Template a remplir

```
{
            "name": "La Creche",
            "type": "bord-de-mer",
            "localisation": "nord",
            "url": "terlincthun_france_3295326",
            "goodDirection": [
                "OSO",
                "O",
                "ONO"
            ],
            "minSpeed": 13,
            "maxSpeed": 23,
            "distance": "132km, 1h50mn",
            "geoloc": "50.75035246960507, 1.594958234383776",
            "needSeaCheck": true,
            "tideTableUrl": "Wimereux/",
            "excludeDays": [
                0,
                1,
                2,
                3,
                4,
                5,
                6
            ],
            "monthsToExcludes": [
                1,
                2,
                3,
                4,
                5,
                6,
                7,
                8
            ],
            "description": "Fermeture de janvier a fin aout",
            "balise": "",
            "ffvl": "https://federation.ffvl.fr/terrain/740",
            "youtube": "https://www.youtube.com/watch?v=L3AfTOjkCpU"
        }
``` 

# Fin spot template
