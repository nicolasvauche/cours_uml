# Correction de l'exercice : création d'un Diagramme d'État pour le cycle de vie d'une commande dans un système de commerce électronique

## États de la Commande
- "Commande Créée" : État initial après la création de la commande.
- "Paiement Accepté" : Après la confirmation du paiement.
- "Expédiée" : Lorsque la commande est expédiée.
- "Livrée" : Lorsque le client reçoit la commande.
- "Annulée" : Si la commande est annulée à n'importe quel stade.

## Transitions et Événements
- De "Commande Créée" à "Paiement Accepté" : Déclenché par l'événement "paiement réussi".
- De "Paiement Accepté" à "Expédiée" : Déclenché par l'événement "commande expédiée".
- De "Expédiée" à "Livrée" : Déclenché par l'événement "commande livrée".
- Transition possible vers "Annulée" à partir de presque tous les états, déclenchée par l'événement "commande annulée".