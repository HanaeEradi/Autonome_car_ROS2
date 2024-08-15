# Projet Voiture Autonome en ROS2




## Résumé
Ce projet présente la version ROS 2 du dépôt AutoCarROS, une plateforme pour le développement d'un véhicule autonome non-holonome robuste dans un environnement simulé à l'aide de ROS 2 et Gazebo 11.





## Launch Files

|Launch File|Objectif|
|-----------|-------|
|`default_launch.py`|Pipeline complet avec des points de passage prédéfinis|
|`click_launch.py`|Pipeline interactif pour les tests et le plaisir|

## Packages

|Package|Objectif|
|-----------|-------|
|`launches`|Contient les fichiers de lancement principaux pour un démarrage rapide.|
|`autocar_description`|autocar_description	Contient le modèle URDF et les fichiers de configuration RViz.|
|`autocar_gazebo`|Contient les fichiers du monde et le modèle SDF.|
|`autocar_map`|Contient la pile de filtre d'occupation bayésienne.|
|`autocar_msgs`|Contient tous les messages personnalisés utilisés dans chaque package.|
|`autocar_nav`|Contient la pile de navigation.|





