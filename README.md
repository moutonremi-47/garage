# Garage V1 - lot fonctionnel initial

PWA personnelle de suivi d’entretien automobile.

## Inclus
- PWA installable et utilisable hors ligne
- Plusieurs véhicules
- Historique des kilométrages
- Interventions et coûts
- Échéances par date, kilométrage, ou les deux
- Statuts OK / à prévoir / en retard
- Export et restauration JSON
- Export CSV des entretiens
- Stockage local IndexedDB

## Publication GitHub Pages
1. Créer un dépôt GitHub, par exemple `garage`.
2. Décompresser tous les fichiers à la racine du dépôt.
3. Dans Settings > Pages, choisir `Deploy from a branch`, branche `main`, dossier `/root`.
4. Ouvrir l’URL GitHub Pages puis utiliser « Ajouter à l’écran d’accueil ».

## Important
Cette première livraison n’intègre pas encore Google Drive, les factures binaires, les dépenses séparées ni le carburant. Elle pose le socle de données et le parcours véhicule / kilométrage / entretien / échéance / sauvegarde. Ne stockez pas de secret GitHub ou Google dans le code.
