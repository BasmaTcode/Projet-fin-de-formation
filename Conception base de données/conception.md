Conception de la Base de Données

La conception de la base de données constitue une étape essentielle dans le développement de la plateforme d’affiliation. Elle permet d’organiser et de gérer efficacement les informations relatives aux utilisateurs, aux produits affiliés, aux clics, aux commissions et aux revenus générés.

La base de données a été conçue en utilisant le système de gestion MySQL afin de garantir la cohérence, la sécurité et la fiabilité des données.

Objectifs de la Base de Données

La base de données a été mise en place afin de permettre :

La gestion des comptes utilisateurs ;
La gestion des produits affiliés ;
Le suivi des clics effectués sur les liens d’affiliation ;
Le calcul et le suivi des commissions ;
La gestion des catégories de produits ;
La génération des statistiques et rapports ;
La gestion des paramètres de la plateforme.
Structure Générale
Utilisateurs (Users)

Cette table contient les informations des utilisateurs inscrits sur la plateforme, notamment les affiliés et les administrateurs.

Produits Affiliés (Products)

Elle regroupe l’ensemble des produits proposés par les différents programmes d’affiliation.

Catégories (Categories)

Cette table permet de classer les produits selon différents domaines ou secteurs d’activité.

Liens d’Affiliation (Affiliate Links)

Elle contient les liens uniques associés à chaque produit afin de suivre les actions des utilisateurs.

Clics (Clicks)

Cette table enregistre les clics réalisés sur les liens d’affiliation pour mesurer les performances des campagnes.

Commissions (Commissions)

Elle stocke les commissions générées à partir des ventes ou actions validées.

Revenus (Earnings)

Cette table permet de suivre les gains réalisés par chaque affilié.

Rapports (Reports)

Elle contient les statistiques et données nécessaires à l’analyse des performances.

Relations entre les Entités
Un utilisateur peut promouvoir plusieurs produits affiliés.
Un produit peut appartenir à une seule catégorie.
Un produit peut être associé à plusieurs clics.
Un utilisateur peut générer plusieurs commissions.
Une commission est liée à un produit affilié.
Un utilisateur peut consulter plusieurs rapports de performance.