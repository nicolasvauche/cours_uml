# Correction de l'Exercice : Diagramme de Cas d'Utilisation pour un Système de Réservation d'Hôtel

## Acteurs Identifiés
- Client : Utilise le système pour réserver, modifier ou annuler des réservations.
- Personnel de l'Hôtel : Gère les réservations et assiste les clients.
- Système de Paiement en Ligne : Gère les transactions financières pour les réservations.

## Cas d'Utilisation
- Disponibilité des Chambres :
  - Acteurs impliqués : Personnel de l'Hôtel
  - Description : Le personnel crée une chambre en renseignant ses dates de disponibilité, le type de chambre et le prix.

- Réservation d'une Chambre :
  - Acteurs impliqués : Client, Système de Paiement en Ligne.
  - Description : Le client sélectionne les dates, le type de chambre et effectue le paiement.

- Annulation d'une Réservation :
  - Acteurs impliqués : Client.
  - Description : Le client annule une réservation existante.

- Paiement en Ligne :
  - Acteurs impliqués : Client, Système de Paiement en Ligne.
  - Description : Le client effectue un paiement pour sa réservation.

## Liens avec les Exigences Fonctionnelles
Chaque cas d'utilisation correspond à une exigence fonctionnelle spécifique du système. :

| **Cas d'Utilisation**               | **Exigences Fonctionnelles**                                                               |
|-------------------------------------|-------------------------------------------------------------------------------------------|
| Disponibilité des Chambres          | Le système doit permettre aux utilisateurs de voir et de sélectionner des chambres pour les réserver en ligne.  |
| Réservation d'une Chambre           | Le système doit permettre aux utilisateurs de réserver des chambres en ligne.              |
| Annulation d'une Réservation        | Le système doit permettre aux utilisateurs d'annuler leurs réservations en ligne.          |
| Paiement en Ligne                    | Le système doit permettre aux utilisateurs de payer leurs réservations en ligne.           |
