# Nom de code : Synchronizer !
## Introduction
  <p>Dans le cadre d'un cours en Administration Système, nous avons dû réaliser un programme permettant la synchronisation de deux arborescences de fichiers. En d'autres termes, une sorte de Git simplifié.</p>

## Utilisation
* Cloner ce dépôt Git et rendez-vous à la racine du projet
* Deux modes ont été développé :
	* **mode manuel** : À chaque conflit, c'est à l'utilisateur de choisir l'action à effectuer. Lorsqu'aucun log n'est disponible (au premier lancement par exemple), il est automatiquement sélectionné.
	* **mode automatique** : Le script se débrouille tout seul le plus possible (certains cas nécessitent cependant l'intervention de l'utilisateur).
* Lancer le script nommé launcher de la manière suivante :
      `launcher path_TreeA path_TreeB -mode_de_lancement(m/a) path_log`
 > Lors de la première utilisation le chemin du log pointe vers un fichier qui peut être non existant, il sera généré automatiquement après l'exécution du mode manuel.

