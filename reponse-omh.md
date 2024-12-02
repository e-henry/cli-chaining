


# Réponse OMH


## Commande passée

   $ grep '2021' sets.csv | awk -F',' '{ printf "| %s | %s |\n", $3, $2 }' | sort | uniq | awk 'BEGIN { print "| Année | Nom de la boite |\n|-------|-----------------|" } { print }'


## Résultat
