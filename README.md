# SpaceInvaders
Projet SpaceInvaders


## Semaine n°2: du 6 au 12 Avril
### Sprints et fonctionnalités réalisées
#### Fonctionnalité n°2 : Dimensionner le vaisseau

* Story n°1 : Positionner un nouveau vaisseau avec une dimension donnée <br>
  L'objectif va être de positionner un nouveau vaisseau au sein d'un espace de jeu donnée et refactorer le code pour le rendre plus simple et lisible.

* Story n°2 : Faire en sorte qu'il soit impossible de positionner un nouveau vaisseau qui déborde de l'espace de jeu <br>
  Ici le but sera de faire en sorte qu'une exeption soit levée lors d'un positionnement de vaisseau invalide (hors espace de jeu).

* Story n°3 : Déplacer un vaisseau vers la droite en tenant compte de sa dimension <br>
  L'objectif est de pouvoir déplacer le vaisseau vers la droite en prenant en compte sa position. Si celui-ci est à l'extrémité de l'espace de jeu ou au milieu par exemple.

* Story n°4 : Déplacer un vaisseau vers la gauche en tenant compte de sa dimension <br>
  Story identique à la précédente mais du côté gauche. Puis refactoring important dans presque toutes les classes du jeu. 



Objectif : Déplacer le vaisseau avec une vitesse quelconque
### Diagramme de classes
![Diagramme de classe](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/DiagrammeMetier.gif)

### Nuages de mots
![Nuages de mots](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/nuagesDeMot.png)


## Semaine n°3: du 13 au 18 Avril
### Sprints et fonctionnalités réalisées
#### Fonctionnalité n°3: Choisir la vitesse du vaisseau 

* Story n°1 : Ajouter la vitesse au Vaisseau sans régression de comportement <br>
 On a donc ajouter un attribut (vitesse) à une classe (vaisseau) déjà existante.

* Story n°2 : Régler la vitesse du vaisseau <br>
  Nous avons ajuster la vitesse.

* Story n°3 : Faire en sorte que le déplacement se fasse correctement pour une vitesse quelconque <br>
  On a réadapter les déplacements vers la droite et vers la gauche.

* Story n°4 : Et bien, jouons maintenant ! <br>
  Modification de la classe SpaceInvaders pour qu'elle prenne en compte la vitesse.
  
### Diagramme de classes
![Diagramme de classe](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/DiagrammeMetier2.gif)

### Nuages de mots
![Nuages de mots](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/nuagesDeMot2.png)

  ## Semaine n°4: du 4 au 8 Mai
### Sprints et fonctionnalités réalisées
#### Fonctionnalité n°4: Tirer un missile depuis le vaisseau

* Story n°1 : Comprendre ce qu'est un missile et refactorer <br>
 Définition de certains termes puis refactoring, ajout d'une classe Sprite.

* Story n°2 : Comprendre ce que signifie tirer un missile depuis le vaisseau <br>
  Définition de ce qu'est un missile.

* Story n°3 : Tirer un missile  <br>
  Mise en place de la fonctionnalité pour tirer un missile puis refactoring en faisant attention à l'espace de jeu !

* Story n°4 : Et bien, jouons maintenant !  <br>
  Ajustement des différentes touches nécessaire pour jouer puis ajustement des règles concernant les missiles.
  
* Story n°5 : Faire déplacer le missile à la verticale de manière autonome  <br>
  Mise en place d'une classe Direction ajustant les missiles, puis refactoring afin que le missile puisse se déplacer dans le jeu.

### Diagramme de classes
![Diagramme de classe](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/DiagrammeMetier3.gif)

### Nuages de mots
![Nuages de mots](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/nuagesDeMot3.png)

## Semaine n°5: du 11 au 17 mai
### Sprints et fonctionnalités réalisées
#### Fonctionnalité n°5 : Ajouter un envahisseur dans le jeu

* Story n°1 : Refactoring
  Modiffication des package.

* Story n°2 : Envahisseur 
  Création d'une nouvelle classe "Envahisseur".
  
* Story n°3 : Déplacements 
  Faire déplacer l'envahisseur en fonction de l'environnement.

### Diagramme de classes
![Diagramme de classe](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/DiagrammeMetier4.gif)

### Nuages de mots
![Nuages de mots](https://github.com/NoeSoury/depot/blob/master/spaceinvaders/image/nuagesDeMot4.png)
