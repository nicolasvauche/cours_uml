# Correction de l'Exercice : Diagramme de Classes pour un système de gestion de bibliothèque

## Identification des Classes Principales
- **Livre :** Représente les livres disponibles dans la bibliothèque.
- **Auteur :** Représente les auteurs des livres.
- **Emprunteur :** Représente les utilisateurs de la bibliothèque qui empruntent des livres.
- **Emprunt :** Représente les informations spécifiques sur les livres empruntés par les emprunteurs.

## Définition des Attributs et Méthodes
### Livre
- Attributs : titre, auteur, ISBN, disponible
- Méthodes : emprunter(), rendre()

### Auteur
- Attributs : nom, biographie, listeLivres
- Méthodes : ajouterLivre(), obtenirBiographie()

### Emprunteur
- Attributs : nom, adresse, listeEmprunts
- Méthodes : emprunterLivre(), rendreLivre()

### Emprunt
- Attributs : livre, dateEmprunt, dateRetour
- Méthodes : verifierDateRetour(), calculerRetard()

## Établissement des Relations
### Association
- Entre Emprunteur et Emprunt : Un emprunteur peut avoir plusieurs emprunts.

### Héritage
L'héritage entre Livre et Auteur n'est pas approprié, car ils représentent des concepts distincts. Au lieu de l'héritage, une association ou agrégation peut être utilisée pour lier Livre et Auteur.

### Composition ou Agrégation
- Entre Auteur et Livre : Un auteur peut avoir plusieurs livres, mais les livres peuvent exister sans être associés à un auteur dans le système (par exemple, si l'auteur est inconnu).
