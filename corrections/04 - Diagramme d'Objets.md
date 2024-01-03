# Correction de l'Exercice : Diagramme d'Objets pour un emprunt de livre dans une bibliothèque

## Scénario Spécifique
Imaginons le scénario où un emprunteur, Jean Dupont, emprunte le livre "Les Misérables" de Victor Hugo.

## Objets Spécifiques et Leur État

### Livre
- Instance : Livre1
- Attributs :
  - titre = 'Les Misérables'
  - auteur = 'Victor Hugo'
  - ISBN = '123-456789'
  - disponible = False (indiquant que le livre est emprunté)

### Auteur
- Instance : Auteur1
- Attributs :
  - nom = 'Victor Hugo'
  - biographie = 'Écrivain français du XIXe siècle...'

### Emprunteur
- Instance : Emprunteur1
- Attributs :
  - nom = 'Jean Dupont'
  - adresse = '123 Rue de la Paix'

### Emprunt
- Instance : Emprunt1
- Attributs :
  - livre = Livre1 (référence à l'instance du livre)
  - dateEmprunt = '01/01/2023'
  - dateRetour = '15/01/2023'

## Relations entre Objets
- L'objet Emprunteur1 est lié à l'objet Emprunt1 pour indiquer que Jean Dupont a un emprunt en cours.
- L'objet Emprunt1 est associé à l'objet Livre1 pour montrer que "Les Misérables" est le livre emprunté.
- On pourrait également montrer une association entre Livre1 et Auteur1 pour indiquer que Victor Hugo est l'auteur de "Les Misérables".