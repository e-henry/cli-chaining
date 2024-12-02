# Reponse kch

## Commande passée

  $ grep ',2001,' sets.csv | sort -u | awk -F ',' '{print "|-------|----------------|"} {print "| " $3 " | " $2 " |"}' >> reponse-kch.md

  ## Résultat

| Année | Nom de la boite |
| ----- | --------------- |
