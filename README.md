## Travail à rendre - Gestion des mariages

## 1. Création des entités
Les entités principales à créer sont :

-Personne : Une classe de base représentant une personne.

-Homme et Femme : Deux sous-classes qui héritent de Personne.

-Mariage : Représente un mariage avec une clé composite MariageId qui relie un homme et une femme.

## 3. Configuration Hibernate
Configurez Hibernate avec le fichier hibernate.cfg.xml dans le package ma.projet.config. Ce fichier contiendra les informations de connexion MySQL ainsi que la configuration des entités.

## 4. Interface DAO et Utilitaire Hibernate
-Créez l’interface IDao pour les opérations CRUD.

-La classe HibernateUtil fournira un accès à la session Hibernate pour gérer les transactions.

## 5. Fonctionnalités principales
Les principales opérations incluent :

-Ajout de mariages : Ajoutez des mariages entre hommes et femmes.

-Gestion des enfants : Suivez le nombre d'enfants dans chaque mariage.

-Modification et suppression : Gérez les mises à jour et la suppression des entités Mariage.

## 6. Tester le projet
Créez une classe de test où vous pouvez ajouter des mariages, modifier les informations, et tester toutes les autres fonctionnalités du projet.
