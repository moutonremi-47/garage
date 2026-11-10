# Garage 1.6

PWA personnelle de suivi d'entretien multi-véhicules.

## Nouveautés 1.6
- Échéances modifiables : toucher une échéance pour la corriger ou la supprimer.
- Un formulaire invalide reste ouvert au lieu de se fermer.

## Nouveautés 1.5
- Synchronisation multi-appareils : fusion des données (PC, téléphone…) au lieu d'écraser.
- Relecture de Drive à l'ouverture, au retour sur l'application et toutes les 2 minutes.
- Les suppressions sont propagées aux autres appareils.
- Reconnexion Google automatique quand la session a expiré.
- Numéro de version affiché dans Plus.

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
