# Correction de l'Exercice de Création d'un Diagramme d'Activités

## Contexte
Le processus de traitement des commandes dans une entreprise de vente en ligne.

## Étapes du Processus et Éléments du Diagramme

1. **Réception de la Commande**  
L'activité commence par la réception d'une commande de la part du client.

2. **Vérification du Stock (Nœud de Décision)**  
Une fois la commande reçue, le système vérifie la disponibilité du produit en stock.
Représenté par un nœud de décision : si le produit est disponible ou non.

3. **Flux en Cas de Disponibilité**  
Si le produit est en stock :
- Le processus se poursuit avec la préparation de la commande.
- Suivi de l'activité d'expédition de la commande.
- Ces étapes sont connectées séquentiellement par des flèches.

4. **Notification au Client**  
- Une fois la commande expédiée, le client est notifié de l'envoi.
- Cette étape est la dernière activité du processus.

5. **Gestion des Produits Non Disponibles**  
Si le produit n'est pas en stock :
- Le flux diverge vers une activité de notification au client de l'indisponibilité du produit.
- Cette activité est également connectée à un nœud de fin, indiquant la fin du processus pour cette branche.

6. **Barres de Synchronisation**  
Dans ce scénario, les barres de synchronisation peuvent ne pas être nécessaires à moins que certaines activités ne se déroulent en parallèle (par exemple, la préparation de plusieurs commandes simultanément).