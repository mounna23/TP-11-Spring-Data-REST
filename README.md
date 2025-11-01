# TP 11 : Spring Data REST

## Objectif :

L’objectif de ce TP est de créer une application Spring Boot avec Spring Data REST pour :
Gérer des entités Client et Compte (relations un-à-plusieurs).
Exposer automatiquement des endpoints REST sans écrire de contrôleurs.
Initialiser la base de données avec quelques exemples (Amal, Ali…).
Utiliser la pagination, le tri et les projections pour personnaliser et optimiser les réponses de l’API.
  En résumé :
Apprendre à construire une API REST complète, automatique et efficace à partir d’entités JPA grâce à Spring Data REST.

## Configuration du Service REST avec Spring Data REST

###  Exposition Automatique des Repositories

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 09 45 43" src="https://github.com/user-attachments/assets/4de45519-f43e-4850-bb72-4aa0c94c9842" />

###  Utilisation des Projections dans les Requêtes

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 09 49 19" src="https://github.com/user-attachments/assets/ee852d24-6c4d-4f3c-b977-e38a1541300f" />

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 09 49 46" src="https://github.com/user-attachments/assets/7ad71b5e-8f20-4315-add5-80b96be6e06e" />

###  Configuration de la Pagination et du Tri

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 09 59 25" src="https://github.com/user-attachments/assets/135b11ff-4e0e-4f75-ba2f-92ec27048be6" />

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 09 59 45" src="https://github.com/user-attachments/assets/2785ffe9-36e3-4d34-b45b-76c79486cc46" />

### Utilisation des Liens REST pour Naviguer entre les Ressources

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 10 41 44" src="https://github.com/user-attachments/assets/455baf29-d338-4518-850e-c49f810de560" />

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 10 42 08" src="https://github.com/user-attachments/assets/85ef9b14-50d2-4572-93e5-818abb50d2f4" />

###  Personnalisation des Relations avec les Projections

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 10 43 13" src="https://github.com/user-attachments/assets/0bc4761c-9403-48f3-9ae8-d60979867b35" />

###  Requêtes de Recherche par Type de Compte (Utilisation de la Requête de Recherche par Type dans l'URL)

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 10 45 46" src="https://github.com/user-attachments/assets/02f921b8-0b1d-4453-9067-e1f7a455ada5" />

<img width="1378" height="836" alt="Capture d’écran 2025-11-01 à 10 46 01" src="https://github.com/user-attachments/assets/983cf736-c206-4d26-8470-a5435a832dd6" />

## Conclusion
Ce TP a permis de mettre en pratique l’utilisation de Spring Data REST pour exposer automatiquement des services RESTful à partir d’entités JPA.
Nous avons appris à gérer les relations entre entités, initialiser les données, et exploiter la pagination, le tri et les projections pour optimiser les réponses de l’API.
Cette approche simplifie considérablement le développement d’API tout en offrant une structure claire, performante et extensible.
