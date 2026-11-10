# Garage 1.4

PWA personnelle de suivi d'entretien multi-véhicules.

## Nouveautés 1.4
- Historique modifiable : toucher une intervention pour la corriger, ajouter ou retirer une facture, ou la supprimer.

## Nouveautés 1.3
- Connexion Google Drive par redirection (fiable en PWA installée).
- Sauvegarde automatique dans l'appDataFolder privé (scope drive.appdata), 2,5 s après chaque modification.
- Envoi sans limite de taille (factures/photos).
- Sur un nouvel appareil, une sauvegarde Drive existante est récupérée, jamais écrasée.
- Modifications conservées localement et renvoyées si la session Google expire.
- Le service worker ne met plus en cache les échanges Google.

## Prérequis Google Cloud
URI de redirection autorisé du client OAuth : https://moutonremi-47.github.io/garage/
