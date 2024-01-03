# Correction de l'Exercice : Diagramme de Séquence pour un scénario de commande en ligne dans un système e-commerce

## Objets/Acteurs Impliqués
- Client
- Système de Commande
- Base de Données
- Système de Paiement

## Scénario Modélisé
Le processus complet depuis le moment où le client passe la commande pourun produit jusqu'à la confirmation du paiement.

## Éléments du Diagramme de Séquence

### Message Initial du Client au Système de Commande
Le client envoie une requête de commande au système.
Représenté par une flèche du Client vers le Système de Commande.

### Interaction du Système de Commande avec la Base de Données
Le Système de Commande vérifie la disponibilité du produit demandé en interrogeant la Base de Données.
Représenté par une flèche allant du Système de Commande vers la Base de Données et vice versa.

### Enregistrement de la Commande
Suite à la confirmation de la disponibilité, le Système de Commande enregistre la commande.
Peut être illustré par une action interne ou une barre d'activation sur la ligne de vie du Système de Commande.

### Demande de Paiement au Système de Paiement
Le Système de Commande envoie une requête de paiement au Système de Paiement.
Représenté par une flèche du Système de Commande vers le Système de Paiement.

### Confirmation de Paiement
Le Système de Paiement traite la demande et renvoie une confirmation de paiement au Client et au Système de Commande.
Illustré par des flèches du Système de Paiement vers le Client et le Système de Commande.